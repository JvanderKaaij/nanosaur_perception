# 🦕🖼️ nanosaur_perception

 [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) [![Discord](https://img.shields.io/discord/797461428646707211)](https://discord.gg/YvxjxEFPkb) [![GitHub Org's stars](https://img.shields.io/github/stars/rnanosaur?style=social)](https://github.com/rnanosaur) [![Twitter Follow](https://img.shields.io/twitter/follow/raffaello86?style=social)](https://twitter.com/raffaello86)

nanosaur is a little tracked robot [ROS2](https://www.ros.org/) enabled, made for an [NVIDIA Jetson](https://developer.nvidia.com/buy-jetson)

![nanosaur](https://nanosaur.ai/assets/images/intro.jpg)

Meet nanosaur:
* 🦕 Website: [nanosaur.ai](https://nanosaur.ai)
* 🦄 Do you need an help? [Discord](https://discord.gg/YvxjxEFPkb)
* 🧰 For technical details follow [wiki](https://github.com/rnanosaur/nanosaur/wiki)
* 🐳 nanosaur [Docker hub](https://hub.docker.com/u/nanosaur)
* ⁉️ Something wrong? Open an [issue](https://github.com/rnanosaur/nanosaur/issues)
* 🍕 nanosaur is proudly part of [pizzarobotics](https://pizzarobotics.org) community

# CI & CD

**Latest** = ROS2 **_foxy_** at latest tag released

| 🏗️ CI            | latest* | foxy | galactic |
|:-------------:|:-------:|:----:|:--------:|
| 🧠 [core](https://github.com/rnanosaur/nanosaur.git) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=master)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=foxy)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml/badge.svg?branch=galactic)](https://github.com/rnanosaur/nanosaur/actions/workflows/docker-image.yml) |
| 🖼️ [perception](https://github.com/rnanosaur/nanosaur_perception.git)   | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=main)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=foxy)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) | [![Docker Builder CI](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml/badge.svg?branch=galactic)](https://github.com/rnanosaur/nanosaur_perception/actions/workflows/docker-build.yml) |

-------------------------------------

| 🐳 Docker        | latest* | foxy | galactic | Pulls |
|:-------------:|:-------:|:----:|:--------:|:-----:|
| 🧠 [core](https://github.com/rnanosaur/nanosaur.git) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/latest)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/foxy)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/galactic)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🖼️ [perception](https://github.com/rnanosaur/nanosaur_perception.git)    |  [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/latest)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/foxy)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/galactic)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) |

# Build on Jetson device

The command below, build and push (optional) a nanosaur perception docker image
```
. nanosaur_perception/scripts/docker_builder.sh
```

# License

For more information about this project please follow [nanosaur.ai/about](https://nanosaur.ai/about/#license)