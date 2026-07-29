---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das Verschlüsseln oder Entschlüsseln einer PDF‑Datei mit Besitzer‑ oder Benutzerpasswort sowie das Ändern der Sicherheitseinstellungen und des Passworts dar."
type: docs
weight: 520
url: /de/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Stellt das Verschlüsseln oder Entschlüsseln einer PDF‑Datei mit Besitzer‑ oder Benutzerpasswort sowie das Ändern der Sicherheitseinstellungen und des Passworts dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Initialisiert das Objekt von PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Initialisiert das Objekt von PdfFileSecurity. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.lang.String-) | Initialisiert die Fassade. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Ändert das Benutzerpasswort und das Besitzerpasswort mittels des Besitzerpassworts und behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "D:\\\\input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "D:\\\\output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Ändert das Benutzerpasswort und das Passwort mittels des Besitzerpassworts und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. </p> <p> Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. </p> <hr> <pre> string inFile = "input.pdf"; // Der TestPath kann // neu zugewiesen werden. string outFile = "output.pdf"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Ändert das Benutzerpasswort und das Passwort mittels des Besitzerpassworts und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. </p> <hr> <pre> string inFile = "input.pdf"; // Der TestPath kann // neu zugewiesen werden. string outFile = "output.pdf"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Schließt die Fassade. |
| [decryptFile](#decryptFile-java.lang.String-) | Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. Falls das Dokument kein Besitzerpasswort hat, ist die Verwendung des Benutzerpassworts erlaubt. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = \"input.pdf\"; //Der TestPath kann neu zugewiesen werden. string outFile = \"output.pdf\"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile(\"ownerpass\"); |
| [dispose](#dispose--) | Schließt die Fassade. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenkette ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> String inFile = \"input.pdf\"; // Der TestPath kann // neu zugewiesen werden. String outFile = \"output.pdf\"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenkette ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit diese Kombination erkennt. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> String inFile = \"input.pdf\"; // Der TestPath kann // neu zugewiesen werden. String outFile = \"output.pdf\"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Wenn dieser Wert auf true gesetzt ist, wird bei einem Fehlversuch eine Ausnahme ausgelöst. Andernfalls gibt die Methode bei einem Fehlschlag false zurück und die letzte Ausnahme kann über die Eigenschaft LastException abgefragt werden. |
| [getLastException](#getLastException--) | Gibt die Ausnahme zurück, die bei der letzten Operation ausgelöst wurde. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Wenn dieser Wert auf true gesetzt ist, wird bei einem Fehlversuch eine Ausnahme ausgelöst. Andernfalls gibt die Methode bei einem Fehlschlag false zurück und die letzte Ausnahme kann über die Eigenschaft LastException abgefragt werden. |
| [setInputFile](#setInputFile-java.lang.String-) | Legt die Eingabedatei fest. Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Legt den Eingabestream fest. Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Legt die Ausgabedatei fest. Obsolete(\"Use save(outputStream) method for getting facade results.\") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Legt den Ausgabestream fest. Obsolete(\"Use save(outputStream) method for getting facade results.\") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Legt die Pdf-Dateisicherheit mit leeren Benutzer-/Besitzerpasswörtern fest. Das Besitzerpasswort wird durch eine zufällige Zeichenkette ergänzt. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> string inFile = \"input.pdf\"; // Der TestPath kann neu zugewiesen werden. string outFile = \"output.pdf\"; // Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Setzt die PDF-Dateisicherheit mit dem ursprünglichen Passwort. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Ändert das Benutzerpasswort und das Besitzerpasswort mittels Besitzerpasswort und behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch einen zufälligen String ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Ändert das Benutzerpasswort und das Passwort mittels Besitzerpasswort und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch einen zufälligen String ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Ändert das Benutzerpasswort und das Passwort mittels Besitzerpasswort und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch einen zufälligen String ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Entschlüsselt ein verschlüsseltes PDF-Dokument mit dem Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, ist die Verwendung des Benutzerpassworts erlaubt. Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Verschlüsselt eine PDF-Datei mit Benutzerpasswort und Eigentümerpasswort und setzt die Zugriffsrechte des Dokuments. Das Benutzerpasswort und das Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch einen zufälligen String ersetzt, wenn das übergebene Eigentümerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Setzt die Sicherheit einer PDF-Datei mit dem ursprünglichen Passwort. Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "D:\\\\input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "D:\\\\output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Initialisiert das Objekt von PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Initialisiert das Objekt von PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Initialisiert das Objekt von PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Initialisiert das Objekt von PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Initialisiert das Objekt von PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Initialisiert das Objekt von PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.lang.String-}
Initialisiert die Fassade.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Ändert das Benutzerpasswort und das Eigentümerpasswort mittels Eigentümerpasswort und behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch einen zufälligen String ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "D:\\output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Ändert das Benutzerpasswort und das Passwort mittels des Besitzerpassworts und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. </p> <p> Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. </p> <hr> <pre> string inFile = "input.pdf"; // Der TestPath kann // neu zugewiesen werden. string outFile = "output.pdf"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Ändert das Benutzerpasswort und das Passwort mittels des Besitzerpassworts und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft eine Ausnahme, wenn der Vorgang fehlschlägt. </p> <hr> <pre> string inFile = "input.pdf"; // Der TestPath kann // neu zugewiesen werden. string outFile = "output.pdf"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Schließt die Fassade.

### decryptFile {#decryptFile-java.lang.String-}
Entschlüsselt ein verschlüsseltes Pdf-Dokument mit dem Besitzerpasswort. Falls das Dokument kein Besitzerpasswort hat, ist die Verwendung des Benutzerpassworts erlaubt. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = \"input.pdf\"; //Der TestPath kann neu zugewiesen werden. string outFile = \"output.pdf\"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile(\"ownerpass\");

### dispose {#dispose--}
```
public void dispose()
```

Schließt die Fassade.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenkette ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> String inFile = \"input.pdf\"; // Der TestPath kann // neu zugewiesen werden. String outFile = \"output.pdf\"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenkette ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit diese Kombination erkennt. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> String inFile = \"input.pdf\"; // Der TestPath kann // neu zugewiesen werden. String outFile = \"output.pdf\"; // Der TestPath kann // neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Wenn dieser Wert auf true gesetzt ist, wird bei einem Fehlversuch eine Ausnahme ausgelöst. Andernfalls gibt die Methode bei einem Fehlschlag false zurück und die letzte Ausnahme kann über die Eigenschaft LastException abgefragt werden.

**Returns:**
boolescher Wert @deprecated Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zuzulassen.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Gibt die Ausnahme zurück, die bei der letzten Operation ausgelöst wurde.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Wenn dieser Wert auf true gesetzt ist, wird bei einem Fehlversuch eine Ausnahme ausgelöst. Andernfalls gibt die Methode bei einem Fehlschlag false zurück und die letzte Ausnahme kann über die Eigenschaft LastException abgefragt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated Diese Eigenschaft ist veraltet und kann nicht verwendet werden, um Ausnahmen zuzulassen. |

### setInputFile {#setInputFile-java.lang.String-}
Legt die Eingabedatei fest. Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\")

### setInputStream {#setInputStream-java.io.InputStream-}
Legt den Eingabestream fest. Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\")

### setOutputFile {#setOutputFile-java.lang.String-}
Legt die Ausgabedatei fest. Obsolete(\"Use save(outputStream) method for getting facade results.\")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Legt den Ausgabestream fest. Obsolete(\"Use save(outputStream) method for getting facade results.\")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Legt die Pdf-Dateisicherheit mit leeren Benutzer-/Besitzerpasswörtern fest. Das Besitzerpasswort wird durch eine zufällige Zeichenkette ergänzt. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> string inFile = \"input.pdf\"; // Der TestPath kann neu zugewiesen werden. string outFile = \"output.pdf\"; // Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Setzt die PDF-Dateisicherheit mit dem ursprünglichen Passwort. Wirft eine Ausnahme, wenn der Vorgang fehlgeschlagen ist. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Ändert das Benutzerpasswort und das Eigentümerpasswort mittels Eigentümerpasswort und behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird ersetzt Wirft keine Ausnahme, wenn der Vorgang fehlschlug. mit einem zufälligen String, wenn das neue Eigentümerpasswort null oder leer ist. string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "D:\\output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Ändert das Benutzerpasswort und das Passwort mittels Eigentümerpasswort und ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch einen zufälligen String ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = ".D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "D:\\output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und eine entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Entschlüsselt ein verschlüsseltes PDF-Dokument mit dem Besitzerpasswort. Wenn das Dokument kein Besitzerpasswort hat, ist die Verwendung des Benutzerpassworts erlaubt. Wirft keine Ausnahme, wenn der Vorgang fehlgeschlagen ist. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Verschlüsselt eine PDF-Datei mit Benutzerpasswort und Eigentümerpasswort und setzt die Zugriffsrechte des Dokuments. Das Benutzerpasswort und das Eigentümerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch einen zufälligen String ersetzt, wenn das übergebene Eigentümerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "input.pdf"; //Der TestPath kann neu zugewiesen werden. string outFile = "output.pdf"; //Der TestPath kann neu zugewiesen werden. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Legt die PDF-Dateisicherheit mit dem ursprünglichen Passwort fest. Wirft keine Ausnahme, wenn der Vorgang fehlschlägt. string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
