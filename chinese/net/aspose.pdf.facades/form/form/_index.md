---
title: "Form.Form"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 构造函数。无参数的 Form 构造器"
type: docs
weight: 10
url: /zh/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Form 的无参数构造函数。

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Form 的构造函数。

```csharp
public Form(string srcFileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcFileName | String | 源文件路径。 |

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

表单的构造函数。

```csharp
public Form(Stream srcStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | Stream | 源流。 |

## 示例

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

基于 *document* 初始化新的 [`Form`](../) 对象。

```csharp
public Form(Document document)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | Document | Pdf 文档。 |

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


