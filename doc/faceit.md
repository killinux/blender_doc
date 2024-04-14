use faceit-release-v2.3.40.zip

patreon KylieStylish Workshop https://www.patreon.com/kyliestylishworkshop/posts


blender 3.6.2

1. setup: use Existing face rig
2. Expressions: Load Faceit Expressions  确定
3. 烘培： Bake Shape Keys  确定
4. 
5. Control： Generate Control Rig  确定，忽略错误
6. Mocap：Live Recorder  ---> Face cap ---》 address：10.3.194.247 ，start Receiver
7. Face cap 链接
8. staop Receier ---- Clear Recorded Data 

制作视频：
https://moejj.com/ffmpeg/
https://blog.csdn.net/qq_29007291/article/details/128133875
ctrol shift 5录屏

ffmpeg -i aaa.mov -to 00:00:12 -codec copy aaa.mp4

ffmpeg -i aaa.mp4 -vf crop=2880:1800:10:1800   b.mp4
