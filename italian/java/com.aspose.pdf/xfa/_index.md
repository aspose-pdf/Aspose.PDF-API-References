---
title: "XFA"
linktitle: "XFA"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il modulo XML relativo all'XML Forms Architecture (XFA)."
type: docs
weight: 5550
url: /it/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Rappresenta il modulo XML relativo all'XML Forms Architecture (XFA).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Aggiungi il valore XML al nodo del modello che corrisponde all'espressione XPath |
| [beginCachedUpdates](#beginCachedUpdates--) | Avvia la modalità di aggiornamenti memorizzati nella cache. Tutte le modifiche apportate a XFA saranno memorizzate nella cache e salvate nella struttura del documento alla chiamata EndCachedUpdates. Questo consente di migliorare le prestazioni evitando operazioni ridondanti durante il salvataggio dei pacchetti XML nel documento quando vengono apportate molte modifiche a XFA. |
| [endCachedUpdates](#endCachedUpdates--) | Termina gli aggiornamenti memorizzati nella cache e salva tutti i dati nella struttura del documento. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Appiattisci il campo del modulo XFA. |
| [get_Item](#get_Item-java.lang.String-) | Ottiene il valore del nodo dati secondo {@code path}. |
| [getConfig](#getConfig--) | Componente Config XFA di un modulo XFA. |
| [getDatasets](#getDatasets--) | Componente Datasets XFA di un modulo XFA. |
| [getFieldNames](#getFieldNames--) | Elenco dei nomi dei campi nel modello del modulo. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Restituisce una mappa con il nome breve del campo e il suo valore stringa per tutti i campi. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Restituisce il nodo XML del modello di campo XFA. |
| [getFieldTemplates](#getFieldTemplates--) | Restituisce l'elenco di tutti i modelli di campo nel modulo XFA. |
| [getForm](#getForm--) | Ottiene il componente Form di XFA di un modulo XFA. |
| [getNamespaceManager_](#getNamespaceManager_--) | Ottiene lo spazio dei nomi per il modulo XFA. I seguenti spazi dei nomi sono definiti: "data" per i dati del modulo e "tpl" per il modello del modulo. |
| [getNamespaceManager](#getNamespaceManager--) | Restituisce il gestore degli spazi dei nomi con gli spazi dei nomi utilizzati per il modello e i dati. |
| [getTemplate](#getTemplate--) | Componente Template XFA di un modulo XFA. |
| [getXDP](#getXDP--) | Pacchetto Dati XML (tutti i componenti del modulo XFA all'interno di un contenitore XML circostante). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Ottiene il valore del nodo dati secondo {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Imposta l'immagine per il campo XFA. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Prova a esportare lo script di calcolo dal modulo XFA. Altrimenti restituisce la stringa vuota; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Aggiungi il valore XML al nodo del modello che corrisponde all'espressione XPath

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Avvia la modalità di aggiornamenti memorizzati nella cache. Tutte le modifiche apportate a XFA saranno memorizzate nella cache e salvate nella struttura del documento alla chiamata EndCachedUpdates. Questo consente di migliorare le prestazioni evitando operazioni ridondanti durante il salvataggio dei pacchetti XML nel documento quando vengono apportate molte modifiche a XFA.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Termina gli aggiornamenti memorizzati nella cache e salva tutti i dati nella struttura del documento.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Appiattisci il campo del modulo XFA.

### get_Item {#get_Item-java.lang.String-}
Ottiene il valore del nodo dati secondo {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

Componente Config XFA di un modulo XFA.

**Returns:**
Oggetto XmlNode

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

Componente Datasets XFA di un modulo XFA.

**Returns:**
Oggetto XmlNode

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Elenco dei nomi dei campi nel modello del modulo.

**Returns:**
array di valori String

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Restituisce una mappa con il nome breve del campo e il suo valore stringa per tutti i campi. </p>

**Returns:**
Oggetto {@code HashMap<String, String>}

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Restituisce il nodo XML del modello di campo XFA.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Restituisce l'elenco di tutti i modelli di campo nel modulo XFA.

**Returns:**
Elenco dei modelli di campo.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Ottiene il componente Form di XFA di un modulo XFA.

**Returns:**
Oggetto XmlNode

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Ottiene lo spazio dei nomi per il modulo XFA. I seguenti spazi dei nomi sono definiti: "data" per i dati del modulo e "tpl" per il modello del modulo.

**Returns:**
Oggetto XmlNamespaceManager

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Restituisce il gestore degli spazi dei nomi con gli spazi dei nomi utilizzati per il modello e i dati.

**Returns:**
Oggetto XmlNamespaceManager

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

Componente Template XFA di un modulo XFA.

**Returns:**
Oggetto XmlNode

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

Pacchetto Dati XML (tutti i componenti del modulo XFA all'interno di un contenitore XML circostante).

**Returns:**
Oggetto XmlDocument

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Ottiene il valore del nodo dati secondo {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Imposta l'immagine per il campo XFA.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Prova a esportare lo script di calcolo dal modulo XFA. Altrimenti restituisce la stringa vuota;
