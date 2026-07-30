---
title: "FontRepository.FindFont"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FontRepository. Recherche et renvoie la police avec le nom de police spécifié"
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
| fontName | String | Nom de police. |

### Valeur de retour

Objet de police.

## Exemples

L'exemple montre comment trouver une police et remplacer la police du texte de la première Page.

```csharp
// Trouver la police
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, bool) {#findfont_3}

Recherche et renvoie la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de police. |
| ignoreCase | Boolean | sensibilité à la casse |

### Valeur de retour

Objet de police.

## Exemples

L'exemple montre comment trouver une police et remplacer la police du texte de la première Page.

```csharp
// Trouver la police
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, FontStyles) {#findfont_1}

Recherche et renvoie la police avec le nom de police et le style de police spécifiés.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Nom de famille de police. |
| stl | FontStyles | Valeur du style de police. |

### Valeur de retour

Objet de police correspondant aux paramètres de la requête de recherche.

## Exemples

L'exemple montre comment trouver une police et remplacer la police du texte de la première Page.

```csharp
// Trouver la police
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
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
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Recherche et renvoie la police avec le nom de police et le style de police spécifiés en ignorant ou en respectant la sensibilité à la casse.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Nom de famille de police. |
| stl | FontStyles | Valeur du style de police. |
| ignoreCase | Boolean | sensibilité à la casse |

### Valeur de retour

Objet de police correspondant aux paramètres de la requête de recherche.

## Exemples

L'exemple montre comment trouver une police et remplacer la police du texte de la première Page.

```csharp
// Trouver la police
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
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
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


