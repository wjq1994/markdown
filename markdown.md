
# markdown用法

#### 说明

markdown主要包括以下几类语法：
标题、段落、行内格式、代码块、引用块、超链接、图片、列表、水平分割线、表格、任务列表、删除线、自动链接
不同的IDE还支持扩展的语法画流程图和时序图、插入数学公式、做PPT、写微信公众号

## *代码块*

```javascript
if (TextUtils.isEmpty(text)) {
    return null;
}
```

## **引用块**

> 引用块段落一。
>
> 引用块段落二。
>> 内嵌引用块段落一。
>
> ### 引用块内的标题


## 超链接

行内式 [简书](https://www.jianshu.com/u/8073a2bdfea3) 链接。

行内式 [GitHub](https://github.com/) 链接。

引用式 [博客][1] 链接。

引用式 [GitHub][2] 链接，带 title。

[1]: https://www.jianshu.com/u/8073a2bdfea3
[2]: https://github.com/ "我的 GitHub 主页"

## 图片

![Alt text](https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png "favicon")

## 列表

- 苹果
- 葡萄
- 榴莲

1.苹果

2.葡萄

3.榴莲

## 水平分割线

***

-----

- - -

## 表格

| 编号  | 姓名（左） | 年龄（右） | 性别（中） |
| ----- | :--------  | ---------: | :------:   |
| 0     | 张三       | 28         | 男         |
| 1     | 李四       | 29         | 男         |


## 任务列表

###### 在 GitHub / GitLab 里有较好的支持。


- [x] 洗碗
- [ ] 清洗油烟机
- [ ] 拖地

## 删除线

后面三个字打上~~删除线~~。

## 自动链接

https://github.com

<example@gmail.com>

## 可以插入html代码
<font face="黑体" color="red">我是黑体字,但是红体字</font>

- - -
###### 参考链接
https://markdown-zh.readthedocs.io/en/latest/
