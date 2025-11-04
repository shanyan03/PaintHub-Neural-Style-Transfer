# PaintHub — Neural Style Transfer (TensorFlow + Tkinter GUI)

**One-liner:** Turn any photo into art in the style of **Van Gogh, Munch, or Picasso** using neural style transfer, wrapped in a simple **Tkinter** desktop GUI.

## What’s here
- `Main.ipynb` — end-to-end notebook (core NST logic + quick tests)
- `app/` — GUI code and assets (browse image, pick style, apply, save)
- `styles/` — built-in style images (Van Gogh / Munch / Picasso)
- `samples/` — example content & outputs for the README
- `requirements.txt` — minimal dependencies

## Notebooks
View directly on GitHub:
- **Neural Style Transfer** → [`Main.ipynb`](Main.ipynb)  
  Loads a content image + selected style, extracts content/style stats via a CNN, and optimizes an output image to match **content** of the photo and **style** of the painting.

## Highlights
- **Classic NST (Gatys et al.)** implementation with TensorFlow: optimize an image to match content & style feature stats  
- **Fast & simple GUI**: pick an image, choose a style (Van Gogh / Munch / Picasso), press **Apply**, then **Download**
- **Reproducible**: notebook for experiments, GUI for end users
- **Extensible**: drop new style images into `styles/` and they appear in the GUI

## Getting started
~ upon running the main.py file ~

1. Click <START> to proceed. 

2. Click <BROWSE IMAGE> to choose your image of choice. 

3. Click <Next> to proceed after selecting your image. 

4. Explore your style choices by clicking <VAN GOGH> / <PICASSO> / <MUNCH>. 

5. After choosing your preferred style, click <APPLY> to initiate transformation process. 

6. You will be directed to the Main Menu again. Click <QUIT> to proceed with the selected image. Click <StART> to choose a new image again.

7. Wait patiently until a window pops up, displaying your new generated image.

8. Click <DOWNLOAD> to save the generated image. 

9. A dialogue box should pop up showing your downloaded image file directory. 


Enjoy using PaintHub!

## Demo
[![Watch the demo](Inputpenguin.jpeg.jpg)](demo/Painthub_demo.mp4)

## Author
Lee Shan Yan 
