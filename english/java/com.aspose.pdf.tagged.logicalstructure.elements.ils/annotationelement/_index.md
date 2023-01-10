---
title: AnnotationElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for annotation structure elements in logical structure.
type: docs
weight: 11
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.ils/annotationelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.ils/ilselement)
```
public abstract class AnnotationElement extends ILSElement
```

Represents a base class for annotation structure elements in logical structure.
## Methods

| Method | Description |
| --- | --- |
| [getAnnotations()](#getAnnotations--) |  |
| [getAlternateDescriptions()](#getAlternateDescriptions--) | Gets or Sets the Alternate Descriptions for annotation. |
| [setAlternateDescriptions(String value)](#setAlternateDescriptions-java.lang.String-) | Gets or Sets the Alternate Descriptions for annotation. |
### getAnnotations() {#getAnnotations--}
```
public final System.Collections.Generic.List<Annotation> getAnnotations()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Annotation>
### getAlternateDescriptions() {#getAlternateDescriptions--}
```
public final String getAlternateDescriptions()
```


Gets or Sets the Alternate Descriptions for annotation. Text that shall be displayed for the annotation or, if this type of annotation does not display text, an alternate description of the annotation's contents in human-readable form.

**Returns:**
java.lang.String - String value
### setAlternateDescriptions(String value) {#setAlternateDescriptions-java.lang.String-}
```
public final void setAlternateDescriptions(String value)
```


Gets or Sets the Alternate Descriptions for annotation. Text that shall be displayed for the annotation or, if this type of annotation does not display text, an alternate description of the annotation's contents in human-readable form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

