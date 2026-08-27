---
title: "Klass Form"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.Form class. Klass som representerar Acro-formulärobjekt"
type: docs
weight: 4410
url: /sv/net/aspose.pdf.facades/form/
---
## Form class

Klass som representerar Acro‑formulärobjekt.

```csharp
public sealed class Form : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Form](form/#constructor)() | Konstruktor för Form utan parametrar. |
| [Form](form/#constructor_1)(Document) | Initierar ett nytt `Form`-objekt baserat på *dokumentet*. |
| [Form](form/#constructor_4)(Stream) | Konstruktor för formulär. |
| [Form](form/#constructor_7)(string) | Konstruktor för Form. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Hämtar lista över fältnamn på formuläret. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Hämtar alla namn på formulärets skicka-knappar. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Resultat av den senaste importoperationen. Array av objekt som beskriver importresultatet för varje fält. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Stänger öppna filer utan några ändringar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exporterar innehållet i pdf-fältens data till fdf-strömmen. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exporterar innehållet i alla fält i dokumentet till en JSON-ström. Värden för knappfält exporteras inte. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exporterar innehållet i pdf-fältens data till xml-strömmen. Värdet för knappfältet exporteras inte. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exporterar innehållet i pdf-fältens data till xml-strömmen. Värdet för knappfältet exporteras inte. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extraherar XFA-datapaket |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Fyller i ett streckkodsfält enligt dess fullständiga fältnamn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Fyller i kryssrutan med ett booleskt värde. Obs: Gäller endast för kryssruta. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.CheckBoxField" ska du ange det fullständiga namnet och inte "CheckBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt fältnamn. Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan anges med dess index. Obs: Gäller endast för radioknappar, kombinationsrutor och listrutor. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.ListBoxField" ska du ange det fullständiga namnet och inte "ListBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Fyller i fältet med ett giltigt värde enligt ett fullständigt fältnamn. Innan fälten fylls i måste varje fältnamns namn och dess motsvarande giltiga värden vara kända. Både fältnamnen och värdena är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.TextField" ska du ange det fullständiga namnet och inte "TextField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Fyll ett fält med flera val. Obs: endast för AcroForm-listruta. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Fyller fältet med angivet värde. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Fyller i textrutefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Obs: Gäller endast för textruta. Både fältnamnen och värdena är skiftlägeskänsliga. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Överlagrar funktionen FillImageField. Indatan är en bildström. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständiga fältnamn. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Plattar till alla fält. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Plattar till ett specifikt fält med det fullständiga fältnamnet. Alla andra fält förblir oförändrade. Om fältnamnet är ogiltigt förblir alla fält oförändrade. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Returnerar det aktuella värdet för radioknappsalternativfält. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Hämtar radioknappens alternativfält och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappgrupper. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Hämtar fältets värde enligt dess fältnamn. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Returnerar ett FrofmFieldFacade-objekt som innehåller alla utseendeattribut. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Returnerar fältets flaggor. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Hämta begränsningen för textfältet. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Returnerar fälttypen. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Returnerar submit‑knappens inskickningsflaggor. |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importerar all fältdata från en JSON-ström till dokumentets fält, genom att matcha fälten efter deras fullständiga namn. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importerar fältens innehåll från xml-filen och placerar dem i den nya pdf-filen. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Avgör om fältet är obligatoriskt eller inte. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är godkänt. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Sparar dokumentet i angiven ström. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Sparar dokumentet i angiven fil. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Ersätter XFA-data med angivet datapaket. Datapaketet kan extraheras med hjälp av ExtractXfaData. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Klass som beskriver resultatet av fältimport. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status för importerat fält |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


