# Unity 中英文双语插件

对于初学者来说`Unity`满满的英文很是头疼，但是如果直接切换中文，又会导致写代码不太方便，为此开发了能够同时显示中英文的插件。

## 工作原理
Unity 的中文版由一个中英文对照表进行翻译，所以插件做的事情就是替换里面的内容，达到“双语”的效果。支持`MacOS`、`Windows`，`Linux`没有进行测试

## 功能
1. 对于单个英文单词的内容，可以选择只使用英文，减少不必要的中文翻译
2. 在原有的中文短语（非句子）后面，添加了对应的英文短语（方括号内）
3. 可以添加`中文/英文`忽略词配置文件，只保留中文或者英文(插件已内置了一个默认配置)
4. 其他的内容没有做替换，原样保留

**效果如下：**

<img width="555" alt="image" src="https://github.com/liu-shx/UnityTranslation/assets/90260874/6243710b-58b6-4c53-9619-473b0b5e3420">

## 主界面

<img width="503" alt="image" src="https://github.com/liu-shx/UnityTranslation/assets/90260874/325ba0a1-302f-4845-8723-00590644ef75">

## 使用步骤
1. 在`Unity Hub`中，为编辑器添加中文模块

2. 切换`Unity`语言为中文

3. 导入插件包

4. 打开`Unity`，选择`Window`-->`中英双语翻译`-->`中英翻译`，然后重启`Unity`即可

## 注意事项
1. 使用哪个`Unity`版本，就添加哪个版本的中文模块
2. 必须把`Unity --> Languge`切换为中文，才能有双语效果
3. 翻译后，必须重启
4. `Window`-->`中英双语翻译`--`还原备份`可以还原成原来的中文

