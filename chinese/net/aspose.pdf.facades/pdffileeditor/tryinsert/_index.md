---
title: "PdfFileEditor.TryInsert"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。将页面从另一个文件插入到输入的 Pdf 文件中"
type: docs
weight: 420
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

将另一个文件中的页面插入到输入的 Pdf 文件中。

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

## 备注

TryInsert 方法类似于 Insert 方法，但如果操作失败，TryInsert 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

将另一个文件中的页面插入到输入的 Pdf 文件中。

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

如果操作成功完成则为 true；否则为 false。

## 备注

TryInsert 方法类似于 Insert 方法，但如果操作失败，TryInsert 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


