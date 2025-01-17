
<h1 align="center">
  <br>
  <img src="https://github.com/ethereum-proxy/Minerproxy/blob/main/logo.png" width="500"/>
</h1>

<h4 align="center">全新以太坊代理，支持 芯片机 / 显卡机，支持 ETH / ETC 抽水，协议完美适配。
<br />Go语言原生开发，博采众长，性能强悍，稳定、高效、不掉线。矿池曲线平稳，抽水精确。
<br />无暗抽、无暗抽、无暗抽。。。。
</h4>
全网最稳定的 ETH / ETC 以太坊代理中转程序，minerproxy代理，支持TCP和SSL协议，支持自有加密客户端LetSec协议，支持专业芯片机与显卡机，内置商业SSL证书，自定义抽水，web界面管理支持手机端，自启动守护进程，开机自动运行，防火墙和连接数限制一键搞定。高效稳定，无视CC，无视DDOS，不怕攻击。
<h4 align="center">更多功能，持续更新！！！</h4>
<h4 align="center"><a style="color:red" href="https://github.com/ethereum-proxy/Letminer">本地加密客户端 letsec 现已上线 >></a></h4>

# · Minerproxy使用方式
独立使用
```bash
【矿机】 ---SSL/TCP连接--->【minerproxy本地端口】 ---SSL/TCP连接--->【矿池】
```
或者 搭配 letsec 使用
<a style="color:red" href="https://github.com/ethereum-proxy/Letminer"> 什么是 Letsec ？</a>
```bash
【矿机】 ---SSL/TCP连接---> 【letsec本地端口】 ---> 【minerproxy本地端口】 ---SSL/TCP连接--->【矿池】
```

# · Liunx在线安装
 · 推荐系统：Ubuntu 16+ / Debian 8+ / CentOS 7+，使用 root 用户输入下面命令安装或卸载<br />
 · 服务器可以直连Github
```bash
  bash <(curl -s -L https://raw.githubusercontent.com/ethereum-proxy/Minerproxy/main/install.sh)
```
 · 服务器无法访问Github
```bash
  bash <(curl -s -L https://cdn.statically.io/gh/ethereum-proxy/Minerproxy/main/install.sh)
```

# · Liunx离线安装
```bash
1、直接下载zip压缩包，
2、解压，运行安装脚本 ：bash install.sh       
```

# · Windows安装
```bash
1、直接下载zip压缩包，
2、解压下载的压缩包，双击 windows启动.bat 即可。或直接双击minerproxy_windows.exe
```

# ·  重要提示

*  1、Linux系统第一次安装完成后请重启服务器，连接限制修改方可生效！
*  2、安装完成后，请立即修改默认密码！
*  3、minerproxy已内置SSL证书，如需更换，请将您的证书文件命名为 server.key 与 server.pem ,并放置于程序安装目录下！如果看不懂这句话就不要管，凤凰不用自己的域名证书无法使用SSL模式
*  4、本地算力跟矿池算力差距5%以内是正常情况，导致这个差额的因素有： 挖矿软件手续费：0.65%-2% 网络传输损失：2%-3% 挖矿任务切换损失：0.5%-1% 超频过度：＞1% 如果差距过大，首先确认机器是否稳定跑满24小时，如果没跑满一天，先继续观察，稳定跑满一天后再看矿池的24小时平均算力，一般是接近矿机本地算力的； 如果已经跑满24小时，差距仍然大，通常都是超频过度


# ·  版本日志
```bash
2022/07/04 v1.0.1  控制台矿机列表增加筛选功能。
                   优化逻辑，提升稳定性。
2022/07/01 v1.0.0  MinerProxy发布第一个版本！
```

# · 联系我们
```bash
1、Telegram技术交流群：https://t.me/Minerproxy666
2、欢迎建议、使用反馈、定制需求，电报群直接私聊群主
```    
## :scroll: 开发抽水
* 本软件如果您开启了抽水则为 1 % 的开发者费用,如果您不开启抽水,则没有开发者费用,可以自行抓包查看！
