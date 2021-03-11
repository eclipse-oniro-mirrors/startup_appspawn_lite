# appspawn应用孵化器组件<a name="ZH-CN_TOPIC_0000001081995748"></a>

-   [简介](#section469617221261)
-   [目录](#section15884114210197)
-   [约束](#section12212842173518)
-   [对应仓库](#section641143415335)

## 简介<a name="section469617221261"></a>

应用孵化器，负责接受应用程序框架的命令孵化应用进程，设置其对应权限，并调用应用程序框架的入口。

## 目录<a name="section15884114210197"></a>

```
base/startup/appspawn_lite/     # 应用孵化器组件
├── LICENSE
└── services
    ├── include              # 应用孵化器组件头文件目录
    ├── src                  # 应用孵化器组件源文件目录
    └── test                 # 应用孵化器组件测试用例源文件目录
        └── unittest
```

## 约束<a name="section12212842173518"></a>

目前支持小型系统设备（参考内存≥1MB），如Hi3516DV300 、Hi3518EV300。

## 对应仓库<a name="section641143415335"></a>

启动恢复子系统

hmf/startup/syspara\_lite

**hmf/startup/appspawn\_lite**

hmf/startup/bootstrap\_lite

hmf/startup/init\_lite

hmf/startup/startup

hmf/startup/systemrestore

