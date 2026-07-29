---
title: "ComHelper.OpenFile"
second_title: "Aspose.PDF for .NET API 参考"
description: "ComHelper 方法。仅使用文件名创建并返回 Document。与 Document 相同。"
type: docs
weight: 20
url: /zh/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

仅使用 *filename* 创建并返回 Document。与 [`Document`](../../document/document/) 相同。

```csharp
public Document OpenFile(string filename)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | pdf 文档文件的名称。 |

### 返回值

Document 对象

### 另请参见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

初始化并返回用于处理加密文档的 [`Document`](../../document/) 类的新实例。

```csharp
public Document OpenFile(string filename, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| password | String | 用户或所有者密码。 |

### 返回值

Document 对象

### 另请参见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

初始化用于处理加密文档的 [`Document`](../../document/) 类的新实例。

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | Document 文件名。 |
| password | String | 用户或所有者密码。 |
| isManagedStream | Boolean | 如果设置为 `true`，内部流将在退出前关闭；否则，不会关闭。 |

### 返回值

Document 对象

### 另请参见

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

从文件打开现有 Document，提供必要的转换选项以获取 pdf 文档。

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | String | 用于转换为 pdf 文档的输入文件。 |
| options | LoadOptions | 表示将 *filename* 转换为 pdf 文档的属性。 |

### 返回值

Document 对象

### 另请参见

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


