# Reinforcement Learning Hackathon - Deep Learning Labs (by Nextgrid) 

## Context

On July 25. 2022, a Reinforcement Learning online Hackathon was held by Deep Learning Labs (Nextgrid), for which the main goal was to answer 3 very famous Reinforcement Learning Open AI's Gym Challenges :

  * Cart Pole
  * Lunar Lander
  * Bipedal Walker

Here are 3 Jupyter Notebooks, containing each core challenge, providing a way to parallelize the training of the agents in each environment.

## Requirements

First, make sure you have Anaconda (conda), Jupyter Notebook and pip installed

### Create and activate environment:

```
conda create -n name_for_your_environment python=3.8
```

```
conda activate name_for_your_environment
```

### Install all project's dependencies

```
pip install "ray[rllib]" tensorflow torch
```

```
pip install gym
```

```
pip install gym[all]
```

```
pip install ffmpeg
```

```
pip install imageio-ffmpeg
```