---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Azione eseguita con l'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine viene rimosso"
type: docs
weight: 2290
url: /it/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Azione eseguita con l'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine viene rimosso

## Campi

| Campo | Descrizione |
| --- | --- |
| [Check](#Check) | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso solo se non ci sono altri riferimenti all'immagine da altre pagine. Questo potrebbe richiedere più tempo rispetto all'opzione ForceDelete. |
| [ForceDelete](#ForceDelete) | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso dal documento. Se esistono altri riferimenti allo stesso oggetto, il documento potrebbe risultare corrotto. |
| [KeepContents](#KeepContents) | L'immagine verrà rimossa dalla collezione. Se il contenuto della pagina contiene riferimenti all'immagine, questi non verranno rimossi. Il documento potrebbe diventare non valido. |
| [None](#None) | L'immagine verrà rimossa dalla collezione e dal contenuto della pagina, ma l'oggetto immagine non verrà eliminato. La dimensione del file non diminuirà. |

### Check {#Check}
```
public static final int Check
```

L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso solo se non ci sono altri riferimenti all'immagine da altre pagine. Questo potrebbe richiedere più tempo rispetto all'opzione ForceDelete.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso dal documento. Se esistono altri riferimenti allo stesso oggetto, il documento potrebbe risultare corrotto.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

L'immagine verrà rimossa dalla collezione. Se il contenuto della pagina contiene riferimenti all'immagine, questi non verranno rimossi. Il documento potrebbe diventare non valido.

### None {#None}
```
public static final int None
```

L'immagine verrà rimossa dalla collezione e dal contenuto della pagina, ma l'oggetto immagine non verrà eliminato. La dimensione del file non diminuirà.
