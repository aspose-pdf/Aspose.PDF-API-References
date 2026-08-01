---
title: "DictionaryEditor.Item"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "DictionaryEditor 속성. 지정된 키를 가진 요소를 가져오거나 설정합니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor indexer

지정된 키에 해당하는 요소를 가져오거나 설정합니다.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| 키 | 가져오거나 설정할 요소의 키. |

### 반환 값

지정된 키를 가진 요소.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 키가 null입니다. |
| KeyNotFoundException | 속성을 검색했지만 키를 찾을 수 없습니다. |
| ArgumentException | 키를 편집하거나 설정할 수 없을 경우 예외를 발생시킵니다. |

### 또 보기

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


