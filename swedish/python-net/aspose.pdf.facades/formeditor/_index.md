---
title: "FormEditor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass för att redigera formulär (lägga till/ta bort fält etc)"
type: docs
weight: 110
url: /sv/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Klass för att redigera formulär (lägga till/ta bort fält etc)

Typen FormEditor exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Initierar en ny instans av klassen FormEditor |
| FormEditor(src_file_name, dest_file_name) | Initierar en ny instans av klassen FormEditor |
| FormEditor() | Konstruktor för FormEditor. |
| FormEditor(document) | Initierar en ny instans av klassen FormEditor |
| FormEditor(document, dest_file_name) | Initierar en ny instans av klassen FormEditor |
| FormEditor(document, dest_stream) | Initierar en ny instans av klassen FormEditor |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| src_file_name | Hämtar eller anger namn på källfilen. |
| dest_file_name | Hämtar eller anger namn på målfilen. |
| src_stream | Hämtar eller anger källström. |
| dest_stream | Hämtar eller anger målström. |
| items | Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta. |
| export_items | Ställer in alternativ för kombinationsruta med exportvärden. |
| facade | Ställer in visuella attribut för fältet. |
| radio_gap | Medlemmen som registrerar avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| radio_horiz | Flaggan som anger om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är sant. |
| radio_button_item_size | Hämtar eller anger storleken på radioknappselementet (när ett nytt radioknappsfält läggs till). |
| submit_flag | Ställ in inskickningsknappens inskickningsflaggor |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save() | Sparar ändringar i destinationsfilen. |
| save(dest_file) | Sparar ändringar i destinationsfilen. |
| save(dest_stream) | Sparar ändringar i destinationsfilen. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Lägg till fält av angiven typ i formuläret. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Lägg till fält av angiven typ i formuläret. |
| copy_inner_field(field_name, new_field_name, page_num) | Kopierar ett befintligt fält till samma position på angivet sidnummer.<br/>            Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Kopierar ett befintligt fält till en ny position som specificeras av både sidnummer och koordinater.<br/>            Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| copy_outer_field(src_file_name, field_name) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med originalt sidnummer och koordinater.<br/>            Observera: Endast för AcroForm-fält (exklusive radioknappar). |
| copy_outer_field(src_file_name, field_name, page_num) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och originala koordinater.<br/>             Observera: Endast för AcroForm-fält (exklusive radioknappar). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och koordinater.<br/>            Observera: Endast för AcroForm-fält (exklusive radioknappar). |
| decorate_field(field_name) | Ändrar visuella attribut för det angivna fältet. |
| decorate_field(field_type) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| decorate_field() | Ändrar visuella attribut för det angivna fältet. |
| add_list_item(field_name, item_name) | Lägger till ett nytt objekt i listboxen. |
| add_list_item(field_name, export_name) | Lägg till ett nytt objekt med Export‑värde till det befintliga listboxfältet, endast för AcroForm‑kombinationsruta‑fältet. |
| close() | Stänger fasaden. |
| set_field_attribute(field_name, flag) | Ange attribut för fältet. |
| set_field_appearance(field_name, flags) | Ställ in fältflaggor |
| get_field_appearance(field_name) | Hämta fältflaggor. |
| set_submit_flag(field_name, submit_form_flag) | Ställ in sändningsflagga för sändningsknappen. |
| set_submit_url(field_name, url) | Anger URL för knappen. |
| set_field_limit(field_name, field_limit) | Anger maximal teckenantal för textfältet. |
| set_field_comb_number(field_name, comb_number) | Anger antal combs för ett vanligt enkelradigt textfält (fältet är <br/>            automatiskt delat i lika många jämnt fördelade positioner, eller combs, <br/>            som värdet på parametern combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Ange ny position för fältet. |
| remove_field(field_name) | Ta bort fältet från formuläret. |
| reset_facade() | Återställ alla visuella attribut till ett tomt värde. |
| reset_inner_facade() | Återställ alla visuella attribut för den inre fasaden till ett tomt värde. |
| rename_field(field_name, new_field_name) | Ändra fältets namn. |
| remove_field_action(field_name) | Ta bort skicka‑åtgärden för fältet. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Lägg till en skicka‑knapp på formuläret. |
| del_list_item(field_name, item_name) | Ta bort objektet från listfältet. |
| set_field_script(field_name, script) | Ange JavaScript för ett PushButton‑fält. Om tidigare JavaScript fanns, kommer det att ersättas av det nya. |
| add_field_script(field_name, script) | Lägg till JavaScript för ett PushButton‑fält. Om ett tidigare evenemang finns, läggs det nya evenemanget till efter det. |
| single_2_multiple(field_name) | Ändra ett enkelradigt textfält till ett flerradigt. |
| set_field_alignment(field_name, alignment) | Ange justeringsstilen för ett textfält. |
| set_field_alignment_v(field_name, alignment) | Ange den vertikala justeringsstilen för ett textfält. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

