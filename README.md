# Eyuyan_Curl
1. 这是一个基于Openssl+CURL系列开发高度拟浏览器的易语言框架
2. 本项目只适用于Eyuyan_X86用户
3. 本项目基于zyCurl底包重构而来,底包作者@kyozy.
4. 包含H2特征Akamai,修改TLS特征Extensions,curves,sigalgs,padding,RANDOM_GREASE_GROUP,RANDOM_GREASE_PADDING,RANDOM_SHUFFLE_EXT,RANDOM_GREASE_KEY_SHARE,RANDOM_SHUFFLE_KEY_SHARE
5. 默认不支持TLS1.0&2.0&自动重定向
6. 相似项目基于boringSSL+CURL https://github.com/lexiforest/curl_cffi

## 更新日志
2025/12/26第一次发版测试
仅作测试，不代表没有BUG，不代表不会把轮子推倒，意味着不能基于它做任何开发。
2025/12/28第二次发版测试
仅作测试，不代表没有BUG，不代表不会把轮子推倒，意味着不能基于它做任何开发。

## 公益项目
2025/12/26-本项目永久免费
发现任何收费功能，应当举报收费开发者，并拉黑他。

## 封装规则
1. 永远不支持内存加载DLL
2. 所有字符串输入必须遵循RFC标准，所有"字符串"必须输入UTF-8编码"包括磁盘路径"
3. 包括所有功能输入字符串必须遵循RFC标准一律UTF-8
4. 开发者包括所有SSL必须验证根证书
5. 遵循RFC各项标准
6. 后续封装一些Openssl的一些常用的加密算法


## 支持系统
Win8，Server2012及以上，低版本BUG一律不修。

## VS2022运行库
基础版本号：VS2022运行库以上
<a href="https://learn.microsoft.com/zh-tw/cpp/windows/latest-supported-vc-redist?view=msvc-170" target="_blank">Microsoft Visual C++ 可转散发套件的最新支持下载项目</a>


## 引用框架
1. brotli-1.2.0
2. c-ares-1.34.6
3. cJSON1.7.19
4. curl-8.17.0
5. libpsl-0.21.5
6. libssh2-1.11.1
7. nghttp2-1.68.0
8. nghttp3-1.14.0
9. ngtcp2-1.19.0
10. openssl3.6.0
11. zlib-1.3.1
12. zstd-1.5.7

## 项目分发规则
本项目以GPL-3.0 license开源协议分发代码

1. 禁止通过贩卖开源代码来获利，不限于收费易语言模块引用我开源的代码。

2. 本文仅用于开源协议研究与学习，所有示例代码遵守原协议条款发布。

3. 作者不以任何形式通过网盘、可执行文件或非源码渠道分发相关内容。

## 使用说明
1. 本项目是为了学习研究用，不得进行任何形式的转发，发布，传播。

2. 请于24小时内删除本项目。若使用期间造成任何损失，作者不负任何责任。

3. 本项目使用者因为违反本声明的规定而触犯中华人民共和国法律的，一切后果自负，作者不承担任何责任。

4. 凡以任何方式直接、间接使用本项目者，视为自愿接受本声明的约束。

5. 本项目如无意中侵犯了某个媒体或个人的知识产权，请来信或来电告之，作者将立即删除。
