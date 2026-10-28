---
title: "CosPdfDictionary.TryGetValue"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "CosPdfDictionary 메서드. 문자열, 이름, 불리언, 숫자와 같은 단순 데이터 유형에 접근합니다. 다른 유형에 대해서는 null을 반환합니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue method

string, name, bool, number와 같은 단순 데이터 유형에 접근하기 위해 사용됩니다. 다른 유형에 대해서는 null을 반환합니다.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | String | 키 값 |
| value | ICosPdfPrimitive& | 키에 대해 [`ICosPdfPrimitive`](../../icospdfprimitive/)를 반환하거나 null을 반환합니다. |

### 반환 값

`[`ICosPdfPrimitive`](../../icospdfprimitive/)`가 문자열, 이름, bool, 숫자와 같은 경우 true를 반환합니다. 다른 모든 유형에 대해서는 false를 반환합니다.

### 또 보기

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


