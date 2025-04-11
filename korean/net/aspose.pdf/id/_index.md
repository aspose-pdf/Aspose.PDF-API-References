---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id 클래스. 파일 식별자 구조를 나타냅니다.
type: docs
weight: 5850
url: /ko/net/aspose.pdf/id/
---
## ID 클래스

파일 식별자 구조를 나타냅니다.

```csharp
public class Id
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | 마지막으로 업데이트된 시점의 문서 내용을 기반으로 식별자를 변경합니다. |
| [Original](../../aspose.pdf/id/original/) { get; } | 원래 생성된 시점의 문서 내용을 기반으로 하는 영구 식별자입니다. |

## 예제

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)