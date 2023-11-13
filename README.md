
# Face Swapping With Deep Fakes Methods

<div align="center">

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/sabahesaraY)

[![Twitter](https://img.shields.io/twitter/follow/sabahesaraki?style=social)](https://twitter.com/saba_hesaraki)

</div>

## Installation
  
1. Clone this repository
  ```bash
  git clone https://github.com/saba99/Face_Swap.git
  cd Face_Swap

  ```
2. Install dependent packages
  ```bash
  pip install -r requirements.txt
  ```
  
3. Download weights
  ```bash
  sh download_models.sh
  ```

 ## Face Swap On Image

  ** Colab <a href="https://colab.research.google.com/drive/1pLyLbnBma9PiWioMxmyPBn-TWhkI6mqt"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="google colab logo"></a>
  
  You may set the target face, and then source will be swapped on this person, or you may skip this parameter, and then source will be swapped on any person in the image.
  ```bash
  python inference.py --target_path {PATH_TO_IMAGE} --image_to_image True
  ```

## Face Swap For Images-Results
<div>
<img src="https://github.com/saba99/Face_Swap/assets/33378412/80d1507e-be8e-4f5d-be6d-acb7caca8447">
<img src="https://github.com/saba99/Face_Swap/assets/33378412/b69da8d8-48e4-45f9-ba99-b4c33b04de12">
<img src="https://github.com/saba99/Face_Swap/assets/33378412/ac846aae-4686-4461-9a56-4df0ddbf2ba5">
<img src="https://github.com/saba99/Face_Swap/assets/33378412/f9309cc9-f746-48b7-bbac-8d85658d1081">
 
</div>


## Face Swap On Video

 ** Colab <a href="https://colab.research.google.com/drive/11luB-78FmWdpdGwAvjigJge4bJo8pkKM#scrollTo=j6ifzr5I1phS"><img src="https://colab.research.google.com/assets/colab-badge.svg" 
    alt="google colab logo"></a>

  1.download Face Video From this link [[Face Videos](https://www.pexels.com/search/videos/face/)] 
 

  2. Face Swap On Video
  
  ```bash
  Swap to one specific person in the video. You must set face from the target video (for example, crop from any frame).
  ```

  
  python inference.py --source_paths {PATH_TO_IMAGE} --target_faces_paths {PATH_TO_IMAGE} --target_video {PATH_TO_VIDEO}
  ```
  Swap to many person in the video. You must set multiple faces for source and the corresponding multiple faces from the target video.
  ```bash
  python inference.py --source_paths {PATH_TO_IMAGE PATH_TO_IMAGE ...} --target_faces_paths {PATH_TO_IMAGE PATH_TO_IMAGE ...} --target_video {PATH_TO_VIDEO}
  ```

  3.Watch the  Results

  <table class="center">
<tr>
  <td style="text-align:center;"><b>Source Video</b></td>
  <td style="text-align:center;"><b>Image for Swapping</b></td>
  <td style="text-align:center;"><b>Target Video</b></td>
</tr>
  
<tr>
<td>

https://github.com/saba99/Face_Swap/assets/33378412/811a7222-973b-4935-b040-131ee740bf8f.mp4

</td>
<td>
<img src="https://github.com/saba99/Face_Swap/assets/33378412/ec14173b-4a9d-406c-8e02-4d7a34fbd289" width="300px";height:"400px">


</td>
<td>


https://github.com/saba99/Face_Swap/assets/33378412/b38810f5-258b-4118-990e-0a6ed2aeaba9.mp4


</td>

</tr>
</table>

