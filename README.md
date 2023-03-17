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

    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.207.166.104:443#%F0%9F%87%AF%F0%9F%87%B5%20_JP_%E6%97%A5%E6%9C%AC%202
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu944CQ5LuY6LS55o6o6I2Q77yaaHR0cHMvL3YxLm1rL3ZpcOOAkTIzMCIsImFkZCI6IjEzMC4xNjIuMTM0LjIxOCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJiYjJmN2E0ZS05N2YyLTRkMjEtZGJhMS1iMDY5OWM1Y2RmYTIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3d3IiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@ak1674.www.outline.network.fr8678825324247b8176d59f83c30bd94d23d2e3ac5cd4a743bkwqeikvdyufr.cyou:5601#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_11
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.94:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_15
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKV8zIiwiYWRkIjoiNDMuMTU0LjM0LjQ5IiwicG9ydCI6IjIzMTgzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImI0MDJhNGFmLTI4NWEtNDYzZS1jM2E3LTUzZjkxZWZkZWM3OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3d3IiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_24
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0SHViMmY5SnloRUN5QXEyT3BtME5T@51.79.161.232:443#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_19
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.20:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_3
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1662#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_141
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.91:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_13
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTp0dlgxdiNOU0ZQX0xHX2JK@54.169.160.39:801#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_17
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.59:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_8
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.60:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKV85IiwiYWRkIjoiMTM5Ljk5LjkxLjk1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjMDE1NjQ1MS00ZWZiLTQ1ZTItODRmYy04ZDMxNWM0NjUwZGIiLCJhaWQiOiIzMiIsIm5ldCI6InRjcCIsInBhdGgiOiIvd3ciLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.21:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_5
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.90:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_11
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.41:806#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_15
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.49:801#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_29
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.18:8000#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_1
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.52:809#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_37
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.5.19:8099#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_10
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@176.97.70.125:989#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_84
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.37.176:443#%F0%9F%87%B0%F0%9F%87%B7%20%E9%9F%A9%E5%9B%BD%E3%80%90%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%EF%BC%9Ahttps%2F%2Fv1.mk%2Fvip%E3%80%91143
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@158.247.213.230:989#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29_10
    trojan://b291d129-ee55-4801-a9b8-b5316e5c37b7@138.2.113.84:443?allowInsecure=1&sni=jgwcc3.gaox.ml#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29_1
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKV80IiwiYWRkIjoicGV0YWwuZ2EiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImI3NDRmNWNjLWVhYjItZDJjZC1mNDc3LTc2NjQ2ZDE3OTg3ZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcGV0YWx2d3MiLCJob3N0IjoicGV0YWwuZ2EiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@176.97.65.241:989#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_43
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7MgZ2l0aHViLmNvbS9mcmVlZnEgLSDlj7Dmub7nnIHmlrDljJfluILkuK3ljY7nlLXkv6EgMTIiLCJhZGQiOiJoaW5ldDEyNjEuZ2Z3aXNiZXN0Lnh5eiIsInBvcnQiOiIyMjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjI4NTEzM2UtYjliYS0zZmI1LWEyNDYtOWM3ZGRjYzJjZDdhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvcGV0YWx2d3MiLCJob3N0IjoicGV0YWwuZ2EiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAzMTYwMjMiLCJhZGQiOiIxNTIuNjkuMTk3Ljc0IiwicG9ydCI6IjEyMzQ1IiwidHlwZSI6Im5vbmUiLCJpZCI6ImI4YTZiZjU4LTQ4NWEtNDA0Ni1iMzg2LWIzNjYxYmY2NWVmZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYmIiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.138:807#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_6
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:805#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_4
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgX0pQX+aXpeacrF8zIiwiYWRkIjoic3V6aGloYW4uZXUub3JnIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIwYjg3M2NmZi0xMWFiLTQ3MTYtYzQxYS0wNGY4ODYxMzUwOTEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3JvZXdlc3UiLCJob3N0Ijoic3V6aGloYW4uZXUub3JnIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzAzMTYwMTQiLCJhZGQiOiIxOC4xNjcuMTAyLjE1OCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJiMGM5ZTRiMy0yNDQ1LTQ4YzctYWM4MS0xYzQwOWRmYjViYmIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2ltYWdlcyIsImhvc3QiOiJhc3AuY250di5teWFsaWNkbi5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKV8xIiwiYWRkIjoiMjIzLjE5LjE3Ny4xNDUiLCJwb3J0IjoiMjEwNTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjFkNjM3NmYtMWRmZS00NGQyLThlZTQtY2JmMjhjYjAxMDg3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoQXphZE5ldC50Lm1lKV83IiwiYWRkIjoiMTMyLjE0NS45MS4yMjAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImI3NzE4ZGM0LThjNDYtNDgzYi1kMzQ3LWRkNWQ4MjA5ZTAyMyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvampwd3Z3cyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1IoQXphZE5ldC50Lm1lKV84IiwiYWRkIjoiMTQwLjIzOC4xMy43OCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjA5M2VlZmItN2FiNi00MWRmLWFiYTAtZDVmYTU4MTQ3ZTEwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yZWZmczd5MjZnMHVhIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKV84IiwiYWRkIjoiMTY4LjEzOC4xNzQuMjgiLCJwb3J0IjoiMjU5MzIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzNhNDdjZTYtNWVhOS00ZDIxLWQzZGItY2UzODQyMWQyNTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8yMzQyMyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgZ2l0aHViLmNvbS9mcmVlZnEgLSDml6XmnKzkuJzkuqxMaW5vZGXmlbDmja7kuK3lv4MgMSIsImFkZCI6InY2LjU4MzE4MS54eXoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTYxZDk1MzMtZTIwYS00ZmYwLTgzZDQtODBkMGNjNTg4ZGZiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidjYuNTgzMTgxLnh5eiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1jZmI6ITxzdHI-@81.90.188.58:50000#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29_45
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:807#HK_52
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@3.112.193.151:443#JP_71
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@54.169.62.50:443#SG_124
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@54.169.211.238:443#SG_128
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@18.141.183.204:443#SG_132
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@35.91.221.138:443#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20023
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6IjE1NC52MnJheTMueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMTY4NjEiLCJhZGQiOiIxNTQudjJyYXkzLnh5eiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiIxNTQudjJyYXkzLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfeW91dHViZUDotYTmupDliIbkuqvluIhfMTQ0IiwiYWRkIjoidmRlMi4wYmFkLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTI3MDk0ZDMtZDY3OC00NzYzLTg1OTEtZTI0MGQwYmNhZTg3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jaGF0IiwiaG9zdCI6InZkZTIuMGJhZC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMTY3MDQiLCJhZGQiOiIxNzIuNjQuMTU0LjE1NSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMTY2OTciLCJhZGQiOiIxNzIuNjQuMTU0LjEwMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMTY2OTYiLCJhZGQiOiIxNzIuNjQuMTUzLjE1MCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMTY2OTUiLCJhZGQiOiIxNzIuNjQuMTUzLjE1NSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.212.59.212:443#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20019
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE1LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6IjE1NC52MnJheTMueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDExMCIsImFkZCI6ImNvb2luZy1sdXh1cmlhbnQtYmx1ZS5nbGl0Y2gubWUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjgwZTdkZDU5LWIxZmMtNDVhMC05OGJlLTE0NzhhOWFmODlmMiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXBpIiwiaG9zdCI6ImNvb2luZy1sdXh1cmlhbnQtYmx1ZS5nbGl0Y2gubWUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDgiLCJhZGQiOiJkZjdlLnY5OTY2LnNob3AiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImEyNzk4M2EwLWMxYjktMTFlZC1iMzMzLTIwNWM2ZDVmNWQ3OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImRmN2Uudjk5NjYuc2hvcCIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@38.91.107.66:7306#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29_30
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@167.88.63.44:7307#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29_5
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@158.51.121.154:2376#%F0%9F%87%A8%F0%9F%87%A6%20CA%28AzadNet.t.me%29_73
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@38.91.107.216:5003#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29_343
    ss://YWVzLTI1Ni1nY206UENubkg2U1FTbmZvUzI3@134.195.196.85:8091#%F0%9F%87%A8%F0%9F%87%A6%20CA%28AzadNet.t.me%29_27
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@38.91.101.159:7306#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29_28
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu944CQ5LuY6LS55o6o6I2Q77yaaHR0cHMvL3YxLm1rL3ZpcOOAkTQ4IiwiYWRkIjoibWFpbi5taWxsaW9uYWlyZWFpc2xlLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMmIyMTQxMjItMTkwNi00MjhhLWJiYjctYTAzOWNiYjdjZDVjIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii85SlpGRFRLRSIsImhvc3QiOiJmcjEudHJ1bXAyMDIzLm9yZyIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@167.88.63.59:7306#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29_6
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@38.75.136.102:7306#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29_23
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xODkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0IjoiY2xhc2gxLnNzci1mcmVlMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@134.195.196.230:5500#%F0%9F%87%A8%F0%9F%87%A6%20CA%28AzadNet.t.me%29_20
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MTQiLCJhZGQiOiIxOTguNDEuMjEyLjE0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi5Lyv5Yip5YW544CQ5LuY6LS55o6o6I2Q77yaaHR0cHMvL3YxLm1rL3ZpcOOAkTE3MiIsImFkZCI6IjIwMy4zMC4xOTEuMjAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjVmNjRmYTY1LTdiMTQtNDljNS05NTRkLWFhMTVjNmJmY2FjZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZG9uZ3RhaXdhbmcuY29tIiwiaG9zdCI6ImNsYXNoNi5zc3ItZnJlZS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WMTct5LuY6LS55o6o6I2Qc3VvLnl0L3NzcnN1YiIsImFkZCI6ImNmLWx0LnNoYXJlY2VudHJlLm9ubGluZSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODIzYzMxZGEtNzAxZi00ODNkLWIzNmUtODk2ZTVjZjA5ODdhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zaGlya2VyIiwiaG9zdCI6ImpwMS5zaGFyZWNlbnRyZXByby5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMENETiAyIiwiYWRkIjoiMTQxLjEwMS4xMTUuMzAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoiMTU0LnYycmF5My54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiQFYycmF5TkduIPCfmoAiLCJhZGQiOiI1MS4yMTAuMTAxLjIxMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNGU3NWU2OWItZWFlMC00NjU0LTlhYTYtMGNlNDVkZWFhMGI4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92bWVzcyIsImhvc3QiOiJmcjEtdm1lc3MuZ3JlZW5zc2gueHl6IiwidGxzIjoidGxzIn0=
    trojan://e018b9e8-96eb-45b6-b929-a39812631a30@farsroid.porton.top:443?allowInsecure=0#farsroid.porton.top443
    vmess://eyJ2IjoiMiIsInBzIjoifDY2LjcwTWIiLCJhZGQiOiJ3d3cua3Vyb21pLmV1Lm9yZyIsInBvcnQiOiIzMzQyMSIsInR5cGUiOiJub25lIiwiaWQiOiI5NGU1NmZmOS1jY2YxLTQxNGUtYTExNC00NmUwYTc5ZjY2MTQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0Ijoid3d3Lmt1cm9taS5ldS5vcmciLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrvCfh7cg5LyK5pyXXzAzMTYwMDEiLCJhZGQiOiJ2MnJheS5zZXJ2ZXJwYW5pcy5vcmciLCJwb3J0IjoiMTAwMjAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZWU4MGE4OTUtZmRlYS00MDBmLWI3YzktNmVmMmI4MjQ1ZDIzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidjJyYXkuc2VydmVycGFuaXMub3JnIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrvCfh7cg5LyK5pyXXzAzMTYwMzgiLCJhZGQiOiI0Ni4yNDUuNjUuOTYiLCJwb3J0IjoiMjAwMDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNzE4ZTFjMjgtMmQ0MS00MmM5LTkxNDMtMTlmYThmNWM5ZWY0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS02Q0ROIDIiLCJhZGQiOiIyMDMuMzAuMTg4LjEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoiMTU0LnYycmF5My54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@37.143.129.230:989#FI%28AzadNet.t.me%29_2
    trojan://0ecaae2c-c757-40e2-975a-f5b56a86e140@0001.hn.genzpn.com:443?allowInsecure=1&sni=dl.kgvn.garenanow.com#%F0%9F%87%BB%F0%9F%87%B3%20_VN_%E8%B6%8A%E5%8D%97%202
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HpvCfh7og5r6z5aSn5Yip5LqaXzAzMTYwMDIiLCJhZGQiOiIxNjguMTM4LjEwMi44OSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIwNzkyY2E5NS1hMGJhLTQ1MTAtZWFiMy04ZWEwMzIzOWM1MzIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@193.108.118.30:5500#%F0%9F%87%A9%F0%9F%87%AA%20DE%28AzadNet.t.me%29_12
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@193.108.118.36:7306#%F0%9F%87%A9%F0%9F%87%AA%20DE%28AzadNet.t.me%29_4
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@193.108.118.79:7306#%F0%9F%87%A9%F0%9F%87%AA%20DE%28AzadNet.t.me%29_5
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@217.182.198.219:2376#%F0%9F%87%A9%F0%9F%87%AA%20DE%28AzadNet.t.me%29_61
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@193.108.117.24:7306#%F0%9F%87%A9%F0%9F%87%AA%20DE%28AzadNet.t.me%29_3
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@145.239.1.100:8888#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2015
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@54.36.174.181:5500#%F0%9F%87%AB%F0%9F%87%B7%20FR%28AzadNet.t.me%29_16
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@51.77.53.200:8000#%F0%9F%87%B5%F0%9F%87%B1%20PL%28AzadNet.t.me%29_1
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAzMTYxODI5IiwiYWRkIjoiMTA0LjE5LjE3MC4zNiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJjMDk0MmYzZC01OGNkLTQzYTktODI4Mi0xYmNjM2I5ZjI5MWUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3VpdHNydCIsImhvc3QiOiJmcmVlZnJseGMuYXJnb3R1cy5saXZlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WMjUt5LuY6LS55o6o6I2Qc3VvLnl0L3NzcnN1YiIsImFkZCI6ImRwMi5zY3Byb3h5LnRvcCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODIzYzMxZGEtNzAxZi00ODNkLWIzNmUtODk2ZTVjZjA5ODdhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zaGlya2VyIiwiaG9zdCI6ImRwMi5zY3Byb3h5LnRvcCIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJjbGFzaDEuc3NyLWZyZWUyLnh5eiIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@38.68.135.18:5500#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%20123
    

</details>

### 所有节点
合并节点总数: `1016`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `84`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `90`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `32`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `8`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `1`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `5037`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `219`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `168`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `12`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `36`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `37`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `188`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `138`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `30`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `10`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `23`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `387`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `219`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `292`
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
