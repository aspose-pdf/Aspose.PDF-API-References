---
title: "클래스 Id"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Id 클래스. 파일 식별자 구조를 나타냅니다"
type: docs
weight: 5980
url: /ko/net/aspose.pdf/id/
---
## Id class

파일 식별자 구조를 나타냅니다.

```csharp
public class Id
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | 마지막으로 업데이트된 시점의 문서 내용에 따라 식별자를 변경합니다. |
| [Original](../../aspose.pdf/id/original/) { get; } | 원래 생성된 시점의 문서 내용에 기반한 영구 식별자입니다. |

## 예제

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


