---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 목록 상자에 새 항목을 추가합니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

목록 상자에 새 항목을 추가합니다.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 새 항목이 추가될 필드의 이름입니다. |
| itemName | String | 새 항목의 이름입니다. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### 참조

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

기존 목록 상자 필드에 Export 값을 가진 새 항목을 추가합니다. 이는 AcroForm 콤보 상자 필드에만 해당됩니다.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 항목이 추가될 필드의 이름입니다. |
| exportName | String[] | Export Value가 있는 새 목록 항목을 나타내는 문자열 배열입니다. 즉, (항목 레이블, Export Value)입니다. |

## 예제

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### 참조

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)