from moviepy.editor import *
clip =  clip.volumex(0.99 )
txt_clip =  TextClip("strong cat", fontsize= 70, color= 'red')
txt_clip =  txt_clip.set_pos('center').set_duration(12 )
video = CompositeVideoClip([clip, txt_clip])
video.write_videofile("123")


