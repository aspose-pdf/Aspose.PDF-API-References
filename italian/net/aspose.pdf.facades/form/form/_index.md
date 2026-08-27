---
title: "Form.Form"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Costruttore Form. Costruttore di Form senza parametri"
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

### Vedi anche

* class [Form](../)
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

### Vedi anche

* class [Form](../)
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
| srcStream | Stream | stream di origine. |

## Esempi

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Inizializza un nuovo oggetto [`Form`](../) basato sul *document*.

```csharp
public Form(Document document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Document | Documento Pdf. |

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


