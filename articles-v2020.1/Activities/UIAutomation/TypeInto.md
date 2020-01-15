# 输入文本

输入文本到指定位置

## 属性

目标

- **控件元素** ：接收变量作为输入文本的目标元素。此项和&quot;选择器&quot;二选一填入
- **选择器** ：用于指示要输入文本的目标元素。可通过点击&quot;指定元素&quot;自动生成。仅支持字符串变量和字符串
- **等待超时（毫秒）** ：限定查找目标元素时间，超出指定时间后将不再等待，执行下一个组件。单位为毫秒（ms）,1000ms = 1s。仅支持整型变量和整型

输入

- **文本** ：输入到选择器元素的内容。文本内容所见即所得，不支持转义。支持字符串变量和字符串