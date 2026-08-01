---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。テキストフィールドの垂直配置スタイルを設定します"
type: docs
weight: 270
url: /ja/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

テキストフィールドの垂直配置スタイルを設定します。

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名です。 |
| 配置 | Int32 | 配置スタイルの定義で、FormFieldFacade.AlignTop、FormFieldFacade.AlignMiddle、FormFieldFacade.AlignRight を含みます。 |

### 戻り値

フィールドが見つかり、配置が正常に設定された場合は true。

## 例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


