---
title: "PKCS1"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein Signaturobjekt gemäß dem PKCS#1‑Standard dar.<br/>            RSA‑Verschlüsselungsalgorithmus und SHA‑1‑Digest‑Methode werden zum Signieren verwendet."
type: docs
weight: 180
url: /de/python-net/aspose.pdf.forms/pkcs1/
---

## PKCS1 class

Stellt ein Signaturobjekt gemäß dem PKCS#1‑Standard dar.<br/>            RSA‑Verschlüsselungsalgorithmus und SHA‑1‑Digest‑Methode werden zum Signieren verwendet.

Der PKCS1-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PKCS1(image) | Initialisiert eine neue Instanz der PKCS1-Klasse |
| PKCS1() | Initialisiert eine neue Instanz der [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/) Klasse. |
| PKCS1(pfx, password) | Initialisiert eine neue Instanz der PKCS1-Klasse |
| PKCS1(pfx, password) | Initialisiert eine neue Instanz der PKCS1-Klasse |
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

