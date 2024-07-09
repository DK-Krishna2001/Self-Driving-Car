# Autopilot-TensorFlow

A TensorFlow implementation of this [Project Paper](https://drive.google.com/file/d/1F8SG0vI02mVD3aAkk2v4TmH_5pRTGzx3/view?usp=sharing) with some changes.

## IMPORTANT

Absolutely, under **NO** circumstance, should one ever pilot a car using computer vision software trained with this code (or any homemade software for that matter). It is extremely dangerous to use your self-driving software in a car, even if you think you know what you're doing, not to mention it is quite illegal in most places and any accidents will land you in huge lawsuits.

This code is purely for research and statistics, absolutely **NOT** for application or testing of any sort.

## How to Use

1. Download the [driving dataset](https://github.com/K96guestzone/Driving-Dataset) and extract it into the repository folder.
2. Use `python train.py` to train the model.
3. Use `python run.py` to run the model on a live webcam feed.
4. Use `python run_dataset.py` to run the model on the dataset.
5. To visualize training using Tensorboard, use `tensorboard --logdir=./logs`, then open [http://0.0.0.0:6006](http://0.0.0.0:6006) in your web browser.
