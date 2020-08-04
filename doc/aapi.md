# 云手机接口列表
## PC应用启动过程调用的接口
### 自动登录
```
http://10.0.0.199:9000/fingerauth/ad/getAd.html?client=win&version=2.1.77&uuid=87229925-A226-452b-B381-4A4A0430F046&source=com.redfinger.app
strPostData=sessionId=&userId=0&moduleCode=AD
http://10.0.0.199:9000/fingerlogin/user/getKey.html?client=win&version=2.1.77&uuid=87229925-A226-452b-B381-4A4A0430F046&source=com.redfinger.app
strPostData=userName=15392885277
http://10.0.0.199:9000/fingerlogin/user/getUserRs.html?client=win&version=2.1.77&uuid=87229925-A226-452b-B381-4A4A0430F046&source=com.redfinger.app
strPostData=userName=15392885277&sign=cb6c32df335d12f2a2e049c75679e0c1&os=Windows10&mac=2C-FD-A1-C0-68-56&validCode=&v=2.1.77
```
### 主界面
```
http://10.0.0.199:9000/fingerauth/userNotice/getUserNoticePage.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591&pageSize=20
http://10.0.0.199:9000/fingerlogin/pad/getPadList.html?client=win&version=2.1.77&uuid=146C8771-3660-449d-9F0D-054B1733D8B1&source=com.redfinger.app
strPostData=sessionId=1ebe6c81c79444de9d5a66bd6c680130&userId=1027591&pageNum=1&pageSize=4
http://10.0.0.199:9000/fingerauth/user/getUserInfo.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591
```
### 上报错误
```
=http://127.0.0.1:8080/gatherRequestFail.json?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591&errorInfo=JZM2VjaJ7ng/GxpbhxVwpnPeTWyG1lVeeeFaLX6hgeSAPpAci46hVjf3dDuDRof5E36wujT9tO+mNrsOB49VvRMiLfLmrOa5SrwOSCBdKAblny2BgIIZCTQYhO39fNU47s4fHnx5mtwHaxXYEMbkiDguedYQiq96LONSlHf7WCiFTbHF1RMLEMViF1Dy8Nkkzl4iWXJ6yLcOHyzGr4QHX+WA2BkZ5JQV9fXWwpKccFsqlPSgm4aMdn2z0bB2pVE7qCRdoyPvzsz7eL9jjtgoXtIsJ1OZ+EfyfY8+5Btn5TC+lsNaTa6hIT+JVd40g3jMz2sjtd0AE9wH+26E3Y/QZd3nd+NpFnVjueKr7GqfXV1ZfoU7vs+E7YkcpjoDnYZotuA8DjCVPezLyFx7/An/VvlsGxWll1NwTHZDgS6Qb8hSyWriDjyhukV9rjF1V//AfmDElJ+9FhTCRYaAhWRRrZ7eL2VuJ3kLi0MBC8zEJaGvDdmA8gC5MUJna9sWkmNL90O/7WtqofLJ1Qxoaj0GytLShSCnB9pgDFmQNQDattXtyKguALFz22rnceq60w3b0Tvp54eXhpLeDAdamULNWxxIweE/PAluIbxroCKPUWqB2UN0RDWEAzmIx3ehTreDsRUQeHL99AHzPrJocl/GfzcVLUx5GxywIXf1vgtz28y1+2V25Qcu1MrmVSstMHVk9yCISOOHKBmauBtOBuGrWPfUQKCvo8v7SKQx23ebesb3W+hh4J3GEEXmBzxf3jeS2YLjURPBLdMLMlcmcWb53irWlc6Cec8VvJrfTZNJW3GCnlukUdn3hoJO28y4rWX1GgU6Z+JLWhIMTG47UL/KKYEgXMQEGYXsy5vJMlfAwYh9IRSfltp9YOuVczAKtbVW5UdvPqxZw9zvFkO9/QUGUT2W6ip5azdTMyiOjFefYOjgueug1dO4eBNc4R4USGpFNh7vKWxsW5Ya4gt9ilwMIsDhP3r7nJmNym8kAvd2+8seLsGWjys3hBpAVo+9AldVq/mRmIo4M0roWt3gB8ISisj1pFWgZ7ngHtzM5EP1Squqib6RqCToDgm5TlR79Sbi+SliB56XYrwmPMtMaiqQN/Gjz5mWIy145z1+PWqxAxhXZXRNl9vk+pnJmQZsxUEi4aSjjLyoCVusx2pqWk52YjRsLuOVvYHL/JMF3df1iQG8+BzxdaVtf14VQ/uNP8/rG2qAIPcsbWvqrNGPtEQA+/vIKOo8y/AYiKlhagFRHaU4rV5BvrmQCA+fPCAjvnM+CIMbnrwm8CmZ7xAdW+HzC7L5ci+CZjC54vpVu/geus5MJxObHoOdqAjxrV+MXLagWFqYD+cqf/O0nvoF8pvmdg7sgLzLsrJ9fct5ifHj5XQBw6edSFspe2UbL+yVdH3J8zY8cf7pTuji8nxO6Dh2i5W5VdzYAsApxqDr6ZH7YXUFj+TE4RM+hPjEAMQzXv9TCFjuUCEZPQ3guuWK1lYt4RCUlJb2jvHPVqnPexW4eGPyQ2+wZIGAam1bkpLFF/dH0R4nWgRHDIH/fNfTjOaJJhnJqRoG6TuZp2/NtlBsIzF55KO2PWiPEzO3vaXsecvdUd15BbN1pC72C2TDiIwHNHhXzPcaIiQM7myKWWVF521hyZYnR639M/bW6lmUhfZiZkRdeUOfr23rU0xISkwqL+XyUoHZRTttHOU9JneUKHXSlZpcYix2C+1inCoTTcftNEgrgDzIzVxmxZBC5eNuZpCGKzy5y+mevrq9EiO89V0XZTIwuT5KVJnm9KMEdRI7+llDc6xLLm8kWbjT115srImYd4FKPZVVvGQa87sK4uOJ7JqY0infvmx0KgOoxLOSeEZ79wrjgpNtxw4+0f5feS72YIoPNPmZxDfwzeyU//4PmAAereJf9/SBpZbds0Q17tjdFLUrpQmpZlBQh+q/Mj2khVEeBiPw1uecKM5wLs3EEXSPCHJyVJsxBKu3TdFwVka/4z6VY9BHQrOX2LzJUNllt6ZLoqoOUGwNVABcLEUn7CXtuO3grKgWvD6JXQ2NtWSXYUHrSqDIWObRyRrHUGPg8VhKRU6s7WW111vRmhPuXTifQHXtlsSzDpoC9h61q/wU+PrVw6mVg2S0mAuK0gUTksMVyMRlQzPHcH3eXzk9pIVRHgYj8NbnnCjOcC7NGlObc3Lu+U9pe0xmP/nGwyl/kSGye72uH+iqCiUIXBJGNrf76ZKZ3StWiOR3zdtifEpY8Iekn9sWo0XgtEogLrCMaHdE55p6odVl4DCa4ErD5w9oXaxTiQUuvPN1gO+vdiulerRxdqxKD59MdcvFCjzW1mJqXrD5wXioTNTFQLh+fiiGEVgzt3c+XTpHlmpXqRj6pRPoi2/E6lxhxVvX//L9rsZxHteM7PcYmYQH0WKzJVZLIcs9b84QuWkzKW38U/JFFcaIMvFnOlPFGeIJZVfpLH7R7DDNoom10RgtOAvxtI/rOfpsz4phWJYMbTIyzOXGvm1tmZricHbrHtbg5qq84DnDvoCvWkUdQNImNdFqjJDKWtnNc956m5E4lA6zmcyfPbyWdFoBGG/bhIcr8gVs3IHeXeGfJEaz+KBHW6u/tPUEOcRTTUWROfJfBGi7/uq648NJam2MbVwIaTHPWLhlM46Hi/8IzeJ8A35h5wxM3DhXf8+Qx/3EBaRAAKcPt8r9PIqNfi23EL/Bt0Mq3xEF1XYjHGm56EL/cYf/71b5BlmweJdv5+fRJ2kQiiHtAonoNCQnH5l0LmT3VAukgG/IyhTHSFF3zFXvntLW9n49pIVRHgYj8NbnnCjOcC7NxBF0jwhyclSbMQSrt03RcFZGv+M+lWPQR0Kzl9i8yVBHxtn3U4kv2+i3Rqe9fZZtJ+wl7bjt4KyoFrw+iV0NjbVkl2FB60qgyFjm0ckax1DkinbgfCk2ZZCESKemlLF4YQG0dUDjiQolRvCC1HlfnFuezzOuNsI3lxWPYvQt45028DEgHOEiwhnROvAF531a8GR8pi8Khzjfs9mgZjxxF1eBIi37v0Tu4TXnUrl0iR15VoIp0YOOcbOVFMYTFGYclDyjxoMS7N9eFf4dnns6c9dut9JenNqJCJjjzPaoFUw8in0exaeB2AdSTmANGAL/5fJSgdlFO20c5T0md5Qodc5jHTPWi8ptz01lxm6LYqn2NqFnju3zNusML5rCq4FJElv2x+xKDnGAA9wyZP3d8ncDhWZqrG6o5wBUyEHFDiCIaCOxIEtWDANuPaJRr4+pBjyDoXWnL1UVGmyuCtyZuzkkDOWxCyx7B+BYeJPVD/L6YPPFVgKFXFTV+Sis+1NkoHdS+T00fcLjkUOPxhBQjeXyUoHZRTttHOU9JneUKHXSlZpcYix2C+1inCoTTcftIHv8YAPaC6iTCq280pNCOG+okgigFemJp7S5VZcWH7874NbFbUW3beS4e0Ce8+0IysQBGr5y049Yfy2jtYtWc7JgIN85maG6/MTtfqsU2oH2b+gK9cGtmtalHyQNfTYGHMOEXsNC90DxBSBTe4xUqJbsxa5cCTFMqWCamWUzo7vRpDtPEJvj6Hjt2JdRC5w7&timestamp=1596525084000&padCode=&errorCode=404

```
### 点击菜单发送的请求
```
// 授权管理
http://10.0.0.199:9000/fingerauth/grant/getPadList.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591&grantType=1
// 我的钱包
http://10.0.0.199:9000/fingerauth/goods/getWalletGoods.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591
// 我的钱包--钱包记录
http://10.0.0.199:9000/fingerauth/wallet/recordList.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591&pageNum=1&pageSize=100
//我的礼包
http://10.0.0.199:9000/fingerauth/gift/myGiftList.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=046eb3c0d46445c39cd475f2d56847b1&userId=1027591&giftStatus=&pageNum=1&pageSize=100
//红豆记录
http://10.0.0.199:9000/fingerauth/rbcRecord/getRbcRecord.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=046eb3c0d46445c39cd475f2d56847b1&userId=1027591
//查看订单
http://10.0.0.215:8880/fingerauth/rbcRecord/getRbcRecord.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=046eb3c0d46445c39cd475f2d56847b1&userId=1027591
//我的等级
//我的设置
--头像设置
http://10.0.0.199:9000/fingerauth/user/updateUserData.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
--修改密码
http://10.0.0.199:9000/fingerlogin/user/updatePassword.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=5b0b618b91df4b3593e1be62099cc9fb&userId=1027591&oldPassword=Test1234&newPassword=Test1234&conPassword=Test1234
--设置邮箱验证码
http://10.0.0.199:9000/fingerauth/email/needUserEmailCode.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=046eb3c0d46445c39cd475f2d56847b1&userId=1027591
http://10.0.0.199:9000/fingerauth/email/checkVaildCodeRs.html?client=win&version=2.1.77&uuid=36356415-FF9E-406c-BFE1-93DE2CC194C9&source=com.redfinger.app
strPostData=sessionId=046eb3c0d46445c39cd475f2d56847b1&userId=1027591&userEmail=ndf@qq.com&validCode=sdfa
```
