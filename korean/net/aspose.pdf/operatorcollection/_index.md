---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OperatorCollection 클래스. 클래스는 연산자 컬렉션을 나타냅니다.
type: docs
weight: 7080
url: /ko/net/aspose.pdf/operatorcollection/
---
## OperatorCollection 클래스

클래스는 연산자 컬렉션을 나타냅니다.

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | 컬렉션의 연산자 수를 가져옵니다. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | 컬렉션이 빠른 텍스트 추출로 제한되는지 여부를 나타냅니다. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | 인덱스로 연산자를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 IOperatorSelector 방문자 객체를 수락합니다. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | 다른 컬렉션의 모든 연산자를 컬렉션에 추가합니다. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | 컬렉션에 새 연산자를 추가합니다. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | 내용의 연산자 끝에 연산자를 추가합니다. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | 마지막 업데이트를 취소합니다. 이 메서드는 변경 사항이 내용 업데이트를 발생시키지 않아야 할 때 호출될 수 있습니다. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | 목록에서 모든 연산자를 제거합니다. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | 컬렉션에 주어진 연산자가 포함되어 있으면 true를 반환합니다. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | 연산자를 연산자 목록에 복사합니다. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | 컬렉션에서 연산자를 삭제합니다. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | 컬렉션에서 연산자를 삭제합니다. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | 컬렉션에서 연산자를 삭제합니다. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정하는 데 관련된 애플리케이션 정의 작업을 수행합니다. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | 컬렉션에 대한 열거자를 반환합니다. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | 주어진 위치에 연산자를 삽입합니다. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | 컬렉션에 연산자를 삽입합니다. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | 주어진 위치에 연산자를 삽입합니다. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | 컬렉션에서 연산자를 제거합니다. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | 컬렉션의 연산자를 다른 연산자로 교체합니다. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | 문서 업데이트를 재개합니다. 보류 중인 변경 사항이 있는 경우 내용 스트림을 업데이트합니다. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | 문서 업데이트를 재개합니다. 보류 중인 변경 사항이 있는 경우 내용 스트림을 업데이트합니다. invalidate 매개변수가 true인 경우 모든 연산자를 "변경됨"으로 표시합니다. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | 내용 데이터를 업데이트하지 않습니다. ResumeUpdate가 호출될 때까지 내용 스트림은 업데이트되지 않습니다. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | 연산자의 텍스트 표현을 반환합니다. |

### 참조

* 클래스 [BaseOperatorCollection](../baseoperatorcollection/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)