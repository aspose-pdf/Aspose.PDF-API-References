---
title: Form
second_title: Aspose.PDF per .NET API Reference
description: Costruttore di forme senza parametri.
type: docs
weight: 10
url: /it/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Costruttore di forme senza parametri.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## Form(string) {#constructor_8}

Costruttore di Form.

```csharp
public Form(string srcFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Percorso del file di origine. |

### Esempi

```csharp
Form form = new Form("PdfForm.pdf");
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Costruttore per form.

```csharp
public Form(Stream srcStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcStream | Stream | flusso di origine. |

### Esempi

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Guarda anche

* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Inizializza nuovo[`Form`](../../form) oggetto sulla base del*document* .

```csharp
public Form(Document document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Document | Documento PDF. |

### Guarda anche

* class [Document](../../../aspose.pdf/document)
* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->