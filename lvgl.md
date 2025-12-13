## arduino 使用 lvgl 教程
- 到 github lvgl 项目，下载对应版本的 tag 完整项目代码下来
- 把下载下来的文件放到 用户/文档/Arduino/libraries/lvgl
- 把 lvgl 目录下的 lv_conf_template.h 文件复制到 libraries 目录，改名 lv_conf.h
- 修改 lv_conf.h 文件的配置
```
#if 0 改成 1
LV_TICK_CUSTOM 0 改成 1
```

- 运行 demo 需要的单独配置

在 lv_conf.h 文件中修改需要跑的 demo 的宏，改为1，在文件的末尾

把lvgl下面的 demos, examples 2个文件夹放到 lvgl/src 下面

在官方的 那个单独的 examples 文件里引入头文件
#include "demos/lv_demos.h"