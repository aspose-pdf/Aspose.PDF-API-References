---
title: "ComHelper.OpenFile"
linktitle: "OpenFile"
articleTitle: "OpenFile"
second_title: "Aspose.PDF for .NET API Reference"
description: "ComHelper method. Just create and return Document using filename. The same as Document."
type: docs
weight: 70
url: "/net/aspose.pdf/comhelper/openfile/"
product_version: "26.9.0"
---
## OpenFile(string) {#openfile}

Just create and return Document using *filename*. The same as `#ctor`.

```csharp
public Document OpenFile(string filename)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | The name of the pdf document file. |

### Return Value

[Document](../../../aspose.pdf/document/)

Document object

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_1}

Initialize and return new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document OpenFile(string filename, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| password | string | User or owner password. |

### Return Value

[Document](../../../aspose.pdf/document/)

Document object

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_2}

Initialize new instance of the [`Document`](../../../aspose.pdf/document/) class for working with encrypted document.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Document file name. |
| password | string | User or owner password. |
| isManagedStream | bool | if set to `true` inner stream is closed before exit; otherwise, is not. |

### Return Value

[Document](../../../aspose.pdf/document/)

Document object

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, [LoadOptions](../../../aspose.pdf/loadoptions/)) {#openfile_3}

Open an existing document from a file providing necessary converting oprions to get pdf document.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filename | string | Input file to convert into pdf document. |
| options | LoadOptions | Represents properties for converting *filename* into pdf document. |

### Return Value

[Document](../../../aspose.pdf/document/)

Document object

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

