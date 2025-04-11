---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。テキストフィールドの整列スタイルを設定します
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment メソッド

テキストフィールドの整列スタイルを設定します。

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 定義されたフィールド名。 |
| alignment | Int32 | 整列スタイルの定義。FormFieldFacade.AlignLeft、FormFieldFacade.AlignCenter、FormFieldFacade.AlignRight を含みます。 |

### 戻り値

フィールドが見つかり、整列が設定された場合は true を返します。

## 例

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)