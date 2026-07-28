---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página."
type: docs
weight: 570
url: /es/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página.

## Campos

| Campo | Descripción |
| --- | --- |
| [BLINDH](#BLINDH) | Persianas verticales |
| [BLINDV](#BLINDV) | Persianas verticales |
| [BTWIPE](#BTWIPE) | Desvanecimiento de abajo a arriba |
| [DGLITTER](#DGLITTER) | Brillo diagonal |
| [DISSOLVE](#DISSOLVE) | La página antigua se disuelve |
| [INBOX](#INBOX) | Caja interior |
| [LRGLITTER](#LRGLITTER) | Brillo de izquierda a derecha |
| [LRWIPE](#LRWIPE) | Desvanecimiento de izquierda a derecha |
| [OUTBOX](#OUTBOX) | Caja exterior |
| [RLWIPE](#RLWIPE) | Desvanecimiento de derecha a izquierda |
| [SPLITHIN](#SPLITHIN) | División horizontal EN |
| [SPLITHOUT](#SPLITHOUT) | División horizontal fuera |
| [SPLITVIN](#SPLITVIN) | División vertical EN |
| [SPLITVOUT](#SPLITVOUT) | División vertical fuera |
| [TBGLITTER](#TBGLITTER) | Brillo de arriba a abajo |
| [TBWIPE](#TBWIPE) | Desvanecimiento de arriba a abajo |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Constructor de la clase PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Constructor de la clase PdfPageEditor. |

## Métodos

| Método | Descripción |
| --- | --- |
| [applyChanges](#applyChanges--) | Aplicar los cambios realizados en las páginas del documento. |
| [getAlignment](#getAlignment--) | Obtiene la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. Use getHorizontalAlignment en su lugar |
| [getDisplayDuration](#getDisplayDuration--) | Obtiene la duración de visualización de las páginas. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Devuelve el tamaño de la caja especificada en el documento. </p> <hr> <pre> El siguiente ejemplo muestra cómo obtener la caja de medios de la primera página: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Devuelve el tamaño de la página. |
| [getPageRotation](#getPageRotation-int-) | <p> Devuelve la rotación de la página especificada. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Obtiene la rotación de las páginas, una tabla hash contiene el número de página y el grado de rotación, la clave representa el número de página, el valor de la clave representa la rotación en grados. </p> |
| [getPages](#getPages--) | <p> Devuelve el número total de páginas. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Obtiene el tamaño de página del archivo de salida. |
| [getPageSize](#getPageSize-int-) | <p> Devuelve el tamaño de página de la página especificada. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Obtiene los números de página que se editarán. Por defecto, cada página será editada. |
| [getRotation](#getRotation--) | Obtiene la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0. |
| [getTransitionDuration](#getTransitionDuration--) | Obtiene la duración del efecto de transición. |
| [getTransitionType](#getTransitionType--) | Obtiene el estilo de transición a usar al pasar a esta página desde otra durante una presentación. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. Use getVerticalAlignmentType en su lugar |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Obtiene la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Obtenga el coeficiente de zoom. El valor 1.0 corresponde al 100%. El valor predeterminado es 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Compruebe si el cuadro está definido en la página. |
| [movePosition](#movePosition-float-float-) | <p> Mueve el origen de (0, 0) al punto indicado. El origen está en la esquina inferior izquierda y la unidad es punto (1 pulgada = 72 puntos). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Guarda el documento modificado en un flujo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Guarda el documento modificado en un archivo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Establece la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. Use setHorizontalAlignment en su lugar |
| [setDisplayDuration](#setDisplayDuration-int-) | Establece la duración de visualización para las páginas. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Establece la rotación de las páginas, una tabla hash contiene el número de página y el grado de rotación, la clave representa el número de página, el valor de la clave representa la rotación en grados. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Establece el tamaño de página del archivo de salida. |
| [setProcessPages](#setProcessPages-int:A-) | Establece los números de página que se editarán. Por defecto, cada página será editada. |
| [setRotation](#setRotation-int-) | Establece la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Establece la duración del efecto de transición. |
| [setTransitionType](#setTransitionType-int-) | Establece el estilo de transición a usar al pasar a esta página desde otra durante una presentación. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Establece la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. Use setVerticalAlignmentType en su lugar |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Establece la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Establece el coeficiente de zoom. El valor 1.0 corresponde al 100 %. El valor predeterminado es 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Persianas verticales

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Persianas verticales

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Desvanecimiento de abajo a arriba

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Brillo diagonal

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

La página antigua se disuelve

### INBOX {#INBOX}
```
public static final int INBOX
```

Caja interior

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Brillo de izquierda a derecha

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Desvanecimiento de izquierda a derecha

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Caja exterior

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Desvanecimiento de derecha a izquierda

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

División horizontal EN

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

División horizontal fuera

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

División vertical EN

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

División vertical fuera

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Brillo de arriba a abajo

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Desvanecimiento de arriba a abajo

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Constructor de la clase PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Constructor de la clase PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Aplicar los cambios realizados en las páginas del documento.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Obtiene la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. Use getHorizontalAlignment en su lugar

**Returns:**
Objeto AlignmentType @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Obtiene la duración de visualización de las páginas.

**Returns:**
valor int

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtiene la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left.

**Returns:**
HorizontalAlignment elemento @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Devuelve el tamaño de la caja especificada en el documento. </p> <hr> <pre> El siguiente ejemplo muestra cómo obtener la caja de medios de la primera página: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Devuelve el tamaño de la página.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Devuelve la rotación de la página especificada. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página |  | Índice de página. Las páginas del documento se numeran a partir de 1. |

**Returns:**
Rotación de página en grados.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Obtiene la rotación de las páginas, una tabla hash contiene el número de página y el grado de rotación, la clave representa el número de página, el valor de la clave representa la rotación en grados. </p>

**Returns:**
Objeto {@code Map<Integer, Integer>}

### getPages {#getPages--}
```
public int getPages()
```

<p> Devuelve el número total de páginas. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Número de páginas.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Obtiene el tamaño de página del archivo de salida.

**Returns:**
Objeto PageSize

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Devuelve el tamaño de página de la página especificada. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página |  | Índice de página. Las páginas del documento se numeran a partir de 1. |

**Returns:**
El resultado es una instancia de PageSize. Use las propiedades Width y Height del objeto devuelto para obtener el ancho y alto de la página.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Obtiene los números de página que se editarán. Por defecto, cada página será editada.

**Returns:**
matriz de valores int

### getRotation {#getRotation--}
```
public int getRotation()
```

Obtiene la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0.

**Returns:**
valor int

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Obtiene la duración del efecto de transición.

**Returns:**
valor int

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Obtiene el estilo de transición a usar al pasar a esta página desde otra durante una presentación.

**Returns:**
valor int

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Obtiene la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. Use getVerticalAlignmentType en su lugar

**Returns:**
Objeto VerticalAlignmentType

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Obtiene la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom.

**Returns:**
Elemento VerticalAlignmentType @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Obtenga el coeficiente de zoom. El valor 1.0 corresponde al 100%. El valor predeterminado es 1.0.

**Returns:**
valor flotante

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Compruebe si el cuadro está definido en la página.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Mueve el origen de (0, 0) al punto indicado. El origen está en la esquina inferior izquierda y la unidad es punto (1 pulgada = 72 puntos). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| moveX |  | Coordenada X. |
| moveY |  | Coordenada Y. |

### save {#save-java.io.OutputStream-}
<p> Guarda el documento modificado en un flujo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Guarda el documento modificado en un archivo. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Establece la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. Use setHorizontalAlignment en su lugar

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Establece la duración de visualización para las páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Establece la rotación de las páginas, una tabla hash contiene el número de página y el grado de rotación, la clave representa el número de página, el valor de la clave representa la rotación en grados.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Establece el tamaño de página del archivo de salida.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Establece los números de página que se editarán. Por defecto, cada página será editada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de valores int |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Establece la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Establece la duración del efecto de transición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Establece el estilo de transición a usar al pasar a esta página desde otra durante una presentación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Establece la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. Use setVerticalAlignmentType en su lugar

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Establece la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Establece el coeficiente de zoom. El valor 1.0 corresponde al 100 %. El valor predeterminado es 1.0. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor float <hr> <pre> El siguiente ejemplo muestra cómo cambiar el zoom de las páginas del documento. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
