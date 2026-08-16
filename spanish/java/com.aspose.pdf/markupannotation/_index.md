---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase abstracta que representa una anotación de marcado."
type: docs
weight: 2870
url: /es/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Clase abstracta que representa una anotación de marcado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Constructor |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [clearState](#clearState--) | Borra el estado y el modelo de estado de la anotación. Por ejemplo, borra el estado de revisión de una anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [getCreationDate](#getCreationDate--) | Obtiene la fecha y hora en que se creó la anotación. |
| [getInReplyTo](#getInReplyTo--) | Una referencia a la anotación a la que esta anotación está "en respuesta a". Ambas anotaciones deben estar en la misma página del documento. |
| [getOpacity](#getOpacity--) | Obtiene el valor de opacidad constante que se usará al pintar la anotación. |
| [getPopup](#getPopup--) | Anotación emergente para ingresar o editar el texto asociado a esta anotación. |
| [getReplyType](#getReplyType--) | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y la especificada por InReplyTo. |
| [getRichText](#getRichText--) | Obtiene una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Obtiene una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [getState](#getState--) | Obtiene el estado de la anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [getStateModel](#getStateModel--) | Obtiene el modelo de estado de la anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [getSubject](#getSubject--) | Obtiene el texto que representa la descripción del objeto. |
| [getTitle](#getTitle--) | Obtiene una etiqueta de texto que se mostrará en la barra de título de la ventana emergente de la anotaciónпїЅs cuando esté abierta y activa. Esta entrada debe identificar al usuario que añadió la anotación. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Obtiene la fecha y hora en que se creó la anotación. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Una referencia a la anotación a la que esta anotación está "en respuesta a". Ambas anotaciones deben estar en la misma página del documento. |
| [setMarkedState](#setMarkedState-boolean-) | Establece el estado Marked y Unmarked para la anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [setOpacity](#setOpacity-double-) | Establece el valor de opacidad constante que se usará al pintar la anotación. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Anotación emergente para ingresar o editar el texto asociado a esta anotación. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y la especificada por InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Establece el estado de revisión para una anotación. Los estados Marked y Unmarked se ignoran ya que no pertenecen al Review StateModel. El estado lo establece el usuario que creó la anotación objetivo. El valor se toma de la propiedad Title de la anotación objetivo. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Establece el estado de revisión para una anotación. Los estados Marked y Unmarked se ignoran ya que no pertenecen al Review StateModel. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [setRichText](#setRichText-java.lang.String-) | Establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [setSubject](#setSubject-java.lang.String-) | Establece el texto que representa la descripción del objeto. |
| [setTitle](#setTitle-java.lang.String-) | Establece una etiqueta de texto que se mostrará en la barra de título de la ventana emergente de la anotaciónпїЅs cuando esté abierta y activa. Esta entrada debe identificar al usuario que añadió la anotación. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Constructor

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Constructor

### clearState {#clearState--}
```
public final void clearState()
```

Borra el estado y el modelo de estado de la anotación. Por ejemplo, borra el estado de revisión de una anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtiene la fecha y hora en que se creó la anotación.

**Returns:**
Objeto Date

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Una referencia a la anotación a la que esta anotación está "en respuesta a". Ambas anotaciones deben estar en la misma página del documento.

**Returns:**
Valor de anotación

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtiene el valor de opacidad constante que se usará al pintar la anotación.

**Returns:**
valor double

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Anotación emergente para ingresar o editar el texto asociado a esta anotación.

**Returns:**
Valor de PopupAnnotation

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y la especificada por InReplyTo.

**Returns:**
valor de ReplyType @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Obtiene una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación.

**Returns:**
valor String

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Obtiene una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación.

**Returns:**
valor String

### getState {#getState--}
```
public final AnnotationState getState()
```

Obtiene el estado de la anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

**Returns:**
Estado de anotación.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Obtiene el modelo de estado de la anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

**Returns:**
Modelo de estado de anotación.

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtiene el texto que representa la descripción del objeto.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtiene una etiqueta de texto que se mostrará en la barra de título de la ventana emergente de la anotaciónпїЅs cuando esté abierta y activa. Esta entrada debe identificar al usuario que añadió la anotación.

**Returns:**
valor String

### setCreationDate {#setCreationDate-java.util.Date-}
Obtiene la fecha y hora en que se creó la anotación.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Una referencia a la anotación a la que esta anotación está "en respuesta a". Ambas anotaciones deben estar en la misma página del documento.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Establece el estado Marked y Unmarked para la anotación. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| marcado |  | Verdadero si establece el estado Marcado, y falso si establece el estado No marcado. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Establece el valor de opacidad constante que se usará al pintar la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Anotación emergente para ingresar o editar el texto asociado a esta anotación.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y la especificada por InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Establece el estado de revisión para una anotación. Los estados Marked y Unmarked se ignoran ya que no pertenecen al Review StateModel. El estado lo establece el usuario que creó la anotación objetivo. El valor se toma de la propiedad Title de la anotación objetivo. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Establece el estado de revisión para una anotación. Los estados Marked y Unmarked se ignoran ya que no pertenecen al Review StateModel. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

### setRichText {#setRichText-java.lang.String-}
Establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación.

### setSubject {#setSubject-java.lang.String-}
Establece el texto que representa la descripción del objeto.

### setTitle {#setTitle-java.lang.String-}
Establece una etiqueta de texto que se mostrará en la barra de título de la ventana emergente de la anotaciónпїЅs cuando esté abierta y activa. Esta entrada debe identificar al usuario que añadió la anotación.
