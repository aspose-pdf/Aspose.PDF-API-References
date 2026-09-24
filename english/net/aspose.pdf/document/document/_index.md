---
title: "Document.Document"
linktitle: "Document"
articleTitle: "Document"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document constructor. Initializes a new instance of the Document class."
type: docs
weight: 10
url: "/net/aspose.pdf/document/document/"
product_version: "26.9.0"
---
## Document() {#constructor}

Initializes empty document.

```csharp
public Document()
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream) {#constructor_1}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Stream with pdf document. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_2}

Just init Document using . The same as `#ctor`.

```csharp
public Document(string filename)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | The name of the pdf document file. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document([PdfVersion](../../../aspose.pdf/pdfversion/)) {#constructor_3}

Initializes empty document by version.

```csharp
public Document(PdfVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| version | PdfVersion | The PDF version. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Stream with pdf document. |
| isManagedStream | bool | if set to `true` inner stream is closed before exit; otherwise, is not. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Input stream object, corresponding pdf is password protected. |
| password | string | User or owner password. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)) {#constructor_6}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Input stream object, corresponding pdf is password protected. |
| certOptions | CertificateEncryptionOptions | The certificate encryption options. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)) {#constructor_7}

Initializes new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| certOptions | CertificateEncryptionOptions | The certificate encryption options. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_8}

Just init Document using . The same as `#ctor`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | The name of the pdf document file. |
| isManagedStream | bool | If set to `true` inner stream is closed before exit; otherwise, is not. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_9}

Initializes new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document(string filename, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| password | string | User or owner password. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, [LoadOptions](../../../aspose.pdf/loadoptions/)) {#constructor_10}

Opens an existing document from a file providing necessary converting options to get pdf document.

```csharp
public Document(string filename, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Input file to convert into pdf document. |
| options | LoadOptions | Represents properties for converting into pdf document. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, [LoadOptions](../../../aspose.pdf/loadoptions/)) {#constructor_11}

Opens an existing document from a stream providing necessary converting to get pdf document.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Input stream to convert into pdf document. |
| options | LoadOptions | Represents properties for converting into pdf document. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/), bool) {#constructor_12}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Stream with pdf document. |
| certOptions | CertificateEncryptionOptions | The certificate encryption options. |
| isManagedStream | bool | If set to `true` inner stream is closed before exit; otherwise, is not. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/), bool) {#constructor_13}

Initializes new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| certOptions | CertificateEncryptionOptions | The certificate encryption options. |
| isManagedStream | bool | if set to `true` inner stream is closed before exit; otherwise, is not. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)) {#constructor_14}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Input stream object, corresponding pdf is password protected. |
| password | string | User or owner password. |
| customSecurityHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_15}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Stream with pdf document. |
| password | string | User or owner password. |
| isManagedStream | bool | If set to `true` inner stream is closed before exit; otherwise, is not. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)) {#constructor_16}

Initializes new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| password | string | User or owner password. |
| customSecurityHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_17}

Initializes new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| password | string | User or owner password. |
| isManagedStream | bool | if set to `true` inner stream is closed before exit; otherwise, is not. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)) {#constructor_18}

Initialize new Document instance from the stream.

```csharp
public Document(Stream input, string password, bool isManagedStream, ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | Stream with pdf document. |
| password | string | User or owner password. |
| isManagedStream | bool | If set to `true` inner stream is closed before exit; otherwise, is not. |
| customSecurityHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)) {#constructor_19}

Initializes new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document(string filename, string password, bool isManagedStream, ICustomSecurityHandler customSecurityHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| password | string | User or owner password. |
| isManagedStream | bool | if set to `true` inner stream is closed before exit; otherwise, is not. |
| customSecurityHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

