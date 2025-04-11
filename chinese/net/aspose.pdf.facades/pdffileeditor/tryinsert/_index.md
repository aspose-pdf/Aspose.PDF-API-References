---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将其他文件的页面插入到输入的 Pdf 文件中
type: docs
weight: 420
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

将其他文件的页面插入到输入的 Pdf 文件中。

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入的 Pdf 文件。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portFile | 字符串 | 来自 Pdf 文件的页面。 |
| pageNumber | Int32[] | 在 portFile 中移植的页面编号。 |
| outputFile | 字符串 | 输出的 Pdf 文件。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

TryInsert 方法类似于 Insert 方法，不同之处在于如果操作失败，TryInsert 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

将其他文件的页面插入到输入的 Pdf 文件中。

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 输入的 Pdf 文件流。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portStream | 流 | 用于页面的 Pdf 文件流。 |
| pageNumber | Int32[] | 在 portFile 中移植的页面编号。 |
| outputStream | 流 | 输出流。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TryInsert 方法类似于 Insert 方法，不同之处在于如果操作失败，TryInsert 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

将文件内容插入到源文件中，并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源文件名。 |
| insertLocation | Int32 | 第二个文件将插入的页面编号。 |
| portFile | 字符串 | 将要插入的文件路径。 |
| pageNumber | Int32[] | 源文件中将要插入的页面编号数组。 |
| response | HttpResponse | 将存储结果的响应对象。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TryInsert 方法类似于 Insert 方法，不同之处在于如果操作失败，TryInsert 方法不会抛出异常。

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

将文档插入到其他文档中，并将结果存储到响应对象中。

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源文档的流 |
| insertLocation | Int32 | 其他文档将插入的位置。 |
| portStream | 流 | 要插入的文档。 |
| pageNumber | Int32[] | 在第二个文档中将要插入的页面编号数组。 |
| response | HttpResponse | 将存储结果的响应对象。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TryInsert 方法类似于 Insert 方法，不同之处在于如果操作失败，TryInsert 方法不会抛出异常。

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)