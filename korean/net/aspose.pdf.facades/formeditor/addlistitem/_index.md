---
title: "FormEditor.AddListItem"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor 메서드. 리스트 박스에 새 항목을 추가합니다"
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
| fieldName | String | 새 항목이 추가될 필드의 이름. |
| itemName | String | 새 항목의 이름. |

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Export 값을 가진 새 항목을 기존 목록 상자 필드에 추가합니다. 이는 AcroForm 콤보 박스 필드에만 적용됩니다.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 항목이 추가될 필드의 이름. |
| exportName | String[] | 새 리스트 항목의 내보내기 값을 나타내는 문자열 배열, 예: (항목 레이블, 내보내기 값). |

## 예제

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### 또 보기

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


