---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Document 方法。将文档存储到流中
type: docs
weight: 840
url: /zh/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

将文档存储到流中。

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | Stream | 文档将存储的流。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

将文档保存到指定文件中。

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | String | 文档将存储的文件路径。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

增量保存文档（即使用增量更新技术）。

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

## 备注

为了增量保存文档，我们应该打开文档文件以进行写入。因此，Document 必须使用可写流进行初始化，如下代码片段所示： Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // 进行一些更改并增量保存文档 doc.Save();

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

使用保存选项保存文档。

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | SaveOptions | 保存选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 另请参见

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

使用新名称和文件格式保存文档。

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | String | 文档将存储的文件路径。 |
| format | SaveFormat | 格式选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 另请参见

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

使用新名称和文件格式保存文档。

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 文档将存储的流。 |
| format | SaveFormat | 格式选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 [`HtmlSaveOptions`](../../htmlsaveoptions/) 被传递给方法时引发 ArgumentException。 不支持将文档保存到 html 流。 请使用保存到文件的方法。 |

### 另请参见

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

使用新名称设置其保存选项保存文档。

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFileName | String | 文档将存储的文件路径。 |
| options | SaveOptions | 保存选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 另请参见

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

使用保存选项将文档保存到流中。

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | Stream | 文档将存储的流。 |
| options | SaveOptions | 保存选项。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

异步任务。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 [`HtmlSaveOptions`](../../htmlsaveoptions/) 被传递给方法时引发 ArgumentException。 不支持将文档保存到 html 流。 请使用保存到文件的方法。 |

### 另请参见

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)