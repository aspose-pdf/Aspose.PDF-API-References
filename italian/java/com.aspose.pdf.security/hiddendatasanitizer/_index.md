---
title: "HiddenDataSanitizer"
linktitle: "HiddenDataSanitizer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per sanificare i dati nascosti."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.security/hiddendatasanitizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizer

```
public final class HiddenDataSanitizer extends Object
```

Rappresenta una classe per sanificare i dati nascosti.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HiddenDataSanitizer](#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-) | Fornisce funzionalità per sanificare i dati nascosti da un documento PDF, garantendo che informazioni sensibili o non necessarie come metadati, annotazioni, JavaScript o contenuti privati vengano rimossi o trasformati. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [sanitize](#sanitize-com.aspose.pdf.Document-) | Sanitizza un documento PDF fornito rimuovendo o trasformando i dati nascosti. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-) | Sostituisce il contenuto della pagina con immagini e rimuove altri dati nascosti. Consente di rimuovere il testo nascosto con un colore di sfondo, così come il testo nascosto sotto le immagini. Inoltre, rimuove completamente tutti gli elementi interattivi. Il documento viene convertito in immagini così com'è, quindi viene ripulito da eventuali dati nascosti residui. Se è necessario pulire prima e poi convertire, utilizzare il metodo della classe principale. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-int-) | Sostituisce il contenuto della pagina con immagini e rimuove altri dati nascosti. Consente di rimuovere il testo nascosto con un colore di sfondo, così come il testo nascosto sotto le immagini. Rimuove anche completamente tutti gli elementi interattivi. Il documento viene convertito in immagini così com'è, quindi viene ripulito da eventuali dati nascosti residui. Se è necessario pulire prima e poi convertire, utilizzare il metodo della classe principale. |

### HiddenDataSanitizer {#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-}
Fornisce funzionalità per sanificare i dati nascosti da un documento PDF, garantendo che informazioni sensibili o non necessarie come metadati, annotazioni, JavaScript o contenuti privati vengano rimossi o trasformati.

### sanitize {#sanitize-com.aspose.pdf.Document-}
Sanitizza un documento PDF fornito rimuovendo o trasformando i dati nascosti.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-}
Sostituisce il contenuto della pagina con immagini e rimuove altri dati nascosti. Consente di rimuovere il testo nascosto con un colore di sfondo, così come il testo nascosto sotto le immagini. Inoltre, rimuove completamente tutti gli elementi interattivi. Il documento viene convertito in immagini così com'è, quindi viene ripulito da eventuali dati nascosti residui. Se è necessario pulire prima e poi convertire, utilizzare il metodo della classe principale.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-int-}
Sostituisce il contenuto della pagina con immagini e rimuove altri dati nascosti. Consente di rimuovere il testo nascosto con un colore di sfondo, così come il testo nascosto sotto le immagini. Rimuove anche completamente tutti gli elementi interattivi. Il documento viene convertito in immagini così com'è, quindi viene ripulito da eventuali dati nascosti residui. Se è necessario pulire prima e poi convertire, utilizzare il metodo della classe principale.
