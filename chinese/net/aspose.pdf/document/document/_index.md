---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Document 构造函数。 从输入流初始化新的 Document 实例
type: docs
weight: 10
url: /zh/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 包含 pdf 文档的流。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 包含 pdf 文档的流。 |
| isManagedStream | Boolean | 如果设置为 `true`，则在退出之前关闭内部流；否则，不关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 输入流对象，对应的 pdf 是密码保护的。 |
| password | String | 用户或所有者密码。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 包含 pdf 文档的流。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，则在退出之前关闭内部流；否则，不关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

仅使用 *filename* 初始化 Document。 与 `Document` 相同。

```csharp
public Document(string filename)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | pdf 文档文件的名称。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

仅使用 *filename* 初始化 Document。 与 `Document` 相同。

```csharp
public Document(string filename, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | pdf 文档文件的名称。 |
| isManagedStream | Boolean | 如果设置为 `true`，则在退出之前关闭内部流；否则，不关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

初始化 [`Document`](../) 类的新实例以处理加密文档。

```csharp
public Document(string filename, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 文档文件名。 |
| password | String | 用户或所有者密码。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

初始化 [`Document`](../) 类的新实例以处理加密文档。

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 文档文件名。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，则在退出之前关闭内部流；否则，不关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

初始化空文档。

```csharp
public Document()
```

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

通过版本初始化空文档。

```csharp
public Document(PdfVersion version)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| version | PdfVersion | PDF 版本。 |

### 另请参见

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

从文件打开现有文档，提供必要的转换选项以获取 pdf 文档。

```csharp
public Document(string filename, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 输入文件以转换为 pdf 文档。 |
| options | LoadOptions | 表示将 *filename* 转换为 pdf 文档的属性。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

从流打开现有文档，提供必要的转换以获取 pdf 文档。

```csharp
public Document(Stream input, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 输入流以转换为 pdf 文档。 |
| options | LoadOptions | 表示将 *input* 转换为 pdf 文档的属性。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)