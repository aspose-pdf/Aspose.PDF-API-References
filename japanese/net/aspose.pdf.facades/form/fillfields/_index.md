---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。テキストボックスフィールドにテキスト値を入力し、ドキュメントを保存します。署名されたドキュメントに関連しています。注意 テキストボックスにのみ適用されます。フィールド名と値は大文字と小文字を区別します。
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields メソッド

テキストボックスフィールドにテキスト値を入力し、ドキュメントを保存します。署名されたドキュメントに関連しています。注意: テキストボックスにのみ適用されます。フィールド名と値は大文字と小文字を区別します。

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldNames | String[] | フィールドの名前。 |
| fieldValues | String[] | フィールドの新しい値。 |
| output | Stream& | ドキュメントが保存されるストリーム。 |

### 戻り値

フィールドが見つかり、正常に入力された場合は true。

## 例

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)