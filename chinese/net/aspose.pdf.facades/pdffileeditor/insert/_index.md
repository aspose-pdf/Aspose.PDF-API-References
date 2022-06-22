---
title: Insert
second_title: Aspose.PDF for .NET API 参考
description: 将其他文件中的页面插入到 Pdf 文件中的某个位置
type: docs
weight: 320
url: /zh/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

将其他文件中的页面插入到 Pdf 文件中的某个位置。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| insertLocation | Int32 | 在输入文件中的位置。 |
| portFile | String | 移植的 Pdf 文件。 |
| startPage | Int32 | portFile 中的起始位置。 |
| endPage | Int32 | portFile 中的结束位置。 |
| outputFile | String | 输出 Pdf 文件。 |

### 返回值

成功则为真，否则为假。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

将其他文件中的页面插入到输入 Pdf 文件中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | Pdf 文件的输入流。 |
| insertLocation | Int32 | 在输入文件中插入位置。 |
| portStream | Stream | 页面的 Pdf 文件流。 |
| startPage | Int32 | 从哪个页面开始。 |
| endPage | Int32 | 到哪一页结束。 |
| outputStream | Stream | 输出流。 |

### 返回值

成功则为真，否则为假。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

将其他文件中的页面插入到输入 Pdf 文件中。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| insertLocation | Int32 | 在输入文件中插入位置。 |
| portFile | String | Pdf 文件中的页面。 |
| pageNumber | Int32[] | portFile 中移植的页码。 |
| outputFile | String | 输出 Pdf 文件。 |

### 返回值

成功则为真，否则为假。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

将其他文件中的页面插入到输入 Pdf 文件中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | Pdf 文件的输入流。 |
| insertLocation | Int32 | 在输入文件中插入位置。 |
| portStream | Stream | 页面的 Pdf 文件流。 |
| pageNumber | Int32[] | portFile 中移植的页码。 |
| outputStream | Stream | 输出流。 |

### 返回值

如果操作成功则为真。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

将文件内容插入源文件并将结果存储到 HttpResponse 对象中。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件名。 |
| insertLocation | Int32 | 将插入第二个文件的页码。 |
| portFile | String | 将被插入的文件的路径。 |
| pageNumber | Int32[] | 将插入源文件中的页码数组。 |
| response | HttpResponse | 将存储结果的响应对象。 |

### 返回值

true 插入成功。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

将文档插入其他文档并将结果存储到响应对象中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 带有源文档的流 |
| insertLocation | Int32 | 其他位置文档将被插入。 |
| portStream | Stream | 要插入的文档。 |
| pageNumber | Int32[] | 将插入的第二个文档中的页码数组。 |
| response | HttpResponse | 将存储结果的响应对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
