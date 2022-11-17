---
title: ITextElement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于呈现文本结构元素的界面。
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements/itextelement/
---
```
public interface ITextElement
```

用于呈现文本结构元素的界面。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStructureTextState()](#getStructureTextState--) | 获取文本结构元素的 StructureTextState 对象。 |
| [setText(String text)](#setText-java.lang.String-) | 将文本内容附加到当前文本元素。 |
### getStructureTextState() {#getStructureTextState--}
```
public abstract StructureTextState getStructureTextState()
```


获取文本结构元素的 StructureTextState 对象。

**退货：**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) 值：文本结构元素的 StructureTextState 对象。
### setText(String text) {#setText-java.lang.String-}
```
public abstract void setText(String text)
```


将文本内容附加到当前文本元素。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文字内容 |
