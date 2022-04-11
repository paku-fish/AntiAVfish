# AntiAVfish

一个把shellcode转换为免杀EXE的小工具，基于c++11
因免杀的特殊性，代码暂时不开源(我代码写得比较屎)，用了一种从游戏安全领域借鉴过来的手法

发布时间:2022/04/11
截至至目前 火绒 360 WindowsDefender 均 bypass

用法:
1.生成cobaltstrike/msf的shellcode (RAW)
2.将二进制bin文件放在同一目录下
3.AntiAVfish.exe filename.bin

效果图:
![图片](https://user-images.githubusercontent.com/82560112/162715666-1987c93c-e883-43b8-b177-2ff6c5b8b29d.png)
![图片](https://user-images.githubusercontent.com/82560112/162715707-8e3943da-2bad-4e4d-a80c-ac72f4c08fb6.png)
![图片](https://user-images.githubusercontent.com/82560112/162715717-7c162bc1-20f0-4433-80f9-b78b7668e0dd.png)

