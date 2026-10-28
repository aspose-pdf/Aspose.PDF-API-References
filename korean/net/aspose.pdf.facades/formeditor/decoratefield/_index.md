---
title: "FormEditor.DecorateField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 지정된 필드의 시각적 속성을 변경합니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/formeditor/decoratefield/
---
## DecorateField(string) {#decoratefield_2}

지정된 필드의 시각적 속성을 변경합니다.

```csharp
public void DecorateField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 전체 한정된 필드 이름. |

## 예제

```csharp
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

지정된 필드 유형을 가진 모든 필드의 시각적 속성을 변경합니다.

```csharp
public void DecorateField(FieldType fieldType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldType | FieldType | 데코레이션될 필드의 유형. |

## 예제

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//모든 텍스트 필드를 데코레이션합니다.
fe.DecorateField(FieldType.Text);
```

### 또 보기

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

PDF 문서의 모든 필드에 대한 시각적 속성을 변경합니다.

```csharp
public void DecorateField()
```

## 예제

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//모든 필드를 데코레이션합니다.
fe.DecorateField();
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


