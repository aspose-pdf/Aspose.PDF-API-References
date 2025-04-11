---
title: Form.Form
second_title: Aspose.PDF for .NET API Reference
description: Constructeur de Form. Constructeur de Form sans paramètres
type: docs
weight: 10
url: /fr/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

Constructeur de Form sans paramètres.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Constructeur de Form.

```csharp
public Form(string srcFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcFileName | String | Chemin du fichier source. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

Constructeur pour le formulaire.

```csharp
public Form(Stream srcStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcStream | Stream | flux source. |

## Exemples

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

Initialise un nouvel objet [`Form`](../) basé sur le *document*.

```csharp
public Form(Document document)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Document | Document Pdf. |

### Voir aussi

* classe [Document](../../../aspose.pdf/document/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)