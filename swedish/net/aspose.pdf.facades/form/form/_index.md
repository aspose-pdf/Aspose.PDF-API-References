---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Form-konstruktör. Konstruktör av Form utan parametrar
type: docs
weight: 10
url: /sv/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Konstruktör av Form utan parametrar.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Konstruktör av Form.

```csharp
public Form(string srcFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | Sträng | Sökväg till källfil. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Konstruktör för form.

```csharp
public Form(Stream srcStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | Ström | källström. |

## Exempel

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Initierar ett nytt [`Form`](../) objekt baserat på *dokumentet*.

```csharp
public Form(Document document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Dokument | Pdf-dokument. |

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)