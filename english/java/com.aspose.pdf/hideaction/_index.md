---
title: HideAction
second_title: Aspose.PDF for Java API Reference
description: Represents a hide action that hides or shows one or more annotations on the screen by setting or clearing their Hidden flags.
type: docs
weight: 152
url: /java/com.aspose.pdf/hideaction/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public class HideAction extends PdfAction
```

Represents a hide action that hides or shows one or more annotations on the screen by setting or clearing their Hidden flags.
## Constructors

| Constructor | Description |
| --- | --- |
| [HideAction(Annotation annotation)](#HideAction-com.aspose.pdf.Annotation-) | Initializes a new instance of the  HideAction  class for the specified annotation. |
| [HideAction(Annotation annotation, boolean isHidden)](#HideAction-com.aspose.pdf.Annotation-boolean-) | Initializes a new instance of the  HideAction  class for the specified annotation and invisibility flag. |
| [HideAction(String fieldName)](#HideAction-java.lang.String-) | Initializes a new instance of the  HideAction  class for the specified field name. |
| [HideAction(String fieldName, boolean isHidden)](#HideAction-java.lang.String-boolean-) | Initializes a new instance of the  HideAction  class for the specified field name and invisibility flag. |
| [HideAction(Annotation[] annotations)](#HideAction-com.aspose.pdf.Annotation---) | Initializes a new instance of the  HideAction  class for the specified annotations. |
| [HideAction(Annotation[] annotations, boolean isHidden)](#HideAction-com.aspose.pdf.Annotation---boolean-) | Initializes a new instance of the  HideAction  class for the specified annotations and for invisibility flag. |
| [HideAction(String[] names)](#HideAction-java.lang.String---) | Initializes a new instance of the  HideAction  class for the specified field names. |
| [HideAction(String[] names, boolean isHidden)](#HideAction-java.lang.String---boolean-) | Initializes a new instance of the  HideAction  class for the specified field names and for invisibility flag. |
## Methods

| Method | Description |
| --- | --- |
| [isHidden()](#isHidden--) | Gets or sets status of the annotation(s) to hide/display. |
| [setHidden(boolean value)](#setHidden-boolean-) | Gets or sets status of the annotation(s) to hide/display. |
### HideAction(Annotation annotation) {#HideAction-com.aspose.pdf.Annotation-}
```
public HideAction(Annotation annotation)
```


Initializes a new instance of the  HideAction  class for the specified annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | An annotation to be hidden. |

### HideAction(Annotation annotation, boolean isHidden) {#HideAction-com.aspose.pdf.Annotation-boolean-}
```
public HideAction(Annotation annotation, boolean isHidden)
```


Initializes a new instance of the  HideAction  class for the specified annotation and invisibility flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | An annotation to be hidden or shown. |
| isHidden | boolean | A flag indicating whether to hide the annotation (true) or show it (false). |

### HideAction(String fieldName) {#HideAction-java.lang.String-}
```
public HideAction(String fieldName)
```


Initializes a new instance of the  HideAction  class for the specified field name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | A text string giving the fully qualified field name of an interactive form field. |

### HideAction(String fieldName, boolean isHidden) {#HideAction-java.lang.String-boolean-}
```
public HideAction(String fieldName, boolean isHidden)
```


Initializes a new instance of the  HideAction  class for the specified field name and invisibility flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | A text string giving the fully qualified field name of an interactive form field. |
| isHidden | boolean | A flag indicating whether to hide the field (true) or show it (false). |

### HideAction(Annotation[] annotations) {#HideAction-com.aspose.pdf.Annotation---}
```
public HideAction(Annotation[] annotations)
```


Initializes a new instance of the  HideAction  class for the specified annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotations | [Annotation\[\]](../../com.aspose.pdf/annotation) | An array of annotations to be hidden. |

### HideAction(Annotation[] annotations, boolean isHidden) {#HideAction-com.aspose.pdf.Annotation---boolean-}
```
public HideAction(Annotation[] annotations, boolean isHidden)
```


Initializes a new instance of the  HideAction  class for the specified annotations and for invisibility flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotations | [Annotation\[\]](../../com.aspose.pdf/annotation) | An array of annotations to be hidden or shown. |
| isHidden | boolean | A flag indicating whether to hide the annotations (true) or show it (false). |

### HideAction(String[] names) {#HideAction-java.lang.String---}
```
public HideAction(String[] names)
```


Initializes a new instance of the  HideAction  class for the specified field names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| names | java.lang.String[] | An array of strings giving the fully qualified field names of an interactive form fields. |

### HideAction(String[] names, boolean isHidden) {#HideAction-java.lang.String---boolean-}
```
public HideAction(String[] names, boolean isHidden)
```


Initializes a new instance of the  HideAction  class for the specified field names and for invisibility flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| names | java.lang.String[] | An array of strings giving the fully qualified field names of an interactive form fields. |
| isHidden | boolean | A flag indicating whether to hide the fields (true) or show it (false). |

### isHidden() {#isHidden--}
```
public boolean isHidden()
```


Gets or sets status of the annotation(s) to hide/display.

**Returns:**
boolean - boolean value
### setHidden(boolean value) {#setHidden-boolean-}
```
public void setHidden(boolean value)
```


Gets or sets status of the annotation(s) to hide/display.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

