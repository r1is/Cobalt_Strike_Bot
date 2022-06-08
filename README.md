# Cobalt_Strike_Bot
CobaltStrike 上线通知，飞书群聊机器人通知

## 飞书群聊机器人
在飞书中新建一个群聊，在群聊中添加一个群聊机器人。将其webhook地址复制，替换掉`$feishu_url`中的webhook地址
```bash
$feishu_url = 'https://open.feishu.cn/open-apis/bot/v2/hook/092e2219-726f-4202-876a-cc6ac8641490';
```
<img width="919" alt="image" src="https://user-images.githubusercontent.com/21257485/172523390-4bad37c6-7a31-4fe4-b2fe-a7bb5194cffc.png">

## 服务端部署

```bash
./agscript [IP] [PORT] [UserName] [PassWord] [cna_file_Path]
```
## 效果图
<img width="373" alt="image" src="https://user-images.githubusercontent.com/21257485/172524312-11466b01-3bb4-4c68-a881-6caa60d4adaa.png">
