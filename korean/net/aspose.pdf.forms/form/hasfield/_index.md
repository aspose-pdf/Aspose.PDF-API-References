---
title: "Form.HasField"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 메서드. 양식에 지정된 필드가 이미 있는지 확인합니다."
type: docs
weight: 300
url: /ko/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

양식에 지정된 필드가 이미 있는지 확인합니다.

```csharp
public bool HasField(Field field)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 필드 | 필드 | 확인할 필드. |

### 반환 값

`true` 지정된 필드 이름이 Form에 추가된 경우; 그렇지 않으면 `false`.

### 또 보기

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

지정된 이름을 가진 필드가 이미 양식에 추가되었는지 확인합니다.

```csharp
public bool HasField(string fieldName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) 또는 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) 필드. |

### 반환 값

`true` 지정된 필드 이름이 Form에 추가된 경우; 그렇지 않으면 `false`.

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

지정된 이름을 가진 필드가 이미 양식에 추가되었는지, 필드의 자식 계층 구조까지 확인할 수 있는지 판단합니다.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) 또는 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) 필드. |
| searchChildren | Boolean | `true` 로 설정하면 요청된 *fieldName*에 대해 양식 필드 전체 계층이 검색됩니다 (이 경우 필요한 필드의 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/)을 *fieldName*으로 전달해야 함을 참고하십시오). |

### 반환 값

`true` 지정된 필드 이름이 Form에 추가된 경우; 그렇지 않으면 `false`.

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


