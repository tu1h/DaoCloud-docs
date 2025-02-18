---
hide:
  - toc
---

# Redis

本页可下载 Redis 各版本的离线安装包。

## 下载

| 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
| ---- | --- | ------ | ------ | ------ | ------- |
| [v0.17.0](../../../middleware/redis/release-notes.md) | <font color=green>ARM 64</font> | 574.00 MB | [:arrow_down: redis_0.17.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.17.0_arm64.tar) | [:arrow_down: redis_0.17.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.17.0_arm64_checksum.sha512sum) | 2024-05-08 |
| [v0.17.0](../../../middleware/redis/release-notes.md) | AMD 64 | 603.14 MB | [:arrow_down: redis_0.17.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.17.0_amd64.tar) | [:arrow_down: redis_0.17.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.17.0_amd64_checksum.sha512sum) | 2024-05-08 |
| [v0.16.0](../../../middleware/redis/release-notes.md) | <font color="green">ARM 64</font> | 571.72 MB | [:arrow_down: redis_0.16.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.16.0_arm64.tar) | [:arrow_down: redis_0.16.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.16.0_arm64_checksum.sha512sum) | 2024-04-03 |
| [v0.16.0](../../../middleware/redis/release-notes.md) | AMD 64 | 600.86 MB | [:arrow_down: redis_0.16.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.16.0_amd64.tar) | [:arrow_down: redis_0.16.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.16.0_amd64_checksum.sha512sum) | 2024-04-03 |
| [v0.15.0](../../../middleware/redis/release-notes.md) | AMD 64 | 591.93 MB | [:arrow_down: redis_0.15.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.15.0_amd64.tar) | [:arrow_down: redis_0.15.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.15.0_amd64_checksum.sha512sum) | 2024-02-01 |
| [v0.14.0](../../../middleware/redis/release-notes.md) | AMD 64 | 536.30 MB | [:arrow_down: redis_0.14.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.14.0_amd64.tar) | [:arrow_down: redis_0.14.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.14.0_amd64_checksum.sha512sum) | 2024-01-04 |
| [v0.13.0](../../../middleware/redis/release-notes.md) | AMD 64 | 534.33 MB | [:arrow_down: redis_0.13.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.13.0_amd64.tar) | [:arrow_down: redis_0.13.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.13.0_amd64_checksum.sha512sum) | 2023-12-10 |
| [v0.12.0](../../../middleware/redis/release-notes.md) | AMD 64 | 531.92 MB | [:arrow_down: redis_0.12.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.12.0_amd64.tar) | [:arrow_down: redis_0.12.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.12.0_amd64_checksum.sha512sum) | 2023-11-08 |
| [v0.11.1](../../../middleware/redis/release-notes.md) | AMD 64 | 537.81 MB | [:arrow_down: redis_0.11.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.11.1_amd64.tar) | [:arrow_down: redis_0.11.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mcamel-redis_0.11.1_amd64_checksum.sha512sum) | 2023-10-20 |

## 校验

在下载离线安装包和校验文件的目录，执行以下命令校验完整性：

```sh
echo "$(cat mcamel-redis_0.11.1_amd64_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
mcamel-redis_0.11.1_amd64.tar: OK
```

## 安装

如果是初次安装，请[申请免费体验](../../../dce/license0.md)或联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。