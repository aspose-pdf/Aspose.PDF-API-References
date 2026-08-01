---
title: "클래스 BaseOperatorCollection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.BaseOperatorCollection 클래스. 연산자 컬렉션의 기본 클래스를 나타냅니다."
type: docs
weight: 2940
url: /ko/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

연산자 컬렉션에 대한 기본 클래스를 나타냅니다.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | 컬렉션에 있는 연산자의 수를 가져옵니다. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | 컬렉션이 빠른 텍스트 추출에 제한되는지 여부를 나타냅니다. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용이면 true를 반환합니다. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | 인덱스로 연산자를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | 새 연산자를 컬렉션에 추가합니다. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | 마지막 업데이트를 취소합니다. 이 메서드는 변경 사항이 내용 업데이트를 발생시키지 않아야 할 때 호출될 수 있습니다. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | 컬렉션을 비웁니다. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | 컬렉션에 연산자가 존재하는지 확인합니다. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | 연산자를 연산자 목록에 복사합니다. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | 컬렉션에 대한 열거자를 반환합니다. |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | 연산자를 컬렉션에 삽입합니다. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | 컬렉션에서 연산자를 제거합니다. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | 문서 업데이트를 재개합니다. 보류 중인 변경 사항이 있는 경우 내용 스트림을 업데이트합니다. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | 내용 업데이트 데이터를 억제합니다. ResumeUpdate가 호출될 때까지 내용 스트림이 업데이트되지 않습니다. |

### 또 보기

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


