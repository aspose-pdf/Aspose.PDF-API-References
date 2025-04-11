---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: CheckboxField プロパティ。チェックボックスフィールドの値を取得または設定します
type: docs
weight: 70
url: /ja/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value プロパティ

チェックボックスフィールドの値を取得または設定します。

```csharp
public override string Value { get; set; }
```

## 例

この例では、複数の値を持つチェックボックスの値を取得および設定する方法を示します。

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// Allowed values may be retrieved from the AllowedStates collection
// Set the checkbox value using Value property
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// The value should be any element of AllowedStates
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Uncheck boxes by either setting Value to "Off" or setting Checked to false
checkbox.Value = "Off";
// or, alternately:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### 関連項目

* クラス [CheckboxField](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)