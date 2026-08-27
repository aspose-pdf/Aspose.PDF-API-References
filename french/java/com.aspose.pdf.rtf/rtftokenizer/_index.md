---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe conçue pour extraire le contenu RTF diffusé sous forme d'ensemble de jetons."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Classe conçue pour extraire le contenu RTF diffusé sous forme d'ensemble de jetons.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [readNextToken](#readNextToken--) | Lit le flux d'entrée et renvoie le jeton suivant. |
| [skip](#skip-int-) | Consomme et supprime le nombre spécifié de caractères du flux d'entrée. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Lit le flux d'entrée et renvoie le jeton suivant.

### skip {#skip-int-}
```
public final void skip(int count)
```

Consomme et supprime le nombre spécifié de caractères du flux d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| compte |  | Le nombre de caractères à ignorer. |
