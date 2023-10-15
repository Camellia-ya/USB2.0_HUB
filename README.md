# USB2.0_HUB
* **基于SL2.1A芯片设计的USB2.0（已验证）**

* 里面有三个A口和两个c口（一个作为输入一个作为输出）。Input C可以自主更换为micro口或其他

* D+和D-一定要**差分走线**！由于目前只是usb2.0所以相对于usb3.0来说差分线没有那么严格
* 连接**手机/鼠标/键盘**，外接**ch340**模块可以识别到**COM**口，传输文件的速率只能在**8MB/s-12MB/s**左右

* 为了保险可以在电源加个**tvs管**，布局时把**tvs管**放置板子边缘处。（这里没有加）

***

仓库里是**AD19版本**的原理图和PCB，也有全套的封装库（3D封装的 **.step**文件用的是 **SOLIDWORKS 2019**版本），使用AD的小伙伴可自行下载

使用嘉立创打板的通过以下路径即可获得

**立创开源广场地址：** https://oshwhub.com/yayagood/usb2-0-hub

***

**3D图**

<img width="685" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/707c0f02-0e2b-4428-9a3a-ada587cdb76b">



<img width="661" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/904ba347-deb5-457c-98e8-c359216dc629">





**实物如下**

<img width="649" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/e8b2ea3c-ed9c-4f50-bd9e-3a09e1e705e8">




<img width="632" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/a685fee3-b331-4304-aa37-b4a5a614b02b">




欢迎讨论！🥰🥰
