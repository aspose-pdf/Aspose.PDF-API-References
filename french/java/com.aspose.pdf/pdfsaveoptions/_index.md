---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format Pdf"
type: docs
weight: 3790
url: /fr/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Options d'enregistrement pour l'exportation au format Pdf

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Nom de police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur. Lorsque le document PDF enregistré contient des polices qui ne sont pas disponibles dans le document lui‑même et sur l'appareil, l'API remplace ces polices par la police par défaut (si une police avec {@code DefaultFontName} est trouvée sur l'appareil). |
| [getTempPath](#getTempPath--) | Chemin des fichiers temporaires. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Nom de police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur. Lorsque le document PDF enregistré contient des polices qui ne sont pas disponibles dans le document lui‑même et sur l'appareil, l'API remplace ces polices par la police par défaut (si une police avec {@code DefaultFontName} est trouvée sur l'appareil). |
| [setTempPath](#setTempPath-java.lang.String-) | Chemin des fichiers temporaires. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Constructeur

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Nom de police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur. Lorsque le document PDF enregistré contient des polices qui ne sont pas disponibles dans le document lui‑même et sur l'appareil, l'API remplace ces polices par la police par défaut (si une police avec {@code DefaultFontName} est trouvée sur l'appareil).

**Returns:**
valeur String

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Chemin des fichiers temporaires.

**Returns:**
valeur String

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Nom de police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur. Lorsque le document PDF enregistré contient des polices qui ne sont pas disponibles dans le document lui‑même et sur l'appareil, l'API remplace ces polices par la police par défaut (si une police avec {@code DefaultFontName} est trouvée sur l'appareil).

### setTempPath {#setTempPath-java.lang.String-}
Chemin des fichiers temporaires.
