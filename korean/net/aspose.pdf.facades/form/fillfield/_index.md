---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 완전한 필드 이름에 따라 유효한 값으로 필드를 채웁니다. 필드를 채우기 전에 모든 필드 이름과 해당 유효한 값이 알려져 있어야 합니다. 필드 이름과 값 모두 대소문자를 구분합니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과는 달리 부분 필드 이름으로는 작동하지 않습니다. 예를 들어 필드의 전체 이름이 Form.Subform.TextField인 경우 전체 이름을 지정해야 하며 TextField를 지정해서는 안 됩니다. FieldNames 속성을 사용하여 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색할 수 있습니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

지정된 값으로 필드를 채웁니다.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드의 이름 |
| value | String | 필드의 새 값 |
| fitFontSize | Boolean | true인 경우 편집 상자의 글꼴 크기가 조정됩니다. |

### 반환 값

필드를 찾고 성공적으로 채운 경우 true입니다.

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

완전한 필드 이름에 따라 유효한 값으로 필드를 채웁니다. 필드를 채우기 전에 모든 필드 이름과 해당 유효한 값이 알려져 있어야 합니다. 필드 이름과 값 모두 대소문자를 구분합니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과는 달리 부분 필드 이름으로는 작동하지 않습니다. 예를 들어 필드의 전체 이름이 "Form.Subform.TextField"인 경우 전체 이름을 지정해야 하며 "TextField"를 지정해서는 안 됩니다. FieldNames 속성을 사용하여 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색할 수 있습니다.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 채워야 할 필드의 이름입니다. |
| fieldValue | String | 필드의 값으로, 일부 필드에 대해 유효한 값이어야 합니다. |

### 반환 값

필드를 찾고 성공적으로 채운 경우 true입니다.

## 예제

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

완전한 필드 이름에 따라 유효한 인덱스 값으로 라디오 박스 필드를 채웁니다. 필드를 채우기 전에 필드 이름만 알고 있으면 됩니다. 값은 인덱스로 지정할 수 있습니다. 주의: 라디오 박스, 콤보 박스 및 리스트 박스 필드에만 적용됩니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과는 달리 부분 필드 이름으로는 작동하지 않습니다. 예를 들어 필드의 전체 이름이 "Form.Subform.ListBoxField"인 경우 전체 이름을 지정해야 하며 "ListBoxField"를 지정해서는 안 됩니다. FieldNames 속성을 사용하여 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색할 수 있습니다.

```csharp
public bool FillField(string fieldName, int index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 채워야 할 필드의 이름입니다. |
| index | Int32 | 선택한 항목의 인덱스입니다. |

### 반환 값

필드를 찾고 성공적으로 채운 경우 true입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

부울 값으로 체크 박스 필드를 채웁니다. 주의: 체크 박스에만 적용됩니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과는 달리 부분 필드 이름으로는 작동하지 않습니다. 예를 들어 필드의 전체 이름이 "Form.Subform.CheckBoxField"인 경우 전체 이름을 지정해야 하며 "CheckBoxField"를 지정해서는 안 됩니다. FieldNames 속성을 사용하여 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색할 수 있습니다.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 채워야 할 필드의 이름입니다. |
| beChecked | Boolean | 부울 플래그: true는 체크 박스를 체크하고, false는 체크 해제를 의미합니다. |

### 반환 값

필드를 찾고 성공적으로 채운 경우 true입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

여러 선택으로 필드를 채웁니다. 주의: AcroForm 리스트 박스 필드에만 해당됩니다.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 완전한 필드 이름입니다. |
| fieldValues | String[] | 선택할 여러 항목을 포함하는 문자열 배열입니다. |

## 예제

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

지정된 값으로 필드를 채웁니다.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드의 이름 |
| value | String | 필드의 새 값 |
| fitFontSize | Boolean | true인 경우 편집 상자의 글꼴 크기가 조정됩니다. |

### 반환 값

필드를 찾고 성공적으로 채운 경우 true입니다.

### 참조

* 클래스 [Form](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)