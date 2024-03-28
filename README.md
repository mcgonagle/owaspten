# mcgonagle/owaspten

[![Docker Automated Build](https://img.shields.io/docker/automated/mcgonagle/owaspten.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/owaspten/) [![Apache-2.0 License](https://img.shields.io/github/license/mcgonagle/owaspten.svg?style=flat-square)](https://github.com/mcgonagle/owaspten/blob/master/LICENSE) 

This is a basic Docker image for building and locally previewing [Hovercraft](https://github.com/regebro/hovercraft) presentations. The image is available for public use on Docker Hub at [mcgonagle/owaspten](https://hub.docker.com/r/mcgonagle/owaspten/).

## Usage

To Build:
``` bash
docker build --tag=mcgonagle/owaspten1 .
```

To Run:
``` bash
docker run -it --rm -p "9000:9000" -v mcgonagle/owaspten
```

In a web browser, go to <http://localhost:9000> to view your presentation.
