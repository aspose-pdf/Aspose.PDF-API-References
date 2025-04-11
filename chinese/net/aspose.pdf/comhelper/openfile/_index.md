---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: ComHelper 方法。仅使用文件名创建并返回文档。与 Document 相同
type: docs
weight: 20
url: /zh/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

仅使用 *filename* 创建并返回文档。与 [`Document`](../../document/document/) 相同。

```csharp
public Document OpenFile(string filename)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | 字符串 | PDF 文档文件的名称。 |

### 返回值

文档对象

### 另见

* 类 [Document](../../document/)
* 类 [ComHelper](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

初始化并返回 [`Document`](../../document/) 类的新实例，以便处理加密文档。

```csharp
public Document OpenFile(string filename, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | 字符串 | 文档文件名。 |
| password | 字符串 | 用户或所有者密码。 |

### 返回值

文档对象

### 另见

* 类 [Document](../../document/)
* 类 [ComHelper](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

初始化 [`Document`](../../document/) 类的新实例，以便处理加密文档。

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | 字符串 | 文档文件名。 |
| password | 字符串 | 用户或所有者密码。 |
| isManagedStream | 布尔值 | 如果设置为 `true`，则在退出之前关闭内部流；否则，不关闭。 |

### 返回值

文档对象

### 另见

* 类 [Document](../../document/)
* 类 [ComHelper](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

从文件打开现有文档，提供必要的转换选项以获取 PDF 文档。

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | 字符串 | 输入文件以转换为 PDF 文档。 |
| options | LoadOptions | 表示将 *filename* 转换为 PDF 文档的属性。 |

### 返回值

文档对象

### 另见

* 类 [Document](../../document/)
* 类 [LoadOptions](../../loadoptions/)
* 类 [ComHelper](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)