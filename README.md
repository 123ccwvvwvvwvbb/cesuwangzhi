# cesuwangzhi
v2rayn中可以进行测速的网址搭建，直接部署在cloudflare上即可
1. **默认测速大小为200MB**：当未在路径中指定测速大小时，项目会默认进行200MB的测速。

- 200M   默认测试下载地址: `https://speedtest.cmliussss.workers.dev`
 

2. **自定义测速大小**：通过在路径中指定数字和单位（可选的单位包括 K，M，G），可以设定想要进行测速的数据大小，如“/500M”表示进行500MB的测速。

- 1024K  测试下载地址: `https://speedtest.cmliussss.workers.dev/1024k`
- 200M   测试下载地址: `https://speedtest.cmliussss.workers.dev/200m`
- 1G     测试下载地址: `https://speedtest.cmliussss.workers.dev/1g`

3. **推荐使用workers部署方案并绑定自定义域，即可同时具备 http/https 两种测速途径。**
