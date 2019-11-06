## HTML

### 考察HTML5新特性的本地缓存storag相关内容

#### 说一说localStorage/sessionStorage和cookie（初级）

#### 进阶：localStorage容量是多少，超出会怎么样？（初/中级）

#### 进阶：实现一个safeLocalStorage（中级）

## CSS

### 考察CSS盒模型的理解以及实际业务场景应用

#### 说说你对CSS盒模型的理解（初级）

#### 进阶：盒模型应用 （初级）
```
问题描述: 下面这段代码在浏览器的表现效果是什么样的，是否会占满一行？如果不是如何才能占满一行？

<style>
  .container > img {
    width: 50%;
    border: 1px solid #000;
  }
</style>

<div class='container'>
  <img src='xxxx.jpg' />
  <img src='xxxx.jpg' />
</div>


```

## JS

### 考察防抖和节流的理解以及setTimeout和clearTimeout的高阶使用

#### 谈一谈防抖和节流的理解～ （初/中级）

#### 进阶：实现一个debounce-input（中/高级）
```
问题描述：比如我在百度查的关键词是 '前端面试题'，百度的做法是你每输入一个字就进行模糊匹配，
在实际业务场景中其实有些浪费性能，我们可以等待用户停止输入一段时间后再对input的内容进行查询搜索。
请实现一个延时是500ms的input。

```
