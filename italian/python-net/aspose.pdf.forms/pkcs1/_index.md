---
title: "PKCS1"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta l'oggetto firma relativo allo standard PKCS#1.<br/>            L'algoritmo di crittografia RSA e il metodo di digest SHA-1 sono utilizzati per la firma."
type: docs
weight: 180
url: /it/python-net/aspose.pdf.forms/pkcs1/
---

## PKCS1 class

Rappresenta l'oggetto firma relativo allo standard PKCS#1.<br/>            L'algoritmo di crittografia RSA e il metodo di digest SHA-1 sono utilizzati per la firma.

Il tipo PKCS1 espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PKCS1(image) | Inizializza una nuova istanza della classe PKCS1 |
| PKCS1() | Inizializza una nuova istanza della classe [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/). |
| PKCS1(pfx, password) | Inizializza una nuova istanza della classe PKCS1 |
| PKCS1(pfx, password) | Inizializza una nuova istanza della classe PKCS1 |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| custom_appearance | Ottiene/imposta l'aspetto personalizzato. |
| authority | Il nome della persona o dell'autorità che firma il documento. |
| date | L'ora della firma. |
| location | Il nome host della CPU o la posizione fisica della firma. |
| reason | Il motivo della firma, ad esempio (I agreeРІР‚В¦). |
| contact_info | Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario <br/>            per verificare la firma, ad esempio un numero di telefono. |
| byte_range | Un array di coppie di interi (offset di byte iniziale, lunghezza in byte) <br/>             che descrive l'intervallo di byte esatto per il calcolo del digest. |
| timestamp_settings | Ottiene/imposta le impostazioni del timestamp. |
| ocsp_settings | Ottiene/imposta le impostazioni OCSP. |
| use_ltv | Ottiene/imposta il flag di convalida LTV. |
| show_properties | Forza la visualizzazione/nascondi le proprietà della firma.<br/>            Nel caso ShowProperties sia true, il campo firma ha un formato di aspetto predefinito (stringhe da rappresentare):<br/>            -------------------------------------------<br/>            Firmato digitalmente da {certificate subject}<br/>            Data: {signature.Date}<br/>            Motivo: {signature.Reason}<br/>            Posizione: {signature.Location}<br/>            -------------------------------------------<br/>            dove {X} è un segnaposto per il valore X. Inoltre la firma può avere un'immagine; in questo caso le stringhe elencate sono posizionate sull'immagine.<br/>            ShowProperties è true per impostazione predefinita. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| verify() | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido <br/>            altrimenti false. |

### Vedi anche

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

