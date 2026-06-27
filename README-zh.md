## LoongArch Gradle Docker 镜像

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

为 LoongArch（loong64）架构预构建的 Gradle Docker 镜像，基于 [jdk-loong64](https://github.com/kubernetes-loong64/jdk-loong64) 构建。

## 基于 AnolisOS 龙蜥系统

- [![kubernetesloong64/gradle-loong64:9.6.0-8-anolis](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-8-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-11-anolis](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-11-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-17-anolis](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-17-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-21-anolis](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-21-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-25-anolis](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-25-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-26-anolis](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-26-anolis?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)

## 基于 Debian 系统

- [![kubernetesloong64/gradle-loong64:9.6.0-8-debian](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-8-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-11-debian](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-11-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-17-debian](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-17-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-21-debian](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-21-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-25-debian](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-25-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)
- [![kubernetesloong64/gradle-loong64:9.6.0-26-debian](https://img.shields.io/docker/v/kubernetesloong64/gradle-loong64/9.6.0-26-debian?arch=loong64&logo=docker&label=kubernetesloong64%2Fgradle-loong64)](https://hub.docker.com/r/kubernetesloong64/gradle-loong64/tags)

### 支持的 JDK 版本

| JDK | 支持 |
|-----|----|
| 8   | ✅  |
| 11  | ✅  |
| 17  | ✅  |
| 21  | ✅  |
| 25  | ✅  |
| 26  | ✅  |

### 支持的基础镜像

| 操作系统   | 基础镜像                      |
|--------|---------------------------|
| anolis | openanolis/anolisos:23.4  |
| debian | lcr.loongnix.cn/debian:14 |

### 拉取镜像

镜像发布在 Docker Hub 上 [`kubernetesloong64/gradle-loong64`](https://hub.docker.com/r/kubernetesloong64/gradle-loong64)。

```shell
# JDK 8 (anolis)
docker pull kubernetesloong64/gradle-loong64:9.6.0-8-anolis

# JDK 8 (debian)
docker pull kubernetesloong64/gradle-loong64:9.6.0-8-debian

# JDK 11 (anolis)
docker pull kubernetesloong64/gradle-loong64:9.6.0-11-anolis

# JDK 11 (debian)
docker pull kubernetesloong64/gradle-loong64:9.6.0-11-debian

# JDK 17 (anolis)
docker pull kubernetesloong64/gradle-loong64:9.6.0-17-anolis

# JDK 17 (debian)
docker pull kubernetesloong64/gradle-loong64:9.6.0-17-debian

# JDK 21 (anolis)
docker pull kubernetesloong64/gradle-loong64:9.6.0-21-anolis

# JDK 21 (debian)
docker pull kubernetesloong64/gradle-loong64:9.6.0-21-debian

# JDK 25 (anolis)
docker pull kubernetesloong64/gradle-loong64:9.6.0-25-anolis

# JDK 25 (debian)
docker pull kubernetesloong64/gradle-loong64:9.6.0-25-debian

# JDK 26 (anolis)
docker pull kubernetesloong64/gradle-loong64:9.6.0-26-anolis

# JDK 26 (debian)
docker pull kubernetesloong64/gradle-loong64:9.6.0-26-debian
```

### 使用

```shell
# JDK 8
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-8-anolis gradle --version
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-8-debian gradle --version

# JDK 11
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-11-anolis gradle --version
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-11-debian gradle --version

# JDK 17
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-17-anolis gradle --version
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-17-debian gradle --version

# JDK 21
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-21-anolis gradle --version
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-21-debian gradle --version

# JDK 25
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-25-anolis gradle --version
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-25-debian gradle --version

# JDK 26
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-26-anolis gradle --version
docker run --rm kubernetesloong64/gradle-loong64:9.6.0-26-debian gradle --version
```

### 多阶段构建

此镜像可用于多阶段 Docker 构建。将其与构建阶段结合，在 LoongArch 上编译 Java 项目：

```dockerfile
ARG JDK_VERSION=26

FROM kubernetesloong64/gradle-loong64:9.6.0-${JDK_VERSION}-debian AS builder
COPY . /project
WORKDIR /project
RUN gradle build --no-daemon

FROM kubernetesloong64/jdk-loong64:${JDK_VERSION}-debian
COPY --from=builder /project/build/libs/*.jar /app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]
```

## 许可证

[Apache License 2.0](LICENSE)
