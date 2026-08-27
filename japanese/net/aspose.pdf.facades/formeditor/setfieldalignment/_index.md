---
title: "FormEditor.SetFieldAlignment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。テキストフィールドの配置スタイルを設定します。"
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

テキストフィールドの配置スタイルを設定します。

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名です。 |
| 配置 | Int32 | 配置スタイルの定義で、FormFieldFacade.AlignLeft、FormFieldFacade.AlignCenter、FormFieldFacade.AlignRight を含みます。 |

### 戻り値

フィールドが見つかり、配置が設定された場合は true です。

## 例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


