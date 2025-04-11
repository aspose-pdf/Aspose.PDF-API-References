---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Formda gönder butonu ekle
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn metodu

Formda gönder butonu ekle.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Yeni butonun adı. |
| page | Int32 | Butonun yerleştirileceği sayfa. |
| label | String | Buton başlığı. |
| url | String | Gönder butonunun URL'si. |
| llx | Single | Sol alt köşenin abscissası. |
| lly | Single | Sol alt köşenin ordinatı. |
| urx | Single | Sağ üst köşenin abscissası. |
| ury | Single | Sağ üst köşenin ordinatı. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Ayrıca Bakınız

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)