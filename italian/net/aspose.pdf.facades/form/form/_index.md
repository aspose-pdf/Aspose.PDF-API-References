---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Costruttore di Form. Costruttore di Form senza parametri
type: docs
weight: 10
url: /it/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Costruttore di Form senza parametri.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Costruttore di Form.

```csharp
public Form(string srcFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Percorso del file sorgente. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Costruttore per il modulo.

```csharp
public Form(Stream srcStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcStream | Stream | stream sorgente. |

## Esempi

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Inizializza un nuovo oggetto [`Form`](../) sulla base del *documento*.

```csharp
public Form(Document document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Document | Documento Pdf. |

### Vedi Anche

* classe [Document](../../../aspose.pdf/document/)
* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)