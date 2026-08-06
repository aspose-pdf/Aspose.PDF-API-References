---
title: "PKCS1"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar signaturobjekt enligt PKCS#1‑standarden.<br/>            RSA‑krypteringsalgoritm och SHA-1‑digestmetod används för signering."
type: docs
weight: 180
url: /sv/python-net/aspose.pdf.forms/pkcs1/
---

## PKCS1 class

Representerar signaturobjekt enligt PKCS#1‑standarden.<br/>            RSA‑krypteringsalgoritm och SHA-1‑digestmetod används för signering.

PKCS1-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PKCS1(image) | Initierar en ny instans av klassen PKCS1 |
| PKCS1() | Initierar en ny instans av klassen [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/). |
| PKCS1(pfx, password) | Initierar en ny instans av klassen PKCS1 |
| PKCS1(pfx, password) | Initierar en ny instans av klassen PKCS1 |
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

