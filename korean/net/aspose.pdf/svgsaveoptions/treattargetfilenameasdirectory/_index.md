---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions 필드. 이 옵션은 요청된 출력 파일과 동일한 이름의 대상 디렉토리가 아직 없는 경우 생성될지를 정의합니다. 이렇게 하면 디렉토리는 아래에 설명된 대로 페이지의 모든 출력 SVG 이미지를 포함하게 됩니다. 첫 번째 페이지 외에 다른 페이지의 출력 파일이 요청된 디렉토리에 정확히 생성되지 않지만, 파일 이름에는 페이지 번호에 의해 정의된 접미사 _2...n이 포함됩니다. 예를 들어, 출력 파일을 CAsposeTestsoutput.svg로 정의하고 출력에 여러 페이지의 svg 파일이 포함되면, 페이지 파일은 CAsposeTests 디렉토리에도 생성되며 이름은 output.svg, output_2.svg, output_3.svg 등이 됩니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory 필드

이 옵션은 요청된 출력 파일과 동일한 이름의 대상 디렉토리가 (아직 없는 경우) 생성될지를 정의합니다. 이렇게 하면 디렉토리는 페이지의 모든 출력 SVG 이미지(아래에 설명된 대로)를 포함하게 됩니다. 그렇지 않으면, 첫 번째 페이지 외의 페이지 출력 파일은 요청된 디렉토리에 주 출력 파일로 정확히 생성되지만, 파일 이름에는 페이지 번호에 의해 정의된 접미사 _[2...n]이 포함됩니다. 예를 들어, 출력 파일 "C:\AsposeTests\output.svg"를 정의하고 출력에 여러 페이지의 svg 파일이 포함되면, 페이지 파일은 "C:\AsposeTests\" 디렉토리에도 생성되며 이름은 'output.svg', 'output_2.svg', 'output_3.svg' 등이 됩니다.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### 참조

* 클래스 [SvgSaveOptions](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)