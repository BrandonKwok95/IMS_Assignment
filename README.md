# IMS_Assignment
## Brief Description
### With the continuous development of live video software and video social software, people's de- mand for high-definition video is increasing. This has also brought challenges to related video-industry: how to reduce the video file size as much as possible while ensuring the video quality? The emergence of the HEVC / H.265 protocol is one of the answers. According to related research, at the same level of video quality, the encoded file size is theoretically half that of H.264. However, H.265 provides many optional parameters. At the same time, the same set of parameter encoded video files often fails to achieve the best results. Therefore, this paper mainly focuses on comparing the influence of optional parameters on the encoding result from the perspective of video quality and compression ratio.
### This implementation is to encode source video based on Jupyter(python) and FFmpeg

## Environment Setup
### 1. This assginment is based on MAC OS X 15.4
### 2. Necessary tools:
                    a. Jupyter (python 3.7)
                            (1) os
                            (3) json
                            (2) matplotlib
                    b. FFmpeg (Download from here:
                               https://drive.google.com/drive/folders/1CNPqtE6aGUhXMpXCKtsmlqefAwHIEnrH?usp=sharing)
### 3. Make sure there is enough storage space （about 15GB） on your device  
### 4. Download all source videos from here
       https://drive.google.com/open?id=1J6xB56WZNkNlCy4pFeH37q9296gx1tun
       all the source videos are from https://media.xiph.org/video/derf/

## Implementation
### 1. After finished environment setup, run CreateFolder.ipynb to create folder (setup frame)
### 2. Put all source videos into source-video
### 3. After ensuring all folders have been setup, run Encoding.ipynb to encode source video

## Result
### The implement reulst is in vmaf folder(video quality), video-format(file-size / bit-rate),  encode-video(encoded videos)
### vmaf and video-format have been uploaded on Github, and you can check it.
