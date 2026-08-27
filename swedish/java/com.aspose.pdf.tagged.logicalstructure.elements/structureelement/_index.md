---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en basklass för strukturelement i logisk struktur."
type: docs
weight: 110
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Representerar en basklass för strukturelement i logisk struktur.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Ändra förälderelement för aktuellt struktur-element. |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Ändra förälderelement för aktuellt struktur-element. |
| [clearId](#clearId--) | Rensa ID för struktur-elementet. |
| [generateId](#generateId--) | Generera ID för struktur-elementet. |
| [getActualText](#getActualText--) | Hämtar eller anger den faktiska texten för struktur-elementet. |
| [getAlternativeText](#getAlternativeText--) | Hämtar eller anger alternativ text för struktur-elementet. |
| [getAttributes](#getAttributes--) | Hämtar {@code StructureAttributeCollection}-objektet. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Hämtar {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-objektet. Värde: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-objektet. |
| [getExpansionText](#getExpansionText--) | Hämtar eller anger expansionstexten för struktur-elementet. |
| [getID](#getID--) | Hämtar ID för struktur-elementet. Värde: ID för struktur-elementet. |
| [getLanguage](#getLanguage--) | Hämtar eller anger språket för struktur-elementet. |
| [getPage](#getPage--) | Hämtar sidan där några eller alla underordnade element kommer att renderas. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Hämtar typ av strukturelement. |
| [getTitle](#getTitle--) | Hämtar eller anger titeln för strukturelement. |
| [remove](#remove--) | Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, det motsvarande objektet från dokumentet. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt och det motsvarande objektet från dokumentet. Infogar barnobjekt från det borttagna objektet i dess tidigare förälders barnobjektssamling med start vid indexet för det borttagna objektet. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt och det motsvarande objektet från dokumentet. Infogar barnobjekt från det borttagna objektet i dess tidigare förälders barnobjektssamling med start vid indexet för det borttagna objektet. |
| [setActualText](#setActualText-java.lang.String-) | Hämtar eller anger den faktiska texten för struktur-elementet. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Hämtar eller anger alternativ text för struktur-elementet. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Hämtar eller anger expansionstexten för struktur-elementet. |
| [setId](#setId-java.lang.String-) | Anger ID för strukturelement. |
| [setLanguage](#setLanguage-java.lang.String-) | Hämtar eller anger språket för struktur-elementet. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | sätt Parent Element |
| [setTag](#setTag-java.lang.String-) | Anger anpassad tagg för strukturelement. |
| [setTitle](#setTitle-java.lang.String-) | Hämtar eller anger titeln för strukturelement. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Koppla ett strukturelement till Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Koppla ett strukturelement till Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Koppla ett strukturelement till innehållsströmmen BDC-operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Koppla ett strukturelement till innehållsströmmen XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Koppla ett strukturelement till XImage. |
| [toString](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Ändra förälderelement för aktuellt struktur-element.

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Ändra förälderelement för aktuellt struktur-element.

### clearId {#clearId--}
```
public final void clearId()
```

Rensa ID för struktur-elementet.

### generateId {#generateId--}
```
public final void generateId()
```

Generera ID för struktur-elementet.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Hämtar eller anger den faktiska texten för struktur-elementet.

**Returns:**
Värde: Faktisk text för strukturelementet.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Hämtar eller anger alternativ text för struktur-elementet.

**Returns:**
Värde: Alternativ text för strukturelementet.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Hämtar {@code StructureAttributeCollection}-objektet.

**Returns:**
{@code StructureAttributeCollection} objekt.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Hämtar {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-objektet. Värde: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-objektet.

**Returns:**
AttributeOwnerStandard-instans

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Hämtar eller anger expansionstexten för struktur-elementet.

**Returns:**
Värde: Expansionstext för strukturelementet.

### getID {#getID--}
```
public final String getID()
```

Hämtar ID för struktur-elementet. Värde: ID för struktur-elementet.

**Returns:**
String värde

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Hämtar eller anger språket för struktur-elementet.

**Returns:**
Värde: Språk för strukturelementet.

### getPage {#getPage--}
```
public final Page getPage()
```

Hämtar sidan där några eller alla underordnade element kommer att renderas.

**Returns:**
Page-instans

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Hämtar typ av strukturelement.

**Returns:**
Värde: {@code StructureTypeStandard} objekt för strukturelementet.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Hämtar eller anger titeln för strukturelement.

**Returns:**
Värde: Titel för strukturelementet.

### remove {#remove--}
```
public final void remove()
```

Tar bort: ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt, det motsvarande objektet från dokumentet.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt och det motsvarande objektet från dokumentet. Infogar barnobjekt från det borttagna objektet i dess tidigare förälders barnobjektssamling med start vid indexet för det borttagna objektet.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Tar bort ett element från strukturen, en referens till det från föräldraobjektet, referenser till det från barnobjekt och det motsvarande objektet från dokumentet. Infogar barnobjekt från det borttagna objektet i dess tidigare förälders barnobjektssamling med start vid indexet för det borttagna objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Kontrollera om barnobjekt från det borttagna objektet kan infogas i dess förälders samling av barnobjekt. |

### setActualText {#setActualText-java.lang.String-}
Hämtar eller anger den faktiska texten för struktur-elementet.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Hämtar eller anger alternativ text för struktur-elementet.

### setExpansionText {#setExpansionText-java.lang.String-}
Hämtar eller anger expansionstexten för struktur-elementet.

### setId {#setId-java.lang.String-}
Anger ID för strukturelement.

### setLanguage {#setLanguage-java.lang.String-}
Hämtar eller anger språket för struktur-elementet.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
sätt Parent Element

### setTag {#setTag-java.lang.String-}
Anger anpassad tagg för strukturelement.

### setTitle {#setTitle-java.lang.String-}
Hämtar eller anger titeln för strukturelement.

### tag {#tag-com.aspose.pdf.Annotation-}
Koppla ett strukturelement till Annotation.

### tag {#tag-com.aspose.pdf.Artifact-}
Koppla ett strukturelement till Artifact.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Koppla ett strukturelement till innehållsströmmen BDC-operator.

### tag {#tag-com.aspose.pdf.XForm-}
Koppla ett strukturelement till innehållsströmmen XForm.

### tag {#tag-com.aspose.pdf.XImage-}
Koppla ett strukturelement till XImage.

### toString {#toString--}
```
public String toString()
```

Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
Sträng som representerar det aktuella objektet.
