---
title: "Resources"
linktitle: "Resources"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta le risorse della pagina."
type: docs
weight: 4220
url: /it/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Classe che rappresenta le risorse della pagina.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Cancella i dati nella cache, libera la memoria ecc. |
| [getExtGStates](#getExtGStates--) | Restituisce tutti gli ExGState dalle risorse. |
| [getFonts](#getFonts--) | Restituisce la collezione delle risorse {@code Fonts} |
| [getFonts](#getFonts-boolean-) | Restituisce la collezione dei font. Se le risorse non contengono una voce per i font, verrà creata in base al flag CreateIfAbsent. |
| [getForms](#getForms--) | Restituisce la collezione {@code Forms} dei moduli |
| [getImages](#getImages--) | Restituisce la collezione {@code Images} delle immagini |
| [getResourceDictionary](#getResourceDictionary--) | Campo interno |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Ottiene le risorse per |
| [isCommonResource](#isCommonResource--) | Vero se queste risorse sono comuni, cioè condivise tra più pagine (collocate nel dizionario delle pagine o in ogni pagina come riferimento a oggetto). La manipolazione delle risorse comuni deve essere eseguita con molta attenzione; ad esempio, eliminare un oggetto dalle risorse comuni in una pagina può causare errori nelle altre pagine se l'oggetto eliminato era utilizzato da altre pagine. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Solo per uso interno! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Cancella i dati nella cache, libera la memoria ecc.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Restituisce tutti gli ExGState dalle risorse.

**Returns:**
Restituisce un dizionario con le chiavi dei nomi ExGState.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Restituisce la collezione delle risorse {@code Fonts}

**Returns:**
Oggetto FontCollection

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Restituisce la collezione dei font. Se le risorse non contengono una voce per i font, verrà creata in base al flag CreateIfAbsent.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createIfAbsent |  | Se questo flag è vero, i caratteri verranno creati se questa voce è assente. |

**Returns:**
Collezione di caratteri.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Restituisce la collezione {@code Forms} dei moduli

**Returns:**
Oggetto XFormCollection

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Restituisce la collezione {@code Images} delle immagini

**Returns:**
Oggetto XImageCollection

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Campo interno

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Ottiene le risorse per

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Vero se queste risorse sono comuni, cioè condivise tra più pagine (collocate nel dizionario delle pagine o in ogni pagina come riferimento a oggetto). La manipolazione delle risorse comuni deve essere eseguita con molta attenzione; ad esempio, eliminare un oggetto dalle risorse comuni in una pagina può causare errori nelle altre pagine se l'oggetto eliminato era utilizzato da altre pagine.

**Returns:**
valore booleano

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
Solo per uso interno!
