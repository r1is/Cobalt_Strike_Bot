# Cobalt_Strike_Bot
CobaltStrike 上线通知，飞书群聊机器人通知

## 飞书群聊机器人
在飞书中新建一个群聊，在群聊中添加一个群聊机器人。将其webhook地址复制，替换掉`$feishu_url`中的webhook地址
```bash
$feishu_url = 'https://open.feishu.cn/open-apis/bot/v2/hook/092e2219-726f-4202-876a-cc6ac8641490';
```
<img width="919" alt="image" src="https://user-images.githubusercontent.com/21257485/172523390-4bad37c6-7a31-4fe4-b2fe-a7bb5194cffc.png">

## 服务端部署

此脚本依赖`curl`命令，请确保cs服务端已安装了`curl`
```bash
./agscript [IP] [PORT] [UserName] [PassWord] [cna_file_Path]
```
## 效果图

<center class="half">
<img width="200" alt="image" src="https://user-images.githubusercontent.com/21257485/172524624-fe29121b-eb5b-48b9-a902-06f56e6a53ed.png"><img width="200" alt="image" src="https://user-images.githubusercontent.com/21257485/172755761-0935e9dd-e07b-47f8-ad11-f34824b63eb7.png"><img width="200" alt="image" src="https://user-images.githubusercontent.com/21257485/172755780-99c48e8b-4133-4c4c-9b8e-578fc921cc8f.png">
</center>
