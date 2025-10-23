App Store 搜索 超级指令 即可下载

# 功能说明：短视频去水印解析

## 功能简介
支持解析短视频并去水印，包括：

- 抖音/皮皮虾/火山/微视/最右/快手/全民小视频/皮皮搞笑/梨视频/西瓜/微博/虎牙/绿洲/好看/逗拍/美拍/新片场/A站/全民K歌/6间房  
- 支持使用快捷指令（Shortcuts）解析
- 支持保存小红书实况（LivePhoto）到相册

上游地址：[GitHub - parse-video](https://github.com/wujunwei928/parse-video)

---

## 功能演示

1. **抖音（部分不支持，自行尝试）**  
[img=465,918]https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E8%A7%86%E9%A2%91%E8%A7%A3%E6%9E%90/video_dy.webp[/img]

2. **快手**  
[img=465,918]https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E8%A7%86%E9%A2%91%E8%A7%A3%E6%9E%90/video_ks.webp[/img]

3. **哔哩哔哩**  
[img=465,918]https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E8%A7%86%E9%A2%91%E8%A7%A3%E6%9E%90/video_bibi.webp[/img]

4. **小红书支持实况 LivePhoto 下载保存**  
[img=465,918]https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E8%A7%86%E9%A2%91%E8%A7%A3%E6%9E%90/video_xhs.webp[/img]

5. **支持使用快捷指令解析视频**  
[img=465,918]https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E8%A7%86%E9%A2%91%E8%A7%A3%E6%9E%90/video_cuts.webp[/img]

---

# 功能说明：API 快捷指令与自动化

## 功能简介
应用内提供 **API 接口**，用户可通过 **快捷指令（Shortcuts）** 调用，并结合 **iOS 自动化** 功能，实现：

- 定时签到  
- 其他自动化任务  

无需手动操作，轻松自动化日常流程。

---

## 教程步骤

1. **导入 API 到超级指令**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_1.webp[/img]

2. **使用抓包工具抓取请求**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_2.webp[/img]

3. **在抓包详情点击右上角分享按钮获取 cURL 命令**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_7.webp[/img]

4. **点击导入到超级指令**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_9.webp[/img]

5. **导入成功后可进行请求测试**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_10.webp[/img]

6. **请求成功示例**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_12.webp[/img]

7. **打开快捷指令 APP**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/api%E6%95%99%E7%A8%8B/api_1.webp[/img]

8. **点击“新自动化”**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/api%E6%95%99%E7%A8%8B/api_2.webp[/img]

9. **选择“特定时间”**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/api%E6%95%99%E7%A8%8B/api_3.webp[/img]

10. **设置执行时间、每天重复、立即运行并关闭运行时通知，点击右上角“下一步”**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/api%E6%95%99%E7%A8%8B/api_4.webp[/img]

11. **搜索并选择“API 请求”**（需 iOS 16 及以上）  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/api%E6%95%99%E7%A8%8B/api_5.webp[/img]

12. **设置成功后，每天指定时间会自动运行并发送通知**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/api%E6%95%99%E7%A8%8B/api_6.webp[/img]

13. **快捷指令执行的 API 会有闪电 ⚡️ 标识**  
[img=465,918]
https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5curl%E6%95%99%E7%A8%8B/curl_15.webp[/img]

---

# 下载地址

## iOS App

[img=465,918]https://env-00jxto4zxn5q.normal.cloudstatic.cn/%E6%95%99%E7%A8%8B/%E8%A7%86%E9%A2%91%E8%A7%A3%E6%9E%90/app.webp[/img]

- **App Store 最新版本**：[点击前往 App Store](https://apps.apple.com/cn/app/id6749407359)  
- **GitHub**：[点击访问 GitHub](https://github.com/Zhuzhen6/SuperFinger
