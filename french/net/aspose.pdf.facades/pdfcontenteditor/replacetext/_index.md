---
title: ReplaceText
second_title: Référence de l'API Aspose.PDF pour .NET
description: Remplace le texte du fichier PDF sur la page spécifiée.TextStateaspose.pdf.text/textstate objet famille de polices couleur peut être spécifié pour remplacer le texte.
type: docs
weight: 450
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Remplace le texte du fichier PDF sur la page spécifiée.[`TextState`](../../../aspose.pdf.text/textstate) objet (famille de polices, couleur) peut être spécifié pour remplacer le texte.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcString | String | Chaîne à remplacer. |
| thePage | Int32 | Numéro de page (0 signifie "toutes les pages"). |
| destString | String | La chaîne remplacée. |
| textState | TextState | État du texte (couleur du texte, police, etc.). |

### Return_Value

Renvoie true si un remplacement a été effectué.

### Exemples

L'exemple montre comment remplacer du texte sur la première page du document PDF et définir[`TextState`](../../../aspose.pdf.text/textstate) propriétés de texte pour le nouveau texte.

```csharp
// ouvre le document
Document doc = new Document(inFile);

// Crée une police et la marque pour qu'elle soit intégrée
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crée un objet PdfContentEditor pour éditer le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// crée un objet textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change le texte avec la police spécifiée
editor.ReplaceText("hello world", 1, "hi world", textState);

// enregistre le document
doc.Save(outFile);
```

### Voir également

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Remplace le texte dans le fichier PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcString | String | Chaîne à remplacer. |
| destString | String | Remplacement de chaîne. |

### Return_Value

Renvoie true si un remplacement a été effectué.

### Exemples

L'exemple montre comment remplacer du texte dans un document PDF.

```csharp
// ouvre le document
Document doc = new Document(inFile);

// crée un objet PdfContentEditor pour éditer le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change le texte 
editor.ReplaceText("hello world", "hi world");

// enregistre le document
doc.Save(outFile);
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Remplace le texte du fichier PDF sur la page spécifiée.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcString | String | La piqûre à remplacer. |
| thePage | Int32 | Numéro de page (0 pour toutes les pages) |
| destString | String | Remplacement de chaîne. |

### Return_Value

Renvoie true si un remplacement a été effectué.

### Exemples

L'exemple montre comment remplacer du texte dans un document PDF sur la page spécifiée.

```csharp
// ouvre le document
Document doc = new Document(inFile);

// crée un objet PdfContentEditor pour éditer le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change le texte 
editor.ReplaceText("hello world", 1, "hi world");

// enregistre le document
doc.Save(outFile);
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Remplace le texte dans le fichier PDF en utilisant le[`TextState`](../../../aspose.pdf.text/textstate) objet.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcString | String | Chaîne à remplacer |
| destString | String | Remplacement de chaîne |
| textState | TextState | État du texte (couleur du texte, police, etc.) |

### Return_Value

Renvoie true si un remplacement a été effectué.

### Exemples

L'exemple montre comment remplacer du texte et définir[`TextState`](../../../aspose.pdf.text/textstate) propriétés de texte pour le nouveau texte.

```csharp
// ouvre le document
Document doc = new Document(inFile);

// Crée une police et la marque pour qu'elle soit intégrée
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crée un objet PdfContentEditor pour éditer le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// crée un objet textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change le texte avec la police spécifiée
editor.ReplaceText("hello world", "hi world", textState);

// enregistre le document
doc.Save(outFile);
```

### Voir également

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Remplace le texte dans le fichier PDF et définit la taille de la police.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| srcString | String | Chaîne à remplacer. |
| destString | String | Remplacement de chaîne. |
| fontSize | Int32 | Taille de police. |

### Return_Value

Renvoie true si un remplacement a été effectué.

### Exemples

L'exemple montre comment remplacer du texte et définir la taille de la police pour le nouveau texte.

```csharp
// ouvre le document
Document doc = new Document(inFile);

// Crée une police et la marque pour qu'elle soit intégrée
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// crée un objet PdfContentEditor pour éditer le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change le texte avec la police spécifiée
editor.ReplaceText("hello world", "hi world", 14);

// enregistre le document
doc.Save(outFile);
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
