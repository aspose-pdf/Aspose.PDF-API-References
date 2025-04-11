---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Form-Konstruktor. Konstruktor von Form ohne Parameter
type: docs
weight: 10
url: /de/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Konstruktor von Form ohne Parameter.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Konstruktor von Form.

```csharp
public Form(string srcFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Quell-Dateipfad. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Konstruktor für das Formular.

```csharp
public Form(Stream srcStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcStream | Stream | Quell-Stream. |

## Beispiele

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Initialisiert ein neues [`Form`](../) Objekt auf Basis des *Dokuments*.

```csharp
public Form(Document document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Document | Pdf-Dokument. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)