---
title: "Document"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die ein PDF‑Dokument darstellt"
type: docs
weight: 230
url: /de/python-net/aspose.pdf/document/
---

## Document class

Klasse, die ein PDF‑Dokument darstellt

Der Document-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Document(input) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(input, password, is_managed_stream) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(input, is_managed_stream) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(filename) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(input, password) | Initialisiert eine neue Instanz der Document-Klasse |
| Document() | Initialisiert ein leeres Dokument. |
| Document(filename, options) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(input, options) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(filename, password) | Initialisiert eine neue Instanz der Document-Klasse |
| Document(filename, password, is_managed_stream) | Initialisiert eine neue Instanz der Document-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| java_script | Sammlung von JavaScript auf Dokumentebene. |
| is_licensed | Liest den lizenzierten Zustand des Systems. Gibt true zurück, wenn das System im lizenzierten Modus arbeitet, und false sonst. |
| page_info | Liest oder setzt die Seiteninformationen. (nur für Generator, nicht beim Lesen des Dokuments gefüllt) |
| enable_signature_sanitization | Liest oder setzt das Flag zur Verwaltung der Bereinigung von Signaturfeldern. Standardmäßig aktiviert. |
| is_pdfa_compliant | Liest, ob das Dokument PDF/A-konform ist. |
| is_pdf_ua_compliant | Ermittelt, ob das Dokument pdfua konform ist. |
| is_xref_gaps_allowed | Ermittelt oder setzt, ob das Dokument pdfa konform ist. |
| named_destinations | Sammlung benannter Ziele im Dokument. |
| destinations | Ermittelt die Sammlung von Zielen.<br/>            Veraltet. Bitte verwenden Sie NamedDestinations. |
| pdf_format | Ermittelt das PDF-Format |
| embed_standard_fonts | Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss <br/>            welche das Flag IsEmbedded auf true gesetzt haben. Alle PDF‑Schriften können in das Dokument einfach eingebettet werden, indem das Flag IsEmbedded auf true gesetzt wird, aber PDF‑Standard‑Type1‑Schriften sind eine Ausnahme von dieser Regel.<br/>            Das Einbetten von Standard‑Type1‑Schriften erfordert viel Zeit, daher ist es zum Einbetten dieser Schriften notwendig<br/>            nicht nur das Flag IsEmbedded für die angegebene Schrift auf true zu setzen, sondern auch ein<br/>            zusätzliches Flag auf Dokumentebene zu setzen – EmbedStandardFonts = true;<br/>            Diese Eigenschaft kann nur einmal für alle Schriften gesetzt werden.<br/>            Standardmäßig false. |
| disable_font_license_verifications | Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz der Schriftart verboten sind. <br/>            Beispielsweise kann eine Schriftart nicht in ein PDF‑Dokument eingebettet werden, wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. <br/>            Dieses Flag wird verwendet, um jegliche Lizenzbeschränkungen für alle Schriftarten im aktuellen PDF‑Dokument zu deaktivieren.<br/>            Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, <br/>            die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße selbst übernimmt. <br/>            Daher geschieht dies auf eigenes Risiko. <br/>            Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie nicht gegen <br/>            das Urheberrecht verstoßen. <br/>            Standardmäßig false. |
| font_utilities | Instanz von IDocumentFontUtilities |
| collection | Ermittelt die Sammlung des Dokuments. |
| version | Ermittelt die Version von PDF aus dem PDF‑Dateikopf. |
| open_action | Ermittelt oder setzt die beim Öffnen des Dokuments ausgeführte Aktion. |
| hide_tool_bar | Ermittelt oder setzt das Flag, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| hide_menubar | Ermittelt oder setzt das Flag, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| hide_window_ui | Liest oder setzt das Flag, das angibt, ob Benutzeroberflächenelemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| fit_window | Liest oder setzt das Flag, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite skaliert werden muss. |
| center_window | Liest oder setzt das Flag, das angibt, ob die Position des Dokumentfensters zentriert auf dem Bildschirm angezeigt wird. |
| display_doc_title | Liest oder setzt das Flag, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
| pages | Liest oder setzt die Sammlung von Dokumentseiten.<br/>            Hinweis: Seiten werden in der Sammlung ab 1 nummeriert. |
| outlines | Liest die Gliederungen des Dokuments. |
| aktionen | Liest die Dokumentaktionen. Diese Eigenschaft ist eine Instanz der Klasse DocumentActions, die das Abrufen/Setzen von Aktionen wie BeforClosing, BeforSaving usw. ermöglicht. |
| Formular | Liest das Acro-Formular des Dokuments. |
| embedded_files | Liest die Sammlung von in das Dokument eingebetteten Dateien. |
| direction | Liest oder setzt die Leserichtung des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| page_mode | Liest oder setzt den Seitenmodus, der festlegt, wie das Dokument beim Öffnen angezeigt werden soll. |
| non_full_screen_page_mode | Liest oder setzt den Seitenmodus, der festlegt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| page_layout | Liest oder setzt das Seitenlayout, das beim Öffnen des Dokuments verwendet werden soll. |
| duplex | Liest oder setzt die Option zur Behandlung des Duplexdruckmodus, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| file_name | Name der PDF-Datei, die dieses Dokument verursacht hat |
| Info | Liest Dokumentinformationen. |
| Metadaten | Dokumentmetadaten.<br/>            (Ein PDF-Dokument kann allgemeine Informationen enthalten,<br/>             wie den Titel des Dokuments, den Autor sowie Erstellungs- und Änderungsdaten.<br/>             Solche globalen Informationen über das Dokument (im Gegensatz zu dessen Inhalt oder Struktur) werden Metadaten genannt<br/>             und sollen bei der Katalogisierung und Suche nach Dokumenten in externen Datenbanken helfen.) |
| logical_structure | Liest die logische Struktur des Dokuments. |
| handle_signature_change | Wirf eine Ausnahme, wenn das Dokument mit Änderungen gespeichert wird und eine Signatur enthält |
| crypto_algorithm | Liest Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist. <br/>            Wenn das Dokument nicht verschlüsselt ist, wird in .net 1.1 die entsprechende Ausnahme ausgelöst<br/>            oder CryptoAlgorithm ist für andere .net-Versionen null. |
| is_linearized | Liest oder setzt einen Wert, der angibt, ob das Dokument linearisiert ist. |
| permissions | Liest die Berechtigungen des Dokuments. |
| is_encrypted | Liest den Verschlüsselungsstatus des Dokuments. Wahr, wenn das Dokument verschlüsselt ist. |
| id | Liest die ID. |
| background | Liest oder setzt die Hintergrundfarbe des Dokuments. |
| optimize_size | Liest oder setzt das Optimierungsflag. Wenn Seiten zum Dokument hinzugefügt werden, werden gleiche Ressourcenströme in der resultierenden Datei<br/>            zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. <br/>            Dies ermöglicht, die resultierende Dateigröße zu verringern, kann jedoch zu langsamerer Ausführung und höheren Speicheranforderungen führen.<br/>            Standardwert: false. |
| allow_reuse_page_content | Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren. Wenn verwendet, können unterschiedliche, aber duplizierte Seiten auf dasselbe Inhaltsobjekt verweisen. Bitte beachten Sie, dass dieser Modus Nebenwirkungen haben kann, wie das Ändern von Seiteninhalten, wenn eine andere Seite geändert wird. |
| ignore_corrupted_objects | Liest oder setzt das Flag zum Ignorieren von Fehlern in Quelldateien. <br/>            Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang bei einer Ausnahme abgebrochen <br/>            falls einige Objekte in den Quelldateien beschädigt sind, wenn dieses Flag false ist. <br/>            Beispiel: dest.Pages.Add(src.Pages);<br/>            Wenn dieses Flag auf true gesetzt ist, werden beschädigte Objekte durch leere Werte ersetzt.<br/>            Standardwert: true. |
| page_labels | Liest Seitenbeschriftungen im Dokument. |
| enable_object_unload | Liest oder setzt das Flag, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht. <br/>            Dies reduziert den Speicherverbrauch, kann jedoch die Leistung negativ beeinflussen. |
| tagged_content | Erhält Zugriff auf den TaggedPdf-Inhalt. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| save(output) | Speichert das Dokument in einen Stream. |
| save(output_file_name) | Speichert das Dokument in die angegebene Datei. |
| save() | Speichert das Dokument in einen Stream. |
| save(options) | Speichert das Dokument mit Speicheroptionen. |
| save(output_file_name, format) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| save(output_stream, format) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| save(output_file_name, options) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| save(output_stream, options) | Speichert das Dokument in einen Stream mit Speicheroptionen. |
| export_annotations_to_xfdf(file_name) | Exportiert alle Dokumentenannotationen in eine XFDF-Datei. |
| export_annotations_to_xfdf(stream) | Exportiert alle Dokumentenannotationen in einen Stream. |
| send_to(device, output) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| send_to(device, from_page, to_page, output) | Sendet bestimmte Seiten des Dokuments an das Dokumentgerät zur Verarbeitung. |
| send_to(device, output_file_name) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| send_to(device, from_page, to_page, output_file_name) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| import_annotations_from_xfdf(file_name) | Importiert Anmerkungen aus einer XFDF-Datei in das Dokument. |
| import_annotations_from_xfdf(stream) | Importiert Anmerkungen aus einem Stream in das Dokument. |
| validate(output_log_file_name, format) | Validiere das Dokument in die angegebene Datei. |
| validate(output_log_stream, format) | Validiere das Dokument in die angegebene Datei. |
| validate(options) | Validiere das Dokument in die angegebene Datei. |
| convert(output_log_file_name, format, action, transparency_action) | Konvertiere das Dokument und speichere Fehler in die angegebene Datei. |
| convert(output_log_stream, format, action, transparency_action) | Konvertiere das Dokument und speichere Fehler in die angegebene Datei. |
| convert(output_log_file_name, format, action) | Konvertiere das Dokument und speichere Fehler in die angegebene Datei. |
| convert(options) | Konvertiere das Dokument mit den angegebenen Konvertierungsoptionen. |
| convert(output_log_stream, format, action) | Konvertiere das Dokument und speichere Fehler in die angegebene Datei. |
| convert(fixup, output_log, only_validation, parameters) | Konvertiere das Dokument, indem das Fixup angewendet wird. |
| convert(fixup, output_log, only_validation, parameters) | Konvertiere das Dokument, indem das Fixup angewendet wird. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Konvertiert die Quelldatei im Quellformat in die Zieldatei im Zielformat. |
| convert(src_stream, load_options, dst_file_name, save_options) | Konvertiert den Stream im Quellformat in die Zieldatei im Zielformat. |
| convert(src_file_name, load_options, dst_stream, save_options) | Konvertiert den Stream im Quellformat in die Zieldatei im Zielformat. |
| convert(src_stream, load_options, dst_stream, save_options) | Konvertiert den Stream im Quellformat in die Zieldatei im Zielformat. |
| flatten() | Entfernt alle Felder aus dem Dokument und setzt stattdessen deren Werte ein. |
| flatten(flatten_settings) | Entfernt alle Felder aus dem Dokument und setzt stattdessen deren Werte ein. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Verschlüsselt das Dokument. Rufen Sie dann Save auf, um die verschlüsselte Version des Dokuments zu erhalten. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Verschlüsselt das Dokument. Rufen Sie dann Save auf, um die verschlüsselte Version des Dokuments zu erhalten. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Verschlüsselt das Dokument. Rufen Sie dann Save auf, um die verschlüsselte Version des Dokuments zu erhalten. |
| optimize_resources() | Ressourcen im Dokument optimieren:<br/>            1. Ressourcen, die nicht auf den Dokumentseiten verwendet werden, werden entfernt;<br/>            2. Gleiche Ressourcen werden zu einem Objekt zusammengeführt; <br/>            3. Unbenutzte Objekte werden gelöscht. |
| optimize_resources(strategy) | Ressourcen im Dokument gemäß der definierten Optimierungsstrategie optimieren. |
| bind_xml(file) | XML an das Dokument binden |
| bind_xml(xml_file, xsl_file) | XML an das Dokument binden |
| bind_xml(xml_stream, xsl_stream) | XML/XSL an das Dokument binden |
| bind_xml(stream) | XML/XSL an das Dokument binden |
| remove_pdfa_compliance() | pdfa-Konformität aus dem Dokument entfernen |
| remove_pdf_ua_compliance() | pdfUa-Konformität aus dem Dokument entfernen |
| set_title(title) | Titel für Pdf-Dokument festlegen |
| process_paragraphs() | Absätze für den Generator verarbeiten. |
| remove_metadata() | Entfernt Metadaten aus dem Dokument. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Ändert Dokument-Passwörter. Diese Aktion kann nur mit dem Besitzer-Passwort durchgeführt werden. |
| decrypt() | Entschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die entschlüsselte Version des Dokuments zu erhalten. |
| optimize() | Linearisiere das Dokument, um<br/>            - die erste Seite so schnell wie möglich zu öffnen;<br/>            - die nächste Seite anzuzeigen oder dem Link zur nächsten Seite so schnell wie möglich zu folgen;<br/>            - die Seite schrittweise anzuzeigen, sobald sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (die nützlichsten Daten zuerst anzeigen);<br/>            - Benutzerinteraktionen zu ermöglichen, wie das Folgen eines Links, noch bevor die gesamte Seite empfangen und angezeigt wurde.<br/>            Das Aufrufen dieser Methode speichert das Dokument nicht wirklich. Im Gegenteil, das Dokument wird lediglich für eine optimierte Struktur vorbereitet,<br/>            rufen Sie anschließend Save auf, um das optimierte Dokument zu erhalten. |
| get_catalog_value(key) | Gibt den Wert des Elements aus dem Katalog-Wörterbuch zurück. |
| free_memory() | Löscht den Speicher |
| save_xml(file) | Speichert das Dokument als XML. |
| get_object_by_id(id) | Liefert ein Objekt mit der angegebenen ID im Dokument. |
| repair() | Repariert ein beschädigtes Dokument. |
| get_xmp_metadata(stream) | Liest XMP-Metadaten aus dem Dokument. |
| set_xmp_metadata(stream) | Setzt XMP-Metadaten des Dokuments. |
| check(do_repair) | Validiert das Dokument. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum.<br/>            Nur wenn das Dokument mehr als nodesNumInSubtrees Seitenobjekte enthält, sonst wird nichts getan. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

