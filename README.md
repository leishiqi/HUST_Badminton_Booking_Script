# badminton_booking_script_HUST
华中科技大学专用羽毛球场地预约脚本。本简易脚本仅用作个人娱乐用途。
# Request
+ chrome浏览器，下载对应版本的chromedriver至Application根目录，即必须与chrome.exe在同一文件夹
+ selenium
+ apschedule
# Notice
+ 本脚本无法执行验证码识别，请根据文档注释提前使用未占用port打开新的chrome窗口，并登录校园账号
+ 请根据需要改变apschedule任务执行方式，比如使用crontab每天早8点定时执行
+ 由于校园账号登陆状态无法保持，因此本脚本无法放置服务器后台执行，请自行探索cookie登陆方法
+ 本脚本仅仅只是减少人工步骤，可控制3秒内完成场地的预定（无任何突发情况）