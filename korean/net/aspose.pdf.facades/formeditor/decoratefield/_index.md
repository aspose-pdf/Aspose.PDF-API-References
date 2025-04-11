---
title: FormEditor.DecorateField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 지정된 필드의 시각적 속성을 변경합니다.
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
| fieldName | String | 완전한 필드 이름입니다. |

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

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## DecorateField(FieldType) {#decoratefield_1}

지정된 필드 유형의 모든 필드의 시각적 속성을 변경합니다.

```csharp
public void DecorateField(FieldType fieldType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldType | FieldType | 장식될 필드의 유형입니다. |

## 예제

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignRight;
//decorate all text fields.
fe.DecorateField(FieldType.Text);
```

### 참조

* 열거형 [FieldType](../../fieldtype/)
* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## DecorateField() {#decoratefield}

PDF 문서의 모든 필드의 시각적 속성을 변경합니다.

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
//decorate all fields.
fe.DecorateField();
```

### 참조

* 클래스 [FormEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)