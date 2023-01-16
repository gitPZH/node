# TopFreeProxies
[![GitHub Workflow Status](https://github.com/1904240502/node/actions/workflows/get-proxies.yml/badge.svg)](https://github.com/1904240502/node/actions/workflows/get-proxies.yml) 

![Watchers](https://img.shields.io/github/watchers/1904240502/node) ![Stars](https://img.shields.io/github/stars/1904240502/node) ![Forks](https://img.shields.io/github/forks/1904240502/node) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=1904240502.node) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/1904240502/node#仓库介绍) | [使用方法](https://github.com/1904240502/node#使用方法) | [节点信息](https://github.com/1904240502/node#节点信息) | [软件推荐](https://github.com/1904240502/node#客户端选择) | [仓库声明](https://github.com/1904240502/node#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `base`(Base64) 和 `clash.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/1904240502/node/master/base)
- [Clash](https://raw.githubusercontent.com/1904240502/node/master/clash.yaml)



另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/1904240502/node@master/base)
- [Clash](https://fastly.jsdelivr.net/gh/1904240502/node@master/clash.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `93`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiU0dfQXphZE5ldCg1KSIsImFkZCI6IjE4LjE0My4xMjMuMzUiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjhkZjQ4MzgtNDZkMC00YjViLWMzZjAtYTQwZWM3MDYzMjQ1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiU0dfQXphZE5ldCgxMykiLCJhZGQiOiIxMzkuOTkuOTEuOTUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_AzadNet%2818%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMTYwMjIiLCJhZGQiOiIxMy4xMjQuMi4yNDciLCJwb3J0IjoiMTIzNCIsInR5cGUiOiJub25lIiwiaWQiOiI4MjIwYmZlZS04NGM2LTQwZTMtZDYyOC05ZTFjMmMxY2M4YmQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2JiIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAxMTYxMTk5IiwiYWRkIjoiMTMuMjMwLjE4LjEyNCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI0YTQwNDdjNC0wODZhLTQ4NjEtYjVmMy01M2JmZTQ5ZDdmZjgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3Z2di83NDk0NjczNDUwMTMyNDE4NzAiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgW1ZNZXNzXSDwn4e48J+HrCBTR+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiMTUuMjM1LjE0Ny4xODYiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNmZlYTE2NDktNDI1Yi00MDkyLWJmNTMtMjk3OTIxNTJjOTI1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zc2hraXQvRXJ0dXNnODYvNjM1MDE0NjM4YzI2NC8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgZ2l0aHViLmNvbS9mcmVlZnEgLSDmlrDliqDlnaFPVkggMiIsImFkZCI6IjEzOS45OS42MS4xNTQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTMyYTFmMGQtZjVjZS00MThkLTg1NjAtYzg4ZjUzYzUzNGI5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92bWVzcyIsImhvc3QiOiIxMzkuOTkuNjEuMTU0IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgW1ZNZXNzXSDwn4et8J+HsCBIS+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiYXpoay5ldmFlbGZpZWRhbW5nbWFpbC54eXoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDdjMTNjNjItMmRjMS00ODcxLThhYTAtYzNkMjE1NjhjZDVhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiZ3cuYWxpY2RuLmNvbSIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.138:810#SG_AzadNet%288%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:808#SG_AzadNet%2823%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMikiLCJhZGQiOiI4LjIxMC4yNTMuOTMiLCJwb3J0IjoiMzEwODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZDIwNzBiOTctNmQ3Yy00NGRjLTljN2MtODRhOWM4OTE4MTVlIiwiYWlkIjoiMCIsIm5ldCI6Imh0dHAiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://RRy34GGwsPt47SuC@154.3.32.164:443?allowInsecure=1&sni=sky998dmit3.xyz#HK_AzadNet
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@16.163.189.245:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%281%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.247.107.26:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%282%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.24.95.62:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%283%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.247.106.224:443?allowInsecure=1&sni=data-tw.efyunpan.com#HK_AzadNet%284%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg1KSIsImFkZCI6IjQ3LjI0Mi43OS4xNjciLCJwb3J0IjoiODQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjODJhYzMxNC0zZGFiLTNkYzYtOTQ4OC1hNTFiYWU4MTkwNjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0Rvd25sb2FkIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg2KSIsImFkZCI6IjguMjE4LjU3LjMyIiwicG9ydCI6Ijg0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzgyYWMzMTQtM2RhYi0zZGM2LTk0ODgtYTUxYmFlODE5MDY1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9Eb3dubG9hZCIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg3KSIsImFkZCI6IjguMjE4LjcyLjIzOCIsInBvcnQiOiI4NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM4MmFjMzE0LTNkYWItM2RjNi05NDg4LWE1MWJhZTgxOTA2NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRG93bmxvYWQiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg4KSIsImFkZCI6IjQ3LjI0My44OS4xNzciLCJwb3J0IjoiODQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjODJhYzMxNC0zZGFiLTNkYzYtOTQ4OC1hNTFiYWU4MTkwNjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0Rvd25sb2FkIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg5KSIsImFkZCI6IjE4Mi4xNi4xLjE5NCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIwMGExZGExNC1kNTVmLTVmNzUtZTM0Ni03OWI5ODVlMWE3MjMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL29wdC92aWRlby9pbWFnZXMiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxMCkiLCJhZGQiOiIyMC4xODcuMTIyLjEzMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjc0NGY1Y2MtZWFiMi1kMmNkLWY0NzctNzY2NDZkMTc5ODdmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wZXRhbHZ3cyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    trojan://aef2ca33-b162-409f-8f16-4c736c338412@20.205.37.136:443?allowInsecure=1#HK_AzadNet%2811%29
    trojan://f8d19ba5-8684-45f2-8523-77dbea588955@ru.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2812%29
    trojan://1bf16b43-0ad5-4512-a0e8-34bb8966278e@ap.stablize.top:443?allowInsecure=1#HK_AzadNet%2815%29
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@ar.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2816%29
    trojan://51c44c4e-f8c2-4419-a52b-b4b7bd915078@ca.liangyuandian.top:443?allowInsecure=1#HK_AzadNet%2820%29
    trojan://b2119912-55bb-4e69-a002-b1d2ae75e47e@jp.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2823%29
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@lux.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2826%29
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@de.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2827%29
    trojan://b27c853c-714a-45a5-be55-6451595a1b69@download2hkt.windowsupdate.lol:443?allowInsecure=1#HK_AzadNet%2829%29
    trojan://d4e41ff772c7fd45@45.11.104.94:3389?allowInsecure=1#HK_AzadNet%2830%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMSkiLCJhZGQiOiI4LjIxMC4xNTMuMjQyIiwicG9ydCI6IjQ4NTc3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImRkM2M1Y2U0LTY3NDEtNGNkYi1hNTRkLWJmNDM0NzU5NjllNSIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:800#HK_AzadNet%2835%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMykiLCJhZGQiOiI0Ny4yNDIuMTY3LjEwNyIsInBvcnQiOiI0MTI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJiYTY3OTAwNS1kYjkxLTQ0MTEtYWI2MC1hMjY0MjM0NmE5Y2QiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzNCkiLCJhZGQiOiI0Ny4yNDIuMC4xMCIsInBvcnQiOiI2MTc4MyIsInR5cGUiOiJub25lIiwiaWQiOiI5OTE5YzcwNS0yZDQ2LTQ0MTEtYmZmMy0yYTQ4NzE5ZWYyYWUiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://7175732d-dee5-4e38-91e1-886f95c2b470@52.196.128.38:50188?allowInsecure=1&sni=jp-tk-32.fuckjdieng.uk#JP_AzadNet%281%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.188.25.73:443?allowInsecure=1&sni=data-tw.efyunpan.com#JP_AzadNet%282%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.222.226.159:443?allowInsecure=1&sni=data-jp.efyunpan.com#JP_AzadNet%284%29
    trojan://b42c2c42-b8ef-4cbe-8443-8870cf10875a@20.188.25.176:443?allowInsecure=1&sni=data-jp.efyunpan.com#JP_AzadNet%285%29
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldCg4KSIsImFkZCI6IjEzOS4xNjIuNzcuMjI4IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjgxODBmN2Y0LTU0YTUtNDdhNS1iNmI5LWRjZGNhZTUxOGQ5NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvVFMvcmVjaGFyZ2UvdHpVcmwuaHRtbCIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldCg5KSIsImFkZCI6IjEzOS4xNjIuMTA3LjExMCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI4MTgwZjdmNC01NGE1LTQ3YTUtYjZiOS1kY2RjYWU1MThkOTUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL1RTL3JlY2hhcmdlL3R6VXJsLmh0bWwiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldCgxMCkiLCJhZGQiOiI0My4yMDYuMTU0LjEzNSIsInBvcnQiOiI4NDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM4MmFjMzE0LTNkYWItM2RjNi05NDg4LWE1MWJhZTgxOTA2NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRG93bmxvYWQiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldCgxMSkiLCJhZGQiOiI0My4yMDcuODIuMTc0IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjgxODBmN2Y0LTU0YTUtNDdhNS1iNmI5LWRjZGNhZTUxOGQ5NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvVFMvcmVjaGFyZ2UvdHpVcmwuaHRtbCIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSlBfQXphZE5ldCgxMikiLCJhZGQiOiIxMy4yMzAuMTA5LjIzMiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI4MTgwZjdmNC01NGE1LTQ3YTUtYjZiOS1kY2RjYWU1MThkOTUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL1RTL3JlY2hhcmdlL3R6VXJsLmh0bWwiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xODgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoibGcxLnRydW1wMjAyMy51cyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMENETiIsImFkZCI6IjE4NS4xNjIuMjI4LjIyOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC00IiwiYWRkIjoiMTcyLjY3LjQ1LjE0NCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfQXphZE5ldCgxNTEpIiwiYWRkIjoiNTAuNy44LjIwNSIsInBvcnQiOiI1NTQ1MCIsInR5cGUiOiJub25lIiwiaWQiOiI0ZjFiODNkNC1mZjNhLTRiZjQtZDRiMy0wYjJiMzdlOWMwMGIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfQXphZE5ldCgxMDQpIiwiYWRkIjoiNTEuODEuMjIwLjE5NSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZmVhMTY0OS00MjViLTQwOTItYmY1My0yOTc5MjE1MmM5MjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaGtpdC83dWplanMvNjM3MmVhYzYxZDU0My8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS05Q0ROIiwiYWRkIjoiMTg1LjE2Mi4yMjguMjI4IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@38.86.135.36:9101#US_AzadNet%28259%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@38.91.101.159:443#US_AzadNet%2857%29
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@38.91.107.72:5003#US_AzadNet%28611%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@38.68.134.196:802#US_AzadNet%2889%29
    ss://YWVzLTI1Ni1nY206UENubkg2U1FTbmZvUzI3@145.239.1.100:8090#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E6%AC%A2%E8%BF%8E%E8%AE%A2%E9%98%85Youtube%E7%A0%B4%E8%A7%A3%E8%B5%84%E6%BA%90%E5%90%9B%29%2014
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS01Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OS4xODkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoibGcxLnRydW1wMjAyMy51cyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS03Q0ROIiwiYWRkIjoiMjAzLjI0LjEwOC44IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    ssr://MTA0LjE0OS4xMzkuMTg5OjEwMDAyOmF1dGhfY2hhaW5fYTphZXMtMjU2LWNmYjp0bHMxLjJfdGlja2V0X2F1dGg6Wkc5dVozUmhhWGRoYm1jdVkyOXQvP2dyb3VwPVUxTlNVSEp2ZG1sa1pYSSZyZW1hcmtzPVZWTmZNVEEwTGpFME9TNHhNemt1TVRnNVh6QXhNRFV5TURJek16SXdaaTB6TVhOekpTVSZvYmZzcGFyYW09JnByb3RvcGFyYW09
    ssr://MTczLjgyLjIzNS4xMjQ6NjAwMDA6YXV0aF9jaGFpbl9hOm5vbmU6cGxhaW46Wm1SelptUnpibkYzYW1oaGMyNWlkMmgxWW1aaFltUmgvP2dyb3VwPVUxTlNVSEp2ZG1sa1pYSSZyZW1hcmtzPThKLUh1dkNmaDdnZ1cxTlRVbDBnOEotSHV2Q2ZoN0lnVlZQamdKRGt1NWpvdExubWpxam9qWkR2dkpwb2RIUndjeTh2ZEhRdWMySnpMM1pwY09PQWtTQXkmb2Jmc3BhcmFtPSZwcm90b3BhcmFtPQ
    trojan://d1478689-439c-4590-b7ce-36e786a02dc3@107.181.161.163:443?allowInsecure=1#US_AzadNet%28361%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDIiLCJhZGQiOiIxMDguMTYyLjE5Mi41NSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZmVhMTY0OS00MjViLTQwOTItYmY1My0yOTc5MjE1MmM5MjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaGtpdC9mZGZhZHNmYS82Mzg0OGJmZTIyOGZkLyIsImhvc3QiOiJ1cy1sYi5zc2hraXQub3JnIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDMiLCJhZGQiOiJ1aWNkbi5jZiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZmVhMTY0OS00MjViLTQwOTItYmY1My0yOTc5MjE1MmM5MjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaGtpdC9mZGZhZHNmYS82Mzg0OGJmZTIyOGZkLyIsImhvc3QiOiJ1cy1sYi5zc2hraXQub3JnIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMTYxNTEzIiwiYWRkIjoiMTYzLjE5Ny4yMTEuMTU5IiwicG9ydCI6IjgwODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTg3ODk2NGEtM2JiMy00ZTQzLWVmZTktYjM3NzdmY2M2N2QwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9oa2FhMCIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoibGcxLnRydW1wMjAyMy51cyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiQ0FfQXphZE5ldCgyKSIsImFkZCI6IjM1LjE4My4xMjguODMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjEyZTA4MjU2LWRhNWQtNGIxYy1hZWNhLThjOTczY2NjZWVmOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRmFsbGluZzQyYXdzeXBjYW5vZGUiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiQ0FfQXphZE5ldCgxKSIsImFkZCI6IjE1OS44OS4xMjAuNjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImYzOGZjMTcwLTkwNGUtNDg1My1jM2JiLWM3MGM4YjgyOGZlNiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0ZhbGxpbmc0MmF3c3lwY2Fub2RlIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS03Q0ROIDIiLCJhZGQiOiIyMDMuMjQuMTA4LjgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoibGcxLnRydW1wMjAyMy51cyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6og5b635Zu9XzAxMTYwMDEiLCJhZGQiOiJvbmNsb3Vkcy5tYW5paGlnaHkuZ2EiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMyZjU1YTg2LTUwZDgtNGUxMy1jYzhhLWU5MGVlMzdhMWI3OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6Im9uY2xvdWRzLm1hbmloaWdoeS5nYSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMENETiAyIiwiYWRkIjoiMTg1LjE2Mi4yMjguMjI5IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0yQ0ROIDIiLCJhZGQiOiIxODguMTE0Ljk5LjExIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS00IiwiYWRkIjoiMTQxLjEwMS4xMTQuMTM0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xNENETiIsImFkZCI6IjE5MC45My4yNDYuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiJsZzEudHJ1bXAyMDIzLnVzIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjM4IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xQ0ROIDIiLCJhZGQiOiIyMDMuMzAuMTkxLjE5MSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiJsZzEudHJ1bXAyMDIzLnVzIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xM0NETiIsImFkZCI6IjE5MC45My4yNDUuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi5Lqa5aSq5Zyw5Yy6IDAwMSIsImFkZCI6IjEwMy4xNjYuMTgzLjIyNiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJlZjkxOWM2Ny02NjM4LTQ0MTYtOTFhZi05YTEzZmZlNWI5Y2EiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3RhbmR1bmcyODguY2xpY2siLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiUlVfQXphZE5ldCgyKSIsImFkZCI6IjkxLjE5My4xODEuMTkyIiwicG9ydCI6IjgwOTAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDhiYzMwZTEtYmUzOS00ZWI0LWU4ODctZTY1NzliZTE1YTQ1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7og5L+E572X5pav6IGU6YKmXzAxMTYwMDYiLCJhZGQiOiIxODUuMjIuMTUzLjE2IiwicG9ydCI6IjMxOTkwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImE2YTM3ZTA0LTVlODEtNDRjOS1iZTUzLWJhYTNmZjQ2ZWI4YiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    trojan://a2c8194b-fcfd-4c39-a6bd-31ea9f4ea671@5.135.235.160:443?allowInsecure=1&sni=upload.soft98.download#FR_AzadNet%2815%29
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMTY3MDUiLCJhZGQiOiIxOTguNDEuMjA1LjE4MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZmVhMTY0OS00MjViLTQwOTItYmY1My0yOTc5MjE1MmM5MjUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaGtpdC9mZGZhZHNmYS82Mzg0OGJmZTIyOGZkLyIsImhvc3QiOiJ1cy1sYi5zc2hraXQub3JnIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS05IiwiYWRkIjoiMjAzLjMwLjE4OC4xMjAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ2MTI2MThjLTI0Y2QtNDM3OS05OTI0LWNmZGYzZDYxZmE1YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvSVlLTEQ1M00iLCJob3N0Ijoib3BmcjEudjJyYXlmcmVlMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@93.186.201.124:810#DE_AzadNet
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@172.99.188.99:2376#172.99.188.992376
    trojan://0c6a3341e8d5ab17@103.172.116.121:3389?allowInsecure=1#mianfeifq%2090
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.48.212:443#43.201.48.212443
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh78g5ZOI6JCo5YWL5pav5Z2mXzAxMTYwMDEiLCJhZGQiOiJrejEudjJyYXlzZXJ2LmNvbSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIyZTliODQ0NS0yZWVkLTQ4ZTYtODlmMi1mOGIyMGNiYjZlMzMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaG9jZWFuIiwiaG9zdCI6Imt6MS52MnJheXNlcnYuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Ht/Cfh7ogZ2l0aHViLmNvbS9mcmVlZnEgLSDkv4TnvZfmlq/ojqvmlq/np5FKdXN0SG9zdCAzIiwiYWRkIjoidjEwYS50b2RkbnMudGsiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiYTI1ODgxZjMtOTY3Zi0zMjY1LWJjN2YtOWU2Njg1N2IwMTZiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9mci11bmxpbWl0eHh4IiwiaG9zdCI6InYxMGEudG9kZG5zLnRrIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@172.99.188.71:5001#NL_AzadNet%2810%29
    

</details>

### 所有节点
合并节点总数: `3134`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `85`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `99`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `147`
- [freefq/free](https://github.com/freefq/free), 节点数量: `38`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `7`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `16`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `3723`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `241`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `7273`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `11`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `41`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `47`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `146`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `16`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `37`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `44`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `2347`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `246`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `323`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `50`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=alanbobs999/TopFreeProxies&type=Date)](https://star-history.com/#alanbobs999/TopFreeProxies&Date)
