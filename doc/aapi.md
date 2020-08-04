# 云手机接口列表
## PC应用启动过程
```
http://10.0.0.199:9000/fingerauth/ad/getAd.html?client=win&version=2.1.77&uuid=87229925-A226-452b-B381-4A4A0430F046&source=com.redfinger.app
strPostData=sessionId=&userId=0&moduleCode=AD
http://10.0.0.199:9000/fingerlogin/user/getKey.html?client=win&version=2.1.77&uuid=87229925-A226-452b-B381-4A4A0430F046&source=com.redfinger.app
strPostData=userName=15392885277
http://10.0.0.199:9000/fingerlogin/user/getUserRs.html?client=win&version=2.1.77&uuid=87229925-A226-452b-B381-4A4A0430F046&source=com.redfinger.app
strPostData=userName=15392885277&sign=cb6c32df335d12f2a2e049c75679e0c1&os=Windows10&mac=2C-FD-A1-C0-68-56&validCode=&v=2.1.77

```
## 获取云手机列表
```
http://10.0.0.199:9000/fingerlogin/pad/getPadList.html?client=win&version=2.1.77&uuid=146C8771-3660-449d-9F0D-054B1733D8B1&source=com.redfinger.app
strPostData=sessionId=1ebe6c81c79444de9d5a66bd6c680130&userId=1027591&pageNum=1&pageSize=4
```
