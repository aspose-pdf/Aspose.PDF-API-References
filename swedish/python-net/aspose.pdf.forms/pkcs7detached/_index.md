---
title: "PKCS7Detached"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar PKCS#7‑objektet som följer PKCS#7‑specifikationen i Internet‑RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Version 1.5.<br/>            Den ursprungliga signerade meddelandedigesten för dokumentets byte‑intervall införlivas som det normala PKCS#7‑SignedData‑fältet. <br/>            Ingen data kapslas in i PKCS#7‑SignedData‑fältet."
type: docs
weight: 200
url: /sv/python-net/aspose.pdf.forms/pkcs7detached/
---

## PKCS7Detached class

Representerar PKCS#7‑objektet som följer PKCS#7‑specifikationen i Internet‑RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Version 1.5.<br/>            Den ursprungliga signerade meddelandedigesten för dokumentets byte‑intervall införlivas som det normala PKCS#7‑SignedData‑fältet. <br/>            Ingen data kapslas in i PKCS#7‑SignedData‑fältet.

PKCS7Detached-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PKCS7Detached(image) | Initierar en ny instans av PKCS7Detached-klassen |
| PKCS7Detached() | Initierar en ny instans av [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) klassen. |
| PKCS7Detached(pfx, password) | Initierar en ny instans av PKCS7Detached-klassen |
| PKCS7Detached(pfx, password) | Initierar en ny instans av PKCS7Detached-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| custom_appearance | Hämtar/sätter den anpassade utseendet. |
| authority | Namnet på personen eller myndigheten som signerar dokumentet. |
| date | Tidpunkten för signering. |
| location | CPU-värdnamnet eller den fysiska platsen för signeringen. |
| reason | Anledningen till signeringen, till exempel (Jag samtycker…). |
| contact_info | Information som tillhandahålls av undertecknaren för att möjliggöra att mottagaren kan kontakta undertecknaren <br/>            för att verifiera signaturen, t.ex. ett telefonnummer. |
| byte_range | En array av par av heltal (startbyteoffset, längd i byte) <br/>             som ska beskriva det exakta byteintervallet för beräkning av digest. |
| timestamp_settings | Hämtar/inställer tidsstämpelinställningar. |
| ocsp_settings | Hämtar/inställer OCSP-inställningar. |
| use_ltv | Hämtar/inställer LTV-valideringsflagga. |
| show_properties | Tvinga att visa/dölja signaturens egenskaper.<br/>            Om ShowProperties är true har signaturfältet ett fördefinierat format för utseende (strängar att representera):<br/>            -------------------------------------------<br/>            Digitalt signerat av {certificate subject}<br/>            Datum: {signature.Date}<br/>            Orsak: {signature.Reason}<br/>            Plats: {signature.Location}<br/>            -------------------------------------------<br/>            där {X} är en platshållare för X‑värdet. Signaturen kan också ha en bild; i så fall placeras de listade strängarna över bilden.<br/>            ShowProperties är true som standard. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| verify() | Verifiera dokumentet med avseende på denna signatur och returnera true om dokumentet är giltigt <br/>            annars false. |

### Se även

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

