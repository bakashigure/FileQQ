# FileQQ | 文件QQ

通过文件来聊 QQ  

这是一个很奇怪的项目，为什么有人会需要通过文件聊 QQ 呢？  

我只能说，迫不得已，懂得都懂了_(:з」∠)_

## 使用说明

1. 环境配置

    ```bash
    pip install nb-cli
    nb plugin install nonebot_plugin_apscheduler
    nb plugin install nonebot_plugin_gocqhttp
    nb driver install websockets
    nb driver install fastapi
    ```

2. `nb run` 运行
3. 打开 <http://localhost:8090/go-cqhttp/#/> 登录你的账号
4. 在 `cache/recv` 文件夹下查看聊天记录
5. 在对应的 `cache/send` 文件夹下回复消息，以 两个回车 或 `#` 结尾

## Tips

可以使用的方法包括 ssh、code-server 等，其他请自行尝试

## Todo

- [] Focus 功能

## 打赏

请作者喝杯咖啡吧~ （请备注 FileQQ 项目，感谢你的资瓷 ✿✿ヽ(°▽°)ノ✿）

<div>
<img alt="sponsor" src="https://user-images.githubusercontent.com/18511905/171821963-be1247d1-2959-4d2f-91c1-095a215dd601.jpg" width=262 height=408/>
<img alt="sponsor" src="https://user-images.githubusercontent.com/18511905/171821974-c5b13928-c66a-4168-b472-02b7048a2eff.png" width=298 height=408/>
</div>
