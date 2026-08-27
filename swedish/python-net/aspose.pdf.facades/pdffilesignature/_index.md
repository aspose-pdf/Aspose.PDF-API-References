---
title: "PdfFileSignature"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att signera en PDF-fil med ett certifikat."
type: docs
weight: 310
url: /sv/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Representerar en klass för att signera en PDF-fil med ett certifikat.

Typen PdfFileSignature exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileSignature() | Konstruktorn för klassen PdfFileSignature. |
| PdfFileSignature(input_file) | Initierar en ny instans av klassen PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Initierar en ny instans av klassen PdfFileSignature |
| PdfFileSignature(document) | Initierar en ny instans av klassen PdfFileSignature |
| PdfFileSignature(document, output_file) | Initierar en ny instans av klassen PdfFileSignature |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| signature_appearance | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildfilens namn. |
| is_ltv_enabled | Hämtar flaggan för LTV-aktivering. |
| is_certified | Hämtar flaggan som avgör om ett dokument är certifierat eller inte. |
| signature_appearance_stream | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildström. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(input_file) | Kopplar en Pdf-fil för redigering. |
| bind_pdf(input_stream) | Kopplar en Pdf-ström för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(output_file) | Sparar resultat-PDF till fil. |
| save(output_stream) | Sparar resultat-PDF till ström. |
| save() | Sparar resultat-PDF till fil. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Skapa en signatur i pdf-dokumentet. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Signera dokumentet med den angivna typens signatur. |
| sign(page, visible, annot_rect, sig) | Signera dokumentet med den angivna typens signatur. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Signera dokumentet med den angivna typens signatur. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Signera dokumentet med den angivna typens signatur. |
| sign(sig_name, sig) | Signera dokumentet med den angivna typens signatur. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Certifiera dokumentet med MDP-signaturen.<br/>            Sådan data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature-objektet sig. |
| certify(sig_name, doc_mdp_signature) | Certifiera dokumentet med MDP-signaturen.<br/>            Sådan data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature-objektet sig. |
| remove_signature(sign_name) | Ta bort signaturen enligt signaturens namn. |
| remove_signature(sign_name, remove_field) | Tar bort signaturen enligt signaturens namn. |
| close() | Stänger fasaden. |
| get_access_permissions() | Returnerar åtkomstbehörighetsvärdet för ett certifierat dokument enligt MDP‑signaturtypen. |
| get_sign_names(only_active) | Hämtar namnen på alla icke‑tomma signaturer. |
| get_blank_sign_names() | Hämtar namnen på alla tomma signaturfält. |
| is_contain_signature() | Kontrollerar om PDF‑filen har en digital signatur eller inte. |
| contains_signature() | Kontrollerar om PDF‑filen har en digital signatur eller inte. |
| contains_usage_rights() | Kontrollerar om PDF‑filen har användarrättigheter eller inte. |
| is_covers_whole_document(sign_name) | Kontrollerar om signaturen täcker hela dokumentet. |
| covers_whole_document(sign_name) | Kontrollerar om signaturen täcker hela dokumentet. |
| get_revision(sign_name) | Hämtar revisionen för en signatur. |
| get_total_revision() | Hämtar den totala revisionen. |
| remove_usage_rights() | Tar bort posten för användarrättigheter. |
| verify_signed(sign_name) | Kontrollerar giltigheten för en signatur. |
| get_signer_name(sign_name) | Hämtar namnet på personen eller organisationen som signerar pdf-dokumentet. |
| get_date_time(sign_name) | Hämtar signaturens datum och tid. |
| get_reason(sign_name) | Hämtar anledningen till en signatur. |
| get_location(sign_name) | Hämtar platsen för en signatur. |
| get_contact_info(sign_name) | Hämtar kontaktinformationen för en signatur. |
| verify_signature(sign_name) | Kontrollerar giltigheten för en signatur. |
| extract_image(sign_name) | Extraherar signaturens bild. |
| extract_certificate(sign_name) | Extraherar signaturens enda X.509‑certifikat som en ström. |
| set_certificate(pfx, pass) | Ställer in certifikatfil och lösenord för signeringsrutinen. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

