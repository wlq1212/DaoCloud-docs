# Service Mesh

On this page, you can download offline packages for different versions of the service mesh module.

## Download

| Version   | Architecture | File Size |  Package      | Checksum File | Update Date |
|----------|--------------|-----------|----------------|----------|-------------|
| [v0.21.1](../../mspider/intro/release-notes.md) | AMD 64 | 905.15MB | [:arrow_down: mspider_v0.21.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.21.1_amd64.tar) | [:arrow_down: mspider_v0.21.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.21.1_amd64_checksum.sha512sum) | 2023-12-05 |
| [v0.21.0](../../mspider/intro/release-notes.md) | AMD 64 | 905.15MB | [:arrow_down: mspider_v0.21.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.21.0_amd64.tar) | [:arrow_down: mspider_v0.21.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.21.0_amd64_checksum.sha512sum) | 2023-12-04 |
| [v0.20.3](../../mspider/intro/release-notes.md) | AMD 64 | 949.49MB | [:arrow_down: mspider_v0.20.3_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.3_amd64.tar) | [:arrow_down: mspider_v0.20.3_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.3_amd64_checksum.sha512sum) | 2023-10-27 |
| [v0.20.2](../../mspider/intro/release-notes.md) | AMD 64 | 949.41 MB | [:arrow_down: mspider_v0.20.2_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.2_amd64.tar) | [:arrow_down: mspider_v0.20.2_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.2_amd64_checksum.sha512sum) | 2023-10-18 |
| [v0.20.1](../../mspider/intro/release-notes.md) | AMD 64 | 949.41 MB | [:arrow_down: mspider_v0.20.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.1_amd64.tar) | [:arrow_down: mspider_v0.20.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.1_amd64_checksum.sha512sum) | 2023-10-13 |
| [v0.20.0](../../mspider/intro/release-notes.md) | AMD 64 | 949.40 MB | [:arrow_down: mspider_v0.20.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.0_amd64.tar) | [:arrow_down: mspider_v0.20.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.20.0_amd64_checksum.sha512sum) | 2023-10-12 |
| [v0.19.0](../../mspider/intro/release-notes.md) | AMD 64 | 866.88 MB | [:arrow_down: mspider_v0.19.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.19.0_amd64.tar) | [:arrow_down: mspider_v0.19.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.19.0_amd64_checksum.sha512sum) | 2023-08-31 |
| [v0.18.0](../../mspider/intro/release-notes.md) | AMD64        | 2.41 GB   | [:arrow_down: mspider_v0.18.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.18.0_x86_64.tar) | [:arrow_down: mspider_v0.18.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mspider_v0.18.0_x86_64_checksum.sha512sum) | 2023-08-23   |

## Validation

In the directory where you downloaded the offline package and checksum file,
take v0.18.0 as an example and run the following command to validate the integrity:

```sh
echo "$(cat mspider_v0.18.0_amd64_checksum.sha512sum)" | sha512sum -c
```

If the validation is successful, the result will be similar to:

```none
mspider_v0.18.0_amd64.tar: ok
```

## Installation

If this is your first installation, please [apply for a free trial](../../dce/license0.md)
or contact us for authorization: send an email to info@daocloud.io or call 400 002 6898.
If you have any questions regarding license keys, please contact the DaoCloud delivery team.
