---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Verschlüsselt Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und setzt die Berechtigungen des Dokuments für den Zugriff. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Prozess fehlschlägt
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Verschlüsselt Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und setzt die Berechtigungen des Dokuments für den Zugriff. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Besitzerpasswort. |
| privilege | DocumentPrivilege | Berechtigung festlegen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |

### Rückgabewert

True für Erfolg.

## Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Verschlüsselt Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und setzt die Berechtigungen des Dokuments für den Zugriff. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Es gibt 6 mögliche Kombinationen von KeySize- und Algorithmuswerten. Allerdings sind (KeySize.x40, Algorithm.AES) und (KeySize.x256, Algorithm.RC4) ungültig und eine entsprechende Ausnahme wird ausgelöst, wenn das Kit auf diese Kombination stößt. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Besitzerpasswort. |
| privilege | DocumentPrivilege | Berechtigung festlegen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |
| cipher | Algorithm | Algorithm.AES zur Verschlüsselung mit dem AES-Algorithmus oder Algorithm.RC4 für RC4-Verschlüsselung. |

### Rückgabewert

True für Erfolg.

## Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)