---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Конструктор формы. Конструктор формы без параметров
type: docs
weight: 10
url: /ru/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Конструктор формы без параметров.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Конструктор формы.

```csharp
public Form(string srcFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | Путь к исходному файлу. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Конструктор для формы.

```csharp
public Form(Stream srcStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | исходный поток. |

## Examples

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Инициализирует новый [`Form`](../) объект на основе *документа*.

```csharp
public Form(Document document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Pdf документ. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)