# SwiftVapor
## 学习swift---vapor的一些笔记
---
### 新建项目
打开终端执行<b>Vapor Toolbox</b> 新建命令  
```
vapor new SwiftVapor  
```  
执行完成切换到新建目录下  
```
cd SwiftVapor
```  
生成Xcode工程  `vapor xcode` toolbox询问是否自动打开Xcode,选`y`  
**编译和运行**  
打开xcode 从scheme中选择**run** `My Mac`运行   Xcode终端窗口显示  
```
Server starting on http://localhost:8080
```   
>或者使用命令
```
vapor build
vapor run
```  
>更新vapor  `brew upgrade vapor`  
>如果你使用 SPM 时遇到问题, 清理项目有时会有帮助.
>`vapor clean`




