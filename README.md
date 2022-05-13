# config-nacos
# Why develop this project

# 如果分开编写nacos的dataid时，需注意Data ID格式：${prefix}-${spring.profiles.active}.${file-extension}
推荐直接写：spring.cloud.nacos.config.refreshable-dataids=user-provider-dev.properties
