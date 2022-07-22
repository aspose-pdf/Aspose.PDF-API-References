---
title: Form
second_title: Aspose.PDF för .NET API Referens
description: Klass som representerar formulärobjekt.
type: docs
weight: 3020
url: /sv/net/aspose.pdf.forms/form/
---
## Form class

Klass som representerar formulärobjekt.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Om inställt kommer alla formulärfält att beräknas om när något fält ändras. Standardvärdet är sant. Ställ in på false för att öka prestandan när du fyller i formulär med stora mängder beräknade fält. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Om inställt kommer frånvarande formulärfält att skapas automatiskt om de finns i annoteringar. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Gör det möjligt att ställa in ordning för fältberäkning. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Får antalet fält på detta formulär. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Hämtar eller ställer in standardutseende på formuläret (objekt som beskriver standardteckensnitt, textstorlek och färg för fält i formuläret). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Får standardresurser placerade på det här formuläret. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Om den här egenskapen är sann kommer ytterligare röda gränsrektanglar att ritas för nödvändiga Xfa exclGroup-element containers Den här egenskapen introducerades eftersom frånvaron av analoger för exclGroup under konvertering Xfa-representation av formulär till standard._x0000d_ Det är som standard. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Hämtar lista över alla fält i den lägsta nivån av hierarhisk form. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Om den här egenskapen är sann kommer värdet på NeedsRendering-nyckeln att ignoreras under konverteringen av XFA-formuläret till standardformuläret. Det är falskt som standard. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Returnerar sant om objektet är trådsäkert. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Hämtar fält av formuläret efter fältnamn. Kastar undantag om fältet inte hittades. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Om den här egenskapen är sann kommer "Perms"-ordboken att tas bort från pdf-dokumentet efter konvertering av dynamiska dokument till standard. Ordboken "Perms" kan innehålla regler som stör visningen av obligatoriska fält i Adobe Acrobat reader. Den är falsk som standard. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Om angivet innehåller dokumentet signaturer som kan bli ogiltiga om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, i motsats till en inkrementell uppdatering. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Om angivet innehåller dokumentet minst ett signaturfält. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Returnerar synkroniseringsobjekt. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Hämtar typ av formulär. Möjliga värden är: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Hämtar XFA-data av formuläret (om det finns). |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Lägger till fält i formuläret. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Lägger till fält i formuläret. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Lägger till nytt fält i formuläret; Om det här fältet redan är placerat på ett annat eller detta formulär skapas kopian av fältet. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Lägger till ytterligare utseende av fältet till den angivna sidan i dokumentet på den angivna platsen. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Ställer in XFA för formuläret till angivet värde. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Kopierar fält placerade på formuläret till array. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Ta bort fält från formuläret. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Tar bort fält från formuläret med dess namn. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Tar bort alla formulärfält och placerar deras värden direkt på sidan. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Hämtar uppräkning av formulärfält. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Returnerar fält inuti angiven rektangel. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Kontrollera om formuläret redan har specificerat fält. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Bestämmer om fältet med angivet namn redan har lagts till i formuläret. |

## Fält

| namn | Beskrivning |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Formulär kan innehålla signeringsinformation, dvs kan vara signerade eller osignerade. Och formulärets vy måste ibland bero på om formuläret är signerat eller inte. Den här egenskapen talar om för formulärets omvandlare (t.ex. under konvertering XFA-formulär till standardformulär) om resultatform måste återges som signerad eller osignerad. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Klass som beskriver inställningar för formulärutjämningsproceduren. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Formulär kan innehålla signeringsinformation och kan vara signerade eller osignerade. Ibland måste visningen av formulär i viewer bero på om formuläret är signerat eller inte. Denna uppräkning räknar upp möjliga återgivningslägen under konvertering av formulärtyp med avseende på tecken. |

### Se även

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* namnutrymme [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
