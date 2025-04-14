# Batch Docking: Automated Workflow Based on AutoDock-GPU (V 1.4.1)
这是一个基于AutoDock-GPU的自动化批量对接程序，只需输入小分子的smiles结构文档（支持批量输入）并且提供蛋白质的网格文件（maps.fld）即可自动完成小分子预处理，分子对接，结果提取等步骤。<br>
This project is an automated batch docking pipeline built on AutoDock-GPU, designed to streamline virtual screening workflows.<br>

更多完善的功能和用户手册在将来的更新中被加入！<br>
More complete features and a user manual will be added in future updates!<br>

## 更新日志
### 地理与历史
1. 实现了基于try与traceback模块的运行监视，现在程序不再会因为某一小分子的错误或偶然的对接失败而产生系统级报错导致运行中断<br>
2. 优化了信息显示，调试更为方便，并且显示单次对接迭代次数，防止调试后忘记更改<br>
3. 圆哆啦真好玩，我有晓美焰和二叶莎奈了，还抽到了由比鹤乃，什么时候把环彩羽和秋野枫也抽出来呀<br>
4. 完善了语言包，现在南半球倒立的人们和古人使用该程序没有语言障碍了！<br>
5. 修复了部分已知的bug<br>
6. 优化了部分代码<br>
7. 看了一些猫咪视频，埋了一点猫咪彩蛋<br>
8. 移除了Herobrine<br>

## Changelog<br>
### Error Tracking & Improvements
1. Implemented try/traceback-based runtime monitoring – The program now handles molecule-specific errors without system-level crashes.
2. Enhanced debugging visibility – Added real-time display of per-docking iteration counts to prevent oversight after testing.
3. Magia Exedra is addictive! Got Akimi Homura, Futaba Sana, and Yui Tsuruno... still hunting for Tamaki Iroha and Akino Kaede! 
4. Squashed lingering bugs.
5. Codebase optimizations.
6. Removed Herobrine.


## 运行环境需求
1）装有Ubuntu的WSL2环境或其他Linux发行版<br>
2）已编译的AutoDock-GPU程序<br>
3）安装OpenBaBel<br>
4）安装AutoDockTools<br>
5）安装Python3<br>
6）安装Python2并且具备numpy库<br>
7）上述软件及相关环境变量设置正确<br>

## 未来的发展方向
1）**进一步优化程序运行的逻辑** 让转化失败的可疑分子在结果文件中单独标识出来<br>
2）**优化软件输出** 添加可视化的进度条、进程监视与看门狗<br>
3）**更好的用户手册**<br>

## 本程序历经多次大版本更新，旧有技术文档已失去失效性，请等待稍后的教程更新

## System Requirements
1. A WSL2 environment running Ubuntu, or another Linux distribution.<br>
2. The pre-compiled AutoDock-GPU program.<br>
3. Installation of OpenBaBel.<br>
4. Installation of AutoDockTools.<br>
5. Installation of Python3.<br>
6. Install Python 2 with the numpy library.<br>
7. Ensure that the above software and related environment variables are set up correctly.<br>

## Future Development Directions
1. **Workflow Optimization:** Improving the program’s logic to mark molecules that fail conversion separately in the result files.<br>
2. **Enhanced Output:** Adding visual progress bars, process monitoring, and a watchdog.<br>
3. **Improved User Manual.**<br>

## This program has undergone multiple major version updates. The old technical documentation is now obsolete. Please await the updated tutorial.

The English portion of this project's README was generated by DeepSeek and ChatGPT.







