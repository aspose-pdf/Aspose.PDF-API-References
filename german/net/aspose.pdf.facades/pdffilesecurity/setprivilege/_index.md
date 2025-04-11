---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity-Methode. Setzt die Sicherheit der Pdf-Datei mit leeren Benutzer-/Eigentümerpasswörtern. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge hinzugefügt. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Setzt die Sicherheit der Pdf-Datei mit leeren Benutzer-/Eigentümerpasswörtern. Das Eigentümerpasswort wird durch eine zufällige Zeichenfolge hinzugefügt. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| privilege | DocumentPrivilege | Setze Berechtigung. |

### Rückgabewert

True bei Erfolg.

## Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Setzt die Sicherheit der Pdf-Datei mit dem ursprünglichen Passwort. Wirft eine Ausnahme, wenn der Prozess fehlschlägt.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Ursprüngliches Benutzerpasswort. |
| ownerPassword | String | Ursprüngliches Eigentümerpasswort. |
| privilege | DocumentPrivilege | Setze Berechtigung. |

### Rückgabewert

True bei Erfolg.

## Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Siehe auch

* Klasse [DocumentPrivilege](../../documentprivilege/)
* Klasse [PdfFileSecurity](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)