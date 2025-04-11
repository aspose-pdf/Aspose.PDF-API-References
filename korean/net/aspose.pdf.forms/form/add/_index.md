---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: 양식 메서드. 양식에 필드를 추가합니다.
type: docs
weight: 190
url: /ko/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

양식에 필드를 추가합니다.

```csharp
public void Add(Field field, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| field | Field | 추가해야 하는 필드입니다. |
| pageNumber | Int32 | 추가된 필드가 배치될 페이지 인덱스입니다. |

### 참조

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

양식에 필드를 추가합니다.

```csharp
public void Add(Field field)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| field | Field | 추가해야 하는 필드입니다. |

### 참조

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

양식에 새 필드를 추가합니다; 이 필드가 다른 양식이나 이 양식에 이미 배치되어 있는 경우 필드의 복사본이 생성됩니다.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| field | Field | 필드 이름입니다. |
| partialName | String | 양식의 필드 이름입니다. |
| pageNumber | Int32 | 필드가 추가될 페이지 번호입니다. |

### 반환 값

추가된 필드가 반환됩니다. 필드의 복사본이 생성된 경우 반환됩니다.

### 참조

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)