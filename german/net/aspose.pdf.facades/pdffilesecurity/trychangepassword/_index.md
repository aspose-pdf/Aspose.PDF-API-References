---
title: TryChangePassword
second_title: Aspose.PDF für .NET-API-Referenz
description: Ändert das Benutzerkennwort und das Eigentümerkennwort durch das Eigentümerkennwort behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerkennwort und das neue Eigentümerkennwort können null oder leer sein. Das Eigentümerpasswort wird ersetzt Löst keine Ausnahme aus wenn der Vorgang fehlschlägt. durch eine zufällige Zeichenfolge ersetzt wenn das neue Eigentümerpasswort null oder leer ist.
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Ändert das Benutzerkennwort und das Eigentümerkennwort durch das Eigentümerkennwort, behält die ursprünglichen Sicherheitseinstellungen bei. Das neue Benutzerkennwort und das neue Eigentümerkennwort können null oder leer sein. Das Eigentümerpasswort wird ersetzt Löst keine Ausnahme aus, wenn der Vorgang fehlschlägt. durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Ursprüngliches Besitzerkennwort. |
| newUserPassword | String | Neues Benutzerpasswort. |
| newOwnerPassword | String | Neues Besitzerpasswort. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden.
 string outFile = "D:\\output.pdf";	//Der TestPath kann neu zugewiesen werden.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Siehe auch

* class [PdfFileSecurity](../../pdffilesecurity)
* namensraum [Aspose.Pdf.Facades](../../pdffilesecurity)
* Montage [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentsicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Eigentümerpasswort null oder leer ist. Löst keine Ausnahme aus, wenn der Vorgang fehlschlägt.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Ursprüngliches Besitzerkennwort. |
| newUserPassword | String | Neues Benutzerpasswort. |
| newOwnerPassword | String | Neues Besitzerpasswort. |
| privilege | DocumentPrivilege | Sicherheit zurücksetzen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden.
string outFile = "D:\\output.pdf";	//Der TestPath kann neu zugewiesen werden.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Siehe auch

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* namensraum [Aspose.Pdf.Facades](../../pdffilesecurity)
* Montage [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der PDF-Dokumentsicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende -Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination trifft. Löst keine Ausnahme aus, wenn der Prozess fehlschlägt.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Ursprüngliches Besitzerkennwort. |
| newUserPassword | String | Neues Benutzerpasswort. |
| newOwnerPassword | String | Neues Besitzerpasswort. |
| privilege | DocumentPrivilege | Sicherheit zurücksetzen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |
| cipher | Algorithm | Algorithm.AES zum Verschlüsseln mit dem AES-Algorithmus oder Algorithm.RC4 für die RC4-Verschlüsselung. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden.
string outFile = "D:\\output.pdf";	//Der TestPath kann neu zugewiesen werden.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Siehe auch

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* namensraum [Aspose.Pdf.Facades](../../pdffilesecurity)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
