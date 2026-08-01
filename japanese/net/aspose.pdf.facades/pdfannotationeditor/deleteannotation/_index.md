---
title: "PdfAnnotationEditor.DeleteAnnotation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。指定された注釈名の注釈を削除します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

指定された注釈名の注釈を削除します。

```csharp
public void DeleteAnnotation(string annotName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| annotName | String | 注釈名です。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


