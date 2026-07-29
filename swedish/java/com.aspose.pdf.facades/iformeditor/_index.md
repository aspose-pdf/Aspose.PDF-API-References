---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att redigera formulär (lägga till/ta bort fält etc)"
type: docs
weight: 260
url: /sv/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Klass för att redigera formulär (lägga till/ta bort fält etc)

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Lägg till fält av angiven typ i formuläret. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Lägg till fält av angiven typ i formuläret. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Lägger till ett nytt objekt i listboxen. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Lägg till ett nytt objekt med Export value till det befintliga listboxfältet, endast för AcroForm combo box field. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Lägg till en skicka-knapp på formuläret. |
| [close](#close--) | Stänger objektet |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Kopierar ett befintligt fält till samma position på angivet sidnummer. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Kopierar ett befintligt fält till en ny position som anges av både sidnummer och koordinater. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med ursprungligt sidnummer och koordinater. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och ursprungliga koordinater. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och koordinater. |
| [decorateField](#decorateField--) | Ändrar visuella attribut för alla fält i PDF-dokumentet. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| [decorateField](#decorateField-java.lang.String-) | Ändrar visuella attribut för det angivna fältet. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Ta bort objekt från listfältet. |
| [dispose](#dispose--) | Stänger objektet |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [getDestFileName](#getDestFileName--) | Hämtar destinationsfilens namn. |
| [getDestStream](#getDestStream--) | Hämtar destinationsström. |
| [getDocument](#getDocument--) | Hämtar dokumentet som FormEditor arbetar med. |
| [getExportItems](#getExportItems--) | Hämtar alternativ för kombinationsruta med exportvärden. |
| [getFacade](#getFacade--) | Hämtar visuella attribut för fältet. |
| [getItems](#getItems--) | Returnerar objektarray |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till). |
| [getRadioGap](#getRadioGap--) | Hämta medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [getRadioHoriz](#getRadioHoriz--) | Hämta flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true. |
| [getSaveOptions](#getSaveOptions--) | Hämtar sparalternativ när resultatet lagras som HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Hämtar namn på källfilen. |
| [getSrcStream](#getSrcStream--) | Hämtar källström. |
| [getSubmitFlag](#getSubmitFlag--) | Hämta skicka-knappens inskickningsflaggor |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Ange ny position för fältet. |
| [removeField](#removeField-java.lang.String-) | Ta bort fältet från formuläret. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Ta bort skicka‑åtgärden för fältet. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Ändra namn på fältet. |
| [resetFacade](#resetFacade--) | Återställ alla visuella attribut till tomt värde. |
| [resetInnerFacade](#resetInnerFacade--) | Återställ alla visuella attribut för den inre fasaden till tomt värde. |
| [save](#save--) | Sparar ändringar i destinationsfilen. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Ställer in PdfFormat PDF‑filformat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Anger destinationsfilens namn. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Ställer in destinationsström. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Ställer in alternativ för kombinationsruta med exportvärden. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Ställer in visuella attribut för fältet. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Ange justeringsstil för ett textfält. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Ange vertikal justeringsstil för ett textfält. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Ange fältflaggor |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Ange attribut för fältet. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Ställer in antal fack för ett vanligt enradigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller fack, som värdet på parametern combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Ställer in maximalt teckenantal för textfältet. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Ange JavaScript för ett PushButton‑fält. |
| [setItems](#setItems-java.lang.String:A-) | Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till). |
| [setRadioGap](#setRadioGap-float-) | Ange medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Ställ in flaggan för att ange om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Ställer in namn på källfilen. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Ställer in källströmmen. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Ställ in skicka-flaggan för skicka-knappen. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Ställ in inskickningsknappens inskickningsflaggor |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Ställer in URL för knappen. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Ändra ett enradigt textfält till ett flerradigt. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Lägg till fält av angiven typ i formuläret.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Lägg till fält av angiven typ i formuläret.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Lägger till ett nytt objekt i listboxen.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Lägg till ett nytt objekt med Export value till det befintliga listboxfältet, endast för AcroForm combo box field.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Lägg till en skicka-knapp på formuläret.

### close {#close--}
```
void close()
```

Stänger objektet

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Kopierar ett befintligt fält till samma position på angivet sidnummer.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Kopierar ett befintligt fält till en ny position som anges av både sidnummer och koordinater.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med ursprungligt sidnummer och koordinater.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och ursprungliga koordinater.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och koordinater.

### decorateField {#decorateField--}
```
void decorateField()
```

Ändrar visuella attribut för alla fält i PDF-dokumentet.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Ändrar visuella attribut för alla fält med den angivna fälttypen.

### decorateField {#decorateField-java.lang.String-}
Ändrar visuella attribut för det angivna fältet.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Ta bort objekt från listfältet.

### dispose {#dispose--}
```
void dispose()
```

Stänger objektet

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
String-objekt

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

**Returns:**
ContentDisposition-element

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Hämtar destinationsfilens namn.

**Returns:**
strängvärde

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Hämtar destinationsström.

**Returns:**
OutputStream objekt

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Hämtar dokumentet som FormEditor arbetar med.

**Returns:**
IDocument-objekt

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Hämtar alternativ för kombinationsruta med exportvärden.

**Returns:**
String[][]-objekt

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Hämtar visuella attribut för fältet.

**Returns:**
FormFieldFacade-objekt

### getItems {#getItems--}
```
String [] getItems()
```

Returnerar objektarray

**Returns:**
String[] objekt

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till).

**Returns:**
booleskt värde

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

Hämta medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50.

**Returns:**
flyttalsvärde

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Hämta flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true.

**Returns:**
booleskt värde

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Hämtar sparalternativ när resultatet lagras som HttpResponse.

**Returns:**
SaveOptions-objekt

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Hämtar namn på källfilen.

**Returns:**
strängvärde

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Hämtar källström.

**Returns:**
InputStream-objekt

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
```

Hämta skicka-knappens inskickningsflaggor

**Returns:**
SubmitFormFlag-element

### moveField {#moveField-java.lang.String-float-float-float-float-}
Ange ny position för fältet.

### removeField {#removeField-java.lang.String-}
Ta bort fältet från formuläret.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Ta bort skicka‑åtgärden för fältet.

### renameField {#renameField-java.lang.String-java.lang.String-}
Ändra namn på fältet.

### resetFacade {#resetFacade--}
```
void resetFacade()
```

Återställ alla visuella attribut till tomt värde.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

Återställ alla visuella attribut för den inre fasaden till tomt värde.

### save {#save--}
```
void save()
```

Sparar ändringar i destinationsfilen.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Ställer in PdfFormat PDF‑filformat.

### setDestFileName {#setDestFileName-java.lang.String-}
Anger destinationsfilens namn.

### setDestStream {#setDestStream-java.io.OutputStream-}
Ställer in destinationsström.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Ställer in alternativ för kombinationsruta med exportvärden.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Ställer in visuella attribut för fältet.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Ange justeringsstil för ett textfält.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Ange vertikal justeringsstil för ett textfält.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Ange fältflaggor

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Ange attribut för fältet.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Ställer in antal fack för ett vanligt enradigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller fack, som värdet på parametern combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Ställer in maximalt teckenantal för textfältet.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Ange JavaScript för ett PushButton‑fält.

### setItems {#setItems-java.lang.String:A-}
Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
void setRadioButtonItemSize(double value)
```

Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

Ange medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Ställ in flaggan för att ange om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Ställer in namn på källfilen.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Ställer in källströmmen.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Ställ in skicka-flaggan för skicka-knappen.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Ställ in inskickningsknappens inskickningsflaggor

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Ställer in URL för knappen.

### single2Multiple {#single2Multiple-java.lang.String-}
Ändra ett enradigt textfält till ett flerradigt.
