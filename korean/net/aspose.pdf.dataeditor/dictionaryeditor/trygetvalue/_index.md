---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor 메서드. 문자열, 이름, 불리언, 숫자와 같은 간단한 데이터 유형에 접근합니다. 다른 유형에 대해서는 null을 반환합니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue 메서드

문자열, 이름, 불리언, 숫자와 같은 간단한 데이터 유형에 접근합니다. 다른 유형에 대해서는 null을 반환합니다.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| key | String | 키 값 |
| value | ICosPdfPrimitive& | 키에 대한 [`ICosPdfPrimitive`](../../icospdfprimitive/)를 반환하거나 null을 반환합니다. |

### 반환 값

[`ICosPdfPrimitive`](../../icospdfprimitive/)가 문자열, 이름, 불리언, 숫자와 같으면 true를 반환합니다. 다른 모든 유형에 대해서는 false를 반환합니다.

### 참조

* 인터페이스 [ICosPdfPrimitive](../../icospdfprimitive/)
* 클래스 [DictionaryEditor](../)
* 네임스페이스 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 어셈블리 [Aspose.PDF](../../../)