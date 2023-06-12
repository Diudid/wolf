# games-on-whales/wolf

[![Linux build and test](https://github.com/games-on-whales/wolf/actions/workflows/linux-build-test.yml/badge.svg)](https://github.com/games-on-whales/wolf/actions/workflows/linux-build-test.yml)
[![Discord](https://img.shields.io/discord/856434175455133727.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/kRGUDHNHt2)
[![GitHub license](https://img.shields.io/github/license/games-on-whales/wolf)](https://github.com/games-on-whales/wolf/blob/main/LICENSE)

> An intelligent wolf is better than a foolish lion.
>
> &mdash; <cite>Matshona Dhliwayo.</cite>

Wolf is a streaming server for [Moonlight](https://moonlight-stream.org/) that allows you to share a single server with
multiple remote clients in order to play videogames!

![Wolf basic flow chart](https://github.com/games-on-whales/wolf/blob/stable/docs/modules/ROOT/images/wolf-introduction.svg?raw=true)

It's made from the ground up with the following primary goals:

- Allow multiple users to stream different content by sharing a single remote host hardware
- Provide low latency video and audio stream with full support for gamepads
- Linux and Docker first: run your games with low privileges in containers (based
  on https://github.com/games-on-whales/gow[Games On Whales])
- Mostly hackable, just edit the config file to modify encoding pipelines, GPU settings or Docker/Podman low level
  details

It's a specific tool for a specific need, are you looking for a general purpose streaming solution?
Try out [Sunshine](https://github.com/LizardByte/Sunshine)!

Want to give it a spin? [Checkout our docs](https://games-on-whales.github.io/wolf/stable/)!

[![Youtube video preview](https://github.com/games-on-whales/wolf/blob/stable/docs/modules/ROOT/images/introduction-video.png?raw=true)](https://www.youtube.com/watch?v=z5jzLIUH6rA)

## Acknowledgements

- https://github.com/Drakulix[@Drakulix] for the incredible help given in developing Wolf
- https://github.com/zb140[@zb140] for the constant help and support in https://github.com/games-on-whales/gow[GOW]
- https://github.com/loki-47-6F-64[@loki-47-6F-64] for creating and
  sharing https://github.com/loki-47-6F-64/sunshine[Sunshine]
- https://github.com/ReenigneArcher[@ReenigneArcher] for beying the first stargazer of the project and taking care of
  keeping https://github.com/LizardByte/Sunshine[Sunshine alive]
- All the guys at the https://moonlight-stream.org/[Moonlight] Discord channel, for the tireless help they provide to
  anyone