---
title: "Form"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar formulärobjekt."
type: docs
weight: 110
url: /sv/python-net/aspose.pdf.forms/form/
---

## Form class

Klass som representerar formulärobjekt.

Form-typen exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_synchronized | Returnerar true om objektet är trådsäkert. |
| sync_root | Returnerar synkroniseringsobjekt. |
| auto_recalculate | Om den är satt kommer alla formulärfält att omberäknas när något fält ändras. Standardvärdet är true. Sätt till false för att öka prestandan vid ifyllning av formulär med ett stort antal beräknade fält. |
| auto_restore_form | Om den är satt kommer frånvarande formulärfält att automatiskt skapas om de finns i annotationer. |
| default_resources | Hämtar standardresurser som placeras på detta formulär. |
| default_appearance | Hämtar eller ställer in standardutseendet för formuläret (objekt som beskriver standardtypsnitt, textstorlek och färg för fält i formuläret). |
| xfa | Hämtar XFA-data från formuläret (om det finns). |
| ignore_needs_rendering | Om den här egenskapen är sann kommer värdet för nyckeln NeedsRendering att ignoreras under konvertering <br/>            XFA-formulär till Standard-formulär. Den är falsk som standard. |
| remove_permission | Om den här egenskapen är sann kommer "Perms"-dictionaryn att tas bort från pdf-dokumentet efter konvertering <br/>            dynamiska dokument till standard. "Perms"-dictionaryn kan innehålla regler som stör visning av val av <br/>            obligatoriska fält i Adobe Acrobat Reader.<br/>            Den är falsk som standard. |
| emulate_requierd_groups | Om den här egenskapen är sann kommer ytterligare röda avgränsningsrektanglar att ritas för obligatoriska Xfa exclGroup‑elementbehållare<br/>            Denna egenskap infördes på grund av avsaknaden av motsvarigheter för exclGroup under konvertering av Xfa‑representationen av formulär <br/>            till standard.<br/>            Den är falsk som standard. |
| type | Hämtar formulärets typ. Möjliga värden är: Standard, Statisk, Dynamisk. |
| fields | Hämtar en lista över alla fält på den lägsta nivån i det hierarkiska formuläret. |
| signatures_exist | Om satt, innehåller dokumentet minst ett signaturfält. |
| signatures_append_only | Om satt, innehåller dokumentet signaturer som kan ogiltigförklaras om filen sparas (skrivs) på ett sätt som ändrar dess tidigare innehåll, <br/>            till skillnad från en inkrementell uppdatering. |
| sign_dependent_elements_rendering_mode_when_converted | Formulär kan innehålla signeringsinformation, dvs. kan vara signerade eller osignerade.<br/>              Och formulärets vy måste ibland bero på om formuläret är signerat eller inte.<br/>              Denna egenskap talar om för formulärkonvertern (t.ex. under konvertering av XFA-formulär till Standard-formulär)<br/>              om det resulterande formuläret ska renderas som signerat eller som osignerat. |
## Indexer
| Namn | Beskrivning |
| :- | :- |
| [index] | Hämtar fältet i formuläret efter fältindex. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| delete(field) | Ta bort fält från formuläret. |
| delete(field_name) | Tar bort fält från formuläret efter dess namn. |
| add(field, page_number) | Lägger till fält i formuläret. |
| add(field) | Lägger till fält i formuläret. |
| add(field, partial_name, page_number) | Lägger till ett nytt fält i formuläret; Om detta fält redan är placerat på ett annat eller detta formulär, skapas en kopia av fältet. |
| has_field(field) | Kontrollera om formuläret redan har det angivna fältet. |
| has_field(field_name) | Bestämmer om fältet med angivet namn redan har lagts till i formuläret. |
| copy_to(array, index) | Kopierar fält som placerats i formuläret till en array. |
| flatten() | Tar bort alla formulärfält och placerar deras värden direkt på sidan. |
| add_field_appearance(field, page_number, rect) | Lägger till ett extra utseende för fältet på den angivna sidan i dokumentet på den specificerade platsen. |
| get_fields_in_rect(rect) | Returnerar fält inom den angivna rektangeln. |

### Se även

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

