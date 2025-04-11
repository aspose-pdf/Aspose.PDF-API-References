---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Page 클래스. PDF 문서의 페이지를 나타내는 클래스
type: docs
weight: 8050
url: /ko/net/aspose.pdf/page/
---
## 페이지 클래스

PDF 문서의 페이지를 나타내는 클래스.

```csharp
public sealed class Page : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | 페이지 속성의 컬렉션을 가져옵니다. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | 페이지 주석의 컬렉션을 가져옵니다. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | 페이지의 아트 박스를 가져오거나 설정합니다. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | 페이지의 아티팩트 컬렉션을 가져옵니다. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | 페이지의 배경 색상을 가져오거나 설정합니다. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | 페이지의 배경 이미지를 가져오거나 설정합니다 (생성자 전용, 문서를 읽을 때는 채워지지 않음). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | 페이지의 블리드 박스를 가져오거나 설정합니다. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | SetColor, 이미지 및 양식에서 가져온 정보를 기반으로 페이지의 색상 유형을 설정합니다. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | 페이지의 콘텐츠 스트림에 있는 연산자의 컬렉션을 가져옵니다. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | 페이지의 크롭 박스를 가져오거나 설정합니다. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | 페이지 표시 지속 시간을 가져오거나 설정합니다. 프레젠테이션 중 페이지가 표시될 시간(초)입니다. 지속 시간이 정의되지 않은 경우 -1을 반환합니다. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | 이 페이지의 탭 순서에 있는 필드 객체 목록을 가져옵니다. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | 페이지 바닥글을 가져오거나 설정합니다. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | 투명 이미지 모델에서 사용하기 위해 페이지 그룹의 속성을 지정하는 그룹 속성 클래스를 가져오거나 설정합니다. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | 페이지 머리글을 가져오거나 설정합니다. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | 페이지의 마지막 단락 뒤에 단락 추가 여부를 가져오거나 설정합니다. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | 레이어 컬렉션을 가져오거나 설정합니다. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | 페이지의 미디어 박스를 가져오거나 설정합니다. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | 노트의 선 스타일을 가져오거나 설정합니다. (생성자 전용, 문서를 읽을 때는 채워지지 않음) |
| [Number](../../aspose.pdf/page/number/) { get; } | 페이지 번호를 가져옵니다. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | 페이지 정보를 가져오거나 설정합니다 (생성자 전용, 문서를 읽을 때는 채워지지 않음). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | 단락을 가져옵니다. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | 페이지의 사각형을 가져오거나 설정합니다. 가져올 때: 지정된 경우 페이지 크롭 박스가 반환되고, 그렇지 않으면 페이지 미디어 박스가 반환됩니다. 설정할 때: 페이지 미디어 박스는 항상 설정됩니다. 이 속성은 페이지 회전을 고려하지 않습니다. 회전을 고려한 페이지 사각형을 얻으려면 ActualRect를 사용하십시오. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | 페이지 리소스를 가져옵니다. 리소스 객체는 이미지, 양식 및 글꼴의 컬렉션을 포함합니다. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | 페이지의 회전을 가져오거나 설정합니다. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | 페이지의 변환 행렬을 가져옵니다. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | 페이지의 탭 순서를 가져오거나 설정합니다. 가능한 값: Row, Column. 기본값, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | 목차 정보를 가져오거나 설정합니다. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | 페이지의 트림 박스를 가져오거나 설정합니다. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | UserUnit 값을 가져오거나 설정합니다. 기본 사용자 공간 단위의 크기를 나타내는 양수로, 1 / 72 인치의 배수입니다. 기본값은 1입니다. 이 항목을 페이지에서 지우려면 0 또는 음수 값을 설정하십시오. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | 페이지의 워터마크를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | 주석과 작업할 수 있는 기능을 제공하는 [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) 방문자 객체를 수락합니다. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | 이미지 배치 객체와 작업할 수 있는 기능을 제공하는 [`ImagePlacementAbsorber`](../imageplacementabsorber/) 방문자 객체를 수락합니다. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | 텍스트 객체와 작업할 수 있는 기능을 제공하는 [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) 방문자 객체를 수락합니다. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | 텍스트 객체와 작업할 수 있는 기능을 제공하는 [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) 방문자 객체를 수락합니다. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | 페이지에 그래픽을 추가합니다. [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/) 메서드를 사용하여 요소를 하나씩 추가하는 것보다 빠릅니다. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | 페이지에 이미지를 추가하고 지정된 사각형의 중앙에 위치시켜 이미지 비율을 유지합니다. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | 페이지에 이미지를 추가하고 지정된 사각형의 중앙에 위치시켜 이미지 비율을 유지합니다. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | 페이지에 검색 가능한 이미지를 추가하고 지정된 사각형의 중앙에 위치시켜 이미지 비율을 유지합니다. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | 페이지에 이미지를 추가하고 이미지 사각형 위치에 따라 배치합니다. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | 페이지에 스탬프를 넣습니다. 스탬프는 페이지 번호, 이미지 또는 간단한 텍스트(예: 로고)일 수 있습니다. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | 현재 페이지를 비트맵으로 변환한 다음 바이트 배열을 반환합니다. |
| [AsXml](../../aspose.pdf/page/asxml/)() | 현재 페이지를 UTF-8 인코딩의 XML로 변환합니다. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | 가시적 여백 없이 콘텐츠를 포함하는 사각형(bbox) 값을 계산합니다. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | 페이지를 DSR, OMR, OCR 이미지 스트림용 PNG로 변환합니다. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | 페이지에서 그래픽을 삭제합니다. [`Remove`](../../aspose.pdf.vector/graphicelement/remove/) 메서드를 사용하여 요소를 하나씩 삭제하는 것보다 빠릅니다. |
| [Dispose](../../aspose.pdf/page/dispose/)() | 메모리를 해제합니다. |
| [Flatten](../../aspose.pdf/page/flatten/)() | 페이지에 있는 모든 필드를 제거하고 그 값을 대신 배치합니다. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | 캐시된 데이터를 지웁니다. |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | 페이지 콘텐츠와의 내부 작업에 대한 알림을 반환합니다. (현재 텍스트 추가 시나리오에서 단락 이벤트에 대한 알림만 지원됩니다.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | 크롭 박스(CropBox)에 따라 페이지의 사각형을 반환합니다 (크롭 박스가 null인 경우 미디어 박스 반환). |
| [GetResources](../../aspose.pdf/page/getresources/)() | 페이지와 관련된 리소스를 검색합니다. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | 페이지에 벡터 그래픽이 있는지 여부를 감지합니다. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | 페이지가 비어 있는지 여부를 나타내는 플래그를 가져옵니다. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | 페이지를 그레이스케일로 변환합니다. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | 페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어로 병합합니다. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | 페이지의 모든 레이어를 지정된 새 레이어 이름과 선택적 콘텐츠 그룹 ID로 단일 레이어로 병합합니다. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | 페이지 크기를 조정합니다. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | 주어진 페이지 장치로 페이지를 전송합니다. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | 주어진 페이지 장치로 페이지를 전송합니다. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | 페이지의 크기를 설정합니다. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | 페이지에 벡터 그래픽이 있는 경우 저장을 시도합니다. 저장 형식은 SVG입니다. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | 정수 값을 해당 회전 열거형 멤버로 변환합니다. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | 회전 열거형 멤버를 정수 값으로 변환합니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | 머리글 및 바닥글을 사용자 정의하기 위한 이벤트입니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | 머리글 및 바닥글을 사용자 정의하기 위한 절차입니다. |

### 참조

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)