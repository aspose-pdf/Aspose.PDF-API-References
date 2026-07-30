---
title: "TextAbsorber.Visit"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TextAbsorber. Extrait le texte de la page spécifiée."
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
| page | Page | Objet de page de document PDF. |

## Exemples

L’exemple montre comment extraire du texte sur la première page du document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créer un objet TextAbsorber pour extraire du texte
TextAbsorber absorber = new TextAbsorber();

// accepter l'absorbeur pour toutes les pages du document
absorber.Visit(doc.Pages[1]);

// obtenir le texte extrait
string extractedText = absorber.Text;
```

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extrait le texte sur le XForm spécifié.

```csharp
public virtual void Visit(XForm form)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| formulaire | XForm | Objet de formulaire Pdf. |

## Exemples

L’exemple montre comment extraire du texte sur la première page du document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créer un objet TextAbsorber pour extraire du texte
TextAbsorber absorber = new TextAbsorber();

// accepter l'absorbeur pour toutes les pages du document
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// obtenir le texte extrait
string extractedText = absorber.Text;
```

### Voir aussi

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrait le texte du document spécifié

```csharp
public virtual void Visit(Document pdf)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdf | Document | Objet Pdf pocument. |

## Exemples

L'exemple montre comment extraire du texte d'un document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créer un objet TextAbsorber pour extraire du texte
TextAbsorber absorber = new TextAbsorber();

// accepter l'absorbeur pour toutes les pages du document
absorber.Visit(doc);

// obtenir le texte extrait
string extractedText = absorber.Text;
```

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


