---
title: AnnotationFlags
second_title: Aspose.PDF for Python via .NET API Reference
description: A set of flags specifying various characteristics of the annotation.
type: docs
weight: 930
url: /python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

A set of flags specifying various characteristics of the annotation.

## Members
| Member name | Description |
| :- | :- |
|DEFAULT|Default value.|
|INVISIBLE|If set, do not display the annotation if it does not belong to one of the standard annotation types<br/>            and no annotation handler is available. If clear, display such an unknown annotation<br/>            using an appearance stream specified by its appearance dictionary, if any.|
|HIDDEN|If set, do not display or print the annotation or allow it to interact with the user,<br/>            regardless of its annotation type or whether an annotation handler is available.<br/>            In cases where screen space is limited, the ability to hide and show annotations selectively<br/>            can be used in combination with appearance streams to display auxiliary pop-up information<br/>            similar in function to online help systems.|
|PRINT|If set, print the annotation when the page is printed. If clear, never print the annotation,<br/>            regardless of whether it is displayed on the screen. This can be useful, for example, for annotations<br/>            representing interactive pushbuttons, which would serve no meaningful purpose on the printed page.|
|NO_ZOOM|If set, do not scale the annotation�s appearance to match the magnification of the page.<br/>            The location of the annotation on the page (defined by the upper-left corner of its annotation rectangle)<br/>            remains fixed, regardless of the page magnification.|
|NO_ROTATE|If set, do not rotate the annotation�s appearance to match the rotation of the page.<br/>            The upper-left corner of the annotation rectangle remains in a fixed location on the page,<br/>            regardless of the page rotation.|
|NO_VIEW|If set, do not display the annotation on the screen or allow it to interact with the user.<br/>            The annotation may be printed (depending on the setting of the Print flag)<br/>            but should be considered hidden for purposes of on-screen display and user interaction.|
|READ_ONLY|If set, do not allow the annotation to interact with the user. The annotation may be displayed<br/>            or printed (depending on the settings of the NoView and Print flags) but should not respond to mouse<br/>            clicks or change its appearance in response to mouse motions. This flag is ignored for widget annotations;<br/>            its function is subsumed by the ReadOnly flag of the associated form field.|
|LOCKED|If set, do not allow the annotation to be deleted or its properties (including position and size)<br/>            to be modified by the user. However, this flag does not restrict changes to the annotation�s contents,<br/>            such as the value of a form field.|
|TOGGLE_NO_VIEW|If set, invert the interpretation of the NoView flag for certain events.<br/>            A typical use is to have an annotation that appears only when a mouse cursor is held over it.|
|LOCKED_CONTENTS|If set, do not allow the contents of the annotation to be modified by the user.<br/>            This flag does not restrict deletion of the annotation or changes to other annotation properties,<br/>            such as position and size.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

