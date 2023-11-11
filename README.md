# PPO Experiments

This repo contains most of the code for the blog post "Advancements in PPO". You can read the blog post at https://go281.user.srcf.net/blog/ppo.


## Install

* Python (tested with 3.7)
* Mujoco (download from v1.5.0 from https://www.roboti.us/download.html)

```
pip install -r requirements.txt
```

## Run

Train agents with experiment tracking:
```
python ppo_critic_first.py --gym-id CartPole-v1 --cuda --seed 0
```

## Acknowledgements
This code is modified from the incredible blog post ["The 37 Implementation Details of Proximal Policy Optimization"](https://iclr-blog-track.github.io/2022/03/25/ppo-implementation-details/) and related code https://github.com/vwxyzjn/ppo-implementation-details.

To see more of the code for the project, see https://github.com/George-Ogden/spinningup.