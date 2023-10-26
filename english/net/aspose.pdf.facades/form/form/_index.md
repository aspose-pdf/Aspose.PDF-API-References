---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Form constructor. Construtcor of Form without parameters
type: docs
weight: 10
url: /net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Construtcor of Form without parameters.

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

## Form(string) {#constructor_8}

Constructor of Form.

```csharp
public Form(string srcFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | Source file path. |

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

Constructor for form.

```csharp
public Form(Stream srcStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | source stream. |

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

Initializes new [`Form`](../) object on base of the *document*.

```csharp
public Form(Document document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | Pdf document. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


