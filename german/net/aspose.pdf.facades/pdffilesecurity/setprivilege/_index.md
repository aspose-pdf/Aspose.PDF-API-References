---
title: SetPrivilege
second_title: Aspose.PDF für .NET-API-Referenz
description: Legt die PDF-Dateisicherheit mit leeren Benutzer-/Eigentümerkennwörtern fest. Das Eigentümerkennwort wird durch eine zufällige Zeichenfolge hinzugefügt. Löst eine Ausnahme aus wenn der Vorgang fehlschlägt.
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Legt die PDF-Dateisicherheit mit leeren Benutzer-/Eigentümerkennwörtern fest. Das Eigentümerkennwort wird durch eine zufällige Zeichenfolge hinzugefügt. Löst eine Ausnahme aus, wenn der Vorgang fehlschlägt.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| privilege | DocumentPrivilege | Privileg setzen. |

### Rückgabewert

Wahr für den Erfolg.

### Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden.
string outFile = "D:\\output.pdf"; //Der TestPath kann neu zugewiesen werden.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Siehe auch

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* namensraum [Aspose.Pdf.Facades](../../pdffilesecurity)
* Montage [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Legt die PDF-Dateisicherheit mit dem ursprünglichen Passwort fest. Löst eine Ausnahme aus, wenn der Vorgang fehlschlägt.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userPassword | String | Ursprüngliches Benutzerkennwort. |
| ownerPassword | String | Ursprüngliches Besitzerkennwort. |
| privilege | DocumentPrivilege | Privileg setzen. |

### Rückgabewert

Wahr für den Erfolg.

### Beispiele

```csharp
[C#]
string inFile = "D:\\input.pdf"; //Der TestPath kann neu zugewiesen werden.
string outFile = "D:\\output.pdf"; //Der TestPath kann neu zugewiesen werden.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Siehe auch

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* namensraum [Aspose.Pdf.Facades](../../pdffilesecurity)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
