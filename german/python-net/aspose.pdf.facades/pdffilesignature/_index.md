---
title: "PdfFileSignature"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse zum Signieren einer PDF-Datei mit einem Zertifikat dar."
type: docs
weight: 310
url: /de/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Stellt eine Klasse zum Signieren einer PDF-Datei mit einem Zertifikat dar.

Der PdfFileSignature-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileSignature() | Der Konstruktor der PdfFileSignature-Klasse. |
| PdfFileSignature(input_file) | Initialisiert eine neue Instanz der PdfFileSignature-Klasse |
| PdfFileSignature(input_file, output_file) | Initialisiert eine neue Instanz der PdfFileSignature-Klasse |
| PdfFileSignature(document) | Initialisiert eine neue Instanz der PdfFileSignature-Klasse |
| PdfFileSignature(document, output_file) | Initialisiert eine neue Instanz der PdfFileSignature-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| signature_appearance | Legt das grafische Aussehen der Signatur fest oder ruft es ab. Der Eigenschaftswert stellt den Dateinamen des Bildes dar. |
| is_ltv_enabled | Liest das LTV‑aktivierte‑Flag aus. |
| is_certified | Liest das Flag, das bestimmt, ob ein Dokument zertifiziert ist oder nicht. |
| signature_appearance_stream | Legt das grafische Aussehen der Signatur fest oder ruft es ab. Der Eigenschaftswert stellt den Bild‑Stream dar. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(input_file) | Bindet eine PDF‑Datei zum Bearbeiten. |
| bind_pdf(input_stream) | Bindet einen PDF‑Stream zum Bearbeiten. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(output_file) | Speichert das resultierende PDF in einer Datei. |
| save(output_stream) | Speichert das resultierende PDF in den Stream. |
| save() | Speichert das resultierende PDF in einer Datei. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Erstellt eine Signatur im PDF‑Dokument. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Signiert das Dokument mit der angegebenen Typsignatur. |
| sign(page, visible, annot_rect, sig) | Signiert das Dokument mit der angegebenen Typsignatur. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Signiert das Dokument mit der angegebenen Typsignatur. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Signiert das Dokument mit der angegebenen Typsignatur. |
| sign(sig_name, sig) | Signiert das Dokument mit der angegebenen Typsignatur. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Zertifizieren Sie das Dokument mit der MDP-Signatur.<br/>            Solche Daten wie Signaturgrund, Kontakt und Ort müssen durch die entsprechenden Eigenschaften des Signature-Objekts sig bereitgestellt werden. |
| certify(sig_name, doc_mdp_signature) | Zertifizieren Sie das Dokument mit der MDP-Signatur.<br/>            Solche Daten wie Signaturgrund, Kontakt und Ort müssen durch die entsprechenden Eigenschaften des Signature-Objekts sig bereitgestellt werden. |
| remove_signature(sign_name) | Entfernen Sie die Signatur gemäß dem Namen der Signatur. |
| remove_signature(sign_name, remove_field) | Entfernt die Signatur gemäß dem Namen der Signatur. |
| close() | Schließt die Fassade. |
| get_access_permissions() | Gibt den Zugriffsberechtigungswert des zertifizierten Dokuments vom MDP-Signaturtyp zurück. |
| get_sign_names(only_active) | Ermittelt die Namen aller nicht leeren Signaturen. |
| get_blank_sign_names() | Ermittelt die Namen aller leeren Signaturfelder. |
| is_contain_signature() | Überprüft, ob das PDF eine digitale Signatur hat oder nicht. |
| contains_signature() | Überprüft, ob das PDF eine digitale Signatur hat oder nicht. |
| contains_usage_rights() | Überprüft, ob das PDF Nutzungsrechte hat oder nicht. |
| is_covers_whole_document(sign_name) | Überprüft, ob die Signatur das gesamte Dokument abdeckt. |
| covers_whole_document(sign_name) | Überprüft, ob die Signatur das gesamte Dokument abdeckt. |
| get_revision(sign_name) | Ermittelt die Revision einer Signatur. |
| get_total_revision() | Gibt die gesamte Revision zurück. |
| remove_usage_rights() | Entfernt den Eintrag für Nutzungsrechte. |
| verify_signed(sign_name) | Überprüft die Gültigkeit einer Signatur. |
| get_signer_name(sign_name) | Gibt den Namen der Person oder Organisation zurück, die das PDF-Dokument signiert. |
| get_date_time(sign_name) | Gibt das Datum und die Uhrzeit der Signatur zurück. |
| get_reason(sign_name) | Gibt den Grund einer Signatur zurück. |
| get_location(sign_name) | Gibt den Ort einer Signatur zurück. |
| get_contact_info(sign_name) | Gibt die Kontaktinformationen einer Signatur zurück. |
| verify_signature(sign_name) | Überprüft die Gültigkeit einer Signatur. |
| extract_image(sign_name) | Extrahiert das Bild der Signatur. |
| extract_certificate(sign_name) | Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream. |
| set_certificate(pfx, pass) | Setzt die Zertifikatsdatei und das Passwort für den Signaturvorgang. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

