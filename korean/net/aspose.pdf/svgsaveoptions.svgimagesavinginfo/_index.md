---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo 클래스. 이 클래스는 PDF를 HTML로 변환하는 동안 외부 리소스 이미지 파일 저장과 관련된 데이터 집합을 나타냅니다.
type: docs
weight: 10260
url: /ko/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo 클래스

이 클래스는 PDF를 HTML로 변환하는 동안 외부 리소스 이미지 파일의 저장과 관련된 데이터 집합을 나타냅니다.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 변환기에 의해 설정됩니다. 변환기에서 사용자 정의 메서드의 코드로 전달되는 파일 이름으로 가정됩니다. 사용자 정의 코드에서 파일을 처리하거나 저장할 위치를 결정하는 데 사용할 수 있습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 변환기에 의해 설정됩니다. 저장된 파일의 이진 콘텐츠를 나타냅니다. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 사용자 정의 코드에서 제안된 파일이 사용자 정의 코드가 아닌 변환기의 코드로 표준 방식으로 처리되어야 하는 경우 이 플래그를 "true"로 설정해야 합니다. 따라서 true로 설정되면 사용자 정의 코드가 참조된 파일을 처리하지 않았으며 변환기가 이를 직접 처리해야 함을 의미합니다(저장 위치 및 참조 파일의 이름 지정 모두에 대해). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | HTML에서 참조된 저장된 이미지의 유형을 나타냅니다. 변환기에 의해 설정되며 사용자 정의 코드에서 수행해야 할 작업을 결정하는 데 사용할 수 있습니다. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 변환기에 의해 설정됩니다. 변환기에서 사용자 정의 메서드의 코드로 전달되는 파일 이름으로 가정됩니다. 사용자 정의 코드에서 파일을 처리하거나 저장할 위치를 결정하는 데 사용할 수 있습니다. |

### 참조

* 클래스 [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* 클래스 [SvgSaveOptions](../svgsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)