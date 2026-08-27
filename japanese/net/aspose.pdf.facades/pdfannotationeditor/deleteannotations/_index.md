---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。ドキュメント内のすべての注釈を削除します"
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

ドキュメント内のすべての注釈を削除します。

```csharp
public void DeleteAnnotations()
```

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

ドキュメント内の指定されたタイプのすべての注釈を削除します。

```csharp
public void DeleteAnnotations(string annotType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| annotType | String | 削除される注釈のタイプです。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


