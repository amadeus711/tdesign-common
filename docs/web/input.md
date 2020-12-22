# Input 输入框
用于承载用户信息录入的文本框，常用于表单、对话框等场景，对不同内容的信息录入，可拓展形成多种信息录入形式

### 何时使用
需要用户录入信息时

需要对用户录入的进行进行即时的反馈时

## 1.组件类型
### 1.1.基础输入框
定义：最基础的单行输入框，按状态可分为正常、禁用、错误、带额外提示

使用场景：仅需输入少量内容（20个字以内）的场景

{{ base }}

### 1.2.文本域输入框
定义：可输入多行内容的输入框，如限制字数可在输入框右下角加入字数提示

使用场景：需要输入大量多行文本内容的场景

{{ textarea }}

### 1.3.前后置标签输入框
定义：在输入框前后加入一些特定的纯展示标签，以方便识别及提升效率

使用场景：用于一些有固定组合的场景，如输入网址

备注：区别于“组合输入框”，前后置标签输入框的标签仅用于展示，不可进行操作

{{ addon }}

### 1.4.组合输入框
定义：多个输入框相组合，或与其他控件（如下拉）相组合，以方便识别

使用场景：用于一些固定组合或者固定格式输入的场景，如输入电话号码

备注：1、区别于“前后置标签输入框”，组合输入框是多个可操作的控件相组合

2、在多个输入框组合的场景下（如电话），输入完一个内容框后，光标需要自动跳转至下一个内容框，以方便用户无缝衔接输入

{{ group }}

### 1.5.可清空内容输入框
定义：带清空操作的输入框，可快捷清空输入过的内容

使用场景：通用

{{ clearable }}

### 1.6.密码输入框
定义：由符号代替输入内容的输入框，并可通过操作展示原文信息

使用场景：用于强安全信息输入的场景，如密码输入

{{ password }}