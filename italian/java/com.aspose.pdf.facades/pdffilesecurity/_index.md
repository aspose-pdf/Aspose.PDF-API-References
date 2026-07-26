---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la cifratura o decifratura di un file Pdf con password proprietario o utente, la modifica delle impostazioni di sicurezza e della password."
type: docs
weight: 520
url: /it/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Rappresenta la cifratura o decifratura di un file Pdf con password proprietario o utente, la modifica delle impostazioni di sicurezza e della password.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Inizializza l'oggetto di PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Inizializza l'oggetto di PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Inizializza l'oggetto di PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Inizializza l'oggetto di PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Inizializza l'oggetto di PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Inizializza l'oggetto di PdfFileSecurity. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.lang.String-) | Inizializza la facciata. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | <p> Modifica la password utente e la password tramite password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. <p> Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> string inFile = "D:\\\\input.pdf"; //Il percorso di test potrebbe essere ri-assegnato. string outFile = "D:\\\\output.pdf"; //Il percorso di test potrebbe essere ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");</pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Modifica la password utente e la password tramite password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. <p> Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. string outFile = "output.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Modifica la password utente e la password tramite password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. Esistono 6 combinazioni possibili di valori per KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. string outFile = "output.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Chiude la facciata. |
| [decryptFile](#decryptFile-java.lang.String-) | Decripta un documento Pdf crittografato con la password del proprietario. Se il documento non ha la password del proprietario, è consentito usare la password utente. Lancia un'eccezione se l'operazione fallisce. string inFile = "input.pdf"; //Il percorso di test potrebbe essere ri-assegnato. string outFile = "output.pdf"; //Il percorso di test potrebbe essere ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Chiude la facciata. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Cifra il file Pdf con password utente e password del proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario in ingresso è null o vuota. Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> String inFile = "input.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. String outFile = "output.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Cifra il file Pdf con password utente e password proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario di input è null o vuota. Esistono 6 combinazioni possibili di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono non valide e verrà sollevata l'eccezione corrispondente se il kit incontra questa combinazione. Viene sollevata un'eccezione se il processo fallisce. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Se questo valore è impostato su true, verrà sollevata un'eccezione in caso di errore dell'operazione. Altrimenti, il metodo restituisce false in caso di errore e l'ultima eccezione può essere verificata tramite la proprietà LastException. |
| [getLastException](#getLastException--) | Restituisce l'eccezione che è stata sollevata dall'ultima operazione. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Se questo valore è impostato su true, verrà sollevata un'eccezione in caso di errore dell'operazione. Altrimenti, il metodo restituisce false in caso di errore e l'ultima eccezione può essere verificata tramite la proprietà LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | Imposta il file di input. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Imposta lo stream di input. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Imposta il file di output. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Imposta lo stream di output. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password proprietario verrà aggiunta con una stringa casuale. Viene sollevata un'eccezione se il processo fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Imposta la sicurezza del file Pdf con la password originale. Viene sollevata un'eccezione se il processo fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Modifica la password utente e la password proprietario tramite la password proprietario, mantenendo le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non solleva un'eccezione se il processo fallisce. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Modifica la password utente e la password tramite la password proprietario, consentendo di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non solleva un'eccezione se il processo fallisce. string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Modifica la password utente e la password tramite password proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Esistono 6 combinazioni possibili di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Non genera un'eccezione se il processo fallisce. string inFile = "D:\\\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Decripta un documento Pdf crittografato tramite password proprietario. Se il documento non ha una password proprietario, è consentito utilizzare la password utente. Non genera un'eccezione se il processo fallisce. string inFile = "input.pdf"; //Il TestPath può essere riassegnato. string outFile = "output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Cifra il file Pdf con password utente e password proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario di input è null o vuota. Non genera un'eccezione se il processo fallisce. string inFile = "input.pdf"; //Il TestPath può essere riassegnato. string outFile = "output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Imposta la sicurezza del file Pdf con la password originale. Non genera un'eccezione se il processo fallisce. string inFile = "D:\\\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Inizializza l'oggetto di PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Inizializza l'oggetto di PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Inizializza l'oggetto di PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Inizializza l'oggetto di PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Inizializza l'oggetto di PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Inizializza l'oggetto di PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.lang.String-}
Inizializza la facciata.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Modifica la password utente e la password proprietario tramite password proprietario, mantiene le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Genera un'eccezione se il processo fallisce. string inFile = "D:\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Modifica la password utente e la password tramite password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. <p> Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. string outFile = "output.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Modifica la password utente e la password tramite password del proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la nuova password del proprietario è null o vuota. Esistono 6 combinazioni possibili di valori per KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. string outFile = "output.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Chiude la facciata.

### decryptFile {#decryptFile-java.lang.String-}
Decripta un documento Pdf crittografato con la password del proprietario. Se il documento non ha la password del proprietario, è consentito usare la password utente. Lancia un'eccezione se l'operazione fallisce. string inFile = "input.pdf"; //Il percorso di test potrebbe essere ri-assegnato. string outFile = "output.pdf"; //Il percorso di test potrebbe essere ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Chiude la facciata.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Cifra il file Pdf con password utente e password del proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario in ingresso è null o vuota. Lancia un'eccezione se l'operazione fallisce. </p> <hr> <pre> String inFile = "input.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. String outFile = "output.pdf"; // Il percorso di test potrebbe essere // ri-assegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Cifra il file Pdf con password utente e password proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario di input è null o vuota. Esistono 6 combinazioni possibili di valori KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono non valide e verrà sollevata l'eccezione corrispondente se il kit incontra questa combinazione. Viene sollevata un'eccezione se il processo fallisce. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Se questo valore è impostato su true, verrà sollevata un'eccezione in caso di errore dell'operazione. Altrimenti, il metodo restituisce false in caso di errore e l'ultima eccezione può essere verificata tramite la proprietà LastException.

**Returns:**
valore booleano @deprecated Questa proprietà è deprecata e non può essere utilizzata per consentire il lancio di eccezioni.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Restituisce l'eccezione che è stata sollevata dall'ultima operazione.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Se questo valore è impostato su true, verrà sollevata un'eccezione in caso di errore dell'operazione. Altrimenti, il metodo restituisce false in caso di errore e l'ultima eccezione può essere verificata tramite la proprietà LastException.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano @deprecated Questa proprietà è deprecata e non può essere utilizzata per consentire il lancio di eccezioni. |

### setInputFile {#setInputFile-java.lang.String-}
Imposta il file di input. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Imposta lo stream di input. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Imposta il file di output. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Imposta lo stream di output. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Imposta la sicurezza del file Pdf con password utente/proprietario vuote. La password proprietario verrà aggiunta con una stringa casuale. Viene sollevata un'eccezione se il processo fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Imposta la sicurezza del file Pdf con la password originale. Viene sollevata un'eccezione se il processo fallisce. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Modifica la password utente e la password proprietario tramite password proprietario, mantiene le impostazioni di sicurezza originali. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se il processo fallisce. string inFile = "D:\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Modifica la password utente e la password tramite password proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Non genera un'eccezione se il processo fallisce. string inFile = ".D:\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Cambia la password utente e la password tramite password proprietario, consente di reimpostare la sicurezza del documento Pdf. La nuova password utente e la nuova password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la nuova password proprietario è null o vuota. Ci sono 6 possibili combinazioni di valori di KeySize e Algorithm. Tuttavia (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) sono invalidi e l'eccezione corrispondente verrà sollevata se il kit incontra questa combinazione. Non genera un'eccezione se il processo fallisce. string inFile = "D:\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Decripta un documento Pdf crittografato tramite password proprietario. Se il documento non ha una password proprietario, è consentito utilizzare la password utente. Non genera un'eccezione se il processo fallisce. string inFile = "input.pdf"; //Il TestPath può essere riassegnato. string outFile = "output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Cifra il file Pdf con password utente e password proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password proprietario possono essere null o vuote. La password proprietario verrà sostituita con una stringa casuale se la password proprietario di input è null o vuota. Non genera un'eccezione se il processo fallisce. string inFile = "input.pdf"; //Il TestPath può essere riassegnato. string outFile = "output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Imposta la sicurezza del file Pdf con la password originale. Non genera un'eccezione se il processo fallisce. string inFile = "D:\\input.pdf"; //Il TestPath può essere riassegnato. string outFile = "D:\\output.pdf"; //Il TestPath può essere riassegnato. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
