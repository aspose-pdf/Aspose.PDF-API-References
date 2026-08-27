---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。将输入文件制作成小册子并输出到输出文件。"
type: docs
weight: 430
url: /zh/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

从输入文件创建小册子并输出到输出文件。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 pdf 文件的路径和名称。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

从 InputStream 创建小册子并输出到 outputStream。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

从 inputFile 创建小册子并输出到 outputFile。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 pdf 文件的路径和名称。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |
| pageSize | PageSize | 输出 pdf 文件的页面尺寸。 |

### 返回值

如果操作成功则为 True。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

从输入流创建小册子并将结果保存到输出流。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 PDF 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| pageSize | PageSize | 输出 pdf 文件的页面尺寸。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

从 firstInputFile 创建自定义小册子并输出到 outputFile。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |
| leftPages | Int32[] | 小册子的左侧页面。 |
| rightPages | Int32[] | 小册子的右侧页面。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

从 firstInputStream 创建自定义小册子并输出到 outputStream。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 pdf 流。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

从 firstInputFile 创建自定义小册子并输出到 outputFile。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |
| pageSize | PageSize | 输出 pdf 文件的页面尺寸。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

从 firstInputStream 创建小册子并输出到 outputStream。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 pdf 流。 |
| pageSize | PageSize | 输出 pdf 文件的页面尺寸。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，但如果操作失败，TryMakeBooklet 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


