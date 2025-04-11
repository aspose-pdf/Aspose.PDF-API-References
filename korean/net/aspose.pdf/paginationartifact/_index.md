---
title: Class PaginationArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PaginationArtifact 클래스. 문서의 페이지 매김 아티팩트를 위한 추상 기본 클래스를 나타냅니다.
type: docs
weight: 8260
url: /ko/net/aspose.pdf/paginationartifact/
---
## PaginationArtifact 클래스

문서의 페이지 매김 아티팩트를 위한 추상 기본 클래스를 나타냅니다.

```csharp
public abstract class PaginationArtifact : Artifact
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | 아티팩트의 수평 정렬. 위치가 명시적으로 지정된 경우(위치 속성에서) 이 값은 무시됩니다. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | 아티팩트의 수직 정렬. 위치가 명시적으로 지정된 경우(위치 속성에서) 이 값은 무시됩니다. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | 아티팩트의 하단 여백. 위치가 명시적으로 지정된 경우(위치 속성에서) 이 값은 무시됩니다. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | 아티팩트 내부 연산자의 컬렉션을 가져옵니다. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | 아티팩트 서브타입의 이름을 가져옵니다. 아티팩트 서브타입이 표준 서브타입이 아닌 경우에 사용될 수 있습니다. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | 아티팩트 유형의 이름을 가져옵니다. 아티팩트 유형이 비표준인 경우에 사용될 수 있습니다. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | 아티팩트의 종료 페이지 번호를 가져오거나 설정합니다. 값은 0 이상이어야 합니다. 0 미만의 값이 설정되면 0으로 조정됩니다. 기본값 0은 종료 페이지 경계가 없음을 의미합니다. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | 아티팩트의 XForm을 가져옵니다(사용되는 경우). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | 아티팩트의 이미지를 가져옵니다(존재하는 경우). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | true인 경우 아티팩트가 페이지 내용 뒤에 배치됩니다. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | 아티팩트의 왼쪽 여백. 위치가 명시적으로 지정된 경우(위치 속성에서) 이 값은 무시됩니다. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | 다중 행 텍스트 아티팩트의 행입니다. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | 아티팩트의 불투명도를 가져오거나 설정합니다. 가능한 값은 0..1 범위입니다. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | 아티팩트 위치를 가져오거나 설정합니다. 이 속성이 지정되면 여백과 정렬은 무시됩니다. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | 아티팩트의 사각형을 가져옵니다. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | 아티팩트의 오른쪽 여백. 위치가 명시적으로 지정된 경우(위치 속성에서) 이 값은 무시됩니다. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | 아티팩트 회전 각도를 가져오거나 설정합니다. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | 아티팩트의 시작 페이지 번호를 가져오거나 설정합니다. 값은 1 이상이어야 합니다. 1 미만의 값이 설정되면 1로 조정됩니다. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | 아티팩트가 적용되는 페이지의 하위 집합을 가져오거나 설정합니다(예: 모든 페이지, 짝수 페이지, 홀수 페이지). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | 아티팩트 서브타입을 가져옵니다. 아티팩트가 비표준 서브타입을 가진 경우, 서브타입의 이름은 CustomSubtype을 통해 읽을 수 있습니다. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | 아티팩트의 텍스트를 가져오거나 설정합니다. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | 아티팩트 텍스트의 텍스트 상태입니다. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | 아티팩트의 상단 여백. 위치가 명시적으로 지정된 경우(위치 속성에서) 이 값은 무시됩니다. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | 아티팩트 유형을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 지연된 업데이트를 시작합니다. 성능을 개선하기 위해 동일한 아티팩트에 여러 변경을 해야 하는 경우 이 기능을 사용하십시오. 일반적으로 아티팩트 속성이 변경될 때마다 아티팩트 연산자가 변경됩니다. 이로 인해 아티팩트가 변경될 때마다 페이지 내용이 변경됩니다. 이 효과를 피하려면 모든 아티팩트 업데이트를 StartUpdates/SaveUpdates 호출 사이에 배치하십시오. 이렇게 하면 페이지 내용을 한 번만 변경할 수 있습니다. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | 아티팩트를 폐기합니다. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | 아티팩트의 사용자 정의 값을 가져옵니다. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | 아티팩트에서 사용자 정의 값을 제거합니다. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() 호출 이후에 수행된 아티팩트의 모든 업데이트를 저장합니다. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | 아티팩트의 이미지를 설정합니다. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | 아티팩트의 이미지를 설정합니다. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | 아티팩트의 텍스트 및 텍스트 속성을 설정합니다. 여러 행을 지정할 수 있습니다. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | 페이지 번호로 대체될 문자열을 설정합니다. 기본값은 #입니다. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | 문서 페이지에 아티팩트로 배치된 PDF 페이지를 설정합니다. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | 아티팩트의 텍스트를 설정합니다. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | 아티팩트의 텍스트 및 텍스트 속성을 설정합니다. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | 아티팩트의 사용자 정의 값을 설정합니다. |

### 참조

* 클래스 [Artifact](../artifact/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)