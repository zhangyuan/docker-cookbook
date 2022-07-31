# Docker Cookbook

## Docker 的基本用法

### 从容器中访问宿主机

> 参考 https://docs.docker.com/desktop/networking/#i-want-to-connect-from-a-container-to-a-service-on-the-host

### 使用 .dockerignore 忽略文件

> 参考 https://docs.docker.com/engine/reference/builder/#dockerignore-file

## 编写 Dockerfile

### Use non-root user

### Use tini

> 参考 https://github.com/krallin/tini

### Install dependencies before adding code

### Multi-stage builds

> 参考 https://docs.docker.com/develop/develop-images/multistage-build/

## 使用 Docker Compose 编排容器

### 使用多个docker-compose.yaml文件进行组合

> 参考

### 使用环境变量及其默认值

> 参考 https://docs.docker.com/compose/environment-variables/

#### 定义环境变量及其默认值

#### 使用环境文件

### 控制容器的启动顺序

> 参考 https://github.com/compose-spec/compose-spec/blob/master/spec.md#depends_on

#### 在其他容器启动后启动

#### 在其他容器健康后启动

#### 在其他容器成功运行并退出后启动

### Build the specified stage as defined inside the Dockerfile

## Maintain the freshness of Docker image references

> 参考 https://github.com/realestate-com-au/dfresh 


## 镜像的安全
