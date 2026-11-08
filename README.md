# SO-101 robot learning workshop

Four notebooks take you from a fresh environment to a fine-tuned SmolVLA
policy controlling an SO-101 follower arm:

1. [Environment setup](01_environment.ipynb)
2. [Leader/follower data collection](02_data_collection.ipynb)
3. [SmolVLA training](03_training.ipynb)
4. [Deployment](04_deployment.ipynb)

Open the notebooks in order. Commands that require an interactive terminal, GPU,
or physical robot are presented as copyable terminal commands. Use a terminal
on the machine connected to the hardware, not a remote notebook kernel, for
calibration, teleoperation, recording and deployment.

The examples use a local dataset and do not upload it or the model. They pin a
specific LeRobot source revision; GPU drivers, system libraries and downloaded
model weights are not locked. The default commands assume macOS or Linux with a
POSIX shell, two OpenCV cameras, and an assembled SO-101 leader and follower.
Training expects a CUDA GPU; deployment can run on a different machine.

**Safety:** Robots can move unexpectedly. Secure the arm, clear its workspace,
keep people and loose objects away, and have a person ready to cut motor power.
Only operate under supervision and within the robot's mechanical limits.

## License

This workshop is licensed under the [MIT License](LICENSE). Third-party
dependencies and model weights are subject to their own licenses.
