---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta le informazioni del timbro."
type: docs
weight: 710
url: /it/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Classe che rappresenta le informazioni del timbro.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getForm](#getForm--) | Restituisce XForm del timbro. |
| [getImage](#getImage--) | Restituisce l'immagine del timbro. Può essere null se il timbro non contiene immagini (ad esempio per timbro di testo). |
| [getImageInternal](#getImageInternal--) | Restituisce l'immagine del timbro. Può essere null se il timbro non contiene immagini (ad esempio per timbro di testo). |
| [getIndexOnPage](#getIndexOnPage--) | Restituisce l'indice del timbro nella pagina. |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo dove è posizionato il timbro. |
| [getStampId](#getStampId--) | Restituisce l'identificatore del timbro. |
| [getStampType](#getStampType--) | Restituisce il tipo di timbro (immagine / form). |
| [getText](#getText--) | Ottiene il testo nel timbro. |
| [getVisible](#getVisible--) | Ottiene la visibilità del timbro. Se false, il timbro è nascosto (con HideStampById). Il timbro nascosto può essere ripristinato con ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Restituisce XForm del timbro.

**Returns:**
oggetto XForm

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Restituisce l'immagine del timbro. Può essere null se il timbro non contiene immagini (ad esempio per timbro di testo).

**Returns:**
Oggetto BufferedImage

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Restituisce l'immagine del timbro. Può essere null se il timbro non contiene immagini (ad esempio per timbro di testo).

**Returns:**
Oggetto immagine

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Restituisce l'indice del timbro nella pagina.

**Returns:**
valore int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo dove è posizionato il timbro.

**Returns:**
Elemento rettangolo

### getStampId {#getStampId--}
```
public int getStampId()
```

Restituisce l'identificatore del timbro.

**Returns:**
valore int

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Restituisce il tipo di timbro (immagine / form).

**Returns:**
Elemento StampType @see StampType

### getText {#getText--}
```
public String getText()
```

Ottiene il testo nel timbro.

**Returns:**
valore String

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Ottiene la visibilità del timbro. Se false, il timbro è nascosto (con HideStampById). Il timbro nascosto può essere ripristinato con ShowStampById.

**Returns:**
valore booleano
