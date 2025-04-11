---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将其他文件的页面插入到 Pdf 文件中的指定位置
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

将其他文件的页面插入到 Pdf 文件中的指定位置。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入的 Pdf 文件。 |
| insertLocation | Int32 | 输入文件中的位置。 |
| portFile | 字符串 | 需要移植的 Pdf 文件。 |
| startPage | Int32 | portFile 中的起始位置。 |
| endPage | Int32 | portFile 中的结束位置。 |
| outputFile | 字符串 | 输出的 Pdf 文件。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

将其他文件的页面插入到输入的 Pdf 文件中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 输入的 Pdf 文件流。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portStream | 流 | 用于页面的 Pdf 文件流。 |
| startPage | Int32 | 从哪一页开始。 |
| endPage | Int32 | 到哪一页结束。 |
| outputStream | 流 | 输出流。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

将其他文件的页面插入到输入的 Pdf 文件中。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入的 Pdf 文件。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portFile | 字符串 | 来自 Pdf 文件的页面。 |
| pageNumber | Int32[] | portFile 中移植的页面编号。 |
| outputFile | 字符串 | 输出的 Pdf 文件。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

将其他文件的页面插入到输入的 Pdf 文件中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 输入的 Pdf 文件流。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portStream | 流 | 用于页面的 Pdf 文件流。 |
| pageNumber | Int32[] | portFile 中移植的页面编号。 |
| outputStream | 流 | 输出流。 |

### 返回值

操作成功时返回 true。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)