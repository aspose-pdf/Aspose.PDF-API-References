---
title: "Form.Form"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form‑konstruktor. Konstruktor för Form utan parametrar"
type: docs
weight: 10
url: /sv/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Konstruktor för Form utan parametrar.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Konstruktor för Form.

```csharp
public Form(string srcFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Sökväg till källfil. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Konstruktor för formulär.

```csharp
public Form(Stream srcStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | Stream | källström. |

## Exempel

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Initierar ett nytt [`Form`](../)‑objekt baserat på *dokumentet*.

```csharp
public Form(Document document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Dokument | Pdf‑dokument. |

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


