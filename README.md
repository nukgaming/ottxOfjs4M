# วิธีหา Device Id SCB


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## ขั้นตอน

- หาก SCB EASY ไม่ใช่ Version 3.38.0 ให้ลบออก
- โหลดแอป  ไว้ในเครื่องดังนี้

| แอป | ดาวโหลด |
| ------ | ------ |
| SCB EASY 3.38.0  | [https://github.com/nukgaming/ottxOfjs4M/blob/main/scb-easy_3.38.04219.apk?raw=true][PlDb] |
| Virtual Xposed | [https://github.com/nukgaming/ottxOfjs4M/blob/main/VirtualXposed_0.20.3.apk?raw=true][PlGh] |
| HttpCanary | [https://github.com/nukgaming/ottxOfjs4M/blob/main/com.guoshi.httpcanary_2020-08-18.apk?raw=true][PlGd] |

- ติดตั้ง Virtual Xposed แล้ว HttpCanary และ SCB EASY
- จากนั้นทำตาม video นี้ https://github.com/nukgaming/ottxOfjs4M/blob/main/video.mp4?raw=true
- หลังจากติดตั้ง SCB EASY เข้าไปใน Xposed แล้ว ก็ให้ทำการลงทะเบียนแอป SCB ที่อยู่ใน Xposed ให้เสร็จ
- ขั้นตอนการดึง DeviceID ปิดทุกแอพก่อน แล้วให้ทำตามวิดีโอ https://github.com/nukgaming/ottxOfjs4M/blob/main/video2.mp4?raw=true
- หา endpoint ```login/v2 หรือ login/v3``` ก็ได้ มี DeviceID เหมือนกัน
- เสร็จแล้วก็คัดลอกมาใช้ได้เลย DeviceID Pin6หลัก เลขบัญชี
