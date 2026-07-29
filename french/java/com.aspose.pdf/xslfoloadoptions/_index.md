---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de chargement/importation d'un fichier XSL-FO dans un document PDF."
type: docs
weight: 5780
url: /fr/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Représente les options de chargement/importation d'un fichier XSL-FO dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Crée l'objet {@code XslFoLoadOptions} sans données xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Crée l'objet {@code XslFoLoadOptions} sans données xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Crée l'objet {@code XslFoLoadOptions} sans données xsl. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBasePath](#getBasePath--) | Le chemin/base URL à partir duquel sont recherchés les chemins relatifs vers les ressources externes (le cas échéant) référencées dans le fichier SVG chargé. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération répertorie les stratégies possibles de gestion de ces erreurs. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération répertorie les stratégies possibles de gestion de ces erreurs. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Crée l'objet {@code XslFoLoadOptions} sans données xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Crée l'objet {@code XslFoLoadOptions} sans données xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Crée l'objet {@code XslFoLoadOptions} sans données xsl.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Le chemin/base URL à partir duquel sont recherchés les chemins relatifs vers les ressources externes (le cas échéant) référencées dans le fichier SVG chargé.

**Returns:**
Chaîne

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération répertorie les stratégies possibles de gestion de ces erreurs.

**Returns:**
Élément ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération répertorie les stratégies possibles de gestion de ces erreurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingErrorsHandlingType |  | Élément ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes |
