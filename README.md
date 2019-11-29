# Waifu2x-Extension
### `Download`: https://github.com/AaronFeng753/Waifu2x-Extension/releases/latest
### `User Guide`: https://github.com/AaronFeng753/Waifu2x-Extension/blob/master/User_Guide.md
----
# What is Waifu2x-Extension?
Image & GIF & Video Super-Resolution for Anime-style art using Deep Convolutional Neural Networks.

Based on `Waifu2x-ncnn-vulkan` (version 20190712) and `Waifu2x-converter` . 

Thanks to waifu2x-ncnn-vulkan, Waifu2x-Extension could use any kind of gpu that support `Vulkan`, even Intel GPU. 

If your gpu doesn't support vulkan, you can use Waifu2x-converter, which is also intergrated into the Waifu2x-Extension.

Already been tested on `AMD` RX 550, `NVIDIA` GeForce GTX 1070 and `Intel` UHD 620.

# Features
### New features brought by this extension:
- Much more friendly CUI (Character User Interface).
- Achieved with `waifu2x-ncnn-vulkan`, `waifu2x-converter` and `Anime4K`.
- Support 1x/2x/4x/8x/.... magnification
- Batch enlarge still `images` and `GIF` dynamic images (Waifu2x-ncnn-vulkan & Waifu2x-converter)
- Batch enlarge `video` files (Waifu2x-ncnn-vulkan & Waifu2x-converter & Anime 4k)
- Personalization
- Online update
- Save the enlarged image target as .jpg
- Lossless compression of .jpg images after the target is saved
- Optimize enlarged GIF dynamic images to reduce space usage
- Display processing progress and remaining time
- Smart selection of models
- `Gif compression & image compression` (multi-threading and multiple compression levels)
- Benchmark (to get the tile size value for your computer)
- Multi-threaded mode
- Protect Gif files
- Error catching
- Record error log
- Sleep mode
- Notification sound
- Compatibility test
- Record running log.
- And more

# Samples
### **`Image`** : https://github.com/AaronFeng753/Waifu2x-Extension/tree/master/Samples/image

### **`Video`** : https://github.com/AaronFeng753/Waifu2x-Extension/tree/master/Samples/video

### **`GIF`** : https://github.com/AaronFeng753/Waifu2x-Extension/tree/master/Samples/gif

#### Original Imgae 480x300 (.jpg 93.2 KB):
![Original Imgae](/Samples/image/Original_[480x300].jpg)

#### After 8x magnification, level 3 denoise and compress 3840x2400 (.jpg 525 KB):
![Scaled Imgae](/Samples/image/Waifu2x_8x_[3840x2400].jpg)

#### Comparison
![Comparison](/Samples/image/Comparison.png)

#### Original GIF 500 x 372 (493 KB):
![Original GIF](/Samples/gif/2_original.gif)

#### After 2x magnification, level 2 denoise and gif optimize 1000 x 744 (3.77 MB):
![Original GIF](/Samples/gif/2_waifu2x_compressed.gif)

### `Github doesn't support play video online, pls check link below:`
### **`Video`** : https://github.com/AaronFeng753/Waifu2x-Extension/tree/master/Samples/video

# Screenshot
![mainmenu](/screenshot/mainmenu-en.png) 

# Demonstration(v3.5)
![Demonstration-en](/screenshot/Demonstration-en.gif) 

# How to fix compatibility issue :
#### waifu2x-ncnn-vulkan:
Re-install gpu driver or update it to the latest.
#### waifu2x-converter:
Buy a new computer.
#### Anime4k:
Install the latest JDK and JRE

# Integrated component(In releases):
- waifu2x-ncnn-vulkan version 20190712

- Anime4K Java v0.9 Beta

- ffmpeg version 4.2.1

- gifsicle version 1.92

- Waifu2x-converter version: 2015-11-30T02:17:24

- ImageMagick 7.0.8-68 Q16 x64 2019-10-05


# Credits:
- waifu2x-ncnn-vulkan: https://github.com/nihui/waifu2x-ncnn-vulkan

- FFmpeg: https://ffmpeg.org/

- Gifsicle: https://www.lcdf.org/gifsicle/

- Anime4K: https://github.com/bloc97/Anime4K

- Waifu2x-converter: https://github.com/WL-Amigo/waifu2x-converter-cpp

- ImageMagick: http://www.imagemagick.org/

- Icons made by : Freepik (https://www.flaticon.com/authors/freepik) From Flaticon : https://www.flaticon.com/

# `Donate`

## If this extension helps you, please donate to support developers.

![donate](/donate.jpg)



### Note: The user agreement of the software is modified based on the MIT protocol, allowing others to make secondary modifications to the software or to use the software-processed images, gifs, and videos for commercial purposes (via the consent of the original author of the image, gif, and video content) However, it is forbidden to use the software for commercial use after the second modification, including but not limited to secondary packaging and sales(for example: sale this software on Taobao or Ebay), integrated in other charging software. After the second modification, the source code must be disclosed. For details, please refer to the built-in user agreement. When you open the software, or modify the software, you agree to the software built-in agreement.
