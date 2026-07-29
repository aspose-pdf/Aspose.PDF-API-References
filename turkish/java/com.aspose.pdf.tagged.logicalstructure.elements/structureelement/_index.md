---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mantıksal yapıda yapı öğeleri için temel bir sınıfı temsil eder."
type: docs
weight: 110
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Mantıksal yapıda yapı öğeleri için temel bir sınıfı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Mevcut yapı öğesi için üst öğeyi değiştir |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Mevcut yapı öğesi için üst öğeyi değiştir |
| [clearId](#clearId--) | Yapı öğesi için kimliği temizle. |
| [generateId](#generateId--) | Yapı öğesi için kimlik oluştur. |
| [getActualText](#getActualText--) | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [getAlternativeText](#getAlternativeText--) | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [getAttributes](#getAttributes--) | Alır {@code StructureAttributeCollection} nesnesini. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Alır {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} nesnesi. Değer: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} nesnesi. |
| [getExpansionText](#getExpansionText--) | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [getID](#getID--) | Yapı öğesi için kimliği alır. Değer: yapı öğesinin kimliği. |
| [getLanguage](#getLanguage--) | Yapı öğesi için dili alır veya ayarlar. |
| [getPage](#getPage--) | Bazı veya tüm alt öğelerin render edileceği sayfayı alır. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Yapı öğesinin tipini alır. |
| [getTitle](#getTitle--) | Yapı öğesi için başlığı alır veya ayarlar. |
| [remove](#remove--) | Kaldırır: yapının bir öğesini, üst nesneden ona olan referansı, alt nesnelerden ona olan referansları, belgedeki ilgili nesneyi. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Yapıdan bir öğeyi, üst nesneden ona olan referansı, alt nesnelerden ona olan referansları ve belgedeki ilgili nesneyi kaldırır. Kaldırılan nesnenin alt nesnelerini, kaldırılan nesnenin indeksinden başlayarak eski üst nesnenin alt nesne koleksiyonuna ekler. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Yapıdan bir öğeyi, üst nesneden ona olan referansı, alt nesnelerden ona olan referansları ve belgedeki ilgili nesneyi kaldırır. Kaldırılan nesnenin alt nesnelerini, kaldırılan nesnenin indeksinden başlayarak eski üst nesnenin alt nesne koleksiyonuna ekler. |
| [setActualText](#setActualText-java.lang.String-) | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [setId](#setId-java.lang.String-) | Yapı öğesi için kimliği ayarlar. |
| [setLanguage](#setLanguage-java.lang.String-) | Yapı öğesi için dili alır veya ayarlar. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Üst Öğeyi ayarla |
| [setTag](#setTag-java.lang.String-) | Yapı öğesi için özel etiket ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | Yapı öğesi için başlığı alır veya ayarlar. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Bir yapı öğesini Açıklamaya bağlayın. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Bir yapı öğesini Artefakte bağlayın. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Bir yapı öğesini içerik akışı BDC operatörüne bağlayın. |
| [tag](#tag-com.aspose.pdf.XForm-) | Bir yapı öğesini içerik akışı XForm'a bağlayın. |
| [tag](#tag-com.aspose.pdf.XImage-) | Bir yapı öğesini XImage'e bağlayın. |
| [toString](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Mevcut yapı öğesi için üst öğeyi değiştir

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Mevcut yapı öğesi için üst öğeyi değiştir

### clearId {#clearId--}
```
public final void clearId()
```

Yapı öğesi için kimliği temizle.

### generateId {#generateId--}
```
public final void generateId()
```

Yapı öğesi için kimlik oluştur.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Yapı öğesi için gerçek metni alır veya ayarlar.

**Returns:**
Değer: Yapı öğesinin gerçek metni.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Yapı öğesi için alternatif metni alır veya ayarlar.

**Returns:**
Değer: Yapı öğesinin alternatif metni.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Alır {@code StructureAttributeCollection} nesnesini.

**Returns:**
{@code StructureAttributeCollection} nesnesi.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Alır {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} nesnesi. Değer: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} nesnesi.

**Returns:**
AttributeOwnerStandard örneği

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Yapı öğesi için genişletme metnini alır veya ayarlar.

**Returns:**
Değer: Yapı öğesinin genişletme metni.

### getID {#getID--}
```
public final String getID()
```

Yapı öğesi için kimliği alır. Değer: yapı öğesinin kimliği.

**Returns:**
String değeri

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Yapı öğesi için dili alır veya ayarlar.

**Returns:**
Değer: Yapı öğesinin dili.

### getPage {#getPage--}
```
public final Page getPage()
```

Bazı veya tüm alt öğelerin render edileceği sayfayı alır.

**Returns:**
Sayfa örneği

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Yapı öğesinin tipini alır.

**Returns:**
Değer: {@code StructureTypeStandard} nesnesi yapı öğesine ait.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Yapı öğesi için başlığı alır veya ayarlar.

**Returns:**
Değer: Yapı öğesinin başlığı.

### remove {#remove--}
```
public final void remove()
```

Kaldırır: yapının bir öğesini, üst nesneden ona olan referansı, alt nesnelerden ona olan referansları, belgedeki ilgili nesneyi.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Yapıdan bir öğeyi, üst nesneden ona olan referansı, alt nesnelerden ona olan referansları ve belgedeki ilgili nesneyi kaldırır. Kaldırılan nesnenin alt nesnelerini, kaldırılan nesnenin indeksinden başlayarak eski üst nesnenin alt nesne koleksiyonuna ekler.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Yapıdan bir öğeyi, üst nesneden ona olan referansı, alt nesnelerden ona olan referansları ve belgedeki ilgili nesneyi kaldırır. Kaldırılan nesnenin alt nesnelerini, kaldırılan nesnenin indeksinden başlayarak eski üst nesnenin alt nesne koleksiyonuna ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Kaldırılan nesnenin alt nesnelerinin, üst nesnenin alt nesne koleksiyonuna eklenip eklenemeyeceğini kontrol eder. |

### setActualText {#setActualText-java.lang.String-}
Yapı öğesi için gerçek metni alır veya ayarlar.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Yapı öğesi için alternatif metni alır veya ayarlar.

### setExpansionText {#setExpansionText-java.lang.String-}
Yapı öğesi için genişletme metnini alır veya ayarlar.

### setId {#setId-java.lang.String-}
Yapı öğesi için kimliği ayarlar.

### setLanguage {#setLanguage-java.lang.String-}
Yapı öğesi için dili alır veya ayarlar.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Üst Öğeyi ayarla

### setTag {#setTag-java.lang.String-}
Yapı öğesi için özel etiket ayarlar.

### setTitle {#setTitle-java.lang.String-}
Yapı öğesi için başlığı alır veya ayarlar.

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
