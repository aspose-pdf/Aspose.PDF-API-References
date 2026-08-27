---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe rappresenta un insieme di dati relativi al salvataggio di file immagine di risorse esterne durante la conversione da PDF a HTML."
type: docs
weight: 2070
url: /it/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Questa classe rappresenta un insieme di dati relativi al salvataggio di file immagine di risorse esterne durante la conversione da PDF a HTML.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | crea una nuova istanza di HtmlImageSavingInfo |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Indica al codice personalizzato a quale pagina del set generato di file HTML corrisponde l'immagine salvata. Se la divisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola pagina HTML. |
| [getImageType](#getImageType--) | Rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere usato nel codice personalizzato per decidere cosa fare. |
| [getParentType](#getParentType--) | L'immagine salvata può riferirsi direttamente a HTML o può essere estratta da SVG incorporato in HTML. Questa proprietà può indicare al codice personalizzato quale sia il tipo di genitore dell'immagine elaborata. È impostata dal convertitore e può essere usata nel codice personalizzato per decidere cosa fare con quell'immagine (ad es. il codice personalizzato può decidere dove salvare l'immagine o come deve essere referenziata nel contenuto del genitore). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Indica al codice personalizzato a quale pagina del documento PDF originale corrisponde l'immagine salvata. Poiché è possibile che non vengano salvate tutte le pagine del documento originale, questo valore indica il numero di pagina di origine nel PDF originale. Se il numero di pagina originale per qualche motivo è sconosciuto, restituisce sempre '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Indica al codice personalizzato a quale pagina del set generato di file HTML corrisponde l'immagine salvata. Se la divisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola pagina HTML. |
| [setImageType](#setImageType-int-) | Rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere usato nel codice personalizzato per decidere cosa fare. |
| [setParentType](#setParentType-int-) | L'immagine salvata può riferirsi direttamente a HTML o può essere estratta da SVG incorporato in HTML. Questa proprietà può indicare al codice personalizzato quale sia il tipo di genitore dell'immagine elaborata. È impostata dal convertitore e può essere usata nel codice personalizzato per decidere cosa fare con quell'immagine (ad es. il codice personalizzato può decidere dove salvare l'immagine o come deve essere referenziata nel contenuto del genitore). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Indica al codice personalizzato a quale pagina del documento PDF originale corrisponde l'immagine salvata. Poiché è possibile che non vengano salvate tutte le pagine del documento originale, questo valore indica il numero di pagina di origine nel PDF originale. Se il numero di pagina originale per qualche motivo è sconosciuto, restituisce sempre '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

crea una nuova istanza di HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Indica al codice personalizzato a quale pagina del set generato di file HTML corrisponde l'immagine salvata. Se la divisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola pagina HTML.

**Returns:**
valore int

### getImageType {#getImageType--}
```
public int getImageType()
```

Rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere usato nel codice personalizzato per decidere cosa fare.

**Returns:**
HtmlImageType elemento @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

L'immagine salvata può riferirsi direttamente a HTML o può essere estratta da SVG incorporato in HTML. Questa proprietà può indicare al codice personalizzato quale sia il tipo di genitore dell'immagine elaborata. È impostata dal convertitore e può essere usata nel codice personalizzato per decidere cosa fare con quell'immagine (ad es. il codice personalizzato può decidere dove salvare l'immagine o come deve essere referenziata nel contenuto del genitore).

**Returns:**
ImageParentTypes elemento @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Indica al codice personalizzato a quale pagina del documento PDF originale corrisponde l'immagine salvata. Poiché è possibile che non vengano salvate tutte le pagine del documento originale, questo valore indica il numero di pagina di origine nel PDF originale. Se il numero di pagina originale per qualche motivo è sconosciuto, restituisce sempre '1'.

**Returns:**
valore int

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Indica al codice personalizzato a quale pagina del set generato di file HTML corrisponde l'immagine salvata. Se la divisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola pagina HTML.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlHostPageNumber |  | valore int |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere usato nel codice personalizzato per decidere cosa fare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageType |  | HtmlImageType elemento @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

L'immagine salvata può riferirsi direttamente a HTML o può essere estratta da SVG incorporato in HTML. Questa proprietà può indicare al codice personalizzato quale sia il tipo di genitore dell'immagine elaborata. È impostata dal convertitore e può essere usata nel codice personalizzato per decidere cosa fare con quell'immagine (ad es. il codice personalizzato può decidere dove salvare l'immagine o come deve essere referenziata nel contenuto del genitore).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentType |  | ImageParentTypes elemento @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Indica al codice personalizzato a quale pagina del documento PDF originale corrisponde l'immagine salvata. Poiché è possibile che non vengano salvate tutte le pagine del documento originale, questo valore indica il numero di pagina di origine nel PDF originale. Se il numero di pagina originale per qualche motivo è sconosciuto, restituisce sempre '1'.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfHostPageNumber |  | valore int |
