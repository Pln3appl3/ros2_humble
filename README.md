Ros2 humble packages for Debian Bookworm 64-bit and made to help install SLAM packages for my project.

```
# Install necessary packages
sudo apt update
sudo apt install -y git colcon python3-rosdep2 vcstool wget \
python3-flake8-docstrings python3-pip python3-pytest-cov \
python3-flake8-blind-except python3-flake8-builtins \
python3-flake8-class-newline python3-flake8-comprehensions \
python3-flake8-deprecated python3-flake8-import-order \
python3-flake8-quotes python3-pytest-repeat python3-pytest-rerunfailures \
python3-vcstools libx11-dev libxrandr-dev libasio-dev libtinyxml2-dev

# Build
colcon build --symlink-install

# I have not tested this yet and just kept it in case i need to reinstall ros2_humble for my project so it may not work as intended with just the code above.
