---
title: "Form.FillField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 전체 지정된 필드 이름에 따라 유효한 값으로 필드를 채웁니다. 필드를 채우기 전에 모든 필드 이름과 해당 유효한 값을 알아야 합니다. 필드 이름과 값은 대소문자를 구분합니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않음을 유의하십시오. 예를 들어 필드의 전체 이름이 Form.Subform.TextField인 경우 TextField가 아니라 전체 이름을 지정해야 합니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

전체 한정 필드 이름에 따라 필드를 유효한 값으로 채웁니다. 필드를 채우기 전에 모든 필드 이름과 해당 유효 값들을 알아야 합니다. 필드 이름과 값은 대소문자를 구분합니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다; 예를 들어 필드의 전체 이름이 "Form.Subform.TextField"인 경우 전체 이름을 지정해야 하며 "TextField"만 지정해서는 안 됩니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 채워야 할 필드 이름입니다. |
| fieldValue | String | 일부 필드에 대해 유효한 값이어야 하는 필드 값입니다. |

### 반환 값

필드를 찾고 성공적으로 채우면 true입니다.

## 예제

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//부분 이름으로 필드를 검색하는 방법:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

전체 한정 필드 이름에 따라 라디오 박스 필드를 유효한 인덱스 값으로 채웁니다. 필드를 채우기 전에 필드 이름만 알아야 합니다. 값은 인덱스로 지정할 수 있습니다. 참고: 라디오 박스, 콤보 박스 및 리스트 박스 필드에만 적용됩니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다; 예를 들어 필드의 전체 이름이 "Form.Subform.ListBoxField"인 경우 전체 이름을 지정해야 하며 "ListBoxField"만 지정해서는 안 됩니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다.

```csharp
public bool FillField(string fieldName, int index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 채워야 할 필드 이름. |
| index | Int32 | 선택된 항목의 인덱스. |

### 반환 값

필드를 찾고 성공적으로 채우면 true입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//부분 이름으로 필드를 검색하는 방법:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

체크 박스 필드를 불리언 값으로 채웁니다. 참고: 체크 박스에만 적용됩니다. Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다; 예를 들어 필드의 전체 이름이 "Form.Subform.CheckBoxField"인 경우 전체 이름을 지정해야 하며 "CheckBoxField"만 지정해서는 안 됩니다. 기존 필드 이름을 탐색하고 부분 이름으로 필요한 필드를 검색하려면 FieldNames 속성을 사용할 수 있습니다.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 채워야 할 필드 이름입니다. |
| beChecked | Boolean | 불리언 플래그: true는 체크 박스를 선택함을 의미하고, false는 선택 해제함을 의미합니다. |

### 반환 값

필드를 찾고 성공적으로 채우면 true입니다.

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//부분 이름으로 필드를 검색하는 방법:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

다중 선택으로 필드를 채웁니다. 참고: AcroForm 리스트 박스 필드에만 적용됩니다.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 전체 한정된 필드 이름. |
| fieldValues | String[] | 선택할 여러 항목을 포함하는 문자열 배열입니다. |

## 예제

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

지정된 값으로 필드를 채웁니다.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 필드 이름 |
| 값 | String | 필드의 새 값 |
| fitFontSize | Boolean | true이면 편집 상자의 글꼴 크기가 맞춰집니다. |

### 반환 값

필드를 찾고 성공적으로 채우면 true입니다.

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


