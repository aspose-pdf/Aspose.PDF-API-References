---
title: "클래스 HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo 클래스. HtmlSaveOptions의 SplitToPages 속성이 설정된 경우 PDF를 HTML로 변환하는 동안 변환된 페이지당 하나의 HTML 파일이 생성됩니다. 이 클래스는 PDF를 HTML로 변환하는 동안 하나의 HTML 페이지 마크업을 사용자 지정 저장과 관련된 데이터 집합을 나타냅니다."
type: docs
weight: 5800
url: /ko/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

HtmlSaveOptions의 SplitToPages 속성이 설정된 경우 PDF를 HTML로 변환하는 동안 변환된 페이지당 하나의 HTML 파일이 생성됩니다. 이 클래스는 PDF를 HTML로 변환하는 동안 하나의 HTML 페이지 마크업을 사용자 지정 저장과 관련된 데이터 집합을 나타냅니다.

```csharp
public class HtmlPageMarkupSavingInfo
```

## 필드

| 이름 | 설명 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | 변환기에 의해 설정됩니다. 저장된 HTML을 스트림으로 나타냅니다. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | 필요한 경우 사용자 지정 코드에서 설정해야 합니다. 이 플래그는 특정 이유로 제공된 html-markup을 사용자 지정 코드가 아니라 변환기의 코드 자체로 표준 변환 방식으로 처리해야 할 경우 사용자 지정 코드에서 "true"로 설정해야 합니다. 따라서 사용자 지정 코드에서 이 플래그를 설정하면 해당 파일을 사용자 지정 코드가 처리하지 않았으며 변환기가 직접 처리해야 함을 의미합니다. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | 변환기에 의해 설정됩니다. SplitToPages 속성이 설정된 경우 변환 중에 여러 HTML 파일(페이지당 하나의 HTML 파일)이 생성됩니다. 이 속성은 저장된 HTML 페이지 파일의 순서를 포함합니다. 이 속성은 사용자 지정 코드 로직에서 HTML 페이지를 어떻게 처리하거나 어디에 저장할지 결정하는 데 사용할 수 있으며, 페이지 분할이 해제된 경우 이 값은 항상 '1'을 포함합니다. 이는 해당 경우 전체 원본 문서에 대해 하나의 큰 HTML 페이지가 생성되기 때문입니다. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | 변환기에 의해 설정됩니다. SplitToPages 속성이 설정된 경우 변환 중에 여러 HTML 파일(페이지당 하나의 HTML 파일)이 생성됩니다. 이 속성은 원본 PDF의 어느 페이지에서 저장된 HTML 마크업이 생성되었는지를 사용자 지정 코드에 알려줍니다. 원본 페이지 번호가 알 수 없거나 SplitOnPages=false인 경우 이 속성은 항상 '0'을 포함하여 변환기가 제공된 HTML 마크업 파일에 대한 정확한 원본 PDF 페이지 번호를 제공할 수 없음을 나타냅니다. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | 변환기에 의해 설정됩니다. 변환기에서 사용자 지정 메서드 코드로 전달되는 파일 이름으로, 사용자 지정 코드에서 내용을 어떻게 처리하거나 어디에 저장할지 결정하는 데 사용할 수 있습니다. |

### 또 보기

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


