Wordpress Video Plugin
======================

Originally developped by [daburna][http://www.daburna.de/blog/]

The Wordpress Video Plugin adds a filter for WordPress that allows easy video embedding of 65 supported video sites. Supported sites:

123video.nl, Aniboom, Blip.tv, Break, Brightcove, CBS, Cellfish, Clipfish, Clipsyndicate, Collegehumor, ComedyCentral.com, current.com, D1G.com, dotSUB, Facebook, Flickr Video, FunnyorDie.com, GameTrailers, GameVideos, Generic Flash, Glumbert, GoalVideoz, Google Video, Grouper, Guba, Hamburg1 Video, hulu, IFILM, ISeeIt.TV, Jumpcut, Kewego, Last.fm, LiveLeak, MEGAVIDEO, Metacafe, Mncast.com, Mojvideo.com, MPORA.com, MQSTO.com, MSN, MyspaceTV, MyVideo, Novamov, OnSMASH.com, reason.tv, ReelzChannel, Revver, screencast-o-matic.com, Sevenload, slideshare.com, smotri.com, Sumo.tv, teachertube, Trilulilu, Tu.tv, UnCut, Veoh, Videotube, Vimeo, Vsocial, vzaar.com, Wandeo, wat.tv, Yahoo! Video, Youreporter, Youtube and Youtube Playlist.

There are very little differences on my version 
 * you can use a space or a semicolon between the videocode and the id
 * you can add a start time on youtube videocode

## Videocodes 


This is a list of all featured videosites and a code example for embedding a video of each site.

123video.nl
[123videonl id]
For the URI http://123video.nl/playvideos.asp?MovieID=132273 the id is 132273 → [123videonl 132273]

Aniboom
[aniboom id]
For the URL http://www.aniboom.com/animation-video/479823/Yaku-Shortfilm/, the id part is 479823 → [aniboom 479823]

Blip.tv
[bliptv id width height]
You will find the id, when you copy the video code for an embeded player. Look for this line: src=“http://blip.tv/play/gvFH8rZBgvNh” For the URI http://blip.tv/file/1865111, the id part is gvFH8rZBgvNh → [bliptv gvFH8rZBgvNh]

Break
[break id]
You have to take a look into the code for an embeded player. Search for value=. After it, you will find the URL with the id. For the URI http://embed.break.com/MjI2NTkx → [break MjI2NTkx]

Brightcove
[brightcove id]
For the URI http://link.brightcove.com/services/player/bcpid416542555?bctid=24776439001, the id part is 24776439001 → [brightcove 24776439001]

CBS
[cbs id width height]
For the URI http://www.cbs.com/late_night/late_show/video/?pid=jBKco1lLmfitxBLY9pzs9RDOb1k0paQO&nrd=1 the id part is jBKco1lLmfitxBLY9pzs9RDOb1k0paQO → [cbs jBKco1lLmfitxBLY9pzs9RDOb1k0paQO]
NOTE: CBS currenly works only in the US.

Cellfish
[cellfish id]
For the URI http://cellfish.cellfish.com/multimedia/97749 the id is 97749 → [cellfish 97749]

Clipfish
[clipfish id]
For the URI http://www.clipfish.de/player.php?videoid=NDE2fDM0 the id is NDE2fDM0 →[clipfish NDE2fDM0]

Clipsyndicate
[Clipsyndicate id width height]
For the URI http://www.clipsyndicate.com/publish/video/613132/raw_video_tornado_destroys_iowa_bank?wpid=0 the id is 613132 → [clipsyndicate 613132]

Collegehumor
[collegehumor id] or with configurable size [collegehumor id width height]
For the URI http://www.collegehumor.com/video:1727961 the id is 1727961 → [collegehumor 1727961] or with size [collegehumor 1727961 200 100]

ComedyCentral.com
[comedycentral id]
http://www.comedycentral.com/videos/index.jhtml?videoId=393382&title=comic-con-2011-panel---live-table-read → [comedycentral 393382]

current.com
[current id width height]
For the URI http://current.com/items/89891774/supernews_twouble_with_twitters.htm the id is 89891774 → [current 89891774]

D1G.com
[d1g id width height]
For the URI http://www.d1g.com/video/show/1912587 the id is 1912587 → [d1g 1912587]

Dailymotion
[dailymotion id width height]
Replace “id” with the dailymotion id or the video URL (both works). For the URI http://www.dailymotion.com/de/featured/video/x5fgu1_buffedshow-86-von-buffedde_videogames the id is x5fgu1 → [dailymotion x5fgu1]

dotSUB
[dotsub id width height]
For the URI http://dotsub.com/view/7774e495-71c5-4a64-83d9-28675d835d90 the id is 7774e495-71c5-4a64-83d9-28675d835d90 → [dotsub 7774e495-71c5-4a64-83d9-28675d835d90]

Facebook
[FB id]
For the URI http://www.facebook.com/video/video.php?v=1036384564453 the id is 1036384564453 → [FB 1036384564453]

Flickr Video
[flickr id width height]
For the URI http://www.flickr.com/photos/25530364@N07/3599198949/in/pool-alongphoto the id is 3599198949 → [flickr 3599198949]

Funny or Die
[funnyordie id width height]
For the URI http://www.funnyordie.com/videos/3b1e3750e2 the id is 3b1e3750e2 → [funnyordie 3b1e3750e2]

GameTrailers
[gametrailers id]
For the URI http://gametrailers.com/player/22271.html the id is 22271 → [gametrailers 22271]

GameVideos
[gamevideos id]
For the URI http://www.gamevideos.com/video/id/13217 the id is 13217 → [gamevideos 13217]

Generic Flash
[flash id]
For the URI http://www.messe-ideen.de/upload/magische-zauberkugel.swf the code is [flash http://www.messe-ideen.de/upload/magische-zauberkugel.swf]

Glumbert
[glumbert id]
For the URI http://www.glumbert.com/media/spidermate the id is spidermate → [glumbert spidermate]

GoalVideoz
[goalvideoz id width height]
For the URI http://www.goalvideoz.com/watch/2674-Portugal-vs-Turkey-2nd-Half-Goals-and-Highlights-Euro-2008/ the id is 2674 → [goalvideoz 2674]

Google Video
[google id]
For the URI http://video.google.de/videoplay?docid=-5024787479139933029 the id is -5024787479139933029 → [google -5024787479139933029]

Grouper
[grouper id]
For the URI http://grouper.com/video/MediaDetails.aspx?id=1759771&ml=o%3D0%26t%3D1%26fx%3D%26fp%3D2%26fmx%3D3%26rnd%3D3 the id is 1759771 → [grouper 17597719]

Guba
[guba id width geight]
For the URI http://www.guba.com/watch/3000093083?duration_step=0… the id is 3000093083 → [guba 3000093083]

Hamburg1 Video
[hamburg1 id] or with configurable size [hamburg1 id width height]
For the URI http://www.hamburg1video.de/video/iLyROoaftT81.html the id is iLyROoaftT81 → [hamburg1 iLyROoaftT81] or with size [hamburg1 iLyROoaftT81 200 100]

hulu
[hulu id width height]
You find the id when you copy the video code for the an embedded player. Look for this line near the beginning of the code:

<object width="480" height="270"><param name="movie" value="http://www.hulu.com/embed/KqGQAaGmZu7EaRstGkKYXQ">

→ [hulu KqGQAaGmZu7EaRstGkKYXQ]
NOTE: Hulu currenly works only in the US.

IFILM
[ifilm id]
For the URI http://www.ifilm.com/video/2878371 the id is 2878371 → [ifilm 2878371]

ISeeIt.TV
[iseeittv id width height]
e.g. [iseeittv cqns7lq0g6ua0p]

Jumpcut
[jumpcut id] or with configurable size [jumpcut id width height] For the URI http://jumpcut.com/view/?id=774D8BB8E95911DA897BFEAF976EA1AD the id is 774D8BB8E95911DA897BFEAF976EA1AD → [jumpcut 774D8BB8E95911DA897BFEAF976EA1AD] or with other size [jumpcut 774D8BB8E95911DA897BFEAF976EA1AD 220 100]

Kewego
[kewego id width height]
For the URI http://www.kewego.de/video/iLyROoaftxTc.html the id is iLyROoaftxTc → [kewego iLyROoaftxTc]

Last.fm
[lastfm id]
You will find the id, when you copy the video code for an embeded player. Look for this line: param name=“flashvars” value=“embed=true&creator=Kettcar&title=Landungsbr%C3%BCcken+raus&uniqueName=Landungsbr%C3%BCcken+raus&albumArt=http://cdn.last.fm/coverart/130x130/1422004.jpg&album=Du+Und+Wieviel+Von+Deinen+Freunden&duration=257&image=http://panther3.last.fm/storable/videocap/15582/0/original.jpg&FSSupport=true” the id is: embed=true&creator=Kettcar&title=Landungsbr%C3%BCcken+raus&uniqueName=Landungsbr%C3%BCcken+raus&albumArt=http://cdn.last.fm/coverart/130x130/1422004.jpg&album=Du+Und+Wieviel+Von+Deinen+Freunden&duration=257&image=http://panther3.last.fm/storable/videocap/15582/0/original.jpg&FSSupport=trueS → [lastfm embed=true&creator=Kettcar&title=Landungsbr%C3%BCcken+raus&uniqueName=Landungsbr%C3%BCcken+raus&albumArt=http://cdn.last.fm/coverart/130x130/1422004.jpg&album=Du+Und+Wieviel+Von+Deinen+Freunden&duration=257&image=http://panther3.last.fm/storable/videocap/15582/0/original.jpg&FSSupport=trueS]

LiveLeak
[liveleak id]
For the URI http://www.liveleak.com/view?i=8d3_1181986751 the id is 8d3_1181986751 → [liveleak 8d3_1181986751]

MEGAVIDEO
[megavideo id width height]
For the URI http://www.megavideo.com/?v=Q0G3U6F7 → the id is Q0G3U6F7 → [megavideo Q0G3U6F7]

Metacafe
[metacafe id]
For the URI http://www.metacafe.com/watch/427425/boulot/ the id is 427425 → [metacafe 427425]

Mncast.com
[mncast id width height]
You have to search in the embeded code. Search for “movieID”. For the URI http://www.mncast.com/?4223906 the id is 10005583920080301233042 [mncast 10005583920080301233042]

Mojvideo.com
[mojvideo id width height]
For the URI http://www.mojvideo.com/video-bmw-club-obsotelje/480f35d6e4c046353a58 the id is 480f35d6e4c046353a58 → [mojvideo 480f35d6e4c046353a58]

mpora.com
[mpora id width height]
For the URL http://video.mpora.com/watch/Q9lVFPNia/ the id is Q9lVFPNia → [mpora Q9lVFPNia]

MQSTO.com
[mqstovideocom id]
For the URI http://mqsto.com/video/18830 the id is 18830 → [mqstovideocom 18830]

MSN
[msn id width height]
For the URI http://video.msn.com/video.aspx?vid=71e6a055-7b68-4fc3-880a-1bcffe1433b5 the id is 71e6a055-7b68-4fc3-880a-1bcffe1433b5 → [msn 71e6a055-7b68-4fc3-880a-1bcffe1433b5]

MyspaceTV
[myspacetv id]
For the URI http://vids.myspace.com/index.cfm?fuseaction=vids.individual&VideoID=11315224 the id is 11315224 → [myspacetv 11315224]

MyVideo
[myvideo id]
For the URI http://www.myvideo.de/watch/366128 the id is 366128 → [myvideo 366128]

Novamov
[novamov id]
For the URI http://www.novamov.com/video/oaqqzqx1czqg5 the id is oaqqzqx1czqg5 → [novamov oaqqzqx1czqg5]

OnSMASH.com
[onsmash id width height]
For the http://videos.onsmash.com/v/3X8RTKaK6C3hya7q the id is 3X8RTKaK6C3hya7q → [onsmash 3X8RTKaK6C3hya7q]

reason.tv
[reason id]
For the URI http://reason.tv/video/show/157.html the id is 157 → [reason 157]

ReelzChannel
[reelzchannel id width height]
For the URI http://www.reelzchannel.com/video/32097/indiana-jones-4-trailer the id is 32097 → [reelzchannel 32097]

Revver
[revver id]
For the URI http://one.revver.com/watch/174453 the id is 174453 → [revver 174453]

screencast-o-matic.com
[screencast id width height] For the URI http://www.screencast-o-matic.com/watch/cii3lYtk the id is cii3lYtk → [screencast cii3lYtk]

Sevenload
[sevenload id]
For the URI http://sevenload.de/videos/8A6KASF-arif-playback the id is 8A6KASF → [sevenload 8A6KASF]

slideshare.com
[slideshare id]
Replace “id” with the corresponding values from the URL of the object. For embedding the presentation at http://www.slideshare.net/jboutelle/slidecasting-101 just click on 'Post to Wordpress' and you will get this code [slideshare id=82836&doc=slidecasting-1013073

smotri.com
[smotri id width height]
For the URI http://smotri.com/video/view/?id=v630387892f the id is v630387892f → [smotri v630387892f]

Sumo.tv
[sumotv id]
You will find the id, when you copy the video code for an embeded player. Look for this line: param name=“flashVars” value=“file=00/01/200710049164669307.flv&autostart=true” there you can find the id: 00/01/200710049164669307 → [sumotv 00/01/200710049164669307]

teachertube
[teachertube id]
To find the id look here: [flashvideo width=“425” height=“350” filename=“http://www.teachertube.com/flvideo/11926.flv” /] the id is 11926 → [teachertube 11926]

Trilulilu
[trilulilu id width height]
For the URI http://www.trilulilu.ro/keskifa/d219752d57c01e the id is d219752d57c01e → [trilulilu d219752d57c01e]

Tu.tv
[tutv id]
You will find the id, when you copy the video code for an embeded player. Look for this line: …tutvweb.swf?kpt=aHR0cDovL3d3dy50dS50di92aWRlb3Njb2RpL2MvaS9jaWNsaXN0YS1hYnVzaXZvLmZsdg==&x…, there you can find the id: aHR0cDovL3d3dy50dS50di92aWRlb3Njb2RpL2MvaS9jaWNsaXN0YS1hYnVzaXZvLmZsdg → [tutv aHR0cDovL3d3dy50dS50di92aWRlb3Njb2RpL2MvaS9jaWNsaXN0YS1hYnVzaXZvLmZsdg]

UnCut
[uncut id]
For the URI http://uncutvideo.aol.com/videos/16ea5688332b7df5a5dc5ba6a99f4d3d the id is 16ea5688332b7df5a5dc5ba6a99f4d3d → [uncut 16ea5688332b7df5a5dc5ba6a99f4d3d]

Veoh
[veoh id]
For the URI http://www.veoh.com/videos/v849683cxDDQm7y the id is v849683cxDDQm7y → [veoh v849683cxDDQm7y]

Videotube
[videotube id]
For the URI http://www.videotube.de/ci/page/player/527 the id is 527 → [videotube 527]

Vimeo
[vimeo id width height]
For the URI http://www.vimeo.com/clip:138920 the id is 138920 → [vimeo 138920]

Vsocial
[vsocial id]
For the URI http://www.vsocial.com/video/?d=106492 the id is 106492 → [vsocial 106492]

vzaar.com
[vzaar id width height]
For the URI http://vzaar.com/videos/541684 the id is 541684 → [vzaar 541684]

Wandeo
[wandeo id]
For each URI just copy the code from the box: “on my wordpress blog” → [wandeo c93fb414becc9324eb501770013dee9e]

wat.tv
[wat id width height]
http://www.wat.tv/video/ouverture-mondial-presse-automoto-z9po_z1vx_.html → You will find the id, when you copy the video code for an embeded player. Look for this line: <param name=“movie” value=“http://www.wat.tv/swf2/313547fagwuFO1645548” /> there you find the id. It is 313547fagwuFO1645548 → [wat 313547fagwuFO1645548]

Yahoo! Video
[yahoo id]
You will find the id, when you copy the video code for an embeded player. Look for this line: flashvars='id=3253032&emailUrl=http%3A%2F%2…etc…, there you can find the id: 3253032 → [yahoo 3253032]

Youreporter
[youreporter id]
For the URI http://www.youreporter.it/view_video.php?viewkey=dac8bc8ba637133b2c65 the id is dac8bc8ba637133b2c65 → [youreporter dac8bc8ba637133b2c65]

Youtube
[youtube id] or with configurable size [youtube id width height] or with a start time [youtube id XmXs]
For the URI http://www.youtube.com/watch?v=8DHOZW_8OPk the id is 8DHOZW_8OPk → [youtube 8DHOZW_8OPk] or with size [youtube 8DHOZW_8OPk 210 175] or with start time [youtube 8DHOZW_8OPk 2m10s]

Youtube Playlist
[youtubeplaylist id width height]
For the URI http://de.youtube.com/view_play_list?p=EF1145687A8B929B the id is EF1145687A8B929B → [youtubeplaylist EF1145687A8B929B]