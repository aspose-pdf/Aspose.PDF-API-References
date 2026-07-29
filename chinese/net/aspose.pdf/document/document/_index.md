---
title: "Document.Document"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 构造函数。从输入流初始化新的 Document 实例"
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
| 输入 | Stream | 包含 pdf 文档的流。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 包含 pdf 文档的流。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则，不会关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 输入流对象，对应的 pdf 已受密码保护。 |
| password | String | 用户或所有者密码。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 输入流对象，对应的 pdf 已受密码保护。 |
| certOptions | CertificateEncryptionOptions | 证书加密选项。 |

### 另请参见

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 包含 pdf 文档的流。 |
| certOptions | CertificateEncryptionOptions | 证书加密选项。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则不会关闭。 |

### 另请参见

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

初始化用于处理加密文档的 [`Document`](../) 类的新实例。

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| certOptions | CertificateEncryptionOptions | 证书加密选项。 |

### 另请参见

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

初始化用于处理加密文档的 [`Document`](../) 类的新实例。

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| certOptions | CertificateEncryptionOptions | 证书加密选项。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则，不会关闭。 |

### 另请参见

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 输入流对象，对应的 pdf 已受密码保护。 |
| password | String | 用户或所有者密码。 |
| customSecurityHandler | ICustomSecurityHandler | 自定义安全处理程序。 |

### 另请参见

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 包含 pdf 文档的流。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则不会关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

从 *input* 流初始化新的 Document 实例。

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 包含 pdf 文档的流。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则不会关闭。 |
| customSecurityHandler | ICustomSecurityHandler | 自定义安全处理程序。 |

### 另请参见

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

只需使用 *filename* 初始化 Document。等同于 `Document`。

```csharp
public Document(string filename)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | pdf 文档文件的名称。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

只需使用 *filename* 初始化 Document。等同于 `Document`。

```csharp
public Document(string filename, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | pdf 文档文件的名称。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则不会关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

初始化用于处理加密文档的 [`Document`](../) 类的新实例。

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| password | String | 用户或所有者密码。 |
| customSecurityHandler | ICustomSecurityHandler | 自定义安全处理程序。 |

### 另请参见

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

初始化用于处理加密文档的 [`Document`](../) 类的新实例。

```csharp
public Document(string filename, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| password | String | 用户或所有者密码。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

初始化用于处理加密文档的 [`Document`](../) 类的新实例。

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则，不会关闭。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

初始化用于处理加密文档的 [`Document`](../) 类的新实例。

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则，不会关闭。 |
| customSecurityHandler | ICustomSecurityHandler | 自定义安全处理程序。 |

### 另请参见

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
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

按版本初始化空文档。

```csharp
public Document(PdfVersion version)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 版本 | PdfVersion | PDF 版本。 |

### 另请参见

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

从文件中打开现有文档，并提供必要的转换选项以获取 pdf 文档。

```csharp
public Document(string filename, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | 用于转换为 pdf 文档的输入文件。 |
| options | LoadOptions | 表示将 *filename* 转换为 pdf 文档的属性。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

从流中打开现有文档，并提供必要的转换以获取 pdf 文档。

```csharp
public Document(Stream input, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | Stream | 用于转换为 pdf 文档的输入流。 |
| options | LoadOptions | 表示将 *input* 转换为 pdf 文档的属性。 |

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


