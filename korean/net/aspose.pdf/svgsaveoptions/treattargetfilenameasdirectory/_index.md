---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "SvgSaveOptions 필드. 이 옵션은 요청된 출력 파일과 동일한 이름의 대상 디렉터리가 아직 존재하지 않을 경우, 출력 파일 자체 대신 해당 디렉터리를 생성할지 여부를 정의합니다. 이렇게 하면 디렉터리에 아래에 설명된 대로 모든 페이지의 출력 SVG 이미지가 포함됩니다. 첫 번째 페이지를 제외한 다른 페이지의 출력 파일이 요청된 디렉터리 안에 메인 출력 파일과 동일하게 생성되며, 파일 이름에 페이지 번호에 따라 _2...n 접미사가 붙습니다. 예를 들어 출력 파일을 CAsposeTestsoutput.svg 로 정의하고 여러 페이지의 SVG 파일이 포함될 경우, 페이지 파일들은 CAsposeTests 디렉터리에도 생성되어 output.svg, output_2.svg, output_3.svg 등과 같은 이름을 갖게 됩니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

이 옵션은 요청된 출력 파일 자체 대신 요청된 출력 파일과 동일한 이름의 대상 디렉터리가 (존재하지 않을 경우) 생성될지 여부를 정의합니다. 이렇게 하면 해당 디렉터리에 모든 페이지의 출력 SVG 이미지가 포함됩니다(아래에 설명된 대로). '아니오'인 경우, 첫 번째 페이지를 제외한 페이지들의 출력 파일은 메인 출력 파일과 동일한 디렉터리에 생성되지만 파일 이름에 _[2...n] 접미사가 붙으며, 이는 페이지 번호에 따라 정의됩니다. 예를 들어 출력 파일을 "C:\AsposeTests\output.svg" 로 지정하고 여러 페이지의 SVG 파일이 생성되는 경우, 페이지 파일들은 "C:\AsposeTests\" 디렉터리에도 생성되어 'output.svg', 'output_2.svg', 'output_3.svg' 등과 같은 이름을 갖게 됩니다.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### 또 보기

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


