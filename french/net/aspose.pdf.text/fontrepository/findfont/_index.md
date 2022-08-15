---
title: FindFont
second_title: Référence de l'API Aspose.PDF pour .NET
description: Recherche et renvoie la police avec le nom de police spécifié.
type: docs
weight: 40
url: /fr/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Recherche et renvoie la police avec le nom de police spécifié.

```csharp
public static Font FindFont(string fontName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Nom de la police. |

### Return_Value

Objet de police.

### Exemples

L'exemple montre comment trouver la police et remplacer la police du texte de la première page.

```csharp
// Recherche de police
Font font = FontRepository.FindFont("Arial");

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Change la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir également

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* espace de noms [Aspose.Pdf.Text](../../fontrepository)
* Assemblée [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Recherche et renvoie la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontName | String | Nom de la police. |
| ignoreCase | Boolean | sensibilité à la casse |

### Return_Value

Objet de police.

### Exemples

L'exemple montre comment trouver la police et remplacer la police du texte de la première page.

```csharp
// Recherche de police
Font font = FontRepository.FindFont("Arial");

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Change la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir également

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* espace de noms [Aspose.Pdf.Text](../../fontrepository)
* Assemblée [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Recherche et renvoie la police avec le nom et le style de police spécifiés.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontFamilyName | String | Nom de famille de la police. |
| stl | FontStyles | Valeur du style de police. |

### Return_Value

Objet de police correspondant aux paramètres de la requête de recherche.

### Exemples

L'exemple montre comment trouver la police et remplacer la police du texte de la première page.

```csharp
// Recherche de police
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Change la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir également

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* espace de noms [Aspose.Pdf.Text](../../fontrepository)
* Assemblée [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Recherche et renvoie la police avec le nom et le style de police spécifiés en ignorant ou en respectant la sensibilité à la casse.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fontFamilyName | String | Nom de famille de la police. |
| stl | FontStyles | Valeur du style de police. |
| ignoreCase | Boolean | sensibilité à la casse |

### Return_Value

Objet de police correspondant aux paramètres de la requête de recherche.

### Exemples

L'exemple montre comment trouver la police et remplacer la police du texte de la première page.

```csharp
// Recherche de police
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Change la police de la première occurrence de texte
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir également

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* espace de noms [Aspose.Pdf.Text](../../fontrepository)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
