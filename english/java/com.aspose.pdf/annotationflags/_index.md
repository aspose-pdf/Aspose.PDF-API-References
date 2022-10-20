---
title: AnnotationFlags
second_title: Aspose.PDF for Java API Reference
description: A set of flags specifying various characteristics of the annotation.
type: docs
weight: 18
url: /java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnnotationFlags extends System.Enum
```

A set of flags specifying various characteristics of the annotation.
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Default value. |
| [Invisible](#Invisible) | If set, do not display the annotation if it does not belong to one of the standard annotation types and no annotation handler is available. |
| [Hidden](#Hidden) | If set, do not display or print the annotation or allow it to interact with the user, regardless of its annotation type or whether an annotation handler is available. |
| [Print](#Print) | If set, print the annotation when the page is printed. |
| [NoZoom](#NoZoom) | If set, do not scale the annotation's appearance to match the magnification of the page. |
| [NoRotate](#NoRotate) | If set, do not rotate the annotation's appearance to match the rotation of the page. |
| [NoView](#NoView) | If set, do not display the annotation on the screen or allow it to interact with the user. |
| [ReadOnly](#ReadOnly) | If set, do not allow the annotation to interact with the user. |
| [Locked](#Locked) | If set, do not allow the annotation to be deleted or its properties (including position and size) to be modified by the user. |
| [ToggleNoView](#ToggleNoView) | If set, invert the interpretation of the NoView flag for certain events. |
| [LockedContents](#LockedContents) | If set, do not allow the contents of the annotation to be modified by the user. |
### Default {#Default}
```
public static final int Default
```


Default value.

### Invisible {#Invisible}
```
public static final int Invisible
```


If set, do not display the annotation if it does not belong to one of the standard annotation types and no annotation handler is available. If clear, display such an unknown annotation using an appearance stream specified by its appearance dictionary, if any.

### Hidden {#Hidden}
```
public static final int Hidden
```


If set, do not display or print the annotation or allow it to interact with the user, regardless of its annotation type or whether an annotation handler is available. In cases where screen space is limited, the ability to hide and show annotations selectively can be used in combination with appearance streams to display auxiliary pop-up information similar in function to online help systems.

### Print {#Print}
```
public static final int Print
```


If set, print the annotation when the page is printed. If clear, never print the annotation, regardless of whether it is displayed on the screen. This can be useful, for example, for annotations representing interactive pushbuttons, which would serve no meaningful purpose on the printed page.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```


If set, do not scale the annotation's appearance to match the magnification of the page. The location of the annotation on the page (defined by the upper-left corner of its annotation rectangle) remains fixed, regardless of the page magnification.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```


If set, do not rotate the annotation's appearance to match the rotation of the page. The upper-left corner of the annotation rectangle remains in a fixed location on the page, regardless of the page rotation.

### NoView {#NoView}
```
public static final int NoView
```


If set, do not display the annotation on the screen or allow it to interact with the user. The annotation may be printed (depending on the setting of the Print flag) but should be considered hidden for purposes of on-screen display and user interaction.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


If set, do not allow the annotation to interact with the user. The annotation may be displayed or printed (depending on the settings of the NoView and Print flags) but should not respond to mouse clicks or change its appearance in response to mouse motions. This flag is ignored for widget annotations; its function is subsumed by the ReadOnly flag of the associated form field.

### Locked {#Locked}
```
public static final int Locked
```


If set, do not allow the annotation to be deleted or its properties (including position and size) to be modified by the user. However, this flag does not restrict changes to the annotation's contents, such as the value of a form field.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```


If set, invert the interpretation of the NoView flag for certain events. A typical use is to have an annotation that appears only when a mouse cursor is held over it.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```


If set, do not allow the contents of the annotation to be modified by the user. This flag does not restrict deletion of the annotation or changes to other annotation properties, such as position and size.

