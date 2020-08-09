# Lane Detection and Obstacle Avoidance
Lane Detection and Obstacle Avoidance Implementation using Jetbot nano


## Project Information

### Introduction

The creation of autonomous vehicles (AVs) has faced several challenges as mankind has developed up the levels of vehicular automation. Among these major challenges, two that stand out, in particular, are lane detection and obstacle avoidance. Being able to keep an AV inside a lane and aware of obstacles as the road/track around them changes is a major concern that needs to be addressed if a level five (fully autonomous) vehicle is going to be available one day.


### Project Goals
Our team will retrain the road following model pytorch resnet18 included with the jetbot developer kit to enable the bot to autonomously follow a custom track road. Additionally, this model will be combined with the collision avoidance model torchvision.models.alexnet such that the bot is capable of avoiding obstacles on the road

### Hardware

- SparkFun Jetbot AI Kit (powered by Nvidia Jetson Nano)
- Nvidia Jetson Nano Developer Kit (powered by Nvidia Jetson Nano)
- Waveshare JetBot AI Kit (powered by Nvidia Jetson Nano)
- Non-specific Robot: [Bill of Materials link!](https://github.com/NVIDIA-AI-IOT/jetbot/wiki/bill-of-materials)

### Team Members
Roles are intended to be flexible to a degree. As such do not construe the following roles provided as a highly strict guideline. Details on various roles found here.

- **Khalid Aliweh**  - Team Leader/Builder/Programmer
- **Zane Hernandez** - Programmer/Documentation
- **Ishaan Bhagat** - Graphic Designer/Videographer/Builder
- **Alejandro Montero** - Programmer/Builder
- **Favion Harvard** - Programmer/Builder
- **Asia Vines** - Programmer/Documentation
- **Oscar Anchondo** - Programmer/Documentation/Builder

### Demos

- Khalid Aliweh: [Demo](https://youtu.be/j1x1JDPp2Rw)
- Ishaan Bhagat: [Demo](https://youtu.be/i5l7NZMESuA)
- Zane Hernandez: [Demo](https://www.youtube.com/watch?v=eUa12wc0jus&feature=youtu.be)
- Oscar Anchondo: [Demo](https://youtu.be/og7AqwqMF_c)


### Repo Structure

- **JetbotOriginalNotebooks/***  Directory for the original jetbot notebooks from the jetbot repo [here](https://github.com/NVIDIA-AI-IOT/jetbot/blob/65d9eec48956dda868086dd01c7d8a3c47fb56ba/notebooks/road_following/live_demo.ipynb)
- **Data/contributer_name/***    Directory for the datasets, notebooks and models for the track and collision avoidance custom models
- **Demos/contributer_name/***   Directory for the video demos from each contributer
