---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Remplace le texte dans le fichier PDF à la page spécifiée. La couleur de la famille de polices de l'objet TextState peut être spécifiée pour le texte remplacé
type: docs
weight: 450
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Remplace le texte dans le fichier PDF à la page spécifiée. L'objet [`TextState`](../../../aspose.pdf.text/textstate/) (famille de polices, couleur) peut être spécifié pour le texte remplacé.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | La chaîne à remplacer. |
| thePage | Int32 | Numéro de page (0 signifie "toutes les pages"). |
| destString | String | La chaîne remplacée. |
| textState | TextState | État du texte (Couleur du texte, Police, etc.). |

### Valeur de retour

Retourne vrai si le remplacement a été effectué.

## Exemples

L'exemple démontre comment remplacer le texte sur la première page du document PDF et définir les propriétés de texte [`TextState`](../../../aspose.pdf.text/textstate/) pour le nouveau texte.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### Voir aussi

* classe [TextState](../../../aspose.pdf.text/textstate/)
* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Remplace le texte dans le fichier PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | La chaîne à remplacer. |
| destString | String | Chaîne de remplacement. |

### Valeur de retour

Retourne vrai si le remplacement a été effectué.

## Exemples

L'exemple démontre comment remplacer le texte dans le document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Remplace le texte dans le fichier PDF à la page spécifiée.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | La chaîne à remplacer. |
| thePage | Int32 | Numéro de page (0 pour toutes les pages) |
| destString | String | Chaîne de remplacement. |

### Valeur de retour

Retourne vrai si le remplacement a été effectué.

## Exemples

L'exemple démontre comment remplacer le texte dans le document PDF à la page spécifiée.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Remplace le texte dans le fichier PDF en utilisant l'objet [`TextState`](../../../aspose.pdf.text/textstate/) spécifié.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | Chaîne à remplacer |
| destString | String | Chaîne de remplacement |
| textState | TextState | État du texte (Couleur du texte, Police, etc.) |

### Valeur de retour

Retourne vrai si le remplacement a été effectué.

## Exemples

L'exemple démontre comment remplacer le texte et définir les propriétés de texte [`TextState`](../../../aspose.pdf.text/textstate/) pour le nouveau texte.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### Voir aussi

* classe [TextState](../../../aspose.pdf.text/textstate/)
* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Remplace le texte dans le fichier PDF et définit la taille de la police.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | Chaîne à remplacer. |
| destString | String | Chaîne de remplacement. |
| fontSize | Int32 | Taille de la police. |

### Valeur de retour

Retourne vrai si le remplacement a été effectué.

## Exemples

L'exemple démontre comment remplacer le texte et définir la taille de la police pour le nouveau texte.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)