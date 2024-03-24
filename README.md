<div align="center">
## Vision-Language Model-based Physical Reasoning for Robot Liquid Perception
<img src="https://github.com/laiwenq/VLM_liquid_perception/blob/main/flowchart.png?raw=true" style="width:800px;"/>


![](https://img.shields.io/badge/License-Apache_2.0-green)

---
</div>

## 🎥 Demo Video

[![Demo]([https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fyoutu.be%2LX4WZmvsNmw](https://github.com/laiwenq/VLM_liquid_perception/blob/main/video_cover_img.png?raw=true))](https://youtu.be/LX4WZmvsNmw)

- Hardware and Materials used in Demo: 
   * 6-DoF mobile robot arm with wrist-mounted F/T sensor.
   * High-resolution RGB-D camera on a tripod.
   * Three common household liquids: Peanut Oil, Soy Sauce, and Whiskey.

## Install Dependencies

To install necessary dependencies, run: 

```bash
git clone git@github.com:laiwenq/VLM_liquid_perception.git
pip install -r requiremetns.txt
```

We use OpenAI's `gpt-4-vision-preview` as the backbone LVLM API. Feel free to change it to your own models. 

## Evaluation on Liquid Perception and Recognition Tasks
We have put all codes needed for the evaluation in a Jupyter Notebook. We also provide the full prompts and evaluation data for you to have a try. Feel free to replace the actions with real robotic actions for an online evaluation!
