# Getting Started

## Linux/MacOS

Copy the contents of the `models` directory to your home gazebo folder `$HOME/.gazebo/models`
```bash
$ mkdir -p "$HOME/.gazebo/models"
$ cp -r models/* "$HOME/.gazebo/models"
```

## Running `gazebo`

To view the challenge worlds, you can just run
```bash
$ gazebo challenge_[1|2|3].world
```

**ISSUES**
 * I'm getting a `VMware: vmw_ioctl_command error Invalid argument`.
Run the below command before launching `gazebo`.
Reference https://answers.gazebosim.org//question/13214/virtual-machine-not-launching-gazebo/
```bash
$ export SVGA_VGPU10=0
```

