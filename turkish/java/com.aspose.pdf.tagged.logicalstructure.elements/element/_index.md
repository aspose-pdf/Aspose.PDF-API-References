---
title: "Öğe"
linktitle: "Öğe"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mantıksal yapıda öğe için temel bir sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Mantıksal yapıda öğe için temel bir sınıfı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | {@code /Aspose.Pdf.LogicalStructure.Element} öğesini çocuk koleksiyonuna ekle. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | {@code /Aspose.Pdf.LogicalStructure.Element} öğesini çocuk koleksiyonuna ekle. |
| [clearChilds](#clearChilds--) | Tüm çocukları temizle. |
| [findElements](#findElements-java.lang.Class-) | Belirli bir türdeki Elemanları bul |
| [findElements](#findElements-java.lang.Class-boolean-) | Belirli bir türdeki Elemanları bul |
| [getChildElements](#getChildElements--) | {@code Element} nesnelerinin çocuk koleksiyonunu alır. |
| [getElementEngine](#getElementEngine--) | Üst öğeyi al. |
| [getParentElement](#getParentElement--) | {@code Element} nesnelerinin üst koleksiyonunu alır. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Dahili yöntem |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | {@code /Aspose.Pdf.LogicalStructure.Element} öğesini belirtilen indekste çocuk koleksiyonuna ekle. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | {@code /Aspose.Pdf.LogicalStructure.Element} öğesini belirtilen indekste çocuk koleksiyonuna ekle. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Belirtilen konumda çocuğu kaldır. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Bir yapı öğesini Açıklamaya bağlayın. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Bir yapı öğesini Artefakte bağlayın. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Bir yapı öğesini içerik akışı BDC operatörüne bağlayın. |
| [tag](#tag-com.aspose.pdf.XForm-) | Bir yapı öğesini içerik akışı XForm'a bağlayın. |
| [tag](#tag-com.aspose.pdf.XImage-) | Bir yapı öğesini XImage'e bağlayın. |
| [toString](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
{@code /Aspose.Pdf.LogicalStructure.Element} öğesini çocuk koleksiyonuna ekle.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
{@code /Aspose.Pdf.LogicalStructure.Element} öğesini çocuk koleksiyonuna ekle.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Tüm çocukları temizle.

### findElements {#findElements-java.lang.Class-}
Belirli bir türdeki Elemanları bul

### findElements {#findElements-java.lang.Class-boolean-}
Belirli bir türdeki Elemanları bul

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

{@code Element} nesnelerinin çocuk koleksiyonunu alır.

**Returns:**
Değer: {@code Element} nesnelerinin çocuk koleksiyonu.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Üst öğeyi al.

**Returns:**
Değer: Üst öğe.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

{@code Element} nesnelerinin üst koleksiyonunu alır.

**Returns:**
Değer: {@code Element} nesnelerinin üst koleksiyonu.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Dahili yöntem

**Returns:**
Dahili öğe

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
{@code /Aspose.Pdf.LogicalStructure.Element} öğesini belirtilen indekste çocuk koleksiyonuna ekle.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
{@code /Aspose.Pdf.LogicalStructure.Element} öğesini belirtilen indekste çocuk koleksiyonuna ekle.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Belirtilen konumda çocuğu kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Alt öğe indeksi. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Bir yapı öğesini Açıklamaya bağlayın.

### tag {#tag-com.aspose.pdf.Artifact-}
Bir yapı öğesini Artefakte bağlayın.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Bir yapı öğesini içerik akışı BDC operatörüne bağlayın.

### tag {#tag-com.aspose.pdf.XForm-}
Bir yapı öğesini içerik akışı XForm'a bağlayın.

### tag {#tag-com.aspose.pdf.XImage-}
Bir yapı öğesini XImage'e bağlayın.

### toString {#toString--}
```
public String toString()
```

Geçerli nesneyi temsil eden bir dize döndürür.

**Returns:**
Geçerli nesneyi temsil eden String.
