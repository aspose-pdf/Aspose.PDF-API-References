---
title: "PdfFileEditor.Insert"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。将页面从另一个文件插入到 Pdf 文件的指定位置。"
type: docs
weight: 290
url: /zh/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

在指定位置将另一个文件中的页面插入到 Pdf 文件中。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| insertLocation | Int32 | 输入文件中的位置。 |
| portFile | String | 用于移植的 Pdf 文件。 |
| startPage | Int32 | portFile 中的起始位置。 |
| endPage | Int32 | portFile 中的结束位置。 |
| outputFile | String | 输出 Pdf 文件。 |

### 返回值

成功返回 true，否则返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

将另一个文件中的页面插入到输入的 Pdf 文件中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | Pdf 文件的输入流。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portStream | Stream | 用于页面的 Pdf 文件流。 |
| startPage | Int32 | 从哪一页开始。 |
| endPage | Int32 | 到哪一页结束。 |
| outputStream | Stream | 输出流。 |

### 返回值

成功返回 true，否则返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

将另一个文件中的页面插入到输入的 Pdf 文件中。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portFile | String | Pdf 文件中的页面。 |
| pageNumber | Int32[] | portFile 中的页码。 |
| outputFile | String | 输出 Pdf 文件。 |

### 返回值

成功返回 true，否则返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

将另一个文件中的页面插入到输入的 Pdf 文件中。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | Pdf 文件的输入流。 |
| insertLocation | Int32 | 输入文件中的插入位置。 |
| portStream | Stream | 用于页面的 Pdf 文件流。 |
| pageNumber | Int32[] | portFile 中的页码。 |
| outputStream | Stream | 输出流。 |

### 返回值

如果操作成功则为 True。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


