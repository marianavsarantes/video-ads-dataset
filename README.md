
Towards Understanding the Consumption of Video-Ads on YouTube
=============================================================

Here we provide the datasets for our paper: Towards Understanding the
Consumption of Video-Ads on YouTube.


Data
----

#### video-ad-exhibitions.csv

Video-ad exhibitions on our local dataset. 

ad_id: video-ad identifier

watch-id: video-content identifier

skip_dur: seconds until user skips the exhibition. When the exhibition is watched in full, skip_dur = nan

#### ads-api.json

Global information of video-ads collected through the YouTube API

title: title of the video-ad

description: description of the video-ad

categoryId: category of the video-ad

duration: duration of the video-ad

viewCount: total number of views 

publishedAt: date of upload of the video

#### watch-api.json

Global information of video-contents collected through the YouTube API

title: title of the video-content

description: description of the video-content

categoryId: category of the video-content

duration: duration of the video-content

viewCount: total number of views 

channelId: channel associated with video-content

#### ads-timeseries.json

Daily timeseries of the number of views. For video-ads only.


Bibtex
------

Filled out on publication.
