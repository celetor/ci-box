# aliyundrive-checkin
- https://github.com/libuke/aliyundrive-checkin
- https://github.com/KD-happy/KDCheckin


# 如何使用？ 

    | Name   | Secret                           |
    | ------ | ------------------------------- |
    | TOKEN *   | 阿里云盘Token 可以添加多个用英文逗号(,)分割 无需空格  |
    | SCKEY  | Server酱 推送密钥 |
    | PUSHPLUS_TOKEN  | pushplus 推送Token |
    | WECOM_TOKENS  | 企业微信 Token |
    | WECOM_WEBHOOK  | 企业微信 WEBHOOK |
    | BARK_DEVICEKEY  | IOS应用Bark 推送密钥 |
    | FEISHU_DEVICEKEY  | 飞书 推送密钥 |


### 其它设置
- 需要调整推送内容修改aliyundrive_info.py文件即可
- 自动签到时间修改.github/workflows/checkin.yml文件 cron项即可实现
  - 该cron指定的是格林尼治时间（UTC），如果需要换算成北京时间，要在该cron的基础上增加八小时得到北京时间。

### 如何获取阿里云盘TOKEN？
- [https://alist.nn.ci/zh/guide/drivers/aliyundrive.html](https://alist.nn.ci/zh/guide/drivers/aliyundrive.html)

# 如侵权请联系本人删除
