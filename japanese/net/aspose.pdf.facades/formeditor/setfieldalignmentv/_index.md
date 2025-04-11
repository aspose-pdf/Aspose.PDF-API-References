---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。テキストフィールドの垂直アラインメントスタイルを設定します。
type: docs
weight: 270
url: /ja/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV メソッド

テキストフィールドの垂直アラインメントスタイルを設定します。

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 修飾されたフィールド名。 |
| alignment | Int32 | アラインメントスタイルの定義。FormFieldFacade.AlignTop、FormFieldFacade.AlignMiddle、FormFieldFacade.AlignRight を含みます。 |

### 戻り値

フィールドが見つかり、アラインメントが正常に設定された場合は true を返します。

## 例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)