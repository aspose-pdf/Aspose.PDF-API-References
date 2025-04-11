---
title: TextAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Méthode TextAbsorber. Extrait le texte de la page spécifiée
type: docs
weight: 70
url: /fr/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrait le texte de la page spécifiée

```csharp
public virtual void Visit(Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | Objet de page de document Pdf. |

## Exemples

L'exemple démontre comment extraire le texte de la première page du document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1]);

// get the extracted text
string extractedText = absorber.Text;
```

### Voir aussi

* classe [Page](../../../aspose.pdf/page/)
* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extrait le texte de l'XForm spécifié.

```csharp
public virtual void Visit(XForm form)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| form | XForm | Objet de formulaire Pdf. |

## Exemples

L'exemple démontre comment extraire le texte de la première page du document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// get the extracted text
string extractedText = absorber.Text;
```

### Voir aussi

* classe [XForm](../../../aspose.pdf/xform/)
* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrait le texte du document spécifié

```csharp
public virtual void Visit(Document pdf)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdf | Document | Objet de document Pdf. |

## Exemples

L'exemple démontre comment extraire le texte du document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
absorber.Visit(doc);

// get the extracted text
string extractedText = absorber.Text;
```

### Voir aussi

* classe [Document](../../../aspose.pdf/document/)
* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)