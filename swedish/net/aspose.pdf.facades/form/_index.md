---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Form klass. Klass som representerar Acro form objekt
type: docs
weight: 4290
url: /sv/net/aspose.pdf.facades/form/
---
## Form klass

Klass som representerar Acro form objekt.

```csharp
public sealed class Form : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Form](form/#constructor)() | Konstruktör för Form utan parametrar. |
| [Form](form/#constructor_1)(Document) | Initierar ett nytt `Form` objekt baserat på *dokumentet*. |
| [Form](form/#constructor_4)(Stream) | Konstruktör för form. |
| [Form](form/#constructor_7)(string) | Konstruktör för Form. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om denna egenskap inte anges kommer filen att sparas i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetas med. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Hämtar lista över fältnamn på formuläret. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Hämtar alla namn på formulärens submit-knappar. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Resultat av senaste importoperationen. Array av objekt som beskriver resultatet av importen för varje fält. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar facaden. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Stänger öppnade filer utan några ändringar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter facaden. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exporterar innehållet i fälten i pdf till fdf-strömmen. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exporterar innehållet i alla fält i dokumentet till en JSON-ström. Värden för knappfält exporteras inte. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exporterar innehållet i fälten i pdf till xml-strömmen. Värdet för knappfältet kommer inte att exporteras. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exporterar innehållet i fälten i pdf till xml-strömmen. Värdet för knappfältet kommer inte att exporteras. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extraherar XFA datapaketen |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Fyller ett streckkodfält enligt dess fullständiga kvalificerade fältnamn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Fyller kryssrutan med ett booleanvärde. Observera: Endast tillämpligt på kryssrutor. Vänligen notera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och fungerar inte med delvisa fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har fullständigt namn "Form.Subform.CheckBoxField" bör du ange fullständigt namn och inte "CheckBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det erforderliga fältet med dess delvisa namn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Fyller radioknappfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls måste endast fältets namn vara känt. Medan värdet kan specificeras med sitt index. Observera: Endast tillämpligt på radioknappar, kombinationsrutor och listboxfält. Vänligen notera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och fungerar inte med delvisa fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har fullständigt namn "Form.Subform.ListBoxField" bör du ange fullständigt namn och inte "ListBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det erforderliga fältet med dess delvisa namn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Fyller fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls måste varje fältnamn och dess motsvarande giltiga värden vara kända. Både fältnamn och värden är skiftlägeskänsliga. Vänligen notera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och fungerar inte med delvisa fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel, om fältet har fullständigt namn "Form.Subform.TextField" bör du ange fullständigt namn och inte "TextField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det erforderliga fältet med dess delvisa namn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Fyller ett fält med flera val. Observera: endast för AcroForm List Box Field. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Fyller fältet med angivet värde. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Fyller textfält med textvärden och sparar dokumentet. Relevant för signerade dokument. Observera: Endast tillämpligt på textfält. Både fältnamn och värden är skiftlägeskänsliga. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Överlagrar funktionen för FillImageField. Inmatningen är en bildström. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Klistrar in en bild på den befintliga knappfältet som dess utseende enligt dess fullständiga kvalificerade fältnamn. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Plattar ut alla fält. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Plattar ut ett specificerat fält med det fullständiga kvalificerade fältnamnet. Alla andra fält kommer att förbli oförändrade. Om fieldName är ogiltigt kommer alla fält att förbli oförändrade. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Returnerar det aktuella värdet för radioknappalternativfält. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Hämtar radioknappalternativfält och relaterade värden baserat på fältnamnet. Denna metod har betydelse för radioknappgrupper. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Hämtar fältets värde enligt dess fältnamn. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Returnerar FrofmFieldFacade-objekt som innehåller alla utseendeattribut. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Returnerar flaggor för fältet. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Hämtar begränsningen för textfält. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Returnerar typ av fält. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Hämtar värdet för ett Rich Text-fält, inklusive formateringsinformation för varje tecken. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Returnerar submit-knappens inlämningsflaggor |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importerar innehållet i fälten från fdf-filen och lägger dem i den nya pdf:en. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importerar alla fältdat från en JSON-ström till dokumentfälten, matchar fälten med deras fullständiga namn. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importerar innehållet i fälten från xfdf(xml) filen och lägger dem i den nya pdf:en. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importerar innehållet i fälten från xml-filen och lägger dem i den nya pdf:en. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importerar innehållet i fälten från xml-filen och lägger dem i den nya pdf:en. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Bestämmer om fältet är obligatoriskt eller inte. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är okej. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Sparar dokumentet i angiven ström. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Sparar dokumentet i angiven fil. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Ersätter XFA-data med angivet datapaket. Datapaketen kan extraheras med hjälp av ExtractXfaData. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Klass som beskriver resultatet av fältimport. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status för importerade fält |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)