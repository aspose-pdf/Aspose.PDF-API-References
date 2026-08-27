---
title: "PdfFileEditor.Delete"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。删除输入文件中由编号数组指定的页面，并保存为新的 Pdf 文件"
type: docs
weight: 270
url: /zh/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件路径。 |
| pageNumber | Int32[] | 输入文件中页面的索引。 |
| outputFile | String | 输出文件路径。 |

### 返回值

如果操作成功则为 True。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| pageNumber | Int32[] | 输入文件中页面的索引。 |
| outputStream | Stream | 输出文件流。 |

### 返回值

成功返回 true，否则返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


