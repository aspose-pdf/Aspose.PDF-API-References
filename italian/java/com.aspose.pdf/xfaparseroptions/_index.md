---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "classe per gestire l'incapsulamento dei dati correlati"
type: docs
weight: 5560
url: /it/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

classe per gestire l'incapsulamento dei dati correlati

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | Inizializza una nuova istanza della classe {@code XfaParserOptions}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBasePath](#getBasePath--) | Ottiene o imposta il percorso base. Valore: Il percorso base. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i gruppi Xfa "excluded groups" richiesti. Questa proprietà è stata introdotta perché le assenze di analogie dei gruppi esclusi durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita. |
| [getPageSize](#getPageSize--) | Ottiene o imposta la dimensione della pagina. Valore: La dimensione della pagina. |
| [getSigned](#getSigned--) | Se questa proprietà è true allora il documento verrà convertito utilizzando lo stream del modulo xfa (se esiste). Se è false lo stream del modulo xfa verrà ignorato. Questa proprietà è stata introdotta perché non è chiaro come calcolare il checksum utilizzato per la verifica della firma. |
| [setBasePath](#setBasePath-java.net.URI-) | Ottiene o imposta il percorso base. Valore: Il percorso base. |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i gruppi Xfa "excluded groups" richiesti. Questa proprietà è stata introdotta perché le assenze di analogie dei gruppi esclusi durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita. |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | Ottiene o imposta la dimensione della pagina. Valore: La dimensione della pagina. |
| [setSigned](#setSigned-boolean-) | Se questa proprietà è true allora il documento verrà convertito utilizzando lo stream del modulo xfa (se esiste). Se è false lo stream del modulo xfa verrà ignorato. Questa proprietà è stata introdotta perché non è chiaro come calcolare il checksum utilizzato per la verifica della firma. |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
Inizializza una nuova istanza della classe {@code XfaParserOptions}.

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

Ottiene o imposta il percorso base. Valore: Il percorso base.

**Returns:**
Oggetto URI

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i gruppi Xfa "excluded groups" richiesti. Questa proprietà è stata introdotta perché le assenze di analogie dei gruppi esclusi durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita.

**Returns:**
valore booleano

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Ottiene o imposta la dimensione della pagina. Valore: La dimensione della pagina.

**Returns:**
Oggetto Dimension2D

### getSigned {#getSigned--}
```
public boolean getSigned()
```

Se questa proprietà è true allora il documento verrà convertito utilizzando lo stream del modulo xfa (se esiste). Se è false lo stream del modulo xfa verrà ignorato. Questa proprietà è stata introdotta perché non è chiaro come calcolare il checksum utilizzato per la verifica della firma.

**Returns:**
valore booleano

### setBasePath {#setBasePath-java.net.URI-}
Ottiene o imposta il percorso base. Valore: Il percorso base.

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Se questa proprietà è true allora verranno disegnati rettangoli rossi aggiuntivi per i gruppi Xfa "excluded groups" richiesti. Questa proprietà è stata introdotta perché le assenze di analogie dei gruppi esclusi durante la conversione della rappresentazione Xfa dei moduli allo standard. È false per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
Ottiene o imposta la dimensione della pagina. Valore: La dimensione della pagina.

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

Se questa proprietà è true allora il documento verrà convertito utilizzando lo stream del modulo xfa (se esiste). Se è false lo stream del modulo xfa verrà ignorato. Questa proprietà è stata introdotta perché non è chiaro come calcolare il checksum utilizzato per la verifica della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
