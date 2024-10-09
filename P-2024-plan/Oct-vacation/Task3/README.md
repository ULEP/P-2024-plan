# Task 3

请补充个人信息后，在此完成报告！

@Author:  Zeitgeist-tori \ 胡炜佳
@Email: 2959608864@qq.com

### 1. 命令行与前端界面
通过增加命令行参数，以及编写对应的html文件，该程序实现了交互式操作：用户输入任意式子，可在页面上输出运算结果。

### 1.事件监听器
我一开始没写`document.addEventListener('DOMContentLoaded', function() {}`,即等待页面DOM完全加载再执行的事件监听器；而且在我的html文件中`<script>`还写在了获取输入值代码的前面，这就导致一开始我的`const input = document.getElementById('input'); `始终不能正确获取用户输入值。加上该监听器后

### 2.增加括号功能（未实现）
初步了解到要使用逆波兰表达式，但还没来得及实现。

