---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Form 메서드. 폼에 이미 지정된 필드가 있는지 확인합니다.
type: docs
weight: 280
url: /ko/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

폼에 이미 지정된 필드가 있는지 확인합니다.

```csharp
public bool HasField(Field field)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | 확인할 필드입니다. |

### Return Value

지정된 필드 이름이 폼에 추가되면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

지정된 이름의 필드가 이미 폼에 추가되었는지 확인합니다.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) 또는 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/)의 필드입니다. |

### Return Value

지정된 필드 이름이 폼에 추가되면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

지정된 이름의 필드가 이미 폼에 추가되었는지 확인하며, 필드의 자식 계층을 탐색할 수 있는 기능을 제공합니다.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) 또는 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/)의 필드입니다. |
| searchChildren | Boolean | `true`로 설정하면 요청된 *fieldName*에 대해 폼 필드의 전체 계층이 검색됩니다 (이 경우 필요한 필드의 [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/)을 *fieldName*으로 전달해야 합니다). |

### Return Value

지정된 필드 이름이 폼에 추가되면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)