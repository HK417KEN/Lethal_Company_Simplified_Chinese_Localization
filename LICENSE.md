# 简述

**\* 注意，本项目同时包含开源以及非开源内容，请谨慎使用或者对本项目进行衍生 \***

本项目由 HK417KEN 基于 *XUnity.AutoTranslator* 将 *繁体中文项目* 与 *简体中文项目* 双方项目整合与修改而来。双方因是否开源及其许可的选择不同，故本页面对许可及开源作详细解释，但最终解释权仍归原作者所有。

<br>

# 歧义解释

- "双方" 指的是 *繁体中文项目* 方 与 *简体中文项目* 方
- 空格与大小写的不同应该视为同一个条目

<br>

# 我如何知道，我所使用的内容该遵守谁的许可证

**如果文件中包含有许可信息，请直接遵守文件内的许可信息。**

```
例子1：

简体中文项目：
Welcome!=欢迎！

繁体中文项目：
Welcome!=歡迎！

本项目：
Welcome!=欢迎！

在双方都有该条目下，与其中一方项目完全相等时，则遵守该方项目的许可；即该例子下请遵守 *简体中文项目* 的许可。
```

```
例子2：

简体中文项目：
Toy cube=玩具立方体

繁体中文项目：
Toy cube=玩具方塊

本项目：
Toy cube=魔方

如果双方都有该条目，但等号右边值均不等同的条件下，请自行选择其中一方的项目的许可遵守。
```


```
例子3：

简体中文项目：
--无匹配项--

繁体中文项目：
sr:"^Drop (.+?)\s*:\s*\[G\]$"=丟棄 $1：[G]

本项目：
sr:"^Drop (.+?)\s*:\s*(.+)(\s*\(Hold\)|)?$"=丢下 $1：$2

如果其中一方没有该条目，请遵守有条目的一方的项目许可，无论等号右边的值是否一致；即该例子遵守 *繁体中文项目* 的许可
```

如果双方都没有该条目，且文件或段落内不含许可信息，请遵守该页面的 **其他内容** 的许可

<br>

# 具体文件内的许可信息

如果在具体文件中包含有许可信息，则最优先以该文件或所规定的部分文本遵守其指定的许可信息。

比如 XUnity.AutoTranslator 的 MIT License 和 BepInEx 的 LGPL-2.1

<br>

# XUnity.AutoTranslator

作者：Bepis

项目地址：https://github.com/bbepis/XUnity.AutoTranslator

是否开源：开源

许可证：MIT License

许可页面：https://github.com/bbepis/XUnity.AutoTranslator/blob/master/LICENSE

以下为该作者的许可内容：

```
MIT License

Copyright (c) 2018 Bepis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

<br>

# 繁体中文项目

作者：XoF-eLtTiL

项目地址1：https://thunderstore.io/c/lethal-company/p/XoFKon/Lethal_Company_TC_for_r2modman/

项目地址2：https://github.com/XoF-eLtTiL/Lethal_Company_Traditional_Chinese_Localization

是否开源：非开源

许可证：私有许可

许可页面：https://github.com/XoF-eLtTiL/Lethal_Company_Traditional_Chinese_Localization/issues/5

<br>

# 简体中文项目

作者：Xiahua Liu

项目地址1：https://thunderstore.io/c/lethal-company/p/EggFriedRice/Lethal_Company_CN_Localization_Simplified_Chinese/

项目地址2：https://github.com/xiahualiu/lethal_zh_mod

是否开源：开源

许可证：MIT License

许可页面：https://github.com/xiahualiu/lethal_zh_mod/blob/main/LICENSE

以下为该作者的许可内容：

```
MIT License

Copyright (c) 2023 Xiahua Liu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

<br>

# 其他内容

如果你有能力区分本项目的部分内容并非来自 "**Bepis**" 和 "**XoF-eLtTiL**" 以及 "**Xiahua Liu**" 及其他权利人，那么以下则是 "**HK417KEN**" 提供的 Unlicense 授权许可：

```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>
```
