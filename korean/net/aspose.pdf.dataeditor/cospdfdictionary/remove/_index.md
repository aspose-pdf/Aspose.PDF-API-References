---
title: "CosPdfDictionary.Remove"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "CosPdfDictionary 메서드. 지정된 키를 가진 요소를 CosPdfDictionary에서 제거합니다."
type: docs
weight: 150
url: /ko/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

지정된 키를 가진 요소를 [`CosPdfDictionary`](../)에서 제거합니다.

```csharp
public bool Remove(string key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | String | 제거할 요소의 키. |

### 반환 값

요소가 성공적으로 제거되면 true, 그렇지 않으면 false. 원본 사전에서 키를 찾지 못했거나 키가 편집 가능하지 않은 경우에도 false를 반환합니다.

### 또 보기

* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

특정 객체의 첫 번째 발생을 [`CosPdfDictionary`](../)에서 제거합니다.

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | KeyValuePair`2 | [`CosPdfDictionary`](../)에서 제거할 객체입니다. |

### 반환 값

[`CosPdfDictionary`](../)에서 항목이 성공적으로 제거되면 true; 그렇지 않으면 false. 원본 [`CosPdfDictionary`](../)에서 항목을 찾지 못한 경우에도 false를 반환합니다.

### 또 보기

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


