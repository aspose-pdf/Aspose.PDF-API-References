---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: ComHelper 方法。从输入流初始化并返回新的 Document 实例
type: docs
weight: 30
url: /zh/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

从 *输入* 流初始化并返回新的 Document 实例。

```csharp
public Document OpenStream(Stream input)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 包含 pdf 文档的流。 |

### 返回值

Document 对象

### 另见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

从 *输入* 流初始化并返回新的 Document 实例。

```csharp
public Document OpenStream(Stream input, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 输入流对象，对应的 pdf 是受密码保护的。 |
| password | String | 用户或所有者密码。 |

### 返回值

Document 对象

### 另见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

从 *输入* 流初始化并返回新的 Document 实例。

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 包含 pdf 文档的流。 |
| isManagedStream | Boolean | 如果设置为 `true`，则在退出前关闭内部流；否则，不关闭。 |

### 返回值

Document 对象

### 另见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

从 *输入* 流初始化并返回新的 Document 实例。

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 包含 pdf 文档的流。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，则在退出前关闭内部流；否则，不关闭。 |

### 返回值

Document 对象

### 另见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

从流中打开并返回现有文档，提供必要的转换以获取 pdf 文档。

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | Stream | 输入流以转换为 pdf 文档。 |
| options | LoadOptions | 表示将 *输入* 转换为 pdf 文档的属性。 |

### 返回值

Document 对象

### 另见

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)