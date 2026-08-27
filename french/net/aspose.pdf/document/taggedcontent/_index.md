---
title: "Document.TaggedContent"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Document propriété. Obtient l'accès au contenu TaggedPdf"
type: docs
weight: 540
url: /fr/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

Obtient l'accès au contenu TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Exemples

L'exemple montre comment utiliser le contenu balisé pour créer un nouveau document avec un en-tête, des paragraphes et des images.

```csharp
// Créer un nouveau document
Document document = new Document();

// Obtenir le contenu balisé
ITaggedContent taggedContent = document.TaggedContent;

// Définir la langue du document
taggedContent.SetLanguage("en-US");

// Définir le titre du document PDF
taggedContent.SetTitle("Example document");

// Création et ajout de la Section
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Créer l’en‑tête
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Créer un paragraphe
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Créer une illustration
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Enregistrer le document
document.Save("example.pdf");
```

### Voir aussi

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


