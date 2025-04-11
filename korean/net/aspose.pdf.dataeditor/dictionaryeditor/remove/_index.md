---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor 메서드. DictionaryEditor에서 지정된 키를 가진 요소를 제거합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

[`DictionaryEditor`](../)에서 지정된 키를 가진 요소를 제거합니다.

```csharp
public bool Remove(string key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| key | String | 제거할 요소의 키입니다. |

### 반환 값

요소가 성공적으로 제거되면 true; 그렇지 않으면 false. 이 메서드는 원래 사전에서 키를 찾을 수 없거나 키가 편집할 수 없는 경우에도 false를 반환합니다.

### 참조

* 클래스 [DictionaryEditor](../)
* 네임스페이스 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

[`DictionaryEditor`](../)에서 특정 객체의 첫 번째 발생을 제거합니다.

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | KeyValuePair`2 | [`DictionaryEditor`](../)에서 제거할 객체입니다. |

### 반환 값

item이 [`DictionaryEditor`](../)에서 성공적으로 제거되면 true; 그렇지 않으면 false. 이 메서드는 item이 원래 [`DictionaryEditor`](../)에서 발견되지 않은 경우에도 false를 반환합니다.

### 참조

* 인터페이스 [ICosPdfPrimitive](../../icospdfprimitive/)
* 클래스 [DictionaryEditor](../)
* 네임스페이스 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 어셈블리 [Aspose.PDF](../../../)