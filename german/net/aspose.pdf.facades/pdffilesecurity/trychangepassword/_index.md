---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Ändert das Benutzerpasswort und das Besitzerpasswort, wobei das Besitzerpasswort die ursprünglichen Sicherheitseinstellungen beibehält. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird ersetzt. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. mit einer zufälligen Zeichenfolge, wenn das neue Besitzerpasswort null oder leer ist.
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Ändert das Benutzerpasswort und das Besitzerpasswort, wobei das Besitzerpasswort die ursprünglichen Sicherheitseinstellungen beibehält. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird ersetzt. Wirft keine Ausnahme, wenn der Prozess fehlschlägt. mit einer zufälligen Zeichenfolge, wenn das neue Besitzerpasswort null oder leer ist.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Ursprüngliches Besitzerpasswort. |
| newUserPassword | String | Neues Benutzerpasswort. |
| newOwnerPassword | String | Neues Besitzerpasswort. |

### Rückgabewert

True für Erfolg, oder false.

## Beispiele

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Siehe auch

* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Ursprüngliches Besitzerpasswort. |
| newUserPassword | String | Neues Benutzerpasswort. |
| newOwnerPassword | String | Neues Besitzerpasswort. |
| privilege | DocumentPrivilege | Sicherheit zurücksetzen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |

### Rückgabewert

True für Erfolg, oder false.

## Beispiele

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Ändert das Benutzerpasswort und das Passwort durch das Besitzerpasswort, ermöglicht das Zurücksetzen der Pdf-Dokumentensicherheit. Das neue Benutzerpasswort und das neue Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das neue Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und die entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination trifft. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ownerPassword | String | Ursprüngliches Besitzerpasswort. |
| newUserPassword | String | Neues Benutzerpasswort. |
| newOwnerPassword | String | Neues Besitzerpasswort. |
| privilege | DocumentPrivilege | Sicherheit zurücksetzen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |
| cipher | Algorithm | Algorithm.AES zur Verschlüsselung mit dem AES-Algorithmus oder Algorithm.RC4 für die RC4-Verschlüsselung. |

### Rückgabewert

True für Erfolg, oder false.

## Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)