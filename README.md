# 基于阿里云Alinux3优化镜像，适配ACR构建
FROM alibaba-cloud-linux-3-registry.cn-hangzhou.cr.aliyuncs.com/alinux3/alinux3:latest
# 容器启动命令，测试用
CMD ["echo", "Hello ACR + GitHub CI/CD!"]
