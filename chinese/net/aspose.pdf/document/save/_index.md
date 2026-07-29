---
title: "Document.Save"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 方法。将文档保存到流并使用保存选项"
type: docs
weight: 850
url: /zh/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

使用保存选项将文档保存到流中。

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 文档将被存储的流。 |
| options | SaveOptions | 保存选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当将[`HtmlSaveOptions`](../../htmlsaveoptions/)传递给方法时出现 ArgumentException。将文档保存到 HTML 流不受支持。请使用保存到文件的方法。 |

### 另请参见

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

将文档存储到流中。

```csharp
public void Save(Stream output)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | Stream | 用于存放文档的流。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

将文档保存到指定文件中。

```csharp
public void Save(string outputFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | String | 文档将被存储的文件路径。 |

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

增量保存文档（即使用增量更新技术）。

```csharp
public void Save()
```

## 备注

为了增量保存文档，我们应该以写入模式打开文档文件。因此 Document 必须使用可写流进行初始化，如下面的代码片段所示： Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save();

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

使用保存选项保存文档。

```csharp
public void Save(SaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | SaveOptions | 保存选项。 |

### 另请参见

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

以新名称和文件格式保存文档。

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | String | 文档将被存储的文件路径。 |
| 格式 | SaveFormat | 格式选项。 |

### 另请参见

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

以新名称和文件格式保存文档。

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 文档将被存储的流。 |
| 格式 | SaveFormat | 格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当将[`HtmlSaveOptions`](../../htmlsaveoptions/)传递给方法时出现 ArgumentException。将文档保存到 HTML 流不受支持。请使用保存到文件的方法。 |

### 另请参见

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

以新名称并设置保存选项保存文档。

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | String | 文档将被存储的文件路径。 |
| options | SaveOptions | 保存选项。 |

### 另请参见

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


