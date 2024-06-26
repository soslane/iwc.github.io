## 一、Web服务器

Web服务器是一种软件应用程序，用于接收来自客户端的HTTP请求，并向客户端发送HTTP响应。它们通常用于托管和提供网站和Web应用程序。Web服务器的默认端口通常是80（对于HTTP协议）和443（对于HTTPS协议）。

## 二、Web服务器的创建过程

1、**安装 Internet Information Services (IIS)**：IIS 是 Windows Server 中用于托管 Web 服务器的角色。您可以通过 Server Manager 来安装它。

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/%E5%9B%BE%E7%89%871.png)


2、**配置 Web 服务器**：安装完成后，打开 IIS 管理器。您可以在开始菜单中找到它，路径通常为 "管理工具" -> "Internet Information Services (IIS) 管理器"。在 IIS 管理器中，您可以配置网站、应用程序池、绑定等设置。

3、**创建网站**：在 IIS 管理器中，右键单击 "Sites"，然后选择 "Add Website"。在弹出的对话框中，输入网站的名称、物理路径（网站文件存放的位置）、绑定信息（IP 地址和端口号），然后点击 "OK"。

4、**测试网站**：创建网站后，您可以使用浏览器访问该网站，验证是否已成功创建。

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/%E5%9B%BE%E7%89%872.png)

## 三、创建网站

**1、创建使用ip访问的网站**

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/%E5%9B%BE%E7%89%875.png)

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/%E5%9B%BE%E7%89%873.png)

**2、使用不同端口号架设多个Web网站**

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/20240522122334.png)

**3、使用不同的主机头名架设多个Web网站**

在DNS中创建不同的CNAME记录

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/20240522122432.png)

编辑绑定

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/20240522122631.png)

**4、使用不同的IP地址架设多个Web网站**

高级TCP/IP设置

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/20240522122848.png)

编辑绑定

![](https://jsd.cdn.zzko.cn/gh/soslane/picgo@main/path/20240522123010.png)