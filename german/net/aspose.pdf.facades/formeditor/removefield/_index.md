---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Entfernen Sie das Feld aus dem Formular
type: docs
weight: 210
url: /de/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField-Methode

Entfernen Sie das Feld aus dem Formular.

```csharp
public void RemoveField(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes, das entfernt werden muss. |

## Beispiele

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)