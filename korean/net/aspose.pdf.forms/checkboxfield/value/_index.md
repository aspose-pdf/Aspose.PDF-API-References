---
title: CheckboxField.Value
second_title: Aspose.PDF for .NET API Reference
description: CheckboxField 속성. 체크 박스 필드의 값을 가져오거나 설정합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value 속성

체크 박스 필드의 값을 가져오거나 설정합니다.

```csharp
public override string Value { get; set; }
```

## 예제

이 예제는 다중 값 체크 박스의 값을 가져오고 설정하는 방법을 보여줍니다.

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

### 참조

* 클래스 [CheckboxField](../)
* 네임스페이스 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../../)