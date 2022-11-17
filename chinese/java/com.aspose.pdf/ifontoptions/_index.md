---
title: IFontOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 调整字体行为的有用属性
type: docs
weight: 434
url: /zh/java/com.aspose.pdf/ifontoptions/
---
```
public interface IFontOptions
```

调整字体行为的有用属性
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNotifyAboutFontEmbeddingError()](#getNotifyAboutFontEmbeddingError--) | 有时无法将所需字体嵌入到文档中。 |
| [setNotifyAboutFontEmbeddingError(boolean value)](#setNotifyAboutFontEmbeddingError-boolean-) | 有时无法将所需字体嵌入到文档中。 |
### getNotifyAboutFontEmbeddingError() {#getNotifyAboutFontEmbeddingError--}
```
public abstract boolean getNotifyAboutFontEmbeddingError()
```


有时无法将所需字体嵌入到文档中。原因有很多，例如许可证限制或在目标计算机上找不到所需的字体。当这种情况出现时，它不是简单地检测到的，因为所需的字体是通过一组属性标志 Font.IsEmbedded = true; 嵌入的；当然可以在设置后立即读取此属性，但这不是方便的方法。标志 NotifyAboutFontEmbeddingError 在尝试嵌入字体失败的情况下强制执行异常机制。如果设置此标志，将抛出 FontEmbeddingException 类型的异常。默认为假。

**退货：**
boolean - 布尔值
### setNotifyAboutFontEmbeddingError(boolean value) {#setNotifyAboutFontEmbeddingError-boolean-}
```
public abstract void setNotifyAboutFontEmbeddingError(boolean value)
```


有时无法将所需字体嵌入到文档中。原因有很多，例如许可证限制或在目标计算机上找不到所需的字体。当这种情况出现时，它不是简单地检测到的，因为所需的字体是通过一组属性标志 Font.IsEmbedded = true; 嵌入的；当然可以在设置后立即读取此属性，但这不是方便的方法。标志 NotifyAboutFontEmbeddingError 在尝试嵌入字体失败的情况下强制执行异常机制。如果设置此标志，将抛出 FontEmbeddingException 类型的异常。默认为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |
