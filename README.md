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
高速节点数量: `92`
<details>
  <summary>展开复制节点</summary>

    trojan://da777aae-defb-41d0-a183-2c27da2b4677@150.230.96.103:443?allowInsecure=1&sni=150.230.96.103#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2810%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg1KSIsImFkZCI6IjE1Mi43MC4xMDMuMTk1IiwicG9ydCI6IjM3MjA2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImZmM2ZkMDc4LTk5YjUtNDZiNi04Y2Q1LWQ0OGZmMjcxNzE5YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgW1ZNZXNzXSDwn4et8J+HsCBIS+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIiwiYWRkIjoiaGtibjAzLnRpemkxLm5ldCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2I3MDAxYzctZTQ5NS00MWFjLWI5NDItZjI1ZjYwNTIzNDE0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jbGllbnRhcmVhIiwiaG9zdCI6ImhrYm4wMy50aXppMS5uZXQiLCJ0bHMiOiJ0bHMifQ==
    trojan://8d2d5953-d649-4034-94f2-72f2df2623da@168.138.44.176:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2814%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSIsImFkZCI6IjE4Mi4xNi4xLjE5NCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIwMGExZGExNC1kNTVmLTVmNzUtZTM0Ni03OWI5ODVlMWE3MjMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL29wdC92aWRlby9pbWFnZXMiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSg1KSIsImFkZCI6IjE3Mi4xMDQuMTY3LjI0MCIsInBvcnQiOiI3MjA0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjljNTI3NzZiLTRiMDEtNGFlNi05ZjdkLTI1Y2Q0NzI1ZTEzYyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc2cxIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMzEwMjUiLCJhZGQiOiI0My4xMzQuMTc3LjEzMCIsInBvcnQiOiIyNzgwMyIsInR5cGUiOiJub25lIiwiaWQiOiI0Mjc3OWU3MS0yZTZiLTRlYjQtOWY0My1kZTRlNTdiYjhiMmIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9zZzEiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSgxMSkiLCJhZGQiOiIxMTguMTA3LjU3LjE4MCIsInBvcnQiOiIyNzU0MiIsInR5cGUiOiJub25lIiwiaWQiOiIwYzg4YjVmZS1iMTliLTRiMTctOWFiYi05OWEwODI0ZDA0ZjEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9zZzEiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjQzLjE1NC4zNC40OSIsInBvcnQiOiIyMzE4MyIsInR5cGUiOiJub25lIiwiaWQiOiJiNDAyYTRhZi0yODVhLTQ2M2UtYzNhNy01M2Y5MWVmZGVjNzgiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9zZzEiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_127
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.60:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2818%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSg3KSIsImFkZCI6IjEzOS45OS45MS45NSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3NnMSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.59:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2819%29
    vmess://eyJ2IjoiMiIsInBzIjoiU0dfMTUuMjM1LjE2My4xODBfMDEzMTIwMjNkZDA1LTU5MnZtZXNzIiwiYWRkIjoic2dvdmgxLnYycmF5c2Vydi5jb20iLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNzhmOTM2ZDEtOGE3Mi00YjdjLWFhZmEtYzgyODRlMTVjY2FhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0Ijoic2dvdmgxLnYycmF5c2Vydi5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAxMzEwMTIiLCJhZGQiOiIzLjM1LjEzNC4yMCIsInBvcnQiOiI0NDYyOCIsInR5cGUiOiJub25lIiwiaWQiOiI4ZWM3OGY1NC0wNTFiLTRhZjAtODMyNC0wZDkyNWM3NGM1ZTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0Ijoic2dvdmgxLnYycmF5c2Vydi5jb20iLCJ0bHMiOiIifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@54.254.147.251:804#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2821%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2897%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.20:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2821%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@85.208.108.19:8118#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2879%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.103.37:443#%F0%9F%87%B0%F0%9F%87%B7%20_KR_%E9%9F%A9%E5%9B%BD
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.21:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2820%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.18:443#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2827%29
    trojan://6d64570c-81d4-30fa-b2e2-dce73e1a2702@138.2.45.89:44301?allowInsecure=1&sni=osav101.jd0001.top#%F0%9F%87%AF%F0%9F%87%B5%20%5BTrojan%5D%20%F0%9F%87%AF%F0%9F%87%B5%20JP%E3%80%90%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%EF%BC%9Ahttps%2F%2Ftt.sbs%2Fvip%E3%80%91
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAxMzEwMTciLCJhZGQiOiIxNDYuMTkwLjIwMi45IiwicG9ydCI6IjU3NzExIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZjOTEyODUwLWI2ZGEtNGVjNi05MzQ4LWYzZDFkNzQ3MTkwNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:812#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%289%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1664#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%28171%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@54.169.62.50:443#SG_124
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjE2OC4xMzguMjA2LjE0MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJhZDA1ZTAxZi1jMmMwLTQxZGEtZTc5Yy1mZjY4MjM3MzE3ZjciLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjE2OC4xMzguMTk0LjI0MyIsInBvcnQiOiIzMzQyMSIsInR5cGUiOiJub25lIiwiaWQiOiI5NGU1NmZmOS1jY2YxLTQxNGUtYTExNC00NmUwYTc5ZjY2MTQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg3KSIsImFkZCI6IjE0MS4xNDcuMTgxLjIxOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMGI4NzNjZmYtMTFhYi00NzE2LWM0MWEtMDRmODg2MTM1MDkxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yb2V3ZXN1IiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg4KSIsImFkZCI6IjEzOC4yLjM5LjY3IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiMzM1Yzg4LWQxNGEtNGU2Ny1iNTJjLTU0ZWQ4YmU4MGM0OSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://11a4e5be-3c87-37d2-aac8-00b85ef0fcdc@20.187.108.142:32154?allowInsecure=1&sni=relay-hk-az.fib-sys.cyou#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%288%29
    trojan://c19d1432-8b3e-4818-8837-3d160cf65908@138.2.45.243:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2812%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSg1KSIsImFkZCI6IjQzLjEyOC4xMC4yMzYiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ0ZWE0YTE5LWI5ZTMtNDRiMC1iZDY0LTNkNjBjZmM4Yjg2YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    trojan://6ee96394-2a43-43dc-898b-bbf68a237310@18.177.58.124:50286?allowInsecure=1&sni=jp-tk-31.fuckjdieng.uk#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2815%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgW1ZNZXNzXSDwn4et8J+HsCBIS+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDIiLCJhZGQiOiJ2MS1oay54dHNwZWVkZXIwMDEueHl6IiwicG9ydCI6IjE4MDAxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI2ZmUzYjJjLTEwMDUtMzYyYi05NzAwLTQyNjk2MWNiZDUwYiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJqcC10ay0zMS5mdWNramRpZW5nLnVrIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgW1ZNZXNzXSDwn4e48J+HrCBTR+OAkOS7mOi0ueaOqOiNkO+8mmh0dHBzLy90dC5zYnMvdmlw44CRIDIiLCJhZGQiOiJ2c2cxLjBiYWQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI5MjcwOTRkMy1kNjc4LTQ3NjMtODU5MS1lMjQwZDBiY2FlODciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NoYXQiLCJob3N0IjoidnNnMS4wYmFkLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjguMjEwLjM0LjEwNCIsInBvcnQiOiIyODE4MiIsInR5cGUiOiJub25lIiwiaWQiOiJlM2MwNzRkYy1iY2JiLTQ1YzItYmY1OC05NjMxMGVhNGI5OTkiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSgyKSIsImFkZCI6IjE2Ny4xNzkuMzIuNTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZmZmZmZmZmLWZmZmYtZmZmZi1mZmZmLWZmZmZmZmZmZmZmZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoQXphZE5ldC50Lm1lKSgxKSIsImFkZCI6IjE1MC4yMzAuMjQ5LjE1IiwicG9ydCI6IjQ2ODQyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ1MzBiNWVlLWNlZDQtNGU2NC05Mjg1LTE4NjdmYzVkZjdmOCIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoQXphZE5ldC50Lm1lKSgyKSIsImFkZCI6IjE0NC4yNC44OC4xMDEiLCJwb3J0IjoiMTY4MzMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZjU0MjVjY2YtMzk0Ni00ZmI0LWViMjQtNTM5M2Q3OGEzOTJmIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjEzLjEyNS4xMi40OCIsInBvcnQiOiIyODg1OSIsInR5cGUiOiJub25lIiwiaWQiOiIzYTcxY2FlZi0yOTRiLTQ5MzktYjQ0Ni0zZDA2NjdlZTA4NDIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://b291d129-ee55-4801-a9b8-b5316e5c37b7@138.2.113.84:443?allowInsecure=1#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29%284%29
    trojan://7118b5f4-0ea4-4c11-be7f-11471cb91e4a@144.24.72.126:443?allowInsecure=1&sni=144.24.72.126#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29%285%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:812#%F0%9F%87%A8%F0%9F%87%A6%20CA%28AzadNet.t.me%29%2859%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKSg5KSIsImFkZCI6IjIzLjIzMC4xNDYuMjU0IiwicG9ydCI6IjEyNTgiLCJ0eXBlIjoibm9uZSIsImlkIjoiZWRlYjQxY2MtYTc2YS00N2YyLWZhOTYtYjkxNDFlNjZhMmIwIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IjE0NC4yNC43Mi4xMjYiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC05IiwiYWRkIjoiMjMuMjI3LjM4LjIwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoeegtOino+i1hOa6kOWQmykgMjAiLCJhZGQiOiIxNzIuNjcuNzAuMjIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMyIsImFkZCI6IjE4NS4xNjIuMjI4LjIyOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4NyIsImFkZCI6IjEyOS4xNTkuNDEuMjMzIiwicG9ydCI6IjMyNTg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjM0MWE5MTgyLWM0MjMtNDk5Yy1jNDZlLWQxNzgzOGIyOTAzNyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMCIsImFkZCI6IjIzLjIyNy4zOC4yNyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoeegtOino+i1hOa6kOWQmykgMTQiLCJhZGQiOiIxNzIuNjcuMTY0LjEyNSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2OSIsImFkZCI6IjIwMy4zMC4xOTEuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71BbWF6b24gRUMy5pyN5Yqh5ZmoIDMyIiwiYWRkIjoiMy43MC4yMzkuMTE5IiwicG9ydCI6IjExMTExIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdjYjcyODgzLTk2MzUtNDZlYi04NTMxLThkNjk3OTI3ZmYwNCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xNUNETiIsImFkZCI6IjE5MC45My4yNDUuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiJsZzEudHJ1bXAyMDIzLnVzIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMzEzMTIiLCJhZGQiOiIxNzIuNjcuNDUuMTQ0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My00Q0ROIiwiYWRkIjoiMjAzLjMwLjE5MC4xOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjQwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@169.197.143.232:6379#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2867%29
    ss://YWVzLTI1Ni1nY206a0RXdlhZWm9UQmNHa0M0@169.197.142.48:8882#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2898%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@169.197.142.187:6379#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2868%29
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMzE5MjIiLCJhZGQiOiIxOTguNDEuMjEyLjEyMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMmIyMTQxMjItMTkwNi00MjhhLWJiYjctYTAzOWNiYjdjZDVjIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii85SlpGRFRLRSIsImhvc3QiOiJmcjEudHJ1bXAyMDIzLm9yZyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMyAyIiwiYWRkIjoiMTg1LjE2Mi4yMjguMjI5IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hs/Cfh7Eg6I235YWwXzAxMzEwMTEiLCJhZGQiOiIxODUuMTYyLjIzNS4yNTAiLCJwb3J0IjoiMjA1NCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZjExN2FmNC1jZDUyLTQwZjgtOTIzNi03YzVlM2YzNTdjYzgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NvY2tldC5pbyIsImhvc3QiOiJhY2NvdW50cy5oZXR6bmVyLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMzE5MTgiLCJhZGQiOiIxOTguNDEuMjAzLjYiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJiMjE0MTIyLTE5MDYtNDI4YS1iYmI3LWEwMzljYmI3Y2Q1YyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvOUpaRkRUS0UiLCJob3N0IjoiZnIxLnRydW1wMjAyMy5vcmciLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MiIsImFkZCI6IjIwMy4zMC4xOTEuMTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoeegtOino+i1hOa6kOWQmykgMzMiLCJhZGQiOiIyMDMuMjQuMTA4LjEwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9XzAxMzEwNjgiLCJhZGQiOiIzLjEwLjE4MS42NiIsInBvcnQiOiIxMTExMSIsInR5cGUiOiJub25lIiwiaWQiOiI3Y2I3Mjg4My05NjM1LTQ2ZWItODUzMS04ZDY5NzkyN2ZmMDQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiIifQ==
    trojan://shefelnak@185.16.206.212:443?allowInsecure=1&sni=185.16.206.212#%F0%9F%87%AC%F0%9F%87%A7%20GB%28AzadNet.t.me%29%288%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0yQ0ROIDIiLCJhZGQiOiIxODguMTE0Ljk5LjEwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xM0NETiIsImFkZCI6IjE5MC45My4yNDUuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MSIsImFkZCI6IjIwMy4zMC4xODguMTIxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTAiLCJhZGQiOiIxMDQuMjkuNjQuMzciLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSAxMDEiLCJhZGQiOiIxNTIuNjkuMTk3LjYwIiwicG9ydCI6IjEwNjkiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWM4ZTI2ZmUtODE1MC00YjYwLWFlNjQtODJmYzc3ZWJhMmNmIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6IiJ9
    trojan://e8c1ab3c-89b3-4933-92df-682e6dce7819@152.67.98.30:443?allowInsecure=1#%F0%9F%87%A6%F0%9F%87%BA%20AU%28AzadNet.t.me%29%283%29
    trojan://e05c749b-7c6b-41b8-9c71-9dcf685edf4a@152.67.162.166:443?allowInsecure=1#%F0%9F%87%AE%F0%9F%87%B3%20IN%28AzadNet.t.me%29%281%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTciLCJhZGQiOiIxOTguNDEuMjAzLjE1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xNCIsImFkZCI6IjE5MC45My4yNDUuMTcwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xNSIsImFkZCI6IjE5MC45My4yNDYuMTk1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xOTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xMyIsImFkZCI6IjE5MC45My4yNDQuMjAwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMCAyIiwiYWRkIjoiMjMuMjI3LjM4LjI3IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTUiLCJhZGQiOiIxODUuMTYyLjIyOC4xMTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMENETiAyIiwiYWRkIjoiMTQxLjEwMS4xMTQuMzIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xQ0ROIDIiLCJhZGQiOiIyMDMuMzAuMTkxLjE5MyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    

</details>

### 所有节点
合并节点总数: `1020`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `141`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `100`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `39`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `1`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `3333`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `213`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `242`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `49`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `37`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `50`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `208`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `85`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `35`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `24`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `2522`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `227`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `301`
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
