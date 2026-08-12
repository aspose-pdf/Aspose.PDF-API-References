---
title: "Aspose::Pdf::Forms::Form klass"
linktitle: "Form"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Form klass. Klass som representerar formulärobjekt i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf.forms/form/
---
## Form class


Klass som representerar formulärobjekt.

```cpp
class Form : public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Nested classes

* Class [FlattenSettings](./flattensettings/)
## Enums

| Enum | Beskrivning |
| --- | --- |
| [SignDependentElementsRenderingModes](./signdependentelementsrenderingmodes/) | [Forms](../) kan innehålla signeringsinformation och kan vara signerade eller osignerade. Ibland måste visningen av formulär i visaren bero på om formuläret är signerat eller inte. Detta enum listar möjliga renderingslägen under konvertering av formulärtyp med avseende på signering. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Field\>\&, int32_t) | Lägger till fält på formuläret. |
| [Add](./add/)(const System::SharedPtr\<Field\>\&) | Lägger till fält på formuläret. |
| [Add](./add/)(System::SharedPtr\<Field\>, const System::String\&, int32_t) | Lägger till ett nytt fält till formuläret; Om detta fält redan är placerat på ett annat eller detta formulär, skapas en kopia av fältet. |
| [AddFieldAppearance](./addfieldappearance/)(const System::SharedPtr\<Field\>\&, int32_t, const System::SharedPtr\<Rectangle\>\&) | Lägger till ytterligare utseende för fältet på angiven sida i dokumentet på den specificerade platsen. |
| [AssignXfa](./assignxfa/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&) | Ställer in [XFA](../xfa/) för formuläret till angivet värde. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<Field\>\>\&, int32_t) | Kopierar fält placerade på formuläret till en array. |
| [Delete](./delete/)(const System::SharedPtr\<Field\>\&) | Ta bort fält från formuläret. |
| [Delete](./delete/)(const System::String\&) | Tar bort fält från formuläret efter dess namn. |
| [Flatten](./flatten/)() | Tar bort alla formulärfält och placerar deras värden direkt på sidan. |
| [get_AutoRecalculate](./get_autorecalculate/)() const | Om inställt kommer alla formulärfält att omberäknas när ett fält ändras. Standardvärdet är true. Sätt till false för att öka prestandan när formuläret fylls i med ett stort antal beräknade fält. |
| [get_AutoRestoreForm](./get_autorestoreform/)() const | Om inställt kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer. |
| [get_Count](./get_count/)() const override | Hämtar antalet fält i detta formulär. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Hämtar standardutseendet för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält i formuläret). |
| [get_DefaultResources](./get_defaultresources/)() | Hämtar standardresurser som placerats i detta formulär. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | Om den här egenskapen är true kommer extra röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare. Denna egenskap introducerades eftersom motsvarigheter till exclGroup saknas vid konvertering av Xfa‑representationen av formulär till standard. Den är false som standard. |
| [get_Fields](./get_fields/)() | Hämtar lista över alla fält på den lägsta nivån i det hierarkiska formuläret. |
| [get_HasXfa](./get_hasxfa/)() | Hämtar ett värde som indikerar om dokumentet innehåller [XFA](../xfa/)‑formulär. Denna egenskap introducerades för att avgöra om [IgnoreNeedsRendering](../) ska användas för att ta bort [XFA](../xfa/)‑formuläret i fall där [XFA](../xfa/)‑formuläret finns och [NeedsRendering](../) är false. |
| [get_IgnoreNeedsRendering](./get_ignoreneedsrendering/)() const | Om den här egenskapen är true kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av [XFA](../xfa/)‑formulär till standardformulär. Den är false som standard. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om objektet är trådsäkert. |
| [get_NeedsRendering](./get_needsrendering/)() | Hämtar ett värde som indikerar om dokumentet kräver borttagning av det dynamiska [XFA](../xfa/)‑formuläret. Denna egenskap introducerades för att avgöra om [IgnoreNeedsRendering](../) ska användas för att ta bort [XFA](../xfa/)‑formuläret i fall där [XFA](../xfa/)‑formuläret finns och [NeedsRendering](../) är false. |
| [get_RemovePermission](./get_removepermission/)() const | Om den här egenskapen är true kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning och val av obligatoriska fält i Adobe Acrobat Reader. Den är false som standard. |
| [get_SignaturesAppendOnly](./get_signaturesappendonly/)() | Om inställt innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering. |
| [get_SignaturesExist](./get_signaturesexist/)() | Om inställt innehåller dokumentet minst ett signaturfält. |
| [get_SyncRoot](./get_syncroot/)() const | Returnerar synkroniseringsobjekt. |
| [get_Type](./get_type/)() | Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic. |
| [get_XFA](./get_xfa/)() const | Hämtar [XFA](../xfa/)‑data för formuläret (om det finns). |
| [GetEnumerator](./getenumerator/)() override | Hämtar uppräkning av formulärfält. |
| [GetFieldsInRect](./getfieldsinrect/)(const System::SharedPtr\<Rectangle\>\&) | Returnerar fält inom angiven rektangel. |
| [HasField](./hasfield/)(const System::SharedPtr\<Field\>\&) | Kontrollera om formuläret redan har det angivna fältet. |
| [HasField](./hasfield/)(const System::String\&) | Avgör om fältet med angivet namn redan har lagts till i [Form](./). |
| [HasField](./hasfield/)(const System::String\&, bool) | Avgör om fältet med angivet namn redan har lagts till i [Form](./), med möjlighet att titta in i fältens underordnade hierarki. |
| [idx_get](./idx_get/)(const System::String\&) | Hämtar fältet i formuläret efter fältnamn. Kastar undantag om fältet inte hittades. |
| [idx_get](./idx_get/)(int32_t) | Hämtar fältet i formuläret efter fältindex. |
| [MakeFormAnnotationsIndependent](./makeformannotationsindependent/)(const System::SharedPtr\<Page\>\&) | Gör formulärfältsanteckningar oberoende. |
| [RemoveFieldAppearance](./removefieldappearance/)(const System::SharedPtr\<Field\>\&, int32_t) | Tar bort utseendet för fältet på angivet index. Om endast ett underordnat utseende återstår, bäddar metoden in det i fältet. |
| [set_AutoRecalculate](./set_autorecalculate/)(bool) | Om inställt kommer alla formulärfält att omberäknas när ett fält ändras. Standardvärdet är true. Sätt till false för att öka prestandan när formuläret fylls i med ett stort antal beräknade fält. |
| [set_AutoRestoreForm](./set_autorestoreform/)(bool) | Om inställt kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer. |
| [set_CalculatedFields](./set_calculatedfields/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<Field\>\>\>\&) | Tillåter att ange ordning för fältberäkning. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Ställer in standardutseende för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält i formuläret). |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | Om den här egenskapen är true kommer extra röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare. Denna egenskap introducerades eftersom motsvarigheter till exclGroup saknas vid konvertering av Xfa‑representationen av formulär till standard. Den är false som standard. |
| [set_IgnoreNeedsRendering](./set_ignoreneedsrendering/)(bool) | Om den här egenskapen är true kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering av [XFA](../xfa/)‑formulär till standardformulär. Den är false som standard. |
| [set_RemovePermission](./set_removepermission/)(bool) | Om den här egenskapen är true kommer "Perms"‑ordlistan att tas bort från pdf‑dokumentet efter konvertering av dynamiska dokument till standard. "Perms"‑ordlistan kan innehålla regler som stör visning och val av obligatoriska fält i Adobe Acrobat Reader. Den är false som standard. |
| [set_SignaturesAppendOnly](./set_signaturesappendonly/)(bool) | Om inställt innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, till skillnad från en inkrementell uppdatering. |
| [set_SignaturesExist](./set_signaturesexist/)(bool) | Om inställt innehåller dokumentet minst ett signaturfält. |
| [set_Type](./set_type/)(FormType) | Hämtar formulärets typ. Möjliga värden är: Standard, Static, Dynamic. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
