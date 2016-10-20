# Apache Ant (s6-overlay) Docker Image

[![Docker Pulls](https://img.shields.io/docker/pulls/frekele/ant.svg)](https://hub.docker.com/r/frekele/ant/)
[![Docker Stars](https://img.shields.io/docker/stars/frekele/ant.svg)](https://hub.docker.com/r/frekele/ant/)
[![GitHub issues](https://img.shields.io/github/issues/frekele/docker-ant.svg)](https://github.com/frekele/docker-ant/issues)
[![GitHub forks](https://img.shields.io/github/forks/frekele/docker-ant.svg)](https://github.com/frekele/docker-ant/network)
[![GitHub stars](https://img.shields.io/github/stars/frekele/docker-ant.svg)](https://github.com/frekele/docker-ant/stargazers)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://frekele.github.io/docker-ant/)

[![Ant Image][AntImage]][AntWebsite]

| [Website]  | [GitHub]  | [DockerHub]  |


#### Apache Ant with Oracle JDK Branches:
| Branch                      | From                     | Usage        | Tag Names                           |
| --------------------------- | ------------------------ | ------------ | ------------------------------------|
| [1.9.7-jdk8] - latest       | frekele/java:jdk8        | Production   | 1.9.7-jdk8, latest                  |
| [1.9.7-jdk8u112]            | frekele/java:jdk8u112    | Production   | 1.9.7-jdk8u112                      |
| [1.9.7-jdk8u111]            | frekele/java:jdk8u111    | Production   | 1.9.7-jdk8u111                      |
| [1.9.7-jdk8u102]            | frekele/java:jdk8u102    | Production   | 1.9.7-jdk8u102                      |
| [1.9.7-jdk8u101]            | frekele/java:jdk8u101    | Production   | 1.9.7-jdk8u101                      |
| [1.9.7-jdk8u92]             | frekele/java:jdk8u92     | Production   | 1.9.7-jdk8u92                       |
| [1.9.7-jdk8u91]             | frekele/java:jdk8u91     | Production   | 1.9.7-jdk8u91                       |
| [1.9.7-jdk8u77]             | frekele/java:jdk8u77     | Production   | 1.9.7-jdk8u77                       |
| [1.9.7-jdk8u74]             | frekele/java:jdk8u74     | Production   | 1.9.7-jdk8u74                       |
| [1.9.7-jdk8u73]             | frekele/java:jdk8u73     | Production   | 1.9.7-jdk8u73                       |
| [1.9.7-jdk8u72]             | frekele/java:jdk8u72     | Production   | 1.9.7-jdk8u72                       |
| [1.9.7-jdk8u71]             | frekele/java:jdk8u71     | Production   | 1.9.7-jdk8u71                       |
| [1.9.7-jdk8u66]             | frekele/java:jdk8u66     | Production   | 1.9.7-jdk8u66                       |
| [1.9.7-jdk8u65]             | frekele/java:jdk8u65     | Production   | 1.9.7-jdk8u65                       |
| [1.9.7-jdk8u60]             | frekele/java:jdk8u60     | Production   | 1.9.7-jdk8u60                       |
| [1.9.7-jdk8u51]             | frekele/java:jdk8u51     | Production   | 1.9.7-jdk8u51                       |
| [1.9.7-jdk7]                | frekele/java:jdk7        | Production   | 1.9.7-jdk7                          |
| [1.9.7-jdk7u80]             | frekele/java:jdk7u80     | Production   | 1.9.7-jdk7u80                       |
| [1.9.7-jdk7u79]             | frekele/java:jdk7u79     | Production   | 1.9.7-jdk7u79                       |
| [1.9.7-jdk7u76]             | frekele/java:jdk7u76     | Production   | 1.9.7-jdk7u76                       |
| [1.9.7-jdk7u75]             | frekele/java:jdk7u75     | Production   | 1.9.7-jdk7u75                       |
| [1.9.7-jdk7u72]             | frekele/java:jdk7u72     | Production   | 1.9.7-jdk7u72                       |
| [1.9.7-jdk7u71]             | frekele/java:jdk7u71     | Production   | 1.9.7-jdk7u71                       |
| [dev]                       | frekele/java:jdk8        | Development  | dev                                 |

# Dockerfile extends From:
- https://github.com/frekele/docker-java
- https://hub.docker.com/r/frekele/java


## Relations:
 - https://github.com/just-containers/s6-overlay

### License:
See [ANT LICENSE]

frekele/docker-ant is **licensed** under the **[MIT License]**. The terms of the license are as follows:

    The MIT License (MIT)

    Copyright (c) 2016 Leandro Kersting de Freitas

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

[AntImage]: https://raw.githubusercontent.com/frekele/docker-ant/dev/ant-logo.png
[AntWebsite]: http://ant.apache.org/
[Website]: https://frekele.github.io/docker-ant
[GitHub]: https://github.com/frekele/docker-ant
[DockerHub]: https://hub.docker.com/r/frekele/ant
[ANT LICENSE]: https://github.com/frekele/docker-ant/blob/dev/ANT_LICENSE
[MIT LICENSE]: https://github.com/frekele/docker-ant/blob/dev/LICENSE

[1.9.7-jdk8]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8/Dockerfile
[1.9.7-jdk8u112]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u112/Dockerfile
[1.9.7-jdk8u111]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u111/Dockerfile
[1.9.7-jdk8u102]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u102/Dockerfile
[1.9.7-jdk8u101]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u101/Dockerfile
[1.9.7-jdk8u92]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u92/Dockerfile
[1.9.7-jdk8u91]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u91/Dockerfile
[1.9.7-jdk8u77]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u77/Dockerfile
[1.9.7-jdk8u74]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u74/Dockerfile
[1.9.7-jdk8u73]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u73/Dockerfile
[1.9.7-jdk8u72]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u72/Dockerfile
[1.9.7-jdk8u71]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u71/Dockerfile
[1.9.7-jdk8u66]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u66/Dockerfile
[1.9.7-jdk8u65]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u65/Dockerfile
[1.9.7-jdk8u60]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u60/Dockerfile
[1.9.7-jdk8u51]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u51/Dockerfile
[1.9.7-jdk7]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7/Dockerfile
[1.9.7-jdk7u80]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u80/Dockerfile
[1.9.7-jdk7u79]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u79/Dockerfile
[1.9.7-jdk7u76]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u76/Dockerfile
[1.9.7-jdk7u75]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u75/Dockerfile
[1.9.7-jdk7u72]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u72/Dockerfile
[1.9.7-jdk7u71]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u71/Dockerfile
[dev]: https://github.com/frekele/docker-ant/blob/dev/Dockerfile
