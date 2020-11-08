# XRinteraction
Tools for Blender's XR branch 




# • You need to download XR Branch blender
https://builder.blender.org/download/xr-actions-D9124/

# • Activate VR Inspection Addon

# • Customize your Actions and Landmarks
<br>
(look on screenshots for HTC Vive, other headsets are the same except PROFILE would look different, you can watch PeterKim's videos to understand and also to read some OpenXR doc's about namings)
<br>
https://www.youtube.com/watch?v=mjhJMFVREVM&list=PLiMcpGf16MaxKRdpureVaCao9WXpsncf9&index=7&ab_channel=MuxedReality
<br>
https://www.khronos.org/registry/OpenXR/specs/1.0/refguide/openxr-10-reference-guide.pdf

# • Download xr_modal_swim.py

# • Modify this section in script according to your actions
{<br>
  LEFT_ACTION_SET =  "vive"
  <br>
  LEFT_ACTION = "click_left"<br>
  LEFT_USER_PATH = "/user/hand/left"<br>
  RIGHT_ACTION_SET =  "vive"<br>
  RIGHT_ACTION = "click_right"<br>
  RIGHT_USER_PATH = "/user/hand/right"<br>
}

# • Run xr_modal_swim.py script from blender
# • Start your VR session and enjoy

Make sure you've entered correct operator object.vr_modal_operator in your actions <br>
<br>
<br>
To be able to move your scene, you have to set your landmark as CustomObject and define which object it would be
