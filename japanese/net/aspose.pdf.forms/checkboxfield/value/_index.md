---
title: "CheckboxField.Value"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "CheckboxField プロパティ。チェックボックスフィールドの値を取得または設定します。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

チェックボックスフィールドの値を取得または設定します。

```csharp
public override string Value { get; set; }
```

## 例

この例は、マルチバリューのチェックボックスの値を取得および設定する方法を示しています。

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// 許可された値は AllowedStates コレクションから取得できます。
// Value プロパティを使用してチェックボックスの値を設定します。
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// 値は AllowedStates のいずれかの要素である必要があります。
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Value を "Off" に設定するか、Checked を false に設定することでチェックボックスのチェックを外せます。
checkbox.Value = "Off";
// または、代わりに：
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### 関連項目

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


