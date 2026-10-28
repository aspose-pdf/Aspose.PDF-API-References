---
title: "클래스 HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo 클래스. 이 클래스는 PDF를 HTML로 변환하는 동안 외부 리소스 이미지 파일 저장과 관련된 데이터 집합을 나타냅니다."
type: docs
weight: 5770
url: /ko/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

이 클래스는 PDF를 HTML로 변환하는 동안 외부 리소스 이미지 파일 저장과 관련된 데이터 집합을 나타냅니다.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 컨버터에 의해 설정됩니다. 컨버터에서 사용자 정의 메서드 코드로 전달되는 파일 이름이며, 사용자 정의 코드에서 파일을 어떻게 처리하거나 어디에 저장할지 결정하는 데 사용할 수 있습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 컨버터에 의해 설정됩니다. 저장된 파일의 바이너리 내용을 나타냅니다. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 이 플래그는 특정 이유로 제안된 파일을 사용자 정의 코드가 아니라 컨버터의 코드 자체로 표준 방식에 따라 처리해야 하는 경우 사용자 정의 코드에서 "true"로 설정해야 합니다. 따라서 설정을 true로 하면 사용자 정의 코드가 해당 파일을 처리하지 않았으며 컨버터가 자체적으로 파일을 저장하고 파일명을 지정하는 등 모든 작업을 처리해야 함을 의미합니다. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | 생성된 HTML 페이지 파일 집합 중 어느 Page에 저장된 이미지가 해당되는지 사용자 코드에 알려줍니다. 페이지별 분할이 꺼져 있으면 이 값은 항상 '1'을 포함합니다. 이 경우에는 하나의 HTML Page만 생성되기 때문입니다. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | HTML에서 참조되는 저장된 이미지 유형을 나타냅니다. 변환기에 의해 설정되며 사용자 지정 코드에서 수행할 작업을 결정하는 데 사용할 수 있습니다. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | 저장된 이미지는 HTML 자체와 관련될 수 있거나 HTML에 포함된 SVG에서 추출될 수 있습니다. 이 속성은 사용자 지정 코드에 처리된 이미지의 상위 유형이 무엇인지 알려줄 수 있습니다. 변환기에 의해 설정되며 사용자 지정 코드에서 해당 이미지에 대해 수행할 작업을 결정하는 데 사용할 수 있습니다(예: 사용자 지정 코드가 이미지를 저장할 위치나 상위 콘텐츠에서 어떻게 참조해야 하는지를 결정할 수 있음). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | 저장된 이미지가 원본 PDF 문서의 어느 페이지에 해당하는지 사용자 지정 코드에 알려줍니다. 원본 문서의 모든 페이지가 저장되지 않을 수 있기 때문에 이 값은 원본 PDF에서 호스트 페이지 번호를 나타냅니다. 원본 페이지 번호가 알 수 없는 경우 항상 '1'을 반환합니다. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 컨버터에 의해 설정됩니다. 컨버터에서 사용자 정의 메서드 코드로 전달되는 파일 이름이며, 사용자 정의 코드에서 파일을 어떻게 처리하거나 어디에 저장할지 결정하는 데 사용할 수 있습니다. |

### 또 보기

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


