这个教程：
https://www.patreon.com/Onion365/posts

使用blender3.6.2

mmd_tools的版本，1.0.2 
mmd_tools下载: 
	https://github.com/UuuNyaa/blender_mmd_tools/releases



动作下载：
https://github.com/killinux/mmd 
https://www.fs-pblog.com/post/project-diva-motion-convert-mmd-downloads
PV120 - Shake it.zip 

使用教程：
https://www.patreon.com/posts/full-tutorial-53842695 
这个付费的话用这个
https://www.youtube.com/watch?v=X7IBIlf_1M4



## 简要步骤：
import 模型pmx，去掉紫色，   bind ，   import  动作vmd，    build， 衣服对齐帧， 场景 烘培 

## 具体方法
### import 模型pmx：在工具栏mmd ，import   找到 Shiva.pmx文件
### 去掉紫色：在工具栏Misc ，菜单里勾选掉 Toon Texture ，和 勾选掉 Sphere Texture  （找不到相关贴图）
### bind：在工具栏mmd，Morph Tools里选
	选bone 
	下三角选，bind
	发现 右侧菜单的小人变成两个，多了个占位符 .placeholder
### import  动作vmd：motion 导入 1.vmd 
### build ： build之后头发和x才能抖动
### 裙子：物理菜单，选衣服，对齐帧率 end的数字 
### 烘培：右侧场景菜单：
	Rigid Body  World中的 cache，调整end位  需要的帧
	最下面的 start 和end 的end 也调整成需要的帧率
	烘培： Bake All Dynamics



xps如何转换成mmd ？
只有mmd才能有动作	

Phut Hon Dance_Short Ver
https://bowlroll.net/file/247352



------------
==============================================================
Level 1 tutorial
Tutorial For Blender 3.0.1 and MMDTools v1.0.2
1. Import MMD Model
2. Click Model Name
3. Click "Morph Tool" → Click "Bone" → Click "∨"  → "Click "Bind"
4. Click Model Name
5. Import MMD Motion
6. Click Model Name
7. Click "Build" Physics (make sure all frame are the same before click "build")
Current Frame : 1 → Start Frame : 1 → End Frame : 250
Physics Frame : Simulation Start Frame : 1 → End Frame : 250
Rigid Body World : Simulation Start Frame : 1 → End Frame : 250
(If the physical effect is abnormal, click Clean and then click Build)
8. Go to "Scene Properties"  → Click "RigidBody World"  → Click "Cache" → Click "Bake ALL Dynamics"
9. Add Sound and Click "Scrubbing"     (Sound basically starts at frames 15)
10. "Shift + A" add "Camera" and import MMD Camera Motion → Press numpad keyboard "0"
11. Go to "Output Properties" Set up  Video 1080p or 4K , "Frame Rate 30fps" , File Format Click "FFmpeg Video" and Click Audio Code "Vorbis"
12. Viewport Render Animation
13. Done
Youtube : Supplementary tutorial
YouTube : Solve the foot load some motion can not move
YouTube : Solution to material pink
YouTube : Edit MMD Motion Import To Blender
YouTube : Edit MMD Camera Motion import To Blender 
YouTube : Solve the problem of cloth physics with too fast motion Part 1
YouTube : Solve the problem of cloth physics with too fast motion Part 2
YouTube : Some motions require additional facial and adjust the physics too fast solution
YouTube : For Blender 3.2 MMDTools v2.3.0 Tutorial
If you use Blender 3.2+ MMDTools v2.3.0 or Blender latest version and MMD Tools latest version to Import/Export Motion and Model, you must adjust the "Scale" "0.08" to "1.00" and Click "Property" more details see the video tutorial.
(Recommend Blender 3.0.1+ MMDtools v1.0.2)
================================================================
Blender Download：
https://www.blender.org/
Blender 3.0.1 Download
https://download.blender.org/release/Blender3.0/
=========================================
Blender MMD Tool Plugin Download：
https://github.com/UuuNyaa/blender_mmd_tools
https://github.com/UuuNyaa/blender_mmd_tools/releases
Blender 3.0.1 Use MMDtools v1.0.2 ← Recommend
Blender 3.2 Use MMDtools v2.3.0 or latest version
Install Blender MMDTools add ons Tutorial：
https://youtu.be/NtPSo7xPIkM
=========================================
HDRis Download ：
https://polyhaven.com/hdris
=========================================
30fps to 60fps Flowframes Download：
https://nmkd.itch.io/flowframes
#########################################################################
#########################################################################
Level 2 tutorial














Tutorial HD Picture：Download
Sample Pose : Download
Bone Name/ Morph Name：Download
Xnalara to MMD Converter Tool : Link
PMXEditor : Link
MikuMikuDance : Link
Youtbue : Fix Bone Tutorial
Youtube : MMD Standard Pose and Add Waist Bone Tutorial
Youtube : Solve the foot load some motion can not move Tutorial
Youtube : Morph Facial and Bone Rename Tutorial
Youtube : MMD Hair Physics Butt Physics and Breast Physics Tutorial
Youtube : Blender Import MMD Fix Texture Tutorial
Youtube : Blender Cloth Physics Tutorial
Youtube : 5 Dress Physics Tutorial
Main instructions and attention：
Fix Bone:
Select all right leg bones, click "Edit" → Bone → Merge Bones with similar names", it will merge one bone.
Add Bone:
Remember to add these bones after the bones and facial are done.
Solve the foot load some motion can not move
Morph/Facial:
Rename the left and right bones with the same name , go to "Transform view" , move the right bone or move the left bone and click "INVRT-P" the bones on the left and right sides will move synchronously.
After finishing morph/facial, be sure to rename the left and right bones with different bone names ,The fastest way to rename the bone name is to import pmx with blender and export pmx will be renamed automatically.
MMD Standard Pose:
Transform view click "Save model" window appears "Vertex Morph Threshold 0.00001" "Must be changed to 0.00000"
Blender Dress Physics:
Before doing Blender dress physics, make sure that the model does not have mmd physics.
##########################################################################
Other:
Youtube: How to use mmd stage pmx + HDRI + Cycles Render in blender Tutorial.
Youtube: Fingers emit a particle of light magic Tutorial.
Youtube: Hand holding things Tutorial.