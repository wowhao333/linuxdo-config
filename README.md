# Linux DO Config

本项目是 [**Linux DO Script Lite**](https://github.com/wowhao333/linuxdo-script-lite) 的配合项目，用于提供黑名单列表以供主项目同步。

## 简介

此仓库托管了 Linux DO Script Lite 脚本所需的配置文件，目前主要包含用户黑名单列表。通过与此项目配合，主项目可以实现黑名单的云端同步与更新。

## 包含文件

- `user-blocklist.conf`: 用户黑名单配置文件。
  - **格式说明**：文件内容应为一行一个 `username`（用户名），请勿使用 `nickname`（昵称）。

## 使用方法

此项目主要作为配置源存在，一般不需要直接运行。

配合 **Linux DO Script Lite** 使用时，需要提供配置文件的 **Raw 链接**（原始数据链接）。

例如：
`https://raw.githubusercontent.com/wowhao333/linuxdo-config/main/user-blocklist.conf`
（请确保使用您实际仓库的 raw 链接地址）
