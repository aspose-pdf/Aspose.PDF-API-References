---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.
type: docs
weight: 110
url: /de/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile-Methode

Verschlüsselt die Pdf-Datei mit Benutzerpasswort und Besitzerpasswort und legt die Zugriffsrechte des Dokuments fest. Das Benutzerpasswort und das Besitzerpasswort können null oder leer sein. Das Besitzerpasswort wird durch eine zufällige Zeichenfolge ersetzt, wenn das eingegebene Besitzerpasswort null oder leer ist. Wirft keine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Besitzerpasswort. |
| privilege | DocumentPrivilege | Zugriffsrecht festlegen. |
| keySize | KeySize | KeySize.x40 für 40-Bit-Verschlüsselung, KeySize.x128 für 128-Bit-Verschlüsselung und KeySize.x256 für 256-Bit-Verschlüsselung. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)