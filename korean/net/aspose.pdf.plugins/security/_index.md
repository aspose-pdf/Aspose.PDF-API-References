---
title: "클래스 Security"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.Security 클래스. Security 플러그인을 나타냅니다"
type: docs
weight: 9380
url: /ko/net/aspose.pdf.plugins/security/
---
## Security class

`Security` 플러그인을 나타냅니다.

```csharp
public sealed class Security : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Security](security/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | 지정된 매개변수로 `Security` 처리를 시작합니다. |

## 예제

예제는 PDF 문서를 암호화하는 방법을 보여줍니다.

```csharp
// Security를 생성합니다.
var plugin = new Security();
// 지시사항을 설정하기 위해 EncryptionOptions 객체를 생성합니다.
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// 입력 파일 경로를 추가합니다
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
// 프로세스를 수행합니다.
plugin.Process(opt);
```

예제는 PDF 문서를 복호화하는 방법을 보여줍니다.

```csharp
// Security를 생성합니다.
var plugin = new Security();
// 지시사항을 설정하기 위해 DecryptionOptions 객체를 생성합니다.
var opt = new DecryptionOptions("123456"));
// 입력 파일 경로를 추가합니다
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
// 프로세스를 수행합니다.
plugin.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


