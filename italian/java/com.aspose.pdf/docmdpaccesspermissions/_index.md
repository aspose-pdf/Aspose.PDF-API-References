---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Le autorizzazioni di accesso concesse per questo documento. I valori validi sono: 1 - Nessuna modifica al documento è consentita; qualsiasi modifica al documento invalida la firma. 2 -."
type: docs
weight: 1010
url: /it/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Le autorizzazioni di accesso concesse per questo documento. I valori validi sono: 1 - Non sono consentite modifiche al documento; qualsiasi modifica al documento invalida la firma. 2 - Le modifiche consentite sono la compilazione di moduli, l'istanziazione di modelli di pagina e la firma; altre modifiche invalidano la firma. 3 - Le modifiche consentite sono le stesse della voce 2, oltre alla creazione, eliminazione e modifica di annotazioni; altre modifiche invalidano la firma.

## Campi

| Campo | Descrizione |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Le modifiche consentite sono le stesse di quelle per 2, oltre alla creazione, cancellazione e modifica di annotazioni; altre modifiche invalidano la firma. |
| [FillingInForms](#FillingInForms) | 2 - Le modifiche consentite sono la compilazione di moduli, l'istanziazione di modelli di pagina e la firma; altre modifiche invalidano la firma. |
| [NoChanges](#NoChanges) | 1 - Nessuna modifica al documento è consentita; qualsiasi modifica al documento invalida la firma. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Le modifiche consentite sono le stesse di quelle per 2, oltre alla creazione, cancellazione e modifica di annotazioni; altre modifiche invalidano la firma.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Le modifiche consentite sono la compilazione di moduli, l'istanziazione di modelli di pagina e la firma; altre modifiche invalidano la firma.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Nessuna modifica al documento è consentita; qualsiasi modifica al documento invalida la firma.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
