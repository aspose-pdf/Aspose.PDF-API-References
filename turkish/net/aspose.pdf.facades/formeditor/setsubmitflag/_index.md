---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Gönder butonunun gönderim bayrağını ayarlayın
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag metodu

Gönder butonunun gönderim bayrağını ayarlayın.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Gönder butonunun adı. |
| submitFormFlag | SubmitFormFlag | Gönderim bayrağı. |

### Dönüş Değeri

Alan bulunduysa ve gönderim bayrağı başarıyla ayarlandıysa true döner.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Ayrıca Bakınız

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)