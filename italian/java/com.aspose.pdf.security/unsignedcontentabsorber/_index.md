---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per estrarre contenuti non firmati da un file PDF gestito da firme digitali."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Rappresenta una classe per estrarre contenuti non firmati da un file PDF gestito da firme digitali.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Rappresenta una classe utilizzata per l'elaborazione di contenuti non firmati. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Tentativo di recuperare il contenuto non firmato dal documento associato. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Rappresenta una classe utilizzata per l'elaborazione di contenuti non firmati.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Tentativo di recuperare il contenuto non firmato dal documento associato.

**Returns:**
Un oggetto {@link UnsignedContentAbsorber.Result} contenente i dettagli sul contenuto non firmato, la copertura delle firme digitali, lo stato di successo dell'operazione e un messaggio informativo.
