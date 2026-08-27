---
title: "클래스 HeaderArtifact"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HeaderArtifact 클래스. 헤더 아티팩트를 설명하는 클래스입니다. 이 아티팩트는 페이지의 헤딩을 설정하는 데 사용할 수 있습니다."
type: docs
weight: 5540
url: /ko/net/aspose.pdf/headerartifact/
---
## HeaderArtifact class

Heaader 아티팩트를 설명하는 클래스입니다. 이 artifacgt는 페이지의 머리글을 설정하는 데 사용할 수 있습니다.

```csharp
public class HeaderArtifact : Artifact
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HeaderArtifact](headerartifact/)() | Header Artifact 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | 아티팩트의 수평 정렬. Position 속성에서 위치가 명시적으로 지정된 경우 이 값은 무시됩니다. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | 아티팩트의 수직 정렬. Position 속성에서 위치가 명시적으로 지정된 경우 이 값은 무시됩니다. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | 아티팩트의 하단 여백. Position 속성에서 위치가 명시적으로 지정된 경우 이 값은 무시됩니다. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | 아티팩트 내부 연산자의 컬렉션을 가져옵니다. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | 아티팩트 하위 유형의 이름을 가져옵니다. 아티팩트 하위 유형이 표준 하위 유형이 아닌 경우에 사용할 수 있습니다. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | 아티팩트 유형의 이름을 가져옵니다. 아티팩트 유형이 비표준인 경우에 사용할 수 있습니다. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | 아티팩트의 XForm을 가져옵니다 (XForm이 사용되는 경우). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | 아티팩트의 이미지를 가져옵니다 (존재하는 경우). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | true인 경우, 아티팩트가 페이지 내용 뒤에 배치됩니다. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | 아티팩트의 왼쪽 여백. Position 속성에서 위치가 명시적으로 지정된 경우 이 값은 무시됩니다. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | 다중 행 텍스트 아티팩트의 라인들. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | 아티팩트의 불투명도를 가져오거나 설정합니다. 가능한 값은 0..1 범위입니다. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | 아티팩트 위치를 가져오거나 설정합니다. 이 속성이 지정되면 여백과 정렬이 무시됩니다. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | 아티팩트의 사각형을 가져옵니다. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | 아티팩트의 오른쪽 여백. Position 속성에서 위치가 명시적으로 지정된 경우 이 값은 무시됩니다. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | 아티팩트 회전 각도를 가져오거나 설정합니다. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | 아티팩트 하위 유형을 가져옵니다. 아티팩트에 비표준 하위 유형이 있는 경우, CustomSubtype을 통해 하위 유형 이름을 읽을 수 있습니다. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | 아티팩트의 텍스트를 가져옵니다. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | 아티팩트 텍스트의 텍스트 상태. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | 아티팩트의 상단 여백. Position 속성에서 위치가 명시적으로 지정된 경우 이 값은 무시됩니다. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | 아티팩트 유형을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 지연된 업데이트를 시작합니다. 성능을 향상시키기 위해 동일한 아티팩트에 여러 번 변경해야 할 경우 이 기능을 사용하십시오. 일반적으로 아티팩트 속성이 변경될 때마다 아티팩트 연산자가 변경됩니다. 이는 아티팩트가 변경될 때마다 페이지 내용이 매번 변경되는 원인이 됩니다. 이 효과를 피하려면 모든 아티팩트 업데이트를 StartUpdates/SaveUpdates 호출 사이에 배치하십시오. 이렇게 하면 페이지 내용을 한 번만 변경할 수 있습니다. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | 아티팩트를 해제합니다. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | 아티팩트의 사용자 지정 값을 가져옵니다. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | 아티팩트에서 사용자 지정 값을 제거합니다. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() 호출 이후에 수행된 아티팩트의 모든 업데이트를 저장합니다. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | 아티팩트의 이미지를 설정합니다. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | 아티팩트의 이미지를 설정합니다. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | 아티팩트의 텍스트와 텍스트 속성을 설정합니다. 여러 줄을 지정할 수 있습니다. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | 페이지 번호로 교체될 문자열을 설정합니다. 기본값은 #입니다. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | 문서 페이지에 아티팩트로 배치되는 PDF 페이지를 설정합니다. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | 아티팩트의 텍스트를 설정합니다. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | 아티팩트의 텍스트와 텍스트 속성을 설정합니다. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | 아티팩트의 사용자 지정 값을 설정합니다. |

### 또 보기

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


