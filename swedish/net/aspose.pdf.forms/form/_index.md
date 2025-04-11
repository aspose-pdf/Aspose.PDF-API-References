---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form-klass. Klass som representerar formulärobjekt
type: docs
weight: 5070
url: /sv/net/aspose.pdf.forms/form/
---
## Formulärklass

Klass som representerar formulärobjekt.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Om den är inställd kommer alla formulärfält att beräknas om när något fält ändras. Standardvärdet är sant. Ställ in på falskt för att öka prestandan när du fyller i formuläret med ett stort antal beräknade fält. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Om den är inställd kommer frånvarande formulärfält automatiskt att skapas om de finns i anteckningarna. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Möjliggör att ställa in ordningen för fältberäkning. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Hämtar antalet fält på detta formulär. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Hämtar eller ställer in standardutseendet för formuläret (objekt som beskriver standardfont, textstorlek och färg för fälten på formuläret). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Hämtar standardresurser som placeras på detta formulär. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Om denna egenskap är sann kommer ytterligare röda gränsrektanglar att ritas för obligatoriska Xfa exclGroup-elementbehållare. Denna egenskap introducerades på grund av avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa-representation av formulär till standard. Den är falsk som standard. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Hämtar lista över alla fält på den lägsta nivån av det hierarkiska formuläret. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Om denna egenskap är sann kommer värdet av NeedsRendering-nyckeln att ignoreras under konvertering av XFA-formulär till standardformulär. Den är falsk som standard. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Returnerar sant om objektet är trådsäkert. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Hämtar fältet i formuläret efter fältnamn. Kastar undantag om fältet inte hittades. (2 indexerare) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Om denna egenskap är sann kommer "Perms"-ordboken att tas bort från pdf-dokumentet efter konvertering av dynamiska dokument till standard. "Perms"-ordboken kan innehålla regler som stör visningen av obligatoriska fält i Adobe Acrobat-läsaren. Den är falsk som standard. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Om den är inställd innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Om den är inställd innehåller dokumentet minst ett signaturfält. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Returnerar synkroniseringsobjekt. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Hämtar typ av formuläret. Möjliga värden är: Standard, Statisk, Dynamisk. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Hämtar XFA-data för formuläret (om det finns). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Lägger till fält på formuläret. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Lägger till fält på formuläret. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Lägger till ett nytt fält i formuläret; Om detta fält redan finns på ett annat eller detta formulär, skapas en kopia av fältet. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Lägger till ett ytterligare utseende av fältet på angiven sida av dokumentet på den angivna platsen. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Ställer in XFA för formuläret till angivet värde. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Kopierar fält som placeras på formuläret till en array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Tar bort fält från formuläret. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Tar bort fält från formuläret efter dess namn. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Exporterar PDF-formulärfält till JSON-format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Exporterar PDF-formulärfält till JSON-format och skriver resultatet till den angivna filen. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Tar bort alla formulärfält och placerar deras värden direkt på sidan. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Hämtar enumeration av formulärfält. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Returnerar fält inuti den angivna rektangeln. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Kontrollerar om formuläret redan har det angivna fältet. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Bestämmer om fältet med det angivna namnet redan har lagts till i formuläret. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Bestämmer om fältet med det angivna namnet redan har lagts till i formuläret, med möjlighet att titta i barnhierarkin av fält. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importerar PDF-formulärfält från JSON-format som tillhandahålls i strömmen. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importerar PDF-formulärfält från JSON-format som tillhandahålls i den angivna filen. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Gör formulärfältens anteckningar oberoende. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Tar bort utseendet av fältet vid angiven index. Om endast ett barnutseende återstår, inbäddas det i fältet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Formulär kan innehålla signeringsinformation, dvs. kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Denna egenskap talar om för formulärets konverterare (t.ex. under konvertering av XFA-formulär till standardformulär) huruvida det resulterande formuläret måste renderas som signerat eller osignerat. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Klass som beskriver inställningar för proceduren för att platta till formulär. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Formulär kan innehålla signeringsinformation och kan vara signerade eller osignerade. Ibland måste visningen av formulär i visaren bero på om formuläret är signerat eller inte. Denna enum uppräknar möjliga renderingslägen under konvertering av formulärtyp med avseende på signatur. |

### Se även

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)