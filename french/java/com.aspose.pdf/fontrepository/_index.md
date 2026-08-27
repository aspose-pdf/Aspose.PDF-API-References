---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Effectue une recherche de police. Recherche les polices installées sur le système et les polices PDF standard. Fournit également la fonctionnalité d'ouvrir des polices personnalisées. </p> <hr> <pre> L'exemple montre."
type: docs
weight: 1690
url: /fr/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Effectue une recherche de police. Recherche les polices installées sur le système et les polices PDF standard. Fournit également la fonctionnalité d'ouvrir des polices personnalisées. </p> <hr> <pre> L'exemple montre comment trouver une police et remplacer la police du texte de la première page. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Ajoutez un autre chemin aux polices. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Ajoute une police système avec la police spécifiée. </p> <hr> <pre> L'exemple montre comment ajouter une police système. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Recherche et renvoie la police avec le nom de police spécifié. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Recherche et renvoie la police avec le nom de police spécifié, en ignorant ou en respectant la sensibilité à la casse. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Recherche et renvoie la police avec le nom de police spécifié et le style de police. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Recherche et renvoie la police avec le nom de police spécifié et le style de police, en ignorant ou en respectant la sensibilité à la casse. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Copie de la liste avec les répertoires de polices réels. |
| [getSources](#getSources--) | Obtient la collection des sources de polices. |
| [getSubstitutions](#getSubstitutions--) | Obtient la collection des stratégies de substitution de polices. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Les polices non trouvées seront remplacées par la police standard. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Retourne l'état de la configuration du stockage des sources de polices. <br> Si vrai, utilise ThreadStatic et chaque thread possède ses propres sources de polices. <br> Si faux, utilise une configuration statique globale pour tous les threads. </p> <hr> La valeur par défaut est True. |
| [loadFonts](#loadFonts--) | Charge les polices installées sur le système et les polices PDF standard. Cette méthode a été conçue pour accélérer le processus de chargement des polices. Par défaut, les polices sont chargées lors de la première requête pour n'importe quelle police. L'utilisation de cette méthode charge les polices système et les polices PDF standard immédiatement avant l'ouverture de tout document PDF. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Ouvre la police avec le flux de police spécifié. </p> <hr> <pre> L'exemple montre comment ouvrir une police et remplacer la police du texte de la première page. // Ouvrir la police InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Ouvre la police avec le chemin de fichier de police spécifié. </p> <hr> <pre> L'exemple montre comment ouvrir une police et remplacer la police du texte de la première page. // Ouvrir la police Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Ouvre la police avec le chemin de fichier de police et le chemin du fichier de métriques spécifiés. </p> <hr> <pre> L'exemple montre comment ouvrir une police Type1 avec métriques et remplacer la police du texte de la première page. // Ouvrir la police Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Recharge toutes les polices spécifiées par la propriété {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Restaure la liste des répertoires de polices standard par défaut. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Définit la liste utilisateur avec les chemins de police |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Définissez TRUE si vous devez remplacer les polices non trouvées par la police par défaut. La valeur par défaut est false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Option pour configurer le stockage des sources de polices. Si true, utilise ThreadStatic et chaque thread possède ses propres Font Sources. Si false, utilise une configuration statique globale pour tous les threads. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Ajoutez un autre chemin aux polices.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Ajoute une police système avec la police spécifiée. </p> <hr> <pre> L'exemple montre comment ajouter une police système. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Recherche et renvoie la police avec le nom de police spécifié. </p> <hr> <pre> L'exemple montre comment trouver une police et remplacer la police du texte de la première page. // Trouver la police Font font = FontRepository.findFont("Arial"); // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Recherche et renvoie la police avec le nom de police spécifié en ignorant ou en respectant la sensibilité à la casse. </p> <hr> <pre> L'exemple montre comment trouver une police et remplacer la police du texte de la première page. // Trouver la police Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Recherche et renvoie la police avec le nom de police et le style de police spécifiés. </p> <hr> <pre> L'exemple montre comment trouver une police et remplacer la police du texte de la première page. // Trouver la police Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Recherche et renvoie la police avec le nom de police et le style de police spécifiés en ignorant ou en respectant la sensibilité à la casse. </p> <hr> <pre> L'exemple montre comment trouver une police et remplacer la police du texte de la première page. // Trouver la police Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Copie de la liste avec les répertoires de polices réels.

**Returns:**
liste de String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Obtient la collection des sources de polices.

**Returns:**
objet FontSourceCollection

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Obtient la collection des stratégies de substitution de polices.

**Returns:**
objet FontSubstitutionCollection

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Les polices non trouvées seront remplacées par la police standard.

**Returns:**
valeur booléenne

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Retourne l'état de la configuration du stockage des sources de polices. <br> Si vrai, utilise ThreadStatic et chaque thread possède ses propres sources de polices. <br> Si faux, utilise une configuration statique globale pour tous les threads. </p> <hr> La valeur par défaut est True.

**Returns:**
valeur booléenne

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Charge les polices installées sur le système et les polices PDF standard. Cette méthode a été conçue pour accélérer le processus de chargement des polices. Par défaut, les polices sont chargées lors de la première requête pour n'importe quelle police. L'utilisation de cette méthode charge les polices système et les polices PDF standard immédiatement avant l'ouverture de tout document PDF.

### openFont {#openFont-java.io.InputStream-int-}
<p> Ouvre la police avec le flux de police spécifié. </p> <hr> <pre> L'exemple montre comment ouvrir une police et remplacer la police du texte de la première page. // Ouvrir la police InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Ouvre la police avec le chemin de fichier de police spécifié. </p> <hr> <pre> L'exemple montre comment ouvrir une police et remplacer la police du texte de la première page. // Ouvrir la police Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Ouvre la police avec le chemin de fichier de police spécifié et le chemin de fichier de métriques. </p> <hr> <pre> L'exemple montre comment ouvrir une police Type1 avec des métriques et remplacer la police du texte de la première page. // Ouvrir la police Font font = FontRepository.openFont(\"courier.pfb\", \"courier.afm\"); // Ouvrir le document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Enregistrer le document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Recharge toutes les polices spécifiées par la propriété {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Restaure la liste des répertoires de polices standard par défaut.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Définit la liste utilisateur avec les chemins de police

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Définissez TRUE si vous devez remplacer les polices non trouvées par la police par défaut. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Option pour configurer le stockage des sources de polices. Si true, utilise ThreadStatic et chaque thread possède ses propres Font Sources. Si false, utilise une configuration statique globale pour tous les threads.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isTheadLocal |  | valeur booléenne |
