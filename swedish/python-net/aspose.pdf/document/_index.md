---
title: "Dokument"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar PDF-dokument"
type: docs
weight: 230
url: /sv/python-net/aspose.pdf/document/
---

## Document class

Klass som representerar PDF-dokument

Dokument‑typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Document(input) | Initierar en ny instans av Document‑klassen |
| Document(input, password, is_managed_stream) | Initierar en ny instans av Document‑klassen |
| Document(input, is_managed_stream) | Initierar en ny instans av Document‑klassen |
| Document(filename) | Initierar en ny instans av Document‑klassen |
| Document(input, password) | Initierar en ny instans av Document‑klassen |
| Document() | Initierar ett tomt dokument. |
| Document(filename, options) | Initierar en ny instans av Document‑klassen |
| Document(input, options) | Initierar en ny instans av Document‑klassen |
| Document(filename, password) | Initierar en ny instans av Document‑klassen |
| Document(filename, password, is_managed_stream) | Initierar en ny instans av Document‑klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| java_script | Samling av JavaScript på dokumentnivå. |
| is_licensed | Hämtar licensieringsstatus för systemet. Returnerar true om systemet körs i licensierat läge och false annars. |
| page_info | Hämtar eller anger sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet) |
| enable_signature_sanitization | Hämtar eller anger flaggan för att hantera sanering av signaturfält. Aktiverad som standard. |
| is_pdfa_compliant | Hämtar om dokumentet är PDF/A-kompatibelt. |
| is_pdf_ua_compliant | Hämtar om dokumentet är PDF/UA-kompatibelt. |
| is_xref_gaps_allowed | Hämtar eller anger om dokumentet är PDF/A-kompatibelt. |
| named_destinations | Samling av namngivna destinationer i dokumentet. |
| destinations | Hämtar samlingen av destinationer.<br/>            Föråldrad. Använd NamedDestinations. |
| pdf_format | Hämtar PDF-format |
| embed_standard_fonts | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt <br/>            som har flaggan IsEmbedded satt till true. Alla PDF‑typsnitt kan bäddas in <br/>            i dokumentet enkelt genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑typsnitt är ett undantag från denna regel.<br/>            Inbäddning av standard‑Type1‑typsnitt kräver mycket tid, så för att bädda in dessa typsnitt är det nödvändigt<br/>            inte bara sätta flaggan IsEmbedded till true för det angivna typsnittet utan också sätta <br/>            en extra flagga på dokumentnivå – EmbedStandardFonts = true;<br/>            Denna egenskap kan endast sättas en gång för alla typsnitt.<br/>            Standardvärde false. |
| disable_font_license_verifications | Många operationer med typsnitt kan inte utföras om dessa operationer är förbjudna av typsnittets licens. <br/>            Till exempel kan vissa typsnitt inte bäddas in i ett PDF‑dokument om licensreglerna förbjuder inbäddning för detta typsnitt. <br/>            Denna flagga används för att inaktivera alla licensrestriktioner för alla typsnitt i det aktuella PDF‑dokumentet.<br/>            Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan, <br/>            tar fullt ansvar för eventuella licens‑/lagöverträdelser på sig själv. <br/>            Så han/hon tar det på egen risk. <br/>            Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter <br/>            mot upphovsrättslagen. <br/>            Standardvärde false. |
| font_utilities | IDocumentFontUtilities instance |
| collection | Hämtar samling av dokumentet. |
| version | Hämtar en version av PDF från PDF‑filens header. |
| open_action | Hämtar eller anger åtgärden som utförs vid dokumentets öppning. |
| hide_tool_bar | Hämtar eller anger flagga som specificerar om verktygsfältet ska döljas när dokumentet är aktivt. |
| hide_menubar | Hämtar eller anger flagga som specificerar om menyraden ska döljas när dokumentet är aktivt. |
| hide_window_ui | Hämtar eller anger flagga som specificerar om användargränssnittselement ska döljas när dokumentet är aktivt. |
| fit_window | Hämtar eller anger flagga som specificerar om dokumentfönstret måste anpassas för att passa den första visade sidan. |
| center_window | Hämtar eller anger flagga som specificerar om positionen för dokumentets fönster ska centreras på skärmen. |
| display_doc_title | Hämtar eller anger flagga som specificerar om dokumentfönstrets titelrad ska visa dokumentets titel. |
| sidor | Hämtar eller anger samling av dokumentsidor.<br/>            Observera att sidorna numreras från 1 i samlingen. |
| outlines | Hämtar dokumentets konturer. |
| åtgärder | Hämtar dokumentåtgärder. Denna egenskap är en instans av klassen **DocumentActions** som tillåter att hämta/ange BeforClosing, BeforSaving, etc. åtgärder. |
| formulär | Hämtar Acro Form för dokumentet. |
| embedded_files | Hämtar samling av filer som är inbäddade i dokumentet. |
| direction | Hämtar eller anger läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| page_mode | Hämtar eller anger sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| non_full_screen_page_mode | Hämtar eller anger sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| page_layout | Hämtar eller anger sidlayout som ska användas när dokumentet öppnas. |
| duplex | Hämtar eller anger alternativ för hantering av utskriftsduplexläge som ska användas när filen skrivs ut från utskriftsdialogen. |
| file_name | Namnet på PDF-filen som orsakade detta dokument |
| info | Hämtar dokumentinformation. |
| metadata | Dokumentmetadata.<br/>            (Ett PDF-dokument kan innehålla allmän information,<br/>             såsom dokumentets titel, författare samt skapande- och ändringsdatum.<br/>             Sådan global information om dokumentet (i motsats till dess innehåll eller struktur) kallas metadata<br/>             och är avsedd att underlätta katalogisering och sökning efter dokument i externa databaser.) |
| logical_structure | Hämtar dokumentets logiska struktur. |
| handle_signature_change | Kasta undantag om dokumentet sparas med ändringar och har signatur |
| crypto_algorithm | Hämtar säkerhetsinställningar om dokumentet är krypterat. <br/>            Om dokumentet inte är krypterat kommer motsvarande undantag att kastas i .net 1.1<br/>            eller CryptoAlgorithm blir null för andra .net-versioner. |
| is_linearized | Hämtar eller anger ett värde som indikerar om dokumentet är linjäriserat. |
| permissions | Hämtar dokumentets behörigheter. |
| is_encrypted | Hämtar krypteringsstatus för dokumentet. Sant om dokumentet är krypterat. |
| id | Hämtar ID:t. |
| bakgrund | Hämtar eller anger dokumentets bakgrundsfärg. |
| optimize_size | Hämtar eller anger optimeringsflagga. När sidor läggs till i dokumentet, slås lika resursströmmar i den resulterande filen<br/>            samman till ett PDF-objekt om denna flagga är satt. <br/>            Detta möjliggör att minska den resulterande filstorleken men kan leda till långsammare körning och större minneskrav.<br/>            Standardvärde: false. |
| allow_reuse_page_content | Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken. Om det används kan olika men duplicerade sidor referera till samma innehållsobjekt. <br/>            Observera att detta läge kan orsaka bieffekter som att ändra sidinnehåll när en annan sida ändras. |
| ignore_corrupted_objects | Hämtar eller anger flagga för att ignorera fel i källfiler. <br/>            När sidor från källdokumentet kopieras till måldokumentet stoppas kopieringsprocessen med ett undantag <br/>            om vissa objekt i källfilerna är korrupta när denna flagga är falsk. <br/>            exempel: dest.Pages.Add(src.Pages);<br/>            Om denna flagga sätts till true ersätts korrupta objekt med tomma värden.<br/>            Standardvärde: true. |
| page_labels | Hämtar sidetiketter i dokumentet. |
| enable_object_unload | Hämtar eller anger flagga som möjliggör att dokumentet delvis laddas ur minnet. <br/>            Detta minskar minnesanvändningen men kan ha negativ effekt på prestanda. |
| tagged_content | Hämtar åtkomst till TaggedPdf-innehåll. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| save(output) | Lagrar dokumentet i en ström. |
| save(output_file_name) | Sparar dokumentet i den angivna filen. |
| save() | Lagrar dokumentet i en ström. |
| save(options) | Sparar dokumentet med sparalternativ. |
| save(output_file_name, format) | Sparar dokumentet med ett nytt namn samt ett filformat. |
| save(output_stream, format) | Sparar dokumentet med ett nytt namn samt ett filformat. |
| save(output_file_name, options) | Sparar dokumentet med ett nytt namn och anger dess sparalternativ. |
| save(output_stream, options) | Sparar dokumentet till en ström med sparalternativ. |
| export_annotations_to_xfdf(file_name) | Exporterar alla dokumentanteckningar till en XFDF-fil |
| export_annotations_to_xfdf(stream) | Exportera alla dokumentanteckningar till en ström. |
| send_to(device, output) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| send_to(device, from_page, to_page, output) | Skickar de specifika sidorna i dokumentet till dokumentenheten för bearbetning. |
| send_to(device, output_file_name) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| send_to(device, from_page, to_page, output_file_name) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| import_annotations_from_xfdf(file_name) | Importerar annotationer från XFDF‑fil till dokumentet. |
| import_annotations_from_xfdf(stream) | Importerar annotationer från ström till dokumentet. |
| validate(output_log_file_name, format) | Validera dokumentet till den angivna filen. |
| validate(output_log_stream, format) | Validera dokumentet till den angivna filen. |
| validate(options) | Validera dokumentet till den angivna filen. |
| convert(output_log_file_name, format, action, transparency_action) | Konvertera dokumentet och spara fel i den angivna filen. |
| convert(output_log_stream, format, action, transparency_action) | Konvertera dokumentet och spara fel i den angivna filen. |
| convert(output_log_file_name, format, action) | Konvertera dokumentet och spara fel i den angivna filen. |
| convert(options) | Konvertera dokumentet med angivna konverteringsalternativ |
| convert(output_log_stream, format, action) | Konvertera dokumentet och spara fel i den angivna filen. |
| convert(fixup, output_log, only_validation, parameters) | Konvertera dokumentet genom att tillämpa Fixup. |
| convert(fixup, output_log, only_validation, parameters) | Konvertera dokumentet genom att tillämpa Fixup. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Konverterar källfilen i källformat till destinationsfilen i destinationsformat. |
| convert(src_stream, load_options, dst_file_name, save_options) | Konverterar strömmen i källformat till destinationsfilen i destinationsformat. |
| convert(src_file_name, load_options, dst_stream, save_options) | Konverterar strömmen i källformat till destinationsfilen i destinationsformat. |
| convert(src_stream, load_options, dst_stream, save_options) | Konverterar strömmen i källformat till destinationsfilen i destinationsformat. |
| flatten() | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| flatten(flatten_settings) | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet. |
| optimize_resources() | Optimera resurser i dokumentet:<br/>            1. Resurser som inte används på dokumentets sidor tas bort;<br/>            2. Liknande resurser slås ihop till ett objekt; <br/>            3. Oanvända objekt raderas. |
| optimize_resources(strategy) | Optimera resurser i dokumentet enligt definierad optimeringsstrategi. |
| bind_xml(file) | Koppla xml till dokumentet |
| bind_xml(xml_file, xsl_file) | Koppla xml till dokumentet |
| bind_xml(xml_stream, xsl_stream) | Koppla xml/xsl till dokumentet |
| bind_xml(stream) | Koppla xml/xsl till dokumentet |
| remove_pdfa_compliance() | Ta bort pdfa-efterlevnad från dokumentet |
| remove_pdf_ua_compliance() | Ta bort pdfUa-efterlevnad från dokumentet |
| set_title(title) | Ange titel för Pdf-dokument |
| process_paragraphs() | Bearbeta stycken för generatorn. |
| remove_metadata() | Tar bort metadata från dokumentet. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Ändrar dokumentets lösenord. Denna åtgärd kan endast utföras med ägarlösenordet. |
| decrypt() | Dekrypterar dokumentet. Anropa sedan Save för att få den dekrypterade versionen av dokumentet. |
| optimize() | Lineariserar dokumentet för att<br/>            - öppna den första sidan så snabbt som möjligt;<br/>            - visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt;<br/>            - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först);<br/>            - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats.<br/>            Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom förbereds dokumentet bara för att ha en optimerad struktur,<br/>            anropa sedan Save för att få ett optimerat dokument. |
| get_catalog_value(key) | Returnerar objektets värde från katalogens ordbok. |
| free_memory() | Rensar minnet |
| save_xml(file) | Spara dokumentet till XML. |
| get_object_by_id(id) | Hämtar ett objekt med angivet ID i dokumentet. |
| repair() | Reparerar trasigt dokument. |
| get_xmp_metadata(stream) | Hämta XMP-metadata från dokumentet. |
| set_xmp_metadata(stream) | Ställ in XMP-metadata för dokumentet. |
| check(do_repair) | Validerar dokumentet. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Organiserar sidträdsnoder i ett dokument till ett balanserat träd.<br/>            Endast om dokumentet har fler än nodesNumInSubtrees sidobjekt, annars gör den inget. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

