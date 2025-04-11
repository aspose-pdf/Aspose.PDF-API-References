---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo 클래스. HtmlSaveOptions의 SplitToPages 속성이 설정되면 PDF를 HTML로 변환하는 동안 여러 개의 HTML 파일(변환된 페이지당 하나의 HTML 파일)이 생성됩니다. 이 클래스는 PDF를 HTML로 변환하는 동안 하나의 HTML 페이지 마크업의 사용자 지정 저장과 관련된 데이터 집합을 나타냅니다.
type: docs
weight: 5670
url: /ko/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo 클래스

HtmlSaveOptions의 SplitToPages 속성이 설정되면 PDF를 HTML로 변환하는 동안 여러 개의 HTML 파일(변환된 페이지당 하나의 HTML 파일)이 생성됩니다. 이 클래스는 PDF를 HTML로 변환하는 동안 하나의 HTML 페이지 마크업의 사용자 지정 저장과 관련된 데이터 집합을 나타냅니다.

```csharp
public class HtmlPageMarkupSavingInfo
```

## 필드

| 이름 | 설명 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | 변환기에 의해 설정됩니다. 스트림으로 저장된 HTML을 나타냅니다. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | 필요할 때 사용자 지정 코드에서 설정해야 합니다. 이 플래그는 사용자 지정 코드에서 "true"로 설정되어야 하며, 어떤 이유로 제공된 HTML 마크업이 사용자 지정 코드가 아닌 변환기의 코드로 처리되어야 하는 경우를 나타냅니다. 따라서 사용자 지정 코드에서 이 플래그를 설정하면 사용자 지정 코드가 참조된 파일을 처리하지 않았으며 변환기가 이를 직접 처리해야 함을 의미합니다. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | 변환기에 의해 설정됩니다. SplitToPages 속성이 설정된 경우 여러 개의 HTML 파일(변환된 페이지당 하나의 HTML 파일)이 생성됩니다. 이 속성은 저장된 HTML 페이지 파일의 순서를 포함합니다. 이 속성은 사용자 지정 코드의 논리에서 HTML 페이지를 처리하거나 저장할 위치를 결정하는 데 사용할 수 있으며, 페이지 분할이 꺼져 있는 경우 이 값은 항상 '1'을 포함합니다. 왜냐하면 이 경우 전체 원본 문서에 대해 하나의 큰 HTML 페이지만 생성되기 때문입니다. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | 변환기에 의해 설정됩니다. SplitToPages 속성이 설정된 경우 여러 개의 HTML 파일(변환된 페이지당 하나의 HTML 파일)이 생성됩니다. 이 속성은 사용자 지정 코드에 저장된 HTML 마크업이 원본 PDF의 어떤 페이지에서 생성되었는지를 알려줍니다. 원본 페이지 번호가 어떤 이유로 알 수 없거나 SplitOnPages=false인 경우, 이 속성은 항상 '0'을 포함하여 변환기가 제공된 HTML 마크업 파일에 대한 정확한 원본 PDF의 페이지 번호를 제공할 수 없음을 나타냅니다. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | 변환기에 의해 설정됩니다. 변환기에서 사용자 지정 메서드의 코드로 전달되는 예상 파일 이름입니다. 콘텐츠를 처리하거나 저장할 위치를 결정하는 데 사용자 지정 코드에서 사용할 수 있습니다. |

### 참조

* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)