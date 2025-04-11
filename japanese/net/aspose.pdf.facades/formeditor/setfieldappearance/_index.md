---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。フィールドフラグを設定します
type: docs
weight: 280
url: /ja/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance メソッド

フィールドフラグを設定します

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フラグを更新するフィールドの名前。 |
| flags | AnnotationFlags | フィールドのフラグ。 |

### 戻り値

フラグが正常に更新された場合は true。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### 関連項目

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)