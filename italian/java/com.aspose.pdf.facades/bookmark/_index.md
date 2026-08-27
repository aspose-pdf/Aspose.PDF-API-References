---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un segnalibro."
type: docs
weight: 60
url: /it/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Rappresenta un segnalibro.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Bookmark](#Bookmark--) | Inizializza una nuova istanza della classe {@code Bookmark}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAction](#getAction--) | Ottiene l'azione associata al bookmark. Se PageNumber è presente l'azione non può essere specificata. Il tipo di azione include: \"GoTo\", \"GoToR\", \"Launch\", \"Named\". |
| [getBoldFlag](#getBoldFlag--) | Ottiene il flag grassetto del titolo del bookmark. |
| [getChildItem](#getChildItem--) | Ottiene i figli del bookmark. Obsoleto(\"Use getChildItems() property instead of this one.\") |
| [getChildItems](#getChildItems--) | Ottiene i figli del bookmark. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Non ancora supportato. Il nome dell'azione corrispondente all'esecuzione di una voce di menu nel visualizzatore Acrobat. |
| [getDestination](#getDestination--) | Ottiene la pagina di destinazione del bookmark. Richiesto se l'azione è impostata come \"\". |
| [getItalicFlag](#getItalicFlag--) | Ottiene il flag corsivo del titolo del bookmark. |
| [getLevel](#getLevel--) | Ottiene il livello gerarchico del bookmark. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Ottiene la coordinata inferiore della visualizzazione della pagina. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Ottiene la coordinata sinistra della visualizzazione della pagina. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Ottiene la coordinata destra della visualizzazione della pagina. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Restituisce la coordinata superiore della visualizzazione della pagina. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Restituisce il fattore di zoom della visualizzazione della pagina. |
| [getPageDisplay](#getPageDisplay--) | Restituisce il tipo di pagina di destinazione del segnalibro visualizzato. |
| [getPageNumber](#getPageNumber--) | Restituisce il numero della pagina di destinazione del segnalibro. |
| [getRemoteFile](#getRemoteFile--) | Restituisce il file (percorso) richiesto per l'azione "GoToR" del segnalibro. |
| [getTitle](#getTitle--) | Restituisce il titolo del segnalibro. |
| [getTitleColor](#getTitleColor--) | Restituisce il colore del titolo del segnalibro. |
| [isOpen](#isOpen--) | Restituisce lo stato del segnalibro (aperto, chiuso). |
| [setAction](#setAction-java.lang.String-) | Imposta l'azione associata al segnalibro. Se è presente PageNumber l'azione non può essere specificata. Il tipo di azione include: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Imposta il flag grassetto del titolo del segnalibro. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Imposta i figli del segnalibro. Obsoleto("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Imposta i figli del segnalibro. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Non ancora supportato. Imposta il nome dell'azione corrispondente all'esecuzione di una voce di menu nel visualizzatore Acrobat. |
| [setDestination](#setDestination-java.lang.String-) | Imposta la pagina di destinazione del segnalibro. Necessario se l'azione è impostata come "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Imposta il flag corsivo del titolo del segnalibro. |
| [setLevel](#setLevel-int-) | Imposta il livello gerarchico del segnalibro. |
| [setOpen](#setOpen-boolean-) | Imposta lo stato del segnalibro (aperto, chiuso). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Imposta la coordinata inferiore della visualizzazione della pagina. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Imposta la coordinata sinistra della visualizzazione della pagina. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Imposta la coordinata destra della visualizzazione della pagina. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Imposta la coordinata superiore della visualizzazione della pagina. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Imposta il fattore di zoom della visualizzazione della pagina. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Imposta il tipo di pagina di destinazione del segnalibro visualizzato. |
| [setPageNumber](#setPageNumber-int-) | Imposta il numero della pagina di destinazione del segnalibro. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Imposta il file (percorso) richiesto per l'azione "GoToR" del segnalibro. |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo del segnalibro. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Imposta il colore del titolo del segnalibro. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | converti in OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Inizializza una nuova istanza della classe {@code Bookmark}.

### getAction {#getAction--}
```
public String getAction()
```

Ottiene l'azione associata al bookmark. Se PageNumber è presente l'azione non può essere specificata. Il tipo di azione include: \"GoTo\", \"GoToR\", \"Launch\", \"Named\".

**Returns:**
valore String

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Ottiene il flag grassetto del titolo del bookmark.

**Returns:**
valore booleano

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Ottiene i figli del bookmark. Obsoleto(\"Use getChildItems() property instead of this one.\")

**Returns:**
Elemento Bookmarks

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Ottiene i figli del bookmark.

**Returns:**
elementi figli del segnalibro.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Non ancora supportato. Il nome dell'azione corrispondente all'esecuzione di una voce di menu nel visualizzatore Acrobat.

**Returns:**
array di valore int

### getDestination {#getDestination--}
```
public String getDestination()
```

Ottiene la pagina di destinazione del bookmark. Richiesto se l'azione è impostata come \"\".

**Returns:**
valore String

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Ottiene il flag corsivo del titolo del bookmark.

**Returns:**
valore booleano

### getLevel {#getLevel--}
```
public int getLevel()
```

Ottiene il livello gerarchico del bookmark.

**Returns:**
valore int

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Ottiene la coordinata inferiore della visualizzazione della pagina.

**Returns:**
valore int

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Ottiene la coordinata sinistra della visualizzazione della pagina.

**Returns:**
valore int

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Ottiene la coordinata destra della visualizzazione della pagina.

**Returns:**
valore int

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Restituisce la coordinata superiore della visualizzazione della pagina.

**Returns:**
valore int

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Restituisce il fattore di zoom della visualizzazione della pagina.

**Returns:**
valore int

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Restituisce il tipo di pagina di destinazione del segnalibro visualizzato.

**Returns:**
valore String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Restituisce il numero della pagina di destinazione del segnalibro.

**Returns:**
valore int

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Restituisce il file (percorso) richiesto per l'azione "GoToR" del segnalibro.

**Returns:**
valore String

### getTitle {#getTitle--}
```
public String getTitle()
```

Restituisce il titolo del segnalibro.

**Returns:**
valore String

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Restituisce il colore del titolo del segnalibro.

**Returns:**
Elemento colore

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Restituisce lo stato del segnalibro (aperto, chiuso).

**Returns:**
valore booleano

### setAction {#setAction-java.lang.String-}
Imposta l'azione associata al segnalibro. Se è presente PageNumber l'azione non può essere specificata. Il tipo di azione include: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Imposta il flag grassetto del titolo del segnalibro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Imposta i figli del segnalibro. Obsoleto("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Imposta i figli del segnalibro.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Non ancora supportato. Imposta il nome dell'azione corrispondente all'esecuzione di una voce di menu nel visualizzatore Acrobat.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di valore int |

### setDestination {#setDestination-java.lang.String-}
Imposta la pagina di destinazione del segnalibro. Necessario se l'azione è impostata come "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Imposta il flag corsivo del titolo del segnalibro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Imposta il livello gerarchico del segnalibro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Imposta lo stato del segnalibro (aperto, chiuso).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Imposta la coordinata inferiore della visualizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Imposta la coordinata sinistra della visualizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Imposta la coordinata destra della visualizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Imposta la coordinata superiore della visualizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Imposta il fattore di zoom della visualizzazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Imposta il tipo di pagina di destinazione del segnalibro visualizzato.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Imposta il numero della pagina di destinazione del segnalibro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Imposta il file (percorso) richiesto per l'azione "GoToR" del segnalibro.

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo del segnalibro.

### setTitleColor {#setTitleColor-java.awt.Color-}
Imposta il colore del titolo del segnalibro.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
converti in OutlineItemCollection
