# Docker images for drone.io

[![Join the chat at https://gitter.im/Jdesk/drone-images](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Jdesk/drone-images?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

https://drone.io is open-sourced continuous integration service. It runs tests of project inside docker container. 

## Goal

This repo provides Dockerfiles for languages which could run on drone.io.

## Example

If you want to test ruby app, inside .drone.yml file you should have:

```
image: bugagazavr/ruby:2.1.5
```

# Credits

* [Bugagazavr](https://github.com/Bugagazavr)

## License
drone-images is MIT-licensed.
