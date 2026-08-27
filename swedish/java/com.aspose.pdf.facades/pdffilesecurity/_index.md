---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar kryptering eller dekryptering av en Pdf-fil med ägar- eller användarlösenord, ändring av säkerhetsinställningar och lösenord."
type: docs
weight: 520
url: /sv/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Representerar kryptering eller dekryptering av en Pdf-fil med ägar- eller användarlösenord, ändring av säkerhetsinställningar och lösenord.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Initiera objektet av PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Initiera objektet av PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initiera objektet av PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Initiera objektet av PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Initiera objektet av PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Initiera objektet av PdfFileSecurity. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.lang.String-) | Initierar fasaden. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. <p> Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om kit stöter på denna kombination. Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Stänger fasaden. |
| [decryptFile](#decryptFile-java.lang.String-) | Avkrypterar ett krypterat Pdf-dokument med ägarlösenord. Om dokumentet inte har ägarlösenord, tillåts användning av användarlösenord. Kastar ett undantag om processen misslyckas. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Stänger fasaden. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Krypterar Pdf-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar undantag om processen misslyckas. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Krypterar Pdf-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om kit stöter på denna kombination. Kastar undantag om processen misslyckas. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Om detta värde är satt till true kastas ett undantag vid funktionsfel. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras via egenskapen LastException. |
| [getLastException](#getLastException--) | Returnerar undantaget som kastades av den senaste operationen. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Om detta värde är satt till true kastas ett undantag vid funktionsfel. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras via egenskapen LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | Ställer in indatafilen. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Ställer in indataströmmen. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Ställer in utdatafilen. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Ställer in utdataströmmen. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Ställer in Pdf-filens säkerhet med originalt lösenord. Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar inte ett undantag om processen misslyckas. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Dekrypterar ett krypterat Pdf-dokument med ägarlösenord. Om dokumentet inte har ett ägarlösenord tillåts användning av användarlösenord. Kastar inte ett undantag om processen misslyckas. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Krypterar Pdf-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Ställer in Pdf-filens säkerhet med originalt lösenord. Kastar inte ett undantag om processen misslyckas. string inFile = "D:\\\\input.pdf"; //TestPath kan omassigneras. string outFile = "D:\\\\output.pdf"; //TestPath kan omassigneras. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Initiera objektet av PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Initiera objektet av PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Initiera objektet av PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Initiera objektet av PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Initiera objektet av PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Initiera objektet av PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Initierar fasaden.

### bindPdf {#bindPdf-java.lang.String-}
Initierar fasaden.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. string inFile = "D:\\input.pdf"; //TestPath kan omassigneras. string outFile = "D:\\output.pdf"; //TestPath kan omassigneras. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. <p> Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om kit stöter på denna kombination. Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Stänger fasaden.

### decryptFile {#decryptFile-java.lang.String-}
Avkrypterar ett krypterat Pdf-dokument med ägarlösenord. Om dokumentet inte har ägarlösenord, tillåts användning av användarlösenord. Kastar ett undantag om processen misslyckas. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Stänger fasaden.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Krypterar Pdf-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar undantag om processen misslyckas. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Krypterar Pdf-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algorithm-värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om kit stöter på denna kombination. Kastar undantag om processen misslyckas. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Om detta värde är satt till true kastas ett undantag vid funktionsfel. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras via egenskapen LastException.

**Returns:**
boolean value @deprecated Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Returnerar undantaget som kastades av den senaste operationen.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Om detta värde är satt till true kastas ett undantag vid funktionsfel. Annars returnerar metoden false vid fel och det senaste undantaget kan kontrolleras via egenskapen LastException.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | boolean value @deprecated Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag. |

### setInputFile {#setInputFile-java.lang.String-}
Ställer in indatafilen. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Ställer in indataströmmen. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Ställer in utdatafilen. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Ställer in utdataströmmen. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Ställer in Pdf-filens säkerhet med originalt lösenord. Kastar ett undantag om processen misslyckas. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas Kastar inte ett undantag om processen misslyckas. med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. string inFile = "D:\\input.pdf"; //TestPath kan omassigneras. string outFile = "D:\\output.pdf"; //TestPath kan omassigneras. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. string inFile = ".D:\\input.pdf"; //TestPath kan omassigneras. string outFile = "D:\\output.pdf"; //TestPath kan omassigneras. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av PDF-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algorithm‑värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar inte ett undantag om processen misslyckas. string inFile = "D:\\input.pdf"; //TestPath kan omassigneras. string outFile = "D:\\output.pdf"; //TestPath kan omassigneras. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Dekrypterar ett krypterat Pdf-dokument med ägarlösenord. Om dokumentet inte har ett ägarlösenord tillåts användning av användarlösenord. Kastar inte ett undantag om processen misslyckas. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Krypterar Pdf-fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Ställer in PDF-filens säkerhet med originallösenordet. Kastar inte ett undantag om processen misslyckas. string inFile = "D:\\input.pdf"; //TestPath kan omassigneras. string outFile = "D:\\output.pdf"; //TestPath kan omassigneras. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
