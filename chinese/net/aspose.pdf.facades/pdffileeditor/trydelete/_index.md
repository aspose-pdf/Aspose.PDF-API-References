---
title: "PdfFileEditor.TryDelete"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。删除输入文件中由编号数组指定的页面，并保存为新的 Pdf 文件"
type: docs
weight: 400
url: /zh/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件路径。 |
| pageNumber | Int32[] | 输入文件中页面的索引。 |
| outputFile | String | 输出文件路径。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryDelete 方法类似于 Delete 方法，但如果操作失败，TryDelete 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| pageNumber | Int32[] | 输入文件中页面的索引。 |
| outputStream | Stream | 输出文件流。 |

### 返回值

成功返回 true，否则返回 false。

## 备注

TryDelete 方法类似于 Delete 方法，但如果操作失败，TryDelete 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


