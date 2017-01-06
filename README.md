# Apache Ant (s6-overlay) Docker Image

[![Docker Pulls](https://img.shields.io/docker/pulls/frekele/ant.svg)](https://hub.docker.com/r/frekele/ant/)
[![Docker Stars](https://img.shields.io/docker/stars/frekele/ant.svg)](https://hub.docker.com/r/frekele/ant/)
[![GitHub issues](https://img.shields.io/github/issues/frekele/docker-ant.svg)](https://github.com/frekele/docker-ant/issues)
[![GitHub forks](https://img.shields.io/github/forks/frekele/docker-ant.svg)](https://github.com/frekele/docker-ant/network)
[![GitHub stars](https://img.shields.io/github/stars/frekele/docker-ant.svg)](https://github.com/frekele/docker-ant/stargazers)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://frekele.github.io/docker-ant/)

[![Ant Image][AntImage]][AntWebsite]

| [Website]  | [GitHub]  | [DockerHub]  |

#### Apache Ant 1.10.0 with Oracle JDK Branches:
| Branch                      | From                     | Usage        | Tag Names                            |
| --------------------------- | ------------------------ | ------------ | ------------------------------------ |
| [1.10.0-jdk8] - latest      | frekele/java:jdk8        | Production   | 1.10.0-jdk8, 1.10-jdk8, 1.10, latest |
| [1.10.0-jdk8u112]           | frekele/java:jdk8u112    | Production   | 1.10.0-jdk8u112                      |
| [1.10.0-jdk8u111]           | frekele/java:jdk8u111    | Production   | 1.10.0-jdk8u111                      |
| [1.10.0-jdk8u102]           | frekele/java:jdk8u102    | Production   | 1.10.0-jdk8u102                      |
| [1.10.0-jdk8u101]           | frekele/java:jdk8u101    | Production   | 1.10.0-jdk8u101                      |
| [1.10.0-jdk8u92]            | frekele/java:jdk8u92     | Production   | 1.10.0-jdk8u92                       |
| [1.10.0-jdk8u91]            | frekele/java:jdk8u91     | Production   | 1.10.0-jdk8u91                       |
| [dev]                       | frekele/java:jdk8        | Development  | dev                                  |


#### Apache Ant 1.9.8 with Oracle JDK Branches:
| Branch                      | From                     | Usage        | Tag Names                            |
| --------------------------- | ------------------------ | ------------ | ------------------------------------ |
| [1.9.8-jdk8]                | frekele/java:jdk8        | Production   | 1.9.8-jdk8, 1.9-jdk8, 1.9            |
| [1.9.8-jdk8u112]            | frekele/java:jdk8u112    | Production   | 1.9.8-jdk8u112                       |
| [1.9.8-jdk8u111]            | frekele/java:jdk8u111    | Production   | 1.9.8-jdk8u111                       |
| [1.9.8-jdk8u102]            | frekele/java:jdk8u102    | Production   | 1.9.8-jdk8u102                       |
| [1.9.8-jdk8u101]            | frekele/java:jdk8u101    | Production   | 1.9.8-jdk8u101                       |
| [1.9.8-jdk8u92]             | frekele/java:jdk8u92     | Production   | 1.9.8-jdk8u92                        |
| [1.9.8-jdk8u91]             | frekele/java:jdk8u91     | Production   | 1.9.8-jdk8u91                        |
| [1.9.8-jdk7]                | frekele/java:jdk7        | Production   | 1.9.8-jdk7, 1.9-jdk7                 |
| [1.9.8-jdk7u80]             | frekele/java:jdk7u80     | Production   | 1.9.8-jdk7u80                        |
| [1.9.8-jdk7u79]             | frekele/java:jdk7u79     | Production   | 1.9.8-jdk7u79                        |


#### Apache Ant 1.9.7 with Oracle JDK Branches:
| Branch                      | From                     | Usage        | Tag Names                            |
| --------------------------- | ------------------------ | ------------ | ------------------------------------ |
| [1.9.7-jdk8]                | frekele/java:jdk8        | Production   | 1.9.7-jdk8                           |
| [1.9.7-jdk8u112]            | frekele/java:jdk8u112    | Production   | 1.9.7-jdk8u112                       |
| [1.9.7-jdk8u111]            | frekele/java:jdk8u111    | Production   | 1.9.7-jdk8u111                       |
| [1.9.7-jdk8u102]            | frekele/java:jdk8u102    | Production   | 1.9.7-jdk8u102                       |
| [1.9.7-jdk8u101]            | frekele/java:jdk8u101    | Production   | 1.9.7-jdk8u101                       |
| [1.9.7-jdk8u92]             | frekele/java:jdk8u92     | Production   | 1.9.7-jdk8u92                        |
| [1.9.7-jdk8u91]             | frekele/java:jdk8u91     | Production   | 1.9.7-jdk8u91                        |
| [1.9.7-jdk7]                | frekele/java:jdk7        | Production   | 1.9.7-jdk7                           |
| [1.9.7-jdk7u80]             | frekele/java:jdk7u80     | Production   | 1.9.7-jdk7u80                        |
| [1.9.7-jdk7u79]             | frekele/java:jdk7u79     | Production   | 1.9.7-jdk7u79                        |


***The Apache Ant team currently maintains two lines of development. The 1.9.x releases require Java5 at runtime and 1.10.x requires Java8 at runtime.***

***Both lines are based off of Ant 1.9.7 and the 1.9.x releases are mostly bug fix releases while additional new features are developed for 1.10.x.***

***We recommend using 1.10.x unless you are required to use versions of Java prior to Java8 during the build process.***

- http://ant.apache.org

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

[1.10.0-jdk8]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8/Dockerfile
[1.10.0-jdk8u112]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8u112/Dockerfile
[1.10.0-jdk8u111]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8u111/Dockerfile
[1.10.0-jdk8u102]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8u102/Dockerfile
[1.10.0-jdk8u101]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8u101/Dockerfile
[1.10.0-jdk8u92]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8u92/Dockerfile
[1.10.0-jdk8u91]: https://github.com/frekele/docker-ant/blob/1.10.0-jdk8u91/Dockerfile
[dev]: https://github.com/frekele/docker-ant/blob/dev/Dockerfile

[1.9.8-jdk8]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8/Dockerfile
[1.9.8-jdk8u112]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8u112/Dockerfile
[1.9.8-jdk8u111]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8u111/Dockerfile
[1.9.8-jdk8u102]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8u102/Dockerfile
[1.9.8-jdk8u101]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8u101/Dockerfile
[1.9.8-jdk8u92]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8u92/Dockerfile
[1.9.8-jdk8u91]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk8u91/Dockerfile
[1.9.8-jdk7]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk7/Dockerfile
[1.9.8-jdk7u80]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk7u80/Dockerfile
[1.9.8-jdk7u79]: https://github.com/frekele/docker-ant/blob/1.9.8-jdk7u79/Dockerfile

[1.9.7-jdk8]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8/Dockerfile
[1.9.7-jdk8u112]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u112/Dockerfile
[1.9.7-jdk8u111]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u111/Dockerfile
[1.9.7-jdk8u102]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u102/Dockerfile
[1.9.7-jdk8u101]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u101/Dockerfile
[1.9.7-jdk8u92]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u92/Dockerfile
[1.9.7-jdk8u91]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u91/Dockerfile
[1.9.7-jdk7]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7/Dockerfile
[1.9.7-jdk7u80]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u80/Dockerfile
[1.9.7-jdk7u79]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u79/Dockerfile
