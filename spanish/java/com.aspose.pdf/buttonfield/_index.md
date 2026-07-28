---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un campo de botón pulsador."
type: docs
weight: 440
url: /es/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Clase que representa un campo de botón pulsador.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ButtonField](#ButtonField--) | Constructor del campo de botón para Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor del campo de botón para Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor del campo de botón para Generator. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Agrega una imagen a los recursos del campo y la dibuja. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Agrega una imagen a los recursos del campo y la dibuja. |
| [getAlternateCaption](#getAlternateCaption--) | Obtiene el título alternativo del botón que se mostrará cuando se presione el botón del ratón dentro de su área activa. |
| [getAlternateIcon](#getAlternateIcon--) | Obtiene el ícono alternativo que se mostrará cuando se presione el botón del ratón dentro de su área activa. |
| [getIconFit](#getIconFit--) | Obtiene el objeto de ajuste de ícono que especifica cómo se mostrará el ícono de la anotación de widget dentro de su rectángulo de anotación. |
| [getICPosition](#getICPosition--) | Obtiene la posición del título del ícono. |
| [getNormalCaption](#getNormalCaption--) | Obtiene el título normal. |
| [getNormalIcon](#getNormalIcon--) | Obtiene el ícono normal del botón que se mostrará cuando no esté interactuando con el usuario. |
| [getRolloverCaption](#getRolloverCaption--) | Obtiene el título de desplazamiento del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón. |
| [getRolloverIcon](#getRolloverIcon--) | Obtiene el ícono de desplazamiento del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Establece el título alternativo del botón que se mostrará cuando se presione el botón del ratón dentro de su área activa. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Establece el ícono alternativo que se mostrará cuando se presione el botón del ratón dentro de su área activa. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Establece la posición del título del ícono. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Establece el título normal. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Establece el ícono normal del botón que se mostrará cuando no esté interactuando con el usuario. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Establece el título de desplazamiento del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Establece el ícono de rollover del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Constructor del campo de botón para Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructor del campo de botón para Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor del campo de botón para Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Agrega una imagen a los recursos del campo y la dibuja.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Agrega una imagen a los recursos del campo y la dibuja.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Obtiene el título alternativo del botón que se mostrará cuando se presione el botón del ratón dentro de su área activa.

**Returns:**
valor String

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Obtiene el ícono alternativo que se mostrará cuando se presione el botón del ratón dentro de su área activa.

**Returns:**
objeto XForm

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Obtiene el objeto de ajuste de ícono que especifica cómo se mostrará el ícono de la anotación de widget dentro de su rectángulo de anotación.

**Returns:**
Objeto IconFit

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Obtiene la posición del título del ícono.

**Returns:**
posición del subtítulo del ícono. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Obtiene el título normal.

**Returns:**
valor String

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Obtiene el ícono normal del botón que se mostrará cuando no esté interactuando con el usuario.

**Returns:**
objeto XForm

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Obtiene el título de desplazamiento del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón.

**Returns:**
valor String

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Obtiene el ícono de desplazamiento del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón.

**Returns:**
objeto XForm

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Establece el título alternativo del botón que se mostrará cuando se presione el botón del ratón dentro de su área activa.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Establece el ícono alternativo que se mostrará cuando se presione el botón del ratón dentro de su área activa.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Establece la posición del título del ícono.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Establece el título normal.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Establece el ícono normal del botón que se mostrará cuando no esté interactuando con el usuario.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Establece el título de desplazamiento del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Establece el ícono de rollover del botón que se mostrará cuando el usuario desplace el cursor a su área activa sin presionar el botón del ratón.
