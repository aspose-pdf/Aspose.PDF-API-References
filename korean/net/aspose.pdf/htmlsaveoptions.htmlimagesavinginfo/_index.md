---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo 클래스. 이 클래스는 PDF를 HTML로 변환하는 동안 외부 리소스 이미지 파일 저장과 관련된 데이터 집합을 나타냅니다.
type: docs
weight: 5640
url: /ko/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo 클래스

이 클래스는 PDF를 HTML로 변환하는 동안 외부 리소스 이미지 파일의 저장과 관련된 데이터 집합을 나타냅니다.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 변환기에 의해 설정됩니다. 변환기에서 사용자 정의 메서드의 코드로 전달되는 파일 이름으로 가정됩니다. 사용자 정의 코드에서 파일을 처리하거나 저장할 위치를 결정하는 데 사용할 수 있습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 변환기에 의해 설정됩니다. 저장된 파일의 이진 콘텐츠를 나타냅니다. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 사용자 정의 코드에서 제안된 파일이 사용자 정의 코드가 아닌 변환기의 코드로 표준 방식으로 처리되어야 하는 경우 이 플래그를 "true"로 설정해야 합니다. 따라서 true로 설정하면 사용자 정의 코드가 참조된 파일을 처리하지 않았으며 변환기가 이를 직접 처리해야 함을 의미합니다(저장 위치와 참조 파일의 이름 모두에 대해). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | 저장된 이미지가 생성된 HTML 페이지 파일 집합의 어떤 페이지에 해당하는지를 사용자 정의 코드에 알려줍니다. 페이지 분할이 꺼져 있는 경우 이 값은 항상 '1'을 포함합니다. 왜냐하면 이 경우 단 하나의 HTML 페이지만 생성되기 때문입니다. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | HTML에서 참조된 저장된 이미지의 유형을 나타냅니다. 변환기에 의해 설정되며 사용자 정의 코드에서 수행해야 할 작업을 결정하는 데 사용할 수 있습니다. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | 저장된 이미지는 HTML 자체에 해당할 수 있거나 HTML에 포함된 SVG에서 추출될 수 있습니다. 이 속성은 처리된 이미지의 부모 유형이 무엇인지 사용자 정의 코드에 알려줍니다. 변환기에 의해 설정되며 사용자 정의 코드에서 해당 이미지로 수행해야 할 작업을 결정하는 데 사용할 수 있습니다(예: 사용자 정의 코드가 이미지를 저장할 위치나 부모 콘텐츠에서 어떻게 참조해야 하는지를 결정할 수 있습니다). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | 저장된 이미지가 원본 PDF 문서의 어떤 페이지에 해당하는지를 사용자 정의 코드에 알려줍니다. 원본 문서의 모든 페이지가 저장되지 않을 수 있으므로 이 값은 원본 PDF의 호스트 페이지 번호에 대해 알려줍니다. 원본 페이지 번호가 어떤 이유로 알 수 없는 경우 항상 '1'을 반환합니다. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 변환기에 의해 설정됩니다. 변환기에서 사용자 정의 메서드의 코드로 전달되는 파일 이름으로 가정됩니다. 사용자 정의 코드에서 파일을 처리하거나 저장할 위치를 결정하는 데 사용할 수 있습니다. |

### 참조

* 클래스 [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)