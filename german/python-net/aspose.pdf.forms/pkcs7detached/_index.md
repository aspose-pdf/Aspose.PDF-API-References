---
title: "PKCS7Detached"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt das PKCS#7‑Objekt dar, das der PKCS#7‑Spezifikation im Internet‑RFC 2315 entspricht, <br/>            PKCS #7: Cryptographic Message Syntax, Version 1.5.<br/>            Der ursprünglich signierte Nachrichten‑Digest über den Byte‑Bereich des Dokuments wird als normales PKCS#7‑SignedData‑Feld eingebunden. <br/>            Es werden keine Daten im PKCS#7‑SignedData‑Feld gekapselt."
type: docs
weight: 200
url: /de/python-net/aspose.pdf.forms/pkcs7detached/
---

## PKCS7Detached class

Stellt das PKCS#7‑Objekt dar, das der PKCS#7‑Spezifikation im Internet‑RFC 2315 entspricht, <br/>            PKCS #7: Cryptographic Message Syntax, Version 1.5.<br/>            Der ursprünglich signierte Nachrichten‑Digest über den Byte‑Bereich des Dokuments wird als normales PKCS#7‑SignedData‑Feld eingebunden. <br/>            Es werden keine Daten im PKCS#7‑SignedData‑Feld gekapselt.

Der Typ PKCS7Detached stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PKCS7Detached(image) | Initialisiert eine neue Instanz der PKCS7Detached-Klasse |
| PKCS7Detached() | Initialisiert eine neue Instanz der [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) Klasse. |
| PKCS7Detached(pfx, password) | Initialisiert eine neue Instanz der PKCS7Detached-Klasse |
| PKCS7Detached(pfx, password) | Initialisiert eine neue Instanz der PKCS7Detached-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| custom_appearance | Liest/setzt das benutzerdefinierte Aussehen. |
| authority | Der Name der Person oder Behörde, die das Dokument unterschreibt. |
| date | Der Zeitpunkt der Unterzeichnung. |
| location | Der CPU-Hostname oder physische Standort der Unterzeichnung. |
| reason | Der Grund für die Unterzeichnung, z. B. (I agreeРІР‚В¦). |
| contact_info | Informationen, die vom Unterzeichner bereitgestellt werden, damit ein Empfänger den Unterzeichner kontaktieren kann <br/> um die Signatur zu überprüfen, z. B. eine Telefonnummer. |
| byte_range | Ein Array von Paaren von Ganzzahlen (Start-Byte-Offset, Länge in Bytes) <br/> das den genauen Bytebereich für die Digest-Berechnung beschreibt. |
| timestamp_settings | Liest/Setzt Zeitstempel‑Einstellungen. |
| ocsp_settings | Liest/Setzt OCSP‑Einstellungen. |
| use_ltv | Liest/Setzt LTV‑Validierungs‑Flag. |
| show_properties | Erzwingt das Anzeigen/Verbergen von Signatur‑Eigenschaften.<br/> Wenn ShowProperties true ist, hat das Signaturfeld ein vordefiniertes Anzeigeformat (Zeichenketten zur Darstellung):<br/> -------------------------------------------<br/> Digital signiert von {certificate subject}<br/> Datum: {signature.Date}<br/> Grund: {signature.Reason}<br/> Ort: {signature.Location}<br/> -------------------------------------------<br/> wobei {X} ein Platzhalter für den X‑Wert ist. Die Signatur kann auch ein Bild enthalten; in diesem Fall werden die aufgeführten Zeichenketten über das Bild gelegt.<br/> ShowProperties ist standardmäßig true. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| verify() | Überprüft das Dokument hinsichtlich dieser Signatur und gibt true zurück, wenn das Dokument gültig ist <br/> andernfalls false. |

### Siehe auch

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

