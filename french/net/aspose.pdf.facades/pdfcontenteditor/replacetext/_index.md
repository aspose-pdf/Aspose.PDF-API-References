---
title: "PdfContentEditor.ReplaceText"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Remplace le texte dans le fichier PDF à la page spécifiée. La police, la famille et la couleur de l'objet TextState peuvent être spécifiées pour le texte remplacé"
type: docs
weight: 450
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Remplace le texte dans le fichier PDF à la page spécifiée. L'objet [`TextState`](../../../aspose.pdf.text/textstate/) (famille de police, couleur) peut être spécifié pour le texte remplacé.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | La chaîne à remplacer. |
| thePage | Int32 | Numéro de page (0 signifie "toutes les pages"). |
| destString | String | La chaîne remplacée. |
| textState | TextState | État du texte (Couleur du texte, police, etc). |

### Valeur de retour

Renvoie true si le remplacement a été effectué.

## Exemples

L'exemple montre comment remplacer le texte sur la première page du document PDF et définir les propriétés de texte [`TextState`](../../../aspose.pdf.text/textstate/) pour le nouveau texte.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// Créer une police et la marquer pour qu’elle soit incorporée
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// créez un objet PdfContentEditor pour modifier le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// créez un objet textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// modifiez le texte avec la police spécifiée
editor.ReplaceText("hello world", 1, "hi world", textState);

// enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| destString | String | Remplacement de la chaîne. |

### Valeur de retour

Renvoie true si le remplacement a été effectué.

## Exemples

L'exemple montre comment remplacer le texte dans un document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créez un objet PdfContentEditor pour modifier le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// modifier le texte 
editor.ReplaceText("hello world", "hi world");

// enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Remplace le texte dans le fichier PDF sur la page spécifiée.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcString | String | La chaîne à remplacer. |
| thePage | Int32 | Numéro de page (0 pour toutes les pages) |
| destString | String | Remplacement de la chaîne. |

### Valeur de retour

Renvoie true si le remplacement a été effectué.

## Exemples

L'exemple montre comment remplacer le texte dans un document PDF à la page spécifiée.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créez un objet PdfContentEditor pour modifier le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// modifier le texte 
editor.ReplaceText("hello world", 1, "hi world");

// enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| destString | String | Remplacement de la chaîne |
| textState | TextState | État du texte (Couleur du texte, Police, etc.) |

### Valeur de retour

Renvoie true si le remplacement a été effectué.

## Exemples

L'exemple montre comment remplacer du texte et définir les propriétés de texte [`TextState`](../../../aspose.pdf.text/textstate/) pour le nouveau texte.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// Créer une police et la marquer pour qu’elle soit incorporée
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// créez un objet PdfContentEditor pour modifier le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// créez un objet textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// modifiez le texte avec la police spécifiée
editor.ReplaceText("hello world", "hi world", textState);

// enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| destString | String | Remplacement de la chaîne. |
| fontSize | Int32 | Taille de police. |

### Valeur de retour

Renvoie true si le remplacement a été effectué.

## Exemples

L'exemple montre comment remplacer du texte et définir la taille de police pour le nouveau texte.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// Créer une police et la marquer pour qu’elle soit incorporée
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// créez un objet PdfContentEditor pour modifier le texte
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// modifiez le texte avec la police spécifiée
editor.ReplaceText("hello world", "hi world", 14);

// enregistrez le document
doc.Save(outFile);
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


