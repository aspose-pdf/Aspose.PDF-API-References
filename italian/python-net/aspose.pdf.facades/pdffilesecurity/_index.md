---
title: "PdfFileSecurity"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta la cifratura o la decifratura di un file Pdf con password di proprietario o utente, modificando le impostazioni di sicurezza e la password."
type: docs
weight: 300
url: /it/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Rappresenta la cifratura o la decifratura di un file Pdf con password di proprietario o utente, modificando le impostazioni di sicurezza e la password.

Il tipo PdfFileSecurity espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | Inizializza una nuova istanza della classe PdfFileSecurity |
| PdfFileSecurity(input_file, output_file) | Inizializza una nuova istanza della classe PdfFileSecurity |
| PdfFileSecurity() | Inizializza l'oggetto PdfFileSecurity. |
| PdfFileSecurity(document) | Inizializza una nuova istanza della classe PdfFileSecurity |
| PdfFileSecurity(document, output_file) | Inizializza una nuova istanza della classe PdfFileSecurity |
| PdfFileSecurity(document, output_stream) | Inizializza una nuova istanza della classe PdfFileSecurity |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| allow_exceptions | Se questo valore è impostato su true, verrà sollevata un'eccezione in caso di errore di operazione. Altrimenti, il metodo restituisce false in caso di errore e l'ultima eccezione può essere verificata tramite la proprietà LastException. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Inizializza la facciata. |
| bind_pdf(src_stream) | Inizializza la facciata. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(dest_file) | Salva il documento PDF nel file specificato. |
| save(dest_stream) | Salva il documento PDF nello stream specificato. |
| encrypt_file(user_password, owner_password, privilege, key_size) | Cifra il file Pdf con la password utente e la password proprietario e imposta i privilegi di accesso del documento.<br/>            La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la password proprietario di input è null o vuota.<br/>            Lancia un'eccezione se il processo fallisce. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | Cifra il file Pdf con la password utente e la password proprietario e imposta i privilegi di accesso del documento.<br/>            La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la password proprietario di input è null o vuota.<br/>            Esistono 6 possibili combinazioni di valori di KeySize e Algorithm. <br/>            Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente <br/>            verrà sollevata se il kit incontra questa combinazione.<br/>            Lancia un'eccezione se il processo fallisce. |
| set_privilege(privilege) | Imposta la sicurezza del file Pdf con password utente/proprietario vuote.<br/>            La password proprietario verrà aggiunta con una stringa casuale.<br/>            Lancia un'eccezione se il processo fallisce. |
| set_privilege(user_password, owner_password, privilege) | Imposta la sicurezza del file Pdf con la password originale.<br/>            Lancia un'eccezione se il processo fallisce. |
| change_password(owner_password, new_user_password, new_owner_password) | Modifica la password utente e la password proprietario tramite la password proprietario, mantenendo le impostazioni di sicurezza originali.<br/>             La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>             con una stringa casuale se la nuova password proprietario è null o vuota.<br/>             Lancia un'eccezione se il processo fallisce. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Modifica la password utente e la password tramite la password proprietario, consentendo di reimpostare la sicurezza del documento Pdf.<br/>            La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la nuova password proprietario è null o vuota.<br/>            Lancia un'eccezione se il processo fallisce. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Modifica la password utente e la password tramite password proprietario, consente di reimpostare la sicurezza del documento Pdf.<br/>            La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la nuova password proprietario è null o vuota.<br/>            Esistono 6 combinazioni possibili di valori per KeySize e Algorithm. <br/>            Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente <br/>            verrà sollevata se il kit incontra questa combinazione.<br/>            Viene sollevata un'eccezione se il processo fallisce. |
| try_change_password(owner_password, new_user_password, new_owner_password) | Modifica la password utente e la password proprietario tramite password proprietario, mantiene le impostazioni di sicurezza originali.<br/>             La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>             Non solleva un'eccezione se il processo fallisce.<br/>             con una stringa casuale se la nuova password proprietario è null o vuota. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | Modifica la password utente e la password tramite password proprietario, consente di reimpostare la sicurezza del documento Pdf.<br/>            La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la nuova password proprietario è null o vuota.<br/>            Non solleva un'eccezione se il processo fallisce. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | Modifica la password utente e la password tramite password proprietario, consente di reimpostare la sicurezza del documento Pdf.<br/>            La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la nuova password proprietario è null o vuota.<br/>            Esistono 6 combinazioni possibili di valori per KeySize e Algorithm. <br/>            Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente <br/>            verrà sollevata se il kit incontra questa combinazione.<br/>            Non solleva un'eccezione se il processo fallisce. |
| close() | Chiude la facciata. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | Cifra il file Pdf con password utente e password proprietario e imposta i privilegi del documento per l'accesso.<br/>            La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita <br/>            con una stringa casuale se la password proprietario in ingresso è null o vuota.<br/>            Non solleva un'eccezione se il processo fallisce. |
| decrypt_file(owner_password) | Decripta un documento Pdf cifrato tramite password proprietario. <br/>            Se il documento non ha una password proprietario, è consentito utilizzare la password utente.<br/>            Solleva un'eccezione se il processo fallisce. |
| try_decrypt_file(owner_password) | Decripta un documento Pdf cifrato tramite password proprietario. <br/>            Se il documento non ha una password proprietario, è consentito utilizzare la password utente.<br/>            Non solleva un'eccezione se il processo fallisce. |
| try_set_privilege(user_password, owner_password, privilege) | Imposta la sicurezza del file Pdf con la password originale.<br/>            Non solleva un'eccezione se il processo fallisce. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

