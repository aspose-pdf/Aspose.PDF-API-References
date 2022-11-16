---
title: ISaveableFacade
second_title: 用于 Java API 参考的 Aspose.PDF
description: Facade 接口，它定义了所有可保存外观的通用方法。
type: docs
weight: 72
url: /zh/java/com.aspose.pdf.facades/isaveablefacade/
---
**所有已实现的接口：**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade)
```
public interface ISaveableFacade extends IFacade
```

Facade 接口，它定义了所有可保存外观的通用方法。
## 方法

| 方法 | 描述 |
| --- | --- |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将结果 PDF 文档保存到流中。 |
| [save(String destFile)](#save-java.lang.String-) | 将结果 PDF 文档保存到文件。 |
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream destStream)
```


将结果 PDF 文档保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 输出流对象 |

### save(String destFile) {#save-java.lang.String-}
```
public abstract void save(String destFile)
```


将结果 PDF 文档保存到文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 字符串对象 |
