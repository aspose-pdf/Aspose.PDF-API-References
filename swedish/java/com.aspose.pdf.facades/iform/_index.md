---
title: "IForm"
linktitle: "IForm"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar Acro-formulärobjekt."
type: docs
weight: 250
url: /sv/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Klass som representerar Acro-formulärobjekt.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Stänger öppna filer utan några ändringar. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporterar innehållet i pdf-fälten till fdf-strömmen. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporterar innehållet i pdf-fälten till xml-strömmen. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporterar innehållet i pdf-fälten till xml-strömmen. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Fyll i ett streckkodfält enligt dess fullständigt kvalificerade fältnamn. |
| [fillField](#fillField-java.lang.String-boolean-) | Fyller i kryssrutan med ett boolean-värde. |
| [fillField](#fillField-java.lang.String-int-) | Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Fyller i fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Fyll i ett fält med flera val. Notera: endast för AcroForm List Box-fält. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Överlagrar funktionen FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn. |
| [flattenAllFields](#flattenAllFields--) | Plattar till alla fält. |
| [flattenField](#flattenField-java.lang.String-) | Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet. |
| [getAttachmentName](#getAttachmentName--) | Hämtar eller anger namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Returnerar det aktuella värdet för radioknappsalternativfält. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet. |
| [getContentDisposition](#getContentDisposition--) | Hämtar eller anger hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. |
| [getDestFileName](#getDestFileName--) | Hämtar destinationsfilens namn. |
| [getDestStream](#getDestStream--) | Hämtar destinationsström. |
| [getDocument](#getDocument--) | Hämtar dokumentet som Form arbetar med. |
| [getField](#getField-java.lang.String-) | Hämtar fältets värde enligt dess fältnamn. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Returnerar FrogmFieldFacade-objektet som innehåller alla utseendeattribut. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Returnerar flaggor för fältet. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Hämta begränsningen för textfältet. |
| [getFieldNames](#getFieldNames--) | Hämtar lista över fältnamn i formuläret. |
| [getFieldType](#getFieldType-java.lang.String-) | Returnerar fälttyp. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Hämtar alla namn på formulärets submit-knappar. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. |
| [getRichText](#getRichText-java.lang.String-) | Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken. |
| [getSaveOptions](#getSaveOptions--) | Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Hämtar källfilens namn. |
| [getSrcStream](#getSrcStream--) | Hämtar källström. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Returnerar submit-knappens inskickningsflaggor. |
| [importFdf](#importFdf-java.io.InputStream-) | Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen. |
| [importXml](#importXml-java.io.InputStream-) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Byter namn på ett fält. |
| [save](#save--) | Sparar värdet på de ifyllda fälten och stänger det öppnade Pdf-dokumentet. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Anger PDF-filformat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Anger destinationsfilens namn. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Hämtar destinationsström. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Ställer in källfilens namn. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Hämtar källström. |

### close {#close--}
```
void close()
```

Stänger öppna filer utan några ändringar.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporterar innehållet i pdf-fälten till fdf-strömmen.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporterar innehållet i pdf-fälten till xml-strömmen.

### exportXml {#exportXml-java.io.OutputStream-}
Exporterar innehållet i pdf-fälten till xml-strömmen.

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Fyll i ett streckkodfält enligt dess fullständigt kvalificerade fältnamn.

### fillField {#fillField-java.lang.String-boolean-}
Fyller i kryssrutan med ett boolean-värde.

### fillField {#fillField-java.lang.String-int-}
Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn.

### fillField {#fillField-java.lang.String-java.lang.String-}
Fyller i fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Fyll i ett fält med flera val. Notera: endast för AcroForm List Box-fält.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Överlagrar funktionen FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Plattar till alla fält.

### flattenField {#flattenField-java.lang.String-}
Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Hämtar eller anger namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
string‑objekt

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Returnerar det aktuella värdet för radioknappsalternativfält.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet.

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Hämtar eller anger hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt.

**Returns:**
ContentDisposition-element

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Hämtar destinationsfilens namn.

**Returns:**
String-objekt

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

Hämtar dokumentet som Form arbetar med.

**Returns:**
IDocument-objekt

### getField {#getField-java.lang.String-}
Hämtar fältets värde enligt dess fältnamn.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Returnerar FrogmFieldFacade-objektet som innehåller alla utseendeattribut.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Returnerar flaggor för fältet.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Hämta begränsningen för textfältet.

### getFieldNames {#getFieldNames--}
```
String [] getFieldNames()
```

Hämtar lista över fältnamn i formuläret.

**Returns:**
String[] objekt

### getFieldType {#getFieldType-java.lang.String-}
Returnerar fälttyp.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Hämtar alla namn på formulärets submit-knappar.

**Returns:**
String[] objekt

### getFullFieldName {#getFullFieldName-java.lang.String-}
Hämtar det fullständiga fältnamnet enligt dess korta fältnamn.

### getRichText {#getRichText-java.lang.String-}
Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse.

**Returns:**
SaveOptions-objekt

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Hämtar källfilens namn.

**Returns:**
String-objekt

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Hämtar källström.

**Returns:**
InputStream-objekt

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Returnerar submit-knappens inskickningsflaggor.

### importFdf {#importFdf-java.io.InputStream-}
Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen.

### importXfdf {#importXfdf-java.io.InputStream-}
Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen.

### importXml {#importXml-java.io.InputStream-}
Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen.

### importXml {#importXml-java.io.InputStream-boolean-}
Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen.

### renameField {#renameField-java.lang.String-java.lang.String-}
Byter namn på ett fält.

### save {#save--}
```
void save()
```

Sparar värdet på de ifyllda fälten och stänger det öppnade Pdf-dokumentet.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Anger PDF-filformat.

### setDestFileName {#setDestFileName-java.lang.String-}
Anger destinationsfilens namn.

### setDestStream {#setDestStream-java.io.OutputStream-}
Hämtar destinationsström.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Ställer in källfilens namn.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Hämtar källström.
