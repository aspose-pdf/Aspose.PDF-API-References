---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。根据指定的页码数组从输入文件中删除页面，并保存为新的 Pdf 文件
type: docs
weight: 270
url: /zh/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

根据指定的页码数组从输入文件中删除页面，并保存为新的 Pdf 文件。

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入文件路径。 |
| pageNumber | Int32[] | 输入文件中的页面索引。 |
| outputFile | 字符串 | 输出文件路径。 |

### 返回值

如果操作成功，则为真。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

根据指定的页码数组从输入文件中删除页面，并保存为新的 Pdf 文件。

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 输入文件流。 |
| pageNumber | Int32[] | 输入文件中的页面索引。 |
| outputStream | 流 | 输出文件流。 |

### 返回值

成功时为真，失败时为假。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)