# 第一章：Python基础

本章节将介绍Python的基础知识，包括变量、基本语法等内容，并配有示例代码。

## 1.1 变量

变量用于存储数据。Python无需声明变量类型，直接赋值即可。

```python
x = 10
name = "Alice"
pi = 3.14
```

## 1.2 基本语法

- Python使用缩进表示代码块（通常为4个空格）。
- 语句末尾不需要分号。
- 注释以`#`开头。

```python
# 这是一个注释
if x > 5:
    print("x大于5")
else:
    print("x不大于5")
```

## 1.3 数据类型

常见数据类型有：整数（int）、浮点数（float）、字符串（str）、布尔值（bool）。

```python
age = 20          # int
height = 1.75     # float
name = "Bob"      # str
is_student = True # bool
```

## 1.4 输入与输出

```python
name = input("请输入你的名字：")
print("你好,", name)
```

## 1.5 示例代码

请参考`example.py`文件，包含本章内容的综合示例。
