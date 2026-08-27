---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la posizione nel documento PDF in cui è comparso l'errore di estrazione del testo."
type: docs
weight: 5050
url: /it/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Rappresenta la posizione nel documento PDF in cui è comparso l'errore di estrazione del testo.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Chiave (nome) dell'oggetto PDF Font utilizzato per mostrare l'operatore che causa l'errore di estrazione del testo. |
| [getFormKey](#getFormKey--) | Chiave (nome) del PDF Form XObject in cui è stato individuato l'errore di estrazione del testo del flusso di contenuti. Non vuoto se ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Tipo dell'oggetto PDF (Page o xForm) in cui è stato individuato l'errore di estrazione del testo del flusso di contenuti. |
| [getOperatorIndex](#getOperatorIndex--) | Indice dell'operatore di visualizzazione del testo nel flusso di contenuti (collezione di operatori) che causa l'errore di estrazione del testo. |
| [getOperatorString](#getOperatorString--) | Operatore di visualizzazione del testo che causa l'errore di estrazione del testo. |
| [getPageNumber](#getPageNumber--) | Numero della pagina del documento in cui è stato individuato l'errore di estrazione del testo. |
| [getPath](#getPath--) | Posizione del documento PDF in cui è comparso l'errore di estrazione del testo. |
| [getTextStartPoint](#getTextStartPoint--) | Chiave (nome) dell'oggetto PDF Font utilizzato per mostrare l'operatore che causa l'errore di estrazione del testo. |
| [toString](#toString--) | Restituisce la rappresentazione stringa. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Chiave (nome) dell'oggetto PDF Font utilizzato per mostrare l'operatore che causa l'errore di estrazione del testo.

**Returns:**
valore String

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Chiave (nome) del PDF Form XObject in cui è stato individuato l'errore di estrazione del testo del flusso di contenuti. Non vuoto se ObjectType == 'xForm'.

**Returns:**
valore String

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Tipo dell'oggetto PDF (Page o xForm) in cui è stato individuato l'errore di estrazione del testo del flusso di contenuti.

**Returns:**
valore String

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Indice dell'operatore di visualizzazione del testo nel flusso di contenuti (collezione di operatori) che causa l'errore di estrazione del testo.

**Returns:**
valore int

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Operatore di visualizzazione del testo che causa l'errore di estrazione del testo.

**Returns:**
valore String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Numero della pagina del documento in cui è stato individuato l'errore di estrazione del testo.

**Returns:**
valore int

### getPath {#getPath--}
```
public String getPath()
```

Posizione del documento PDF in cui è comparso l'errore di estrazione del testo.

**Returns:**
valore String

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Chiave (nome) dell'oggetto PDF Font utilizzato per mostrare l'operatore che causa l'errore di estrazione del testo.

**Returns:**
Istanza di Point

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione stringa.

**Returns:**
Rappresentazione stringa.
