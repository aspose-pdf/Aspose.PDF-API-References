---
title: "PdfFileSecurity"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar kryptering eller dekryptering av en PDF-fil med ägare- eller användarlösenord, ändring av säkerhetsinställningarna och lösenordet."
type: docs
weight: 300
url: /sv/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Representerar kryptering eller dekryptering av en PDF-fil med ägare- eller användarlösenord, ändring av säkerhetsinställningarna och lösenordet.

PdfFileSecurity-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Initierar en ny instans av PdfFileSecurity-klassen |
| PdfFileSecurity(input_file, output_file) | Initierar en ny instans av PdfFileSecurity-klassen |
| PdfFileSecurity() | Initiera objektet PdfFileSecurity. |
| PdfFileSecurity(document) | Initierar en ny instans av PdfFileSecurity-klassen |
| PdfFileSecurity(document, output_file) | Initierar en ny instans av PdfFileSecurity-klassen |
| PdfFileSecurity(document, output_stream) | Initierar en ny instans av PdfFileSecurity-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| allow_exceptions | Om detta värde är satt till true kastas ett undantag vid operationens misslyckande. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras med egenskapen LastException. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Initierar fasaden. |
| bind_pdf(src_stream) | Initierar fasaden. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar PDF-dokumentet till den angivna filen. |
| save(dest_stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Krypterar Pdf-filen med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst.<br/>            Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt.<br/>            Kastar ett undantag om processen misslyckas. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Krypterar Pdf-filen med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst.<br/>            Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt.<br/>            Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden.<br/>            Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande <br/>            undantag kommer att kastas om verktyget stöter på denna kombination.<br/>            Kastar ett undantag om processen misslyckas. |
| set_privilege(privilege) | Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord.<br/>            Ägarlösenordet kommer att läggas till som en slumpmässig sträng.<br/>            Kastar ett undantag om processen misslyckas. |
| set_privilege(user_password, owner_password, privilege) | Ställer in Pdf-filens säkerhet med originalt lösenord.<br/>            Kastar ett undantag om processen misslyckas. |
| change_password(owner_password, new_user_password, new_owner_password) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna.<br/>             Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>             med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.<br/>             Kastar ett undantag om processen misslyckas. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet.<br/>            Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.<br/>            Kastar ett undantag om processen misslyckas. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Ändrar användarlösenordet och lösenordet med ägarlösenord, möjliggör att återställa PDF-dokumentets säkerhet.<br/>            Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.<br/>            Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. <br/>            Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande <br/>            undantag kommer att kastas om verktyget stöter på denna kombination.<br/>            Kastar ett undantag om processen misslyckas. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenord, behåller de ursprungliga säkerhetsinställningarna.<br/>             Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>             kastar inte ett undantag om processen misslyckas.<br/>             med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Ändrar användarlösenordet och lösenordet med ägarlösenord, möjliggör att återställa PDF-dokumentets säkerhet.<br/>            Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.<br/>            Kastar inte ett undantag om processen misslyckas. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Ändrar användarlösenordet och lösenordet med ägarlösenord, möjliggör att återställa PDF-dokumentets säkerhet.<br/>            Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt.<br/>            Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. <br/>            Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande <br/>            undantag kommer att kastas om verktyget stöter på denna kombination.<br/>            Kastar inte ett undantag om processen misslyckas. |
| close() | Stänger fasaden. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Krypterar PDF-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst.<br/>            Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas <br/>            med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt.<br/>            Kastar inte ett undantag om processen misslyckas. |
| decrypt_file(owner_password) | Dekrypterar ett krypterat PDF-dokument med ägarlösenord. <br/>            Om dokumentet inte har ägarlösenord tillåts användning av användarlösenord.<br/>            Kastar ett undantag om processen misslyckas. |
| try_decrypt_file(owner_password) | Dekrypterar ett krypterat Pdf-dokument med ägarlösenord. <br/>            Om dokumentet inte har ägarlösenord, tillåts användning av användarlösenord.<br/>            Kastar inte ett undantag om processen misslyckas. |
| try_set_privilege(user_password, owner_password, privilege) | Ställer in Pdf-filens säkerhet med originallösenord.<br/>            Kastar inte ett undantag om processen misslyckas. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

