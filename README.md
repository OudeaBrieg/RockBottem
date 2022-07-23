conda create -n name_for_your_environment python=3.8
conda activate name_for_your_environment
pip install "ray[rllib]" tensorflow torch
pip install gym
pip install gym[all]
pip install ffmpeg
pip install imageio-ffmpeg