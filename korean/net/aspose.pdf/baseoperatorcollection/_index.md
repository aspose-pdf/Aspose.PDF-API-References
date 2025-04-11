---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection 클래스. 연산자 컬렉션의 기본 클래스를 나타냅니다.
type: docs
weight: 2830
url: /ko/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection 클래스

연산자 컬렉션의 기본 클래스를 나타냅니다.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | 컬렉션의 연산자 수를 가져옵니다. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | 컬렉션이 빠른 텍스트 추출로 제한되는지 여부를 나타냅니다. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인 경우 true를 반환합니다. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | 인덱스를 통해 연산자를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | 컬렉션에 새로운 연산자를 추가합니다. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | 마지막 업데이트를 취소합니다. 이 메서드는 변경 사항이 내용 업데이트를 발생시키지 않아야 할 때 호출될 수 있습니다. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | 컬렉션을 지웁니다. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | 컬렉션에 연산자가 존재하는지 확인합니다. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | 연산자를 연산자 목록에 복사합니다. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | 컬렉션에 대한 열거자를 반환합니다. |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | 컬렉션에 연산자를 삽입합니다. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | 컬렉션에서 연산자를 제거합니다. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | 문서 업데이트를 재개합니다. 보류 중인 변경 사항이 있는 경우 내용 스트림을 업데이트합니다. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | 내용 데이터를 업데이트하지 않습니다. ResumeUpdate가 호출될 때까지 내용 스트림은 업데이트되지 않습니다. |

### 참조

* 클래스 [Operator](../operator/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)