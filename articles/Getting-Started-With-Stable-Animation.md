# Stable Animation SDK was released 

Stable Animation SDK was released today. This article summarizes how to get started with Stable Animation. 

# Release Announcement & Resources

- GitHub Notes: https://github.com/rodnavarro/animationsai-content/blob/main/articles/Getting-Started-With-Stable-Animation.md
- https://stability.ai/blog/stable-animation-sdk
- https://platform.stability.ai/docs/features/animation/install

## What this is NOT

- Consistent Character Animation
- Not and Open Source Model Release

## What this is

- Deforum on the cloud 

# Step 1 - Install 

Tested OSX but should be similar on Windows. 

If you don't have python make sure you install. 

```
brew install python
```

## You need to run the UI Locally

```
pip install 'stability_sdk[anim_ui]'  # install the animation SDK
python -m stability_sdk animate --gui # launch the U
```

If you have python3, you need to probably run it like this 

```
pip3 install 'stability_sdk[anim_ui]'  # install the animation SDK
python3 -m stability_sdk animate --gui # launch the U
```

## Install the SDK

### Create a folder for your project

```
mkdir my-project
cd my-project
```

### Create a Python virtual environment
```
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate.bat  # Windows
```
### Install the animation SDK (use [anim_ui] if you'd also like to use the UI)

```
pip install 'stability-sdk[anim]'
```

## Step 2: Generate your first video 

In OSX I had to install the following so the export would work

```
brew install ffmpeg  
```

Else I would get and Error saying ffmpeg folder was not found. 


## Step 3: Publishing your video

Post your video on twitter and mention me @RodMakes. I'd like to see what you came up with. 

In you