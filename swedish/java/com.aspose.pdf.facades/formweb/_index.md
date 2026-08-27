---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar Acro‑formulärgränssnitt."
type: docs
weight: 230
url: /sv/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Representerar Acro‑formulärgränssnitt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initierar fasaden. |
| [close](#close--) | Stänger alla öppna resurser som används av detta dokument. |
| [dispose](#dispose--) | Föråldrad. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporterar innehållet i pdf-fälten till fdf-strömmen. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporterar innehållet i pdf-fälten till xml-strömmen. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporterar innehållet i pdf-fälten till xml-strömmen. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extraherar XFA-datapaket |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Fyll i ett streckkodfält enligt dess fullständigt kvalificerade fältnamn. |
| [fillField](#fillField-java.lang.String-boolean-) | Fyller i kryssrutan med ett boolean-värde. |
| [fillField](#fillField-java.lang.String-int-) | Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Fyller i fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Fyll i ett fält med flera val. Notera: endast för AcroForm List Box-fält. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Fyller fältet med angivet värde. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Fyller textrutefälten med textvärden och sparar dokumentet. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Överlagrar funktionen FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn. |
| [flattenAllFields](#flattenAllFields--) | Plattar till alla fält. |
| [flattenField](#flattenField-java.lang.String-) | Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet. |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Returnerar det aktuella värdet för radioknappsalternativfält. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Hämtar radioknappsalternativfält och relaterade värden baserat på fältnamnet. |
| [getContentDisposition](#getContentDisposition--) | Getshow-innehåll kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [getDestFileName](#getDestFileName--) | Föråldrad. |
| [getDestStream](#getDestStream--) | Föråldrad. |
| [getField](#getField-java.lang.String-) | Hämtar fältets värde enligt dess fältnamn. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Returnerar FrogmFieldFacade-objektet som innehåller alla utseendeattribut. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Returnerar flaggor för fältet. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Hämta begränsningen för textfältet. |
| [getFieldNames](#getFieldNames--) | Hämtar lista över fältnamn i formuläret. |
| [getFieldType](#getFieldType-java.lang.String-) | Returnerar fälttyp. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Hämtar alla namn på formulärets submit-knappar. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. |
| [getImportResult](#getImportResult--) | Resultat av den senaste importoperationen. |
| [getResponse](#getResponse--) | Hämtar eller anger Response-objektet där resultatet av operationen kommer att lagras. |
| [getRichText](#getRichText-java.lang.String-) | Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken. |
| [getSaveOptions](#getSaveOptions--) | Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Föråldrad. |
| [getSrcStream](#getSrcStream--) | Hämtar källström. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Returnerar submit-knappens inskickningsflaggor. |
| [importFdf](#importFdf-java.io.InputStream-) | Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen. |
| [importXml](#importXml-java.io.InputStream-) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [importXml](#importXml-java.lang.String-) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Avgör om fältet är obligatoriskt eller inte. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Byter namn på ett fält. |
| [save](#save--) | <p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Anger PDF-filformat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Föråldrad. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Föråldrad. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Hämtar eller anger Response-objektet där resultatet av operationen kommer att lagras. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Föråldrad. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Hämtar källström. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Ersätter XFA-data med angivet datapaket. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Konstruktör för FormWeb utan parametrar. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initierar fasaden.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initierar fasaden.

### close {#close--}
```
public void close()
```

Stänger alla öppna resurser som används av detta dokument.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Föråldrad.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporterar innehållet i pdf-fälten till fdf-strömmen.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporterar innehållet i pdf-fälten till xml-strömmen.

### exportXml {#exportXml-java.io.OutputStream-}
Exporterar innehållet i pdf-fälten till xml-strömmen.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extraherar XFA-datapaket

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
Fyller fältet med angivet värde.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Fyller textrutefälten med textvärden och sparar dokumentet.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Överlagrar funktionen FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Plattar till alla fält.

### flattenField {#flattenField-java.lang.String-}
Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

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
public ContentDisposition getContentDisposition()
```

Getshow-innehåll kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

**Returns:**
ContentDisposition-element

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Föråldrad.

**Returns:**
String-objekt

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Föråldrad.

**Returns:**
OutputStream objekt

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
public String [] getFieldNames()
```

Hämtar lista över fältnamn i formuläret.

**Returns:**
String[] objekt

### getFieldType {#getFieldType-java.lang.String-}
Returnerar fälttyp.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Hämtar alla namn på formulärets submit-knappar.

**Returns:**
String[] objekt

### getFullFieldName {#getFullFieldName-java.lang.String-}
Hämtar det fullständiga fältnamnet enligt dess korta fältnamn.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Resultat av den senaste importoperationen.

**Returns:**
FormImportResult[] array

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Hämtar eller anger Response-objektet där resultatet av operationen kommer att lagras.

**Returns:**
HttpServletResponse-objekt

### getRichText {#getRichText-java.lang.String-}
Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse.

**Returns:**
SaveOptions-objekt

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Föråldrad.

**Returns:**
String-objekt

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
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

### importXml {#importXml-java.lang.String-}
Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen.

### isRequiredField {#isRequiredField-java.lang.String-}
Avgör om fältet är obligatoriskt eller inte.

### renameField {#renameField-java.lang.String-java.lang.String-}
Byter namn på ett fält.

### save {#save--}
```
public void save()
```

<p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Sparar värdet för de ifyllda fälten och stänger det öppnade Pdf-dokumentet. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Anger PDF-filformat.

### setDestFileName {#setDestFileName-java.lang.String-}
Föråldrad.

### setDestStream {#setDestStream-java.io.OutputStream-}
Föråldrad.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Hämtar eller anger Response-objektet där resultatet av operationen kommer att lagras.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Hämtar eller anger sparalternativ när resultatet lagras som HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Föråldrad.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Hämtar källström.

### setXfaData {#setXfaData-java.io.InputStream-}
Ersätter XFA-data med angivet datapaket.
