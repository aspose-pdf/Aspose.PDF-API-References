---
title: Class BoundsCheckableListT
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Generator.BoundsCheckableList1T 클래스. System.Collections.Generic.List를 감싸는 BoundsCheckableList를 나타냅니다.
type: docs
weight: 5340
url: /ko/net/aspose.pdf.generator/boundscheckablelist-1/
---
## BoundsCheckableList&lt;T&gt; 클래스

System.Collections.Generic.List를 감싸는 BoundsCheckableList를 나타냅니다.

```csharp
public class BoundsCheckableList<T> : IList<T>
    where T : IBoundsCheckableItem
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BoundsCheckableList](boundscheckablelist/#constructor)() | BoundsCheckableList 클래스의 새 인스턴스를 초기화합니다. |
| [BoundsCheckableList](boundscheckablelist/#constructor_1)(BoundsCheckMode, double, double) | BoundsCheckableList 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.generator/boundscheckablelist-1/count/) { get; } | System.Collections.Generic.List에 포함된 요소의 수를 가져옵니다. |
| [IsReadOnly](../../aspose.pdf.generator/boundscheckablelist-1/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf.generator/boundscheckablelist-1/item/) { get; set; } | 컬렉션에서 단락을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.generator/boundscheckablelist-1/add/)(T) | "boundsCheckMode" 매개변수에 따라 System.Collections.Generic.List의 끝에 객체를 추가합니다. |
| [Clear](../../aspose.pdf.generator/boundscheckablelist-1/clear/)() | System.Collections.Generic.List에서 모든 요소를 제거합니다. |
| [Contains](../../aspose.pdf.generator/boundscheckablelist-1/contains/)(T) | 요소가 System.Collections.Generic.List에 있는지 여부를 결정합니다. |
| [CopyTo](../../aspose.pdf.generator/boundscheckablelist-1/copyto/)(T[], int) |  |
| [GetEnumerator](../../aspose.pdf.generator/boundscheckablelist-1/getenumerator/)() | System.Collections.Generic.List를 반복하는 열거자를 반환합니다. |
| [IndexOf](../../aspose.pdf.generator/boundscheckablelist-1/indexof/)(T) | 지정된 객체를 검색하고 전체 System.Collections.Generic.List 내에서 첫 번째 발생의 0 기반 인덱스를 반환합니다. |
| [Insert](../../aspose.pdf.generator/boundscheckablelist-1/insert/)(int, T) | 지정된 인덱스에 System.Collections.Generic.List에 요소를 삽입합니다. |
| [Remove](../../aspose.pdf.generator/boundscheckablelist-1/remove/)(T) | System.Collections.Generic.List에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [RemoveAt](../../aspose.pdf.generator/boundscheckablelist-1/removeat/)(int) | System.Collections.Generic.List의 지정된 인덱스에 있는 요소를 제거합니다. |
| [UpdateBoundsCheckMode](../../aspose.pdf.generator/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode)(BoundsCheckMode) | 초기화된 컬렉션의 boundsCheckMode 매개변수를 업데이트합니다. |
| [UpdateBoundsCheckMode](../../aspose.pdf.generator/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode_1)(BoundsCheckMode, double, double) | 초기화된 컬렉션의 boundsCheckMode 매개변수를 업데이트합니다. |

### 참조

* 인터페이스 [IBoundsCheckableItem](../iboundscheckableitem/)
* 네임스페이스 [Aspose.Pdf.Generator](../../aspose.pdf.generator/)
* 어셈블리 [Aspose.PDF](../../)