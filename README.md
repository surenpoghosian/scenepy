# ScenePy

A tool for saving time on conference video post-production through automation



### Don't forget to install the ffmpeg command line tools first

For <b>MacOS</b>
```
brew install ffmpeg
```

For <b>Linux</b> (not verified)
```
sudo apt install ffmpeg
```

For <b>Windows</b> refer to [this page](https://ffmpeg.org/download.html#build-windows) (not verified)


# How to use this tool

1. synchronize your videos by using the `sync.ipynb`

    Configure the working folder paths and name your files `input1.mp4` (speaker video) and `input2.mp4` (presentation) accordingly

2. create the final video by using `main.ipynb` by utilizing the configurations at the beginning of the notebook

    If you applied the `sync.ipynb` to your videos then you already have `video1_synced.mp4` and `video2_synced.mp4` and can run the `main.ipynb`           notebook.

    The final video will be called `final_output.mp4` located at the same folder as the original videos.

`WARNING: always make copies of your original videos, the code is modifying the original files along the way.`

## How it looks like in practice

This is how the main video frame will look like at the end.

<img width="auto" height="848" alt="frame" src="https://github.com/user-attachments/assets/256cc54a-435c-42f1-b414-e185df8d91ac" />

<br/>
<br/>
<br/>

And this is the banner that shows up for the first 5 seconds of the video

<img width="auto" height="848" alt="banner" src="https://github.com/user-attachments/assets/b9c04c43-6da9-4d16-89bf-527cb8dfc6f3" />
