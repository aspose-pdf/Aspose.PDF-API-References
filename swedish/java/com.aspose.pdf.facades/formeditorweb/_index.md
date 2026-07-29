---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att redigera formulär (ading/ta bort fält etc)"
type: docs
weight: 210
url: /sv/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Klass för att redigera formulär (ading/ta bort fält etc)

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Lägg till fält av angiven typ i formuläret. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Lägg till fält av angiven typ i formuläret. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Lägg till JavaScript för ett PushButton‑fält. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Lägger till ett nytt objekt i listboxen. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Lägg till ett nytt objekt med Export value till det befintliga listboxfältet, endast för AcroForm combo box field. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Lägg till en skicka-knapp på formuläret. |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Kopierar ett befintligt fält till samma position på angivet sidnummer. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Kopierar ett befintligt fält till en ny position som anges av både sidnummer och koordinater. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med ursprungligt sidnummer och koordinater. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och ursprungliga koordinater. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och koordinater. |
| [decorateField](#decorateField--) | Ändrar visuella attribut för alla fält i PDF-dokumentet. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| [decorateField](#decorateField-java.lang.String-) | Ändrar visuella attribut för det angivna fältet. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Ta bort objekt från listfältet. |
| [dispose](#dispose--) | Föråldrad. |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [getDestFileName](#getDestFileName--) | Föråldrad. |
| [getDestStream](#getDestStream--) | Hämtar destinationsström. |
| [getExportItems](#getExportItems--) | Hämtar alternativ för kombinationsruta med exportvärden. |
| [getFacade](#getFacade--) | Hämtar visuella attribut för fältet. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Hämta fältflaggor. |
| [getItems](#getItems--) | Returnerar objektarray |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till). |
| [getRadioGap](#getRadioGap--) | Hämta medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [getRadioHoriz](#getRadioHoriz--) | Hämta flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true. |
| [getResponse](#getResponse--) | Hämtar Response-objektet där resultatet av operationen kommer att lagras. |
| [getSaveOptions](#getSaveOptions--) | Hämtar sparalternativ när resultatet lagras som HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Föråldrad. |
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
| [setDestFileName](#setDestFileName-java.lang.String-) | Föråldrad. |
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
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Ställer in Response-objektet där resultatet av operationen kommer att lagras. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Föråldrad. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Ställer in källströmmen. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Ställ in skicka-flaggan för skicka-knappen. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Ställ in inskickningsknappens inskickningsflaggor |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Ställer in URL för knappen. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Ändra ett enradigt textfält till ett flerradigt. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Konstruktor för FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Lägg till fält av angiven typ i formuläret.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Lägg till fält av angiven typ i formuläret.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Lägg till JavaScript för ett PushButton‑fält.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Lägger till ett nytt objekt i listboxen.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Lägg till ett nytt objekt med Export value till det befintliga listboxfältet, endast för AcroForm combo box field.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Lägg till en skicka-knapp på formuläret.

### close {#close--}
```
public void close()
```

Stänger alla resurser som används av detta dokument.

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
public void decorateField()
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
@Deprecated public void dispose()
```

Föråldrad.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
String-objekt

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

**Returns:**
ContentDisposition-element

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Föråldrad.

**Returns:**
strängvärde

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Hämtar destinationsström.

**Returns:**
OutputStream objekt

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Hämtar alternativ för kombinationsruta med exportvärden.

**Returns:**
String[][]-array

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Hämtar visuella attribut för fältet.

**Returns:**
FormFieldFacade-objekt

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Hämta fältflaggor.

### getItems {#getItems--}
```
public String [] getItems()
```

Returnerar objektarray

**Returns:**
String[] objekt

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till).

**Returns:**
double-värde

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Hämta medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50.

**Returns:**
flyttalsvärde

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

Hämta flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true.

**Returns:**
booleskt värde

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Hämtar Response-objektet där resultatet av operationen kommer att lagras.

**Returns:**
HttpServletResponse-objekt

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar sparalternativ när resultatet lagras som HttpResponse.

**Returns:**
SaveOptions-objekt

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Föråldrad.

**Returns:**
strängvärde

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Hämtar källström.

**Returns:**
InputStream-objekt

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
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
public void resetFacade()
```

Återställ alla visuella attribut till tomt värde.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Återställ alla visuella attribut för den inre fasaden till tomt värde.

### save {#save--}
```
public void save()
```

Sparar ändringar i destinationsfilen.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Ställer in PdfFormat PDF‑filformat.

### setDestFileName {#setDestFileName-java.lang.String-}
Föråldrad.

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
public void setRadioButtonItemSize(double value)
```

Hämtar eller anger storlek på radioknappens objektstorlek (när ett nytt radioknappfält läggs till).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Ange medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Ställ in flaggan för att ange om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Ställer in Response-objektet där resultatet av operationen kommer att lagras.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Föråldrad.

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
