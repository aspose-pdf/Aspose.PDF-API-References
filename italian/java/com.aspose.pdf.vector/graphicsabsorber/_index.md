---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un oggetto assorbitore di elementi grafici. Esegue la ricerca grafica e fornisce l'accesso ai risultati della ricerca tramite {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Rappresenta un oggetto assorbitore di elementi grafici. Esegue la ricerca grafica e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose](#dispose--) | Rilascia tutte le risorse utilizzate dalla classe {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Ottiene la collezione di occorrenze di ricerca presentate con oggetti {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | Riprendi l'aggiornamento per Page#getContents e tutti @link XForm#getContents. È stato fatto per aumentare le prestazioni, vedi anche. |
| [suppressUpdate](#suppressUpdate--) | Sopprime l'aggiornamento per Page#getContents e tutti @link XForm#getContents. È stato fatto per aumentare le prestazioni, vedi anche. |
| [visit](#visit-com.aspose.pdf.Page-) | Esegue la ricerca nella pagina specificata. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Rilascia tutte le risorse utilizzate dalla classe {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Ottiene la collezione di occorrenze di ricerca presentate con oggetti {@link GraphicElement}.

**Returns:**
Istanza di GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Riprendi l'aggiornamento per Page#getContents e tutti @link XForm#getContents. È stato fatto per aumentare le prestazioni, vedi anche.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Sopprime l'aggiornamento per Page#getContents e tutti @link XForm#getContents. È stato fatto per aumentare le prestazioni, vedi anche.

### visit {#visit-com.aspose.pdf.Page-}
Esegue la ricerca nella pagina specificata.
