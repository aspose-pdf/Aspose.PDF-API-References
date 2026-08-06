---
title: "PdfContentEditor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att redigera PDF‑filens innehåll."
type: docs
weight: 190
url: /sv/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Representerar en klass för att redigera PDF‑filens innehåll.

PdfContentEditor-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfContentEditor() | Konstruktorn för PdfContentEditor-objektet. |
| PdfContentEditor(document) | Initierar en ny instans av PdfContentEditor-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| text_search_options | Hämtar eller anger alternativ för textsökning. |
| text_edit_options | Hämtar eller anger alternativ för textredigering. |
| text_replace_options | Hämtar eller anger alternativ för textersättning. |
| replace_text_strategy | En uppsättning parametrar för textersättningsoperationen |
| DOCUMENT_OPEN | En dokumenthändelsetyp. Öppnar ett dokument. |
| DOCUMENT_CLOSE | En dokumenthändelsetyp. Stänger ett dokument. |
| DOCUMENT_WILL_SAVE | En dokumenthändelsetyp. Utför en åtgärd före sparande. |
| DOCUMENT_SAVED | En dokumenthändelsetyp. Utför en åtgärd efter sparande. |
| DOCUMENT_WILL_PRINT | En dokumenthändelsetyp. Utför en åtgärd före utskrift. |
| DOCUMENT_PRINTED | En dokumenthändelsetyp. Utför en åtgärd efter utskrift. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(input_file) | Kopplar en PDF-fil för redigering. |
| bind_pdf(input_stream) | Kopplar en PDF-ström för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar PDF-dokumentet till den angivna filen. |
| save(dest_stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| create_web_link(rect, url, original_page, clr) | Skapar en webblänk i PDF-dokumentet. |
| create_web_link(rect, url, original_page) | Skapar en webblänk i PDF-dokumentet. |
| create_local_link(rect, des_page, original_page, clr) | Skapar en lokal länk i PDF-dokumentet. |
| create_local_link(rect, des_page, original_page) | Skapar en lokal länk i PDF-dokumentet. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Skapar en länk till en annan PDF-dokumentsida. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Skapar en länk till en annan PDF-dokumentsida. |
| create_application_link(rect, application, page, clr) | Skapar en länk för att starta ett program i PDF-dokumentet. |
| create_application_link(rect, application, page) | Skapar en länk för att starta ett program i PDF-dokumentet. |
| create_file_attachment(rect, contents, file_path, page, name) | Skapar en filbilaggsanteckning. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Skapar en filbilaggsanteckning. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Skapar en filbilaggsanteckning. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Skapar en filbilaggsanteckning. |
| add_document_attachment(file_attachment_path, description) | Lägger till dokumentbilaga utan anteckning. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Lägger till dokumentbilaga utan anteckning. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Skapar en gummistämpelanteckning. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Skapar en gummistämpelanteckning. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Skapar en gummistämpelanteckning. |
| delete_image(page_number, index) | Tar bort de angivna bilderna på den angivna sidan. |
| delete_image() | Tar bort de angivna bilderna på den angivna sidan. |
| replace_text(src_string, the_page, dest_string, text_state) | Ersätter text i PDF-filen på den angivna sidan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/)‑objektet (teckensnittsfamilj, färg) kan specificeras för att ersätta text. |
| replace_text(src_string, dest_string) | Ersätter text i PDF-filen på den angivna sidan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/)‑objektet (teckensnittsfamilj, färg) kan specificeras för att ersätta text. |
| replace_text(src_string, the_page, dest_string) | Ersätter text i PDF-filen på den angivna sidan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/)‑objektet (teckensnittsfamilj, färg) kan specificeras för att ersätta text. |
| replace_text(src_string, dest_string, text_state) | Ersätter text i PDF-filen på den angivna sidan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/)‑objektet (teckensnittsfamilj, färg) kan specificeras för att ersätta text. |
| replace_text(src_string, dest_string, font_size) | Ersätter text i PDF-filen på den angivna sidan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/)‑objektet (teckensnittsfamilj, färg) kan specificeras för att ersätta text. |
| delete_stamp_by_ids(stamp_ids) | Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. |
| delete_stamp_by_ids(page_number, stamp_ids) | Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. |
| delete_stamp_by_id(page_number, stamp_id) | Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. |
| delete_stamp_by_id(stamp_id) | Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. |
| close() | Stänger öppet dokument. |
| extract_link() | Extraherar samlingen av Link‑instanser som finns i PDF-dokumentet. |
| create_java_script_link(code, rect, original_page, color) | Skapar en länk till JavaScript i PDF-dokumentet. |
| create_text(rect, title, contents, open, icon, page) | Skapar textannotation i PDF-dokumentet |
| create_free_text(rect, contents, page) | Skapar fri textannotation i PDF-dokumentet |
| create_markup(rect, contents, type, page, clr) | Skapar markup‑annotation i PDF-dokumentet. |
| create_popup(rect, contents, open, page) | Skapar popup‑annotation i PDF-dokumentet. |
| delete_attachments() | Tar bort alla bilagor i PDF-dokumentet. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Skapar linjeanteckning. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Skapar fyrkant‑cirkel‑anteckning. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Skapar kurvanteckning. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Skapar polygonanteckning. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Skapar polylinjeanteckning. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Skapar marköranteckning. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Skapar ett bokmärke med den angivna åtgärden. |
| add_document_additional_action(event_type, code) | Lägger till ytterligare åtgärd för dokumenthändelse. |
| remove_document_open_action() | Tar bort öppningsåtgärden från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit 'GoTo'-åtgärd vid start. |
| change_viewer_preference(viewer_attribution) | Ändrar visningsinställningen. |
| get_viewer_preference() | Returnerar visningsinställningen. |
| replace_image(page_number, index, image_file) | Ersätter den angivna bilden på den angivna sidan i PDF-dokumentet med en annan bild. |
| create_movie(rect, file_path, page) | Skapar filmanteckningar. |
| create_sound(rect, file_path, name, page, rate) | Skapar ljudanteckningar. |
| delete_stamp(page_number, index) | Tar bort flera stämplar på den angivna sidan med stämpelindex. |
| hide_stamp_by_id(page_number, stamp_id) | Döljer stämpeln. Efter döljning kan stämpelns synlighet återställas med metoden ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Visar stämpeln som dolts av HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Ändrar stämpelns position på sidan. |
| move_stamp(page_number, stamp_index, x, y) | Ändrar stämpelns position på sidan. |
| get_stamps(page_number) | Returnerar en array av stämplar på sidan. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

