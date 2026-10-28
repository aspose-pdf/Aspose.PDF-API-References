---
title: "CheckboxField.Value"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "CheckboxField 속성. 체크 박스 필드의 값을 가져오거나 설정합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.forms/checkboxfield/value/
---
## CheckboxField.Value property

체크 박스 필드의 값을 가져오거나 설정합니다.

```csharp
public override string Value { get; set; }
```

## 예제

이 예제는 다중값 체크박스의 값을 가져오고 설정하는 방법을 보여줍니다.

```csharp
using (Document doc = new Document("example.pdf"))
{
Form form = doc.Form;
CheckboxField checkbox = form.Fields[0] as CheckboxField;

// 허용된 값은 AllowedStates 컬렉션에서 가져올 수 있습니다.
// Value 속성을 사용하여 체크박스 값을 설정합니다.
checkbox.Value = checkbox.AllowedStates[0];
checkboxValue = checkbox.Value; // the previously set value, e.g. "option 1"

// 값은 AllowedStates의 요소 중 하나여야 합니다.
checkbox.Value = "option 2";
checkboxValue = checkbox.Value; // option 2

// Value를 "Off"로 설정하거나 Checked를 false로 설정하여 체크박스를 해제합니다.
checkbox.Value = "Off";
// 또는, 대안으로:
// checkbox.Checked = false;
checkboxValue = checkbox.Value; // Off
}
```

### 또 보기

* class [CheckboxField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


