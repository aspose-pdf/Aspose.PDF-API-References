---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: 表单构造函数。无参数的表单构造函数
type: docs
weight: 10
url: /zh/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

无参数的表单构造函数。

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### 另请参见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

表单的构造函数。

```csharp
public Form(string srcFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | 字符串 | 源文件路径。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
```

### 另请参见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

表单的构造函数。

```csharp
public Form(Stream srcStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | 流 | 源流。 |

## 示例

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### 另请参见

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

基于*文档*初始化新的 [`Form`](../) 对象。

```csharp
public Form(Document document)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 文档 | Pdf 文档。 |

### 另请参见

* 类 [Document](../../../aspose.pdf/document/)
* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)