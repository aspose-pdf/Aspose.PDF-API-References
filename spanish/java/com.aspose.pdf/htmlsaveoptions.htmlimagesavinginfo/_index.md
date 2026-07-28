---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML."
type: docs
weight: 2070
url: /es/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Esta clase representa un conjunto de datos relacionados con el guardado de archivos de imagen de recursos externos durante la conversión de PDF a HTML.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | crea una nueva instancia de HtmlImageSavingInfo |

## Métodos

| Método | Descripción |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Indica al código personalizado a qué página del conjunto generado de archivos HTML corresponde la imagen guardada. Si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una página HTML. |
| [getImageType](#getImageType--) | Representa el tipo de imagen guardada referenciada en HTML. Establecido por el convertidor y puede ser usado en código personalizado para decidir qué se debe hacer. |
| [getParentType](#getParentType--) | La imagen guardada puede pertenecer al propio HTML o puede ser extraída de SVG incrustado en HTML. Esta propiedad puede indicar al código personalizado cuál es el tipo de elemento padre de la imagen procesada. Es establecida por el convertidor y puede ser usada en código personalizado para decidir qué se debe hacer con esa imagen (p. ej., el código personalizado puede decidir dónde guardar la imagen o cómo debe referenciarse en el contenido del padre). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Indica al código personalizado a qué página del documento PDF original corresponde la imagen guardada. Dado que es posible que no se guarden todas las páginas del documento original, este valor indica el número de página de origen en el PDF original. Si por alguna razón el número de página original es desconocido, siempre devuelve '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Indica al código personalizado a qué página del conjunto generado de archivos HTML corresponde la imagen guardada. Si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una página HTML. |
| [setImageType](#setImageType-int-) | Representa el tipo de imagen guardada referenciada en HTML. Establecido por el convertidor y puede ser usado en código personalizado para decidir qué se debe hacer. |
| [setParentType](#setParentType-int-) | La imagen guardada puede pertenecer al propio HTML o puede ser extraída de SVG incrustado en HTML. Esta propiedad puede indicar al código personalizado cuál es el tipo de elemento padre de la imagen procesada. Es establecida por el convertidor y puede ser usada en código personalizado para decidir qué se debe hacer con esa imagen (p. ej., el código personalizado puede decidir dónde guardar la imagen o cómo debe referenciarse en el contenido del padre). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Indica al código personalizado a qué página del documento PDF original corresponde la imagen guardada. Dado que es posible que no se guarden todas las páginas del documento original, este valor indica el número de página de origen en el PDF original. Si por alguna razón el número de página original es desconocido, siempre devuelve '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

crea una nueva instancia de HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Indica al código personalizado a qué página del conjunto generado de archivos HTML corresponde la imagen guardada. Si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una página HTML.

**Returns:**
valor int

### getImageType {#getImageType--}
```
public int getImageType()
```

Representa el tipo de imagen guardada referenciada en HTML. Establecido por el convertidor y puede ser usado en código personalizado para decidir qué se debe hacer.

**Returns:**
elemento HtmlImageType @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

La imagen guardada puede pertenecer al propio HTML o puede ser extraída de SVG incrustado en HTML. Esta propiedad puede indicar al código personalizado cuál es el tipo de elemento padre de la imagen procesada. Es establecida por el convertidor y puede ser usada en código personalizado para decidir qué se debe hacer con esa imagen (p. ej., el código personalizado puede decidir dónde guardar la imagen o cómo debe referenciarse en el contenido del padre).

**Returns:**
elemento ImageParentTypes @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Indica al código personalizado a qué página del documento PDF original corresponde la imagen guardada. Dado que es posible que no se guarden todas las páginas del documento original, este valor indica el número de página de origen en el PDF original. Si por alguna razón el número de página original es desconocido, siempre devuelve '1'.

**Returns:**
valor int

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Indica al código personalizado a qué página del conjunto generado de archivos HTML corresponde la imagen guardada. Si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una página HTML.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlHostPageNumber |  | valor int |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Representa el tipo de imagen guardada referenciada en HTML. Establecido por el convertidor y puede ser usado en código personalizado para decidir qué se debe hacer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageType |  | elemento HtmlImageType @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

La imagen guardada puede pertenecer al propio HTML o puede ser extraída de SVG incrustado en HTML. Esta propiedad puede indicar al código personalizado cuál es el tipo de elemento padre de la imagen procesada. Es establecida por el convertidor y puede ser usada en código personalizado para decidir qué se debe hacer con esa imagen (p. ej., el código personalizado puede decidir dónde guardar la imagen o cómo debe referenciarse en el contenido del padre).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parentType |  | elemento ImageParentTypes @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Indica al código personalizado a qué página del documento PDF original corresponde la imagen guardada. Dado que es posible que no se guarden todas las páginas del documento original, este valor indica el número de página de origen en el PDF original. Si por alguna razón el número de página original es desconocido, siempre devuelve '1'.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfHostPageNumber |  | valor int |
