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

    trojan://c19d1432-8b3e-4818-8837-3d160cf65908@138.2.45.243:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2812%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSg3KSIsImFkZCI6IjEzOS45OS45MS45NSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://6ee96394-2a43-43dc-898b-bbf68a237310@18.177.58.124:50286?allowInsecure=1&sni=jp-tk-31.fuckjdieng.uk#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2815%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.18:443#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2827%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@85.208.108.19:8118#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2879%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.93:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2817%29
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@85.208.108.94:4444#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2822%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2897%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.21:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2820%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzAyMDIwNDUiLCJhZGQiOiIzLjM5LjYuODAiLCJwb3J0IjoiMTYzMzMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDA5MDAyYTctMDU4ZS00ZjVjLWJjNWMtZWM3YjAzOGFiNjcyIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6ImpwLXRrLTMxLmZ1Y2tqZGllbmcudWsiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@85.208.108.90:2376#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2850%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@139.99.68.21:6379#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2816%29
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@139.99.120.234:8000#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2817%29
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_127
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSgxKSIsImFkZCI6IjIzLjEwNi4xMjUuMTg1IiwicG9ydCI6IjE3MTM0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjFlYzI2MmI1LTk5NTAtNGUwMS05YmVjLTM0YzQyOTBjYWUwNCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJqcC10ay0zMS5mdWNramRpZW5nLnVrIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjQzLjE1NC4zNC40OSIsInBvcnQiOiIyMzE4MyIsInR5cGUiOiJub25lIiwiaWQiOiJiNDAyYTRhZi0yODVhLTQ2M2UtYzNhNy01M2Y5MWVmZGVjNzgiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoianAtdGstMzEuZnVja2pkaWVuZy51ayIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.20:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2821%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.59:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2819%29
    ssr://ejAxMTEuc2VjdXJpdHktY2xvdWRmcm9udC1jZG4uY29tOjQyODMzOm9yaWdpbjphZXMtMjU2LWNmYjpodHRwX3NpbXBsZTpXWEJZTW05d1FtSnlabkZLZW5wTmN3Lz9ncm91cD1VMU5TVUhKdmRtbGtaWEkmcmVtYXJrcz04Si1IcmZDZmg3QWdTRXNvYUhSMGNITXZMMkYzYTJvdVkyWXZhM2tnNXJPbzVZYU01TDJUNmFxTTVyV0I1YXFTNUwyVDVweTY1Wnk2S1hsdmRYUjFZbVhwbUxfa3ZKX25wNUhtaW9BJm9iZnNwYXJhbT0mcHJvdG9wYXJhbT0
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSg2KSIsImFkZCI6IjE1LjIzNS4xNDcuMTg2IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZmZWExNjQ5LTQyNWItNDA5Mi1iZjUzLTI5NzkyMTUyYzkyNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc3Noa2l0L0VydHVzZzg2LzYzNTAxNDYzOGMyNjQvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@54.254.147.251:804#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2821%29
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@85.208.108.60:6379#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%2818%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.41:810#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2818%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.214.212.124:443#%F0%9F%87%B8%F0%9F%87%AC%20_SG_%E6%96%B0%E5%8A%A0%E5%9D%A1%206
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1664#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29%28171%29
    trojan://0c6a3341e8d5ab17@103.172.116.196:3389?allowInsecure=1#%F0%9F%87%B8%F0%9F%87%AC%20SG%28AzadNet.t.me%29%2814%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgU0coQXphZE5ldC50Lm1lKSgxMSkiLCJhZGQiOiIxMTguMTA3LjU3LjE4MCIsInBvcnQiOiIyNzU0MiIsInR5cGUiOiJub25lIiwiaWQiOiIwYzg4YjVmZS1iMTliLTRiMTctOWFiYi05OWEwODI0ZDA0ZjEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug44CMU0NQ44CNSlAt6JuL57OV5bm25LiN5piv6LCO6KiAIiwiYWRkIjoiY2YtbHQuc2hhcmVjZW50cmUub25saW5lIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyMGU5Mjg4MS01ZmI0LTRiMDUtYmM3Ny01NzkyOTQ3NmRjNjkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NoaXJrZXIiLCJob3N0Ijoib3BjLWpwLnNoYXJlY2VudHJlLm9ubGluZSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgZ2l0aHViLmNvbS9mcmVlZnEgLSDml6XmnKzkuJzkuqxBbWF6b27mlbDmja7kuK3lv4MgMTAiLCJhZGQiOiJqcDgwLTQuc2FuZmVuMDAxLnBpY3MiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiM2MzNGYyNjQtNmQ5Yy00MjM0LWIxZGEtM2I4NGYxODNhOTMxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii96aC1jbiIsImhvc3QiOiJ3d3cuYmFpZHUuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg44CQ55u06L+e44CR54uu5Z+OIC0gNCAyIiwiYWRkIjoiMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMzZhLm5vZGUtZm9yLWJpZ2FpcnBvcnQud2luIiwicG9ydCI6IjEyMzU2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImU5MWRiNDljLTA0MWQtNDBlMC04OGYzLTA4YmE2NWI4ZWQyMCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3poLWNuIiwiaG9zdCI6Ind3dy5iYWlkdS5jb20iLCJ0bHMiOiIifQ==
    ssr://aXBsYy1odS5taWVsaW5rLWRuczIuY29tOjY2ODphdXRoX2FlczEyOF9tZDU6cmM0LW1kNTpodHRwX3NpbXBsZTpiV2xsYW5WdGNDNWpiMjAvP2dyb3VwPVUxTlNVSEp2ZG1sa1pYSSZyZW1hcmtzPThKLUhyZkNmaDdBZ1NWQk1RLVM0ay1lNnYtLTluT2F5cXVhNHIxc3lMakJkS0doMGRIQnpMeTloZDJ0cUxtTm1MMnQ1SU9henFPV0dqT1M5ay1tcWpPYTFnZVdxa3VTOWstYWN1dVdjdWlsNWIzVjBkV0psNlppXzVMeWY1NmVSNW9xQU5BJm9iZnNwYXJhbT1ZV3BoZUM1dGFXTnliM052Wm5RdVkyOXQmcHJvdG9wYXJhbT1PRFExTVRjNk1HUTBPVEkyWVRBdE9UZzRNUzB6TmpBNUxXSTJaV1V0TkRjeE5tUmhPRFJsTlRsbA
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:812#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%289%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAyMDIxMDciLCJhZGQiOiIxMDMuMjU0Ljc0LjE2OCIsInBvcnQiOiIyMjk5MyIsInR5cGUiOiJub25lIiwiaWQiOiJkMjZiY2ZiMi1hYTlhLTQ5MjMtYTdjYS0wMGU0MmY1YTQ5MmIiLCJhaWQiOiI1MyIsIm5ldCI6InRjcCIsInBhdGgiOiIvemgtY24iLCJob3N0Ijoid3d3LmJhaWR1LmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAyMDIwMDQiLCJhZGQiOiIxOC4xNDMuMTIzLjM1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY4ZGY0ODM4LTQ2ZDAtNGI1Yi1jM2YwLWE0MGVjNzA2MzI0NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjguMjEwLjM0LjEwNCIsInBvcnQiOiIyODE4MiIsInR5cGUiOiJub25lIiwiaWQiOiJlM2MwNzRkYy1iY2JiLTQ1YzItYmY1OC05NjMxMGVhNGI5OTkiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSg1KSIsImFkZCI6IjQzLjEyOC4xMC4yMzYiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ0ZWE0YTE5LWI5ZTMtNDRiMC1iZDY0LTNkNjBjZmM4Yjg2YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    trojan://shenmegui@37.123.196.250:28893?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%286%29
    trojan://11a4e5be-3c87-37d2-aac8-00b85ef0fcdc@20.187.108.142:32154?allowInsecure=1&sni=relay-hk-az.fib-sys.cyou#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29%288%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSgyKSIsImFkZCI6IjE2Ny4xNzkuMzIuNTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZmZmZmZmZmLWZmZmYtZmZmZi1mZmZmLWZmZmZmZmZmZmZmZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSgzKSIsImFkZCI6IjE2OC4xMzguMjA2LjE0MSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJhZDA1ZTAxZi1jMmMwLTQxZGEtZTc5Yy1mZjY4MjM3MzE3ZjciLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg0KSIsImFkZCI6IjE2OC4xMzguMTk0LjI0MyIsInBvcnQiOiIzMzQyMSIsInR5cGUiOiJub25lIiwiaWQiOiI5NGU1NmZmOS1jY2YxLTQxNGUtYTExNC00NmUwYTc5ZjY2MTQiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgSlAoQXphZE5ldC50Lm1lKSg3KSIsImFkZCI6IjE0MS4xNDcuMTgxLjIxOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMGI4NzNjZmYtMTFhYi00NzE2LWM0MWEtMDRmODg2MTM1MDkxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yb2V3ZXN1IiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgZ2l0aHViLmNvbS9mcmVlZnEgLSDml6XmnKzkuJzkuqxMaW5vZGXmlbDmja7kuK3lv4MgMSIsImFkZCI6InY2LjU4MzE4MS54eXoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTYxZDk1MzMtZTIwYS00ZmYwLTgzZDQtODBkMGNjNTg4ZGZiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidjYuNTgzMTgxLnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKSgxKSIsImFkZCI6IjE4LjE2My4yLjE3NiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjEwYWJmMjEtNzYxZS00MWJiLWE0NWItZjA3YWVhNTEwMWI5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii96aC1jbiIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggMS4yNHxVUyDnvo7lm715b3V0dWJl6Zi/5Lyf56eR5oqAIDgiLCJhZGQiOiIxNzIuNjQuMTU0LjE1MCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kb25ndGFpd2FuZy5jb20iLCJob3N0IjoiY2xhc2g2LnNzci1mcmVlLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MSIsImFkZCI6IjIwMy4zMC4xODguMTIxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX1VTX+e+juWbvV/mnaXmupA7a3VhaXp1aS5jb20t5b+r5Zi056eR5oqAXzIiLCJhZGQiOiJjZi1keC1kbnMuc2hhcmVjZW50cmUub25saW5lIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyMGU5Mjg4MS01ZmI0LTRiMDUtYmM3Ny01NzkyOTQ3NmRjNjkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NoaXJrZXIiLCJob3N0IjoidXMtZHAyLnNoYXJlY2VudHJlLm9ubGluZSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MjAiLCJhZGQiOiIyMDMuMzAuMTkxLjgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX1VTX+e+juWbvSA2IDIiLCJhZGQiOiJtYWluLm1pbGxpb25haXJlYWlzbGUuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyYjIxNDEyMi0xOTA2LTQyOGEtYmJiNy1hMDM5Y2JiN2NkNWMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzlKWkZEVEtFIiwiaG9zdCI6ImZyMS50cnVtcDIwMjMub3JnIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2MyIsImFkZCI6IjIwMy4zMC4xOTEuNyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@129.146.190.42:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%28AzadNet.t.me%29%2849%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDMg5rSb5p2J55+2OSIsImFkZCI6IjIwMy4zMC4xOTEuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDM4IiwiYWRkIjoidXMtMi4wcmQubmV0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1OTc4ODhjMC1hMzE4LTExZWQtYjUzNi0yMDVjNmQ1ZjVkNzgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3RxOThlMHlrIiwiaG9zdCI6InVzLTIuMHJkLm5ldCIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDMwIiwiYWRkIjoid3d3LnNjaWVuY2VkaXJlY3QuY29tIiwicG9ydCI6IjIwNTMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTQzNzZjMDYtZmVkNi00YzljLWU4YzgtYzg0M2Y2YTJiNDYwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiZ2VybWFueTFjZG4ubGV0c21ha2Vtb25leS5wcm8iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDI5IiwiYWRkIjoiaHVjbG91ZC50ayIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMmRmM2VkNGEtNDMxMy00NWY5LWI3NDItMmYwMmNlNTkzYTZlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9odWh1IiwiaG9zdCI6Imh1Y2xvdWQudGsiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC04IiwiYWRkIjoiMjMuMjI3LjM4LjIxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0NSIsImFkZCI6IjE3Mi42Ny4yMDMuMTYyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3OCIsImFkZCI6IjE3Mi42Ny4xNDUuMTY2IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMyIsImFkZCI6IjE4NS4xNjIuMjI4LjIyOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xMCIsImFkZCI6IjIzLjIyNy4zOC4yNyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDI2IiwiYWRkIjoiMTcyLjY3LjE5OS4zNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC02IiwiYWRkIjoiMjMuMjI3LjM4LjIzIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKSgxMCkiLCJhZGQiOiIyMy4xMDUuMTk5LjE2MCIsInBvcnQiOiIyMzE2NiIsInR5cGUiOiJub25lIiwiaWQiOiJmMWNkYTlkYS1jODU5LTRmMjYtZjYwOS1hMmU4ODM3Y2M5YjgiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoiIn0=
    trojan://0c355515-b1e5-4c0a-b843-e1defbe7c0fa@trxjp.ballistics.top:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%2049
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNCIsImFkZCI6IjIwMy4yNC4xMDguOCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xNENETiIsImFkZCI6IjE5MC45My4yNDYuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    trojan://0c355515-b1e5-4c0a-b843-e1defbe7c0fa@trfg.ballistics.top:443?allowInsecure=0#Relay_%20%7C25.25Mb
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAyMDI4NTEiLCJhZGQiOiIxNDEuMTAxLjExNC4xMDIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjVmNjRmYTY1LTdiMTQtNDljNS05NTRkLWFhMTVjNmJmY2FjZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZG9uZ3RhaXdhbmcuY29tIiwiaG9zdCI6ImNsYXNoNi5zc3ItZnJlZS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAyMDIxMzMxIiwiYWRkIjoiMTYyLjE1OS4xMzcuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BVUlLTjhBVSIsImhvc3QiOiJvcGxnMS5jZmNkbjIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xNENETiIsImFkZCI6IjE5MC45My4yNDYuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiQ05feW91dHViZUDotYTmupDliIbkuqvluIhfMTU5IiwiYWRkIjoiQ0xPVURGTEFSRS5RVUVTVCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3ZGFmZTg3LWUyOGQtNGEzMy1mNjA4LTM3NWUxYTA1ZTdiNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJpZXMiLCJob3N0Ijoic2N3LmNsb3VkZmxhcmUucXVlc3QiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi03Q0ROIiwiYWRkIjoiMjAzLjI0LjEwOC45IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    trojan://origin@176.31.83.90:443?allowInsecure=1#%F0%9F%87%AB%F0%9F%87%B7%20FR%28AzadNet.t.me%29%281%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNCAyIiwiYWRkIjoiMjAzLjI0LjEwOC44IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WMTEt5LuY6LS55o6o6I2Qc3VvLnl0L3NzcnN1YiIsImFkZCI6ImNmLWx0LnNoYXJlY2VudHJlLm9ubGluZSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjBlOTI4ODEtNWZiNC00YjA1LWJjNzctNTc5Mjk0NzZkYzY5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zaGlya2VyIiwiaG9zdCI6InVzLWRwMi5zaGFyZWNlbnRyZS5vbmxpbmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMkNETiIsImFkZCI6IjE0MS4xMDEuMTE1LjMyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xODkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    trojan://e8c1ab3c-89b3-4933-92df-682e6dce7819@152.67.98.30:443?allowInsecure=1#%F0%9F%87%A6%F0%9F%87%BA%20AU%28AzadNet.t.me%29%283%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC04IDIiLCJhZGQiOiIyMy4yMjcuMzguMjEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC02IDIiLCJhZGQiOiIyMy4yMjcuMzguMjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC00IiwiYWRkIjoiMjMuMjI3LjM4LjI1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xM0NETiIsImFkZCI6IjE5MC45My4yNDQuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6ogREUoQXphZE5ldC50Lm1lKSg4KSIsImFkZCI6Ijc5LjEzMi4xMzMuMzgiLCJwb3J0IjoiNTQ0NTgiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzFiMDIyZjItNTQ0MS00ZTlhLWZmZTctNDNmZWU3YWIwNjg4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@109.169.72.249:809#AE%28AzadNet.t.me%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC0xNyIsImFkZCI6IjE5OC40MS4yMTIuMTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImM1YTJkN2I4LWJmODQtNGY5Ny04NTc3LWI5Yjg3ZjJiYWFmNyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQVVJS044QVUiLCJob3N0Ijoib3BsZzEuY2ZjZG4yLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My00Q0ROIiwiYWRkIjoiMjAzLjMwLjE5MC4xOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xOTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My01Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OS4xOTEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    

</details>

### 所有节点
合并节点总数: `1071`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `139`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `100`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `55`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `101`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `3333`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `220`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `288`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `51`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `38`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `130`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `250`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `101`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `56`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `18`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `2640`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `247`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `315`
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
