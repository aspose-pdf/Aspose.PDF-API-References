---
title: TeXFragment
second_title: Aspose.PDF for Java API Reference
description: Represents LaTeX fragment.
type: docs
weight: 359
url: /java/com.aspose.pdf/texfragment/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment)
```
public class TeXFragment extends FormattedFragment
```

Represents LaTeX fragment.
## Constructors

| Constructor | Description |
| --- | --- |
| [TeXFragment(String text)](#TeXFragment-java.lang.String-) | Initializes a new instance of the HtmlFragment class. |
| [TeXFragment(String text, boolean removeIndents)](#TeXFragment-java.lang.String-boolean-) | Initializes a new instance of the HtmlFragment class. |
## Methods

| Method | Description |
| --- | --- |
| [getTeXLoadOptionsOfInstance()](#getTeXLoadOptionsOfInstance--) | Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [setTeXLoadOptionsOfInstance(TeXLoadOptions value)](#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | Gets or sets LatexLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [getLatexLoadOptionsOfInstance()](#getLatexLoadOptionsOfInstance--) | Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [setLatexLoadOptionsOfInstance(TeXLoadOptions value)](#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. |
| [deepClone()](#deepClone--) | Clones fragment. |
### TeXFragment(String text) {#TeXFragment-java.lang.String-}
```
public TeXFragment(String text)
```


Initializes a new instance of the HtmlFragment class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text |

### TeXFragment(String text, boolean removeIndents) {#TeXFragment-java.lang.String-boolean-}
```
public TeXFragment(String text, boolean removeIndents)
```


Initializes a new instance of the HtmlFragment class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The fragment text |
| removeIndents | boolean | Determines whether not to make indents while typesetting LaTeX fragment |

### getTeXLoadOptionsOfInstance() {#getTeXLoadOptionsOfInstance--}
```
public TeXLoadOptions getTeXLoadOptionsOfInstance()
```


Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Returns:**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - TeXLoadOptions instance
### setTeXLoadOptionsOfInstance(TeXLoadOptions value) {#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public void setTeXLoadOptionsOfInstance(TeXLoadOptions value)
```


Gets or sets LatexLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | TeXLoadOptions instance |

### getLatexLoadOptionsOfInstance() {#getLatexLoadOptionsOfInstance--}
```
public final TeXLoadOptions getLatexLoadOptionsOfInstance()
```


Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Returns:**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - TeXLoadOptions instance
### setLatexLoadOptionsOfInstance(TeXLoadOptions value) {#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public final void setLatexLoadOptionsOfInstance(TeXLoadOptions value)
```


Gets or sets TeXLoadOptions that will be used for loading (and rendering) of LaTeX into this instance of class. Please use it when it's necessary use specific setting for import of LaTeX for this or that instance (f.e when this or that instance should use specific BasePath for imported LaTeX or should use specific loader of external resources) If parameter is default (null), then standard LaTeX loading options will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | TeXLoadOptions instance |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones fragment.

**Returns:**
java.lang.Object - Cloned fragment.
