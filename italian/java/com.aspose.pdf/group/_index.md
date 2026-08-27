---
title: "Group"
linktitle: "Group"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente."
type: docs
weight: 1850
url: /it/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

Una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | Il costruttore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Ottiene ColorSpace <p> |
| [isKnockout](#isKnockout--) | solo per uso interno Se questo flag è false, gli oggetti successivi all'interno del gruppo vengono compositi con quelli precedenti con cui si sovrappongono; se true, vengono compositi con lo sfondo iniziale del gruppo e sovrascrivono ("knock out") qualsiasi oggetto sovrapposto precedente. |
| [isTransparency](#isTransparency--) | per uso interno restituisce solo il flag di trasparenza del gruppo. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | Lo spazio colore del gruppo. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | Se questo flag è false, gli oggetti successivi all'interno del gruppo vengono compositi con quelli precedenti con cui si sovrappongono; se è true, vengono compositi con lo sfondo iniziale del gruppo e sovrascrivono ("knock out") qualsiasi oggetto precedente sovrapposto. |

### Group {#Group-com.aspose.pdf.Page-}
Il costruttore.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Ottiene ColorSpace <p>

**Returns:**
Valore ColorSpace. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

solo per uso interno Se questo flag è false, gli oggetti successivi all'interno del gruppo vengono compositi con quelli precedenti con cui si sovrappongono; se true, vengono compositi con lo sfondo iniziale del gruppo e sovrascrivono ("knock out") qualsiasi oggetto sovrapposto precedente.

**Returns:**
Elemento ExtendedBoolean @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

per uso interno restituisce solo il flag di trasparenza del gruppo.

**Returns:**
valore booleano

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
Lo spazio colore del gruppo.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
Se questo flag è false, gli oggetti successivi all'interno del gruppo vengono compositi con quelli precedenti con cui si sovrappongono; se è true, vengono compositi con lo sfondo iniziale del gruppo e sovrascrivono ("knock out") qualsiasi oggetto precedente sovrapposto.
