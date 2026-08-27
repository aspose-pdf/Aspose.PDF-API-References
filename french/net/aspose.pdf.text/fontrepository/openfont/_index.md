---
title: "FontRepository.OpenFont"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FontRepository. Ouvre la police avec le flux de police spécifié"
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Ouvre la police avec le flux de police spécifié.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontStream | Stream | Flux de police. |
| fontType | FontTypes | Valeur du type de police. |

### Valeur de retour

Objet de police.

## Exemples

L'exemple montre comment ouvrir la police et remplacer la police du texte de la première page.

```csharp
// Ouvrir la police
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // Ouvrir le document
    Document doc = new Document(@"D:\Tests\input.pdf");

    // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // Accepter l'absorbeur pour la première page
    doc.Pages[1].Accept(absorber);

    // Modifier la police de la première occurrence de texte
    absorber.TextFragments[1].TextState.Font = font;

    // Enregistrer le document
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### Voir aussi

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Ouvre la police avec le chemin de fichier de police spécifié.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Chemin du fichier de police. |

### Valeur de retour

Objet de police.

## Exemples

L'exemple montre comment ouvrir la police et remplacer la police du texte de la première page.

```csharp
// Ouvrir la police
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Ouvre la police avec le chemin du fichier de police spécifié et le chemin du fichier de métriques.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Chemin du fichier de police. |
| metricsFilePath | String | Chemin du fichier de métriques de police. |

### Valeur de retour

Objet de police.

## Exemples

L'exemple montre comment ouvrir une police Type1 avec les métriques et remplacer la police du texte de la première page.

```csharp
// Ouvrir la police
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


