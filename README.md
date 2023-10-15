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

<img width="698" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/b6dd7409-54b3-4665-865c-244c5e8ccab0">


<img width="760" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/cebb1d38-e1bb-4ef5-8dfd-55c1a23cdb32">




**实物如下**


<img width="641" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/62384281-a8c4-408c-8bcb-1e4acbf55385">


<img width="618" alt="image" src="https://github.com/Camellia-ya/USB2.0_HUB/assets/126542281/09e168c4-25de-46f4-a2f4-28529cae62ed">



欢迎讨论！
