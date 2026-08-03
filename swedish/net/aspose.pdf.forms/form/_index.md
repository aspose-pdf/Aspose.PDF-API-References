---
title: "Klass Form"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Forms.Form-klass. Klass som representerar ett formulärobjekt"
type: docs
weight: 5190
url: /sv/net/aspose.pdf.forms/form/
---
## Form class

Klassen som representerar formulärobjekt.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Om inställd kommer alla formulärfält att omberäknas när ett fält ändras. Standardvärdet är true. Ställ in på false för att öka prestandan när formuläret fylls med ett stort antal beräknade fält. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Om inställd kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Tillåter att ange ordning för fältberäkning. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Hämtar antalet fält i detta formulär. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Hämtar eller anger standardutseendet för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält i formuläret). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Hämtar standardresurser som placerats på detta formulär. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Om den här egenskapen är sann kommer ytterligare röda avgränsningsrektanglar att ritas för nödvändiga Xfa exclGroup‑elementbehållare. Denna egenskap infördes eftersom avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa‑representation av formulär till standard. Den är falsk som standard. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Hämtar en lista över alla fält på den lägsta nivån i det hierarkiska formuläret. |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | Hämtar ett värde som indikerar om dokumentet innehåller ett XFA‑formulär. Denna egenskap infördes för att avgöra om [`IgnoreNeedsRendering`](./ignoreneedsrendering/) ska användas för att ta bort XFA‑formuläret i fall där XFA‑formuläret är närvarande och [`NeedsRendering`](./needsrendering/) är falskt. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Om den här egenskapen är sann kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av XFA‑formulär till standardformulär. Den är falsk som standard. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Returnerar true om objektet är trådsäkert. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Hämtar fältet i formuläret efter fältnamn. Kastar ett undantag om fältet inte hittas. (2 indexerare) |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | Hämtar ett värde som indikerar om dokumentet kräver borttagning av det dynamiska XFA‑formuläret. Denna egenskap infördes för att avgöra om [`IgnoreNeedsRendering`](./ignoreneedsrendering/) ska användas för att ta bort XFA‑formuläret i fall där XFA‑formuläret är närvarande och [`NeedsRendering`](./needsrendering/) är falskt. |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Om den här egenskapen är sann kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning och val av obligatoriska fält i Adobe Acrobat Reader. Den är falsk som standard. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Om den är inställd innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, i motsats till en inkrementell uppdatering. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Om den är inställd innehåller dokumentet minst ett signaturfält. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Returnerar synkroniseringsobjektet. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Hämtar XFA‑data för formuläret (om det finns). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Lägger till ett fält i formuläret. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Lägger till ett fält i formuläret. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Lägger till ett nytt fält i formuläret; om detta fält redan är placerat i ett annat eller i detta formulär skapas en kopia av fältet. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Lägger till ett ytterligare utseende för fältet på den angivna sidan i dokumentet på den specificerade platsen. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Ställer in XFA för formuläret till det angivna värdet. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Kopierar fält som placerats i formuläret till en array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Ta bort fält från formuläret. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Tar bort fält från formuläret efter dess namn. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Exporterar PDF‑formulärfält till JSON‑format och skriver resultatet till den angivna strömmen. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Exporterar PDF‑formulärfält till JSON‑format och skriver resultatet till den specificerade filen. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Tar bort alla formulärfält och placerar deras värden direkt på sidan. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Hämtar uppräkning av formulärfält. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Returnerar fält inom den angivna rektangeln. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Kontrollera om formuläret redan har det angivna fältet. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Bestämmer om fältet med angivet namn redan har lagts till i formuläret. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Bestämmer om fältet med angivet namn redan har lagts till i formuläret, med möjlighet att titta i fältens underordnade hierarki. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importerar PDF-formulärfält från JSON-format som tillhandahålls i strömmen. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importerar PDF-formulärfält från JSON-format som tillhandahålls i den angivna filen. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Gör formulärfältsanteckningar oberoende. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Tar bort utseendet för fältet på angivet index. Om endast ett underordnat utseende återstår, bäddar metoden in det i fältet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Formulär kan innehålla signeringsinformation, d.v.s. kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Denna egenskap talar till formulärkonverteraren (t.ex. under konvertering av XFA-formulär till standardformulär) om det resulterande formuläret ska renderas som signerat eller som osignerat. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Klass som beskriver inställningar för formulärets plattningsprocedur. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Formulär kan innehålla signeringsinformation och kan vara signerade eller osignerade. Ibland måste vyn av formulär i visaren bero på om formuläret är signerat eller inte. Denna enum listar möjliga renderingslägen under konvertering av formulärtypen med avseende på signatur. |

### Se även

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


