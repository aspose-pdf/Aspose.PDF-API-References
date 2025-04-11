---
title: DictionaryEditor.Item
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor 속성. 지정된 키를 가진 요소를 가져오거나 설정합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor 인덱서

지정된 키를 가진 요소를 가져오거나 설정합니다.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| key | 가져오거나 설정할 요소의 키입니다. |

### 반환 값

지정된 키를 가진 요소입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 키가 null입니다. |
| KeyNotFoundException | 속성이 검색되었지만 키를 찾을 수 없습니다. |
| ArgumentException | 키를 편집하거나 설정할 수 없는 경우 예외를 발생시킵니다. |

### 참조

* 인터페이스 [ICosPdfPrimitive](../../icospdfprimitive/)
* 클래스 [DictionaryEditor](../)
* 네임스페이스 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 어셈블리 [Aspose.PDF](../../../)