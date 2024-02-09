# 最短代码 OOM 大赛！

![61HSF0(A7FUWL%2HHKQW WB_tmb](https://github.com/InvoluteHell/OutOfMemory/assets/18511905/23ea5fb8-291a-4496-be78-c6f52508bc97)


## 比赛规则

- 使用最短的代码占满内存！考虑大家设备各不相同，为方便比赛计量，实际占用 4G 及以上的内存即可
- 要求在不使用断点等调试手段的情况下，使用 任务管理器 / htop / top 等第三方主流工具 **截图** 并上传  
  即要占用一定的时间，申请内存后立刻进程结束这种无法截图的不行
- 计分规则为：代码字符数量 乘 字符种类。最小者获胜！
- 对于类似 Matlab 等解释器本身占用极大的语言，实际占用需减去解释器本身占用
- 不准联网；不准通过环境变量、文件名、编译参数等耍赖；不准使用专门为本次比赛设计的编程语言、操作系统、API 等。总之不准卡 bug，主办方享有比赛规则解释权（
 
## 参赛方式

- 每个人新建一个文件夹，在里面放上你的代码、截图、README 等，并通过 Pull Request 提交  
  请组织内成员不要直接 push，这样的没法计分，给我老老实实用 PR！
- 比赛使用 GitHub Action 自动生成排名，参赛者无需再手动修改
- 可以使用 `python3 .github/scoring.py <file>` 来给自己算一下分（

## 排名

<!-- begin of RANKING -->
| Rank | Player | File | Length | Category | Score |
| ---- | ------ | ---- | ------ | -------- | ----- |
| 1 | [Moeweb647252](Moeweb647252) | [oom.bat](Moeweb647252/oom.bat) | 5 | 3 | 15 |
| 2 | [wanz](wanz) | [oom.py](wanz/oom.py) | 9 | 3 | 27 |
| 3 | [dragove](dragove) | [oom.py](dragove/oom.py) | 9 | 5 | 45 |
| 4 | [HisAtri](HisAtri) | [new.py](HisAtri/new.py) | 10 | 5 | 50 |
| 5 | [horror-proton](horror-proton) | [oom.sh](horror-proton/oom.sh) | 10 | 8 | 80 |
| 6 | [Cherry-mma](Cherry-mma) | [main.wl](Cherry-mma/main.wl) | 10 | 9 | 90 |
| 7 | [lovemilk](lovemilk) | [oom.rb](lovemilk/oom.rb) | 14 | 9 | 126 |
| 8 | [Rear_Sagittar](Rear_Sagittar) | [fuckwin.ps1](Rear_Sagittar/fuckwin.ps1) | 13 | 12 | 156 |
| 9 | [Zhilu](Zhilu) | [simple-oom.js](Zhilu/simple-oom.js) | 17 | 13 | 221 |
| 10 | [limaomao](limaomao) | [omm.py](limaomao/omm.py) | 26 | 16 | 416 |
| 11 | [yusuixian](yusuixian) | [main.cpp](yusuixian/main.cpp) | 26 | 17 | 442 |
| 12 | [mr_cino](mr_cino) | [oom.wo](mr_cino/oom.wo) | 26 | 17 | 442 |
| 13 | [Cherry](Cherry) | [main.c](Cherry/main.c) | 27 | 18 | 486 |
| 14 | [bakashigure](bakashigure) | [a](bakashigure/a) | 26 | 19 | 494 |
| 15 | [RaySky_Rt](RaySky_Rt) | [oom.cpp](RaySky_Rt/oom.cpp) | 26 | 19 | 494 |
| 16 | [lianhong](lianhong) | [main.go](lianhong/main.go) | 43 | 24 | 1032 |
| 17 | [Ns2Kracy](Ns2Kracy) | [main.go](Ns2Kracy/main.go) | 46 | 27 | 1242 |
| 18 | [wzyisyyds](wzyisyyds) | [rust.rs](wzyisyyds/rust.rs) | 48 | 27 | 1296 |
<!-- end of RANKING -->

## 奖品

- 第一名：一箱难喝的黑咖啡。由 @MistEO 赞助！
- 最佳创意奖：10 美元 苹果 或 Google Play 礼品卡。由 @守夜人 赞助！
- 随机参与奖：V 你 50！由 @时雨 赞助！

欢迎老板们赞助更多奖品~

## 时间

2024/02/09 ~ 2024/02/12 大年初三 晚上（北京时间）

就是现在！

## 讨论

欢迎加入 [QQ 群](https://jq.qq.com/?_wv=1027&k=8aBWumWU) (672372860), [Telegram 群](https://t.me/+NjDljiDRrpI4NTU1) ，或通过 issue, discussions 讨论！
