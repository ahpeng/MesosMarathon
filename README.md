<a href="https://portal.azure.cn/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fahpeng%2FMesosMarathon%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=/https%3A%2F%2Fraw.githubusercontent.com%2Fahpeng%2FMesosMarathon%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

本模板参考Azure Stack Quick Template。可以同时在中国区Azure和私有云上部署。

</a>本模板作了以下的改动：
</a>1. 修改Ubuntu的源sources.list，指向国内的源，您也可以将以下的脚本中的源，指向其他源服务器
</a>https://raw.githubusercontent.com/ahpeng/MesosMarathon/master/parts/configure-mesos-azure.sh
</a>2. 修改了Mesos的源，指向盆盆自己搭建的源服务器，由于这台服务器可能会被关闭(以节省资源)，所以强烈建议大家自己搭建并修改源地址。可以参考以下文档：
</a>https://linux.cn/article-4926-1.html
</a>3. 修改了AdminRouter的LUA文件下载地址，将其从github转储到国内Azure的Storage，如果您有自己的转储地址，可以修改脚本文件。

</a>感谢微软中国Azure架构师Steven Lian和Wei Heng、张磊老师的大力帮助。


