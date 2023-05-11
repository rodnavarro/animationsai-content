# Stable Animation SDK was released 

Stable Animation SDK was released today. This article summarizes how to get started with Stable Animation. 

# Release Announcement

https://stability.ai/blog/stable-animation-sdk

# What this is NOT

- Consistent Character Animation

# What this is

- Deforum on the cloud 

# Install 

Tested OSX but should be similar on Windows. 

## Running the UI

```
pip install 'stability_sdk[anim_ui]'  # install the animation SDK
python -m stability_sdk animate --gui # launch the U
```

## SDK

### Create a folder for your project
mkdir my-project
cd my-project

### Create a Python virtual environment
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate.bat  # Windows

### Install the animation SDK (use [anim_ui] if you'd also like to use the UI)
pip install 'stability-sdk[anim]'
