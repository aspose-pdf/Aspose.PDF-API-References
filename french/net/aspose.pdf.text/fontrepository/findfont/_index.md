---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: Méthode FontRepository. Recherche et renvoie la police avec le nom de police spécifié
type: docs
weight: 40
url: /fr/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Recherche et renvoie la police avec le nom de police spécifié.

```csharp
public static Font FindFont(string fontName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de la police. |

### Valeur de retour

Objet Font.

## Exemples

L'exemple démontre comment trouver une police et remplacer la police du texte de la première page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Recherche et renvoie la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de la police. |
| ignoreCase | Boolean | sensibilité à la casse |

### Valeur de retour

Objet Font.

## Exemples

L'exemple démontre comment trouver une police et remplacer la police du texte de la première page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Recherche et renvoie la police avec le nom de police spécifié et le style de police.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Nom de la famille de polices. |
| stl | FontStyles | Valeur du style de police. |

### Valeur de retour

Objet Font correspondant aux paramètres de la demande de recherche.

## Exemples

L'exemple démontre comment trouver une police et remplacer la police du texte de la première page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Recherche et renvoie la police avec le nom de police spécifié et le style de police en ignorant ou en respectant la sensibilité à la casse.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Nom de la famille de polices. |
| stl | FontStyles | Valeur du style de police. |
| ignoreCase | Boolean | sensibilité à la casse |

### Valeur de retour

Objet Font correspondant aux paramètres de la demande de recherche.

## Exemples

L'exemple démontre comment trouver une police et remplacer la police du texte de la première page.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)