# shadowsocks goproxy安卓插件
 
### 数据流
为了方便理解插件怎么工作的，下面对使用插件前后流量走向做个对比

#### 使用插件前

```text
本地VPN -》本地SS-》----互联网------》SS服务器
```

##### 使用插件后

```text
本地VPN -》本地SS-》本地goproxy-》----互联网------》goproxy服务器
```
