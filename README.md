# NaiveProxy  一键配置脚本

## 部署步骤  

1.SSH进入VPS，并执行以下命令运行NaiveProxy脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/Misaka-blog/naiveproxy-script/main/naiveproxy.sh && bash naiveproxy.sh
```
2.安装NaiveProxy,设置NaiveProxy和Caddy的端口、域名、用户名密码及伪装网站地址  
3.安装完成之后，脚本将会显示NaiveProxy协议的节点信息及分享二维码  
4.V2rayN为例，依次点击“服务器”→“添加自定义服务器”,输入别名、导入json文件，Core类型选择naiveproxy，端口输入xxxx  
Naiveproxy Core: https://github.com/klzgrad/naiveproxy/releases  
5.由于NaiveProxy在V2rayN为自定义配置节点，故不能使用平常用的真链接和测速进行测试节点连通性。所以说只能依靠链接来测试连通性  


## 参考项目

- https://github.com/lxhao61/integrated-examples


## License

GNU Affero General Public License v3.0
