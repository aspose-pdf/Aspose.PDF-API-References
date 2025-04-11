---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: Méthode FontRepository. Ouvre une police avec le flux de police spécifié
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Ouvre une police avec le flux de police spécifié.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontStream | Stream | Flux de police. |
| fontType | FontTypes | Valeur du type de police. |

### Valeur de retour

Objet Font.

## Exemples

L'exemple démontre comment ouvrir une police et remplacer la police du texte de la première page.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### Voir aussi

* classe [Font](../../font/)
* énum [FontTypes](../../fonttypes/)
* classe [FontRepository](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Ouvre une police avec le chemin de fichier de police spécifié.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Chemin du fichier de police. |

### Valeur de retour

Objet Font.

## Exemples

L'exemple démontre comment ouvrir une police et remplacer la police du texte de la première page.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

* classe [Font](../../font/)
* classe [FontRepository](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Ouvre une police avec le chemin de fichier de police spécifié et le chemin de fichier de métriques.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Chemin du fichier de police. |
| metricsFilePath | String | Chemin du fichier de métriques de police. |

### Valeur de retour

Objet Font.

## Exemples

L'exemple démontre comment ouvrir une police Type1 avec des métriques et remplacer la police du texte de la première page.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

* classe [Font](../../font/)
* classe [FontRepository](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)