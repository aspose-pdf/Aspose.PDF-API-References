---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Security 클래스. 보안 플러그인을 나타냅니다.
type: docs
weight: 9230
url: /ko/net/aspose.pdf.plugins/security/
---
## 보안 클래스

`Security` 플러그인을 나타냅니다.

```csharp
public sealed class Security : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Security](security/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | 지정된 매개변수로 `Security` 처리를 시작합니다. |

## 예제

이 예제는 PDF 문서를 암호화하는 방법을 보여줍니다.

```csharp
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

이 예제는 PDF 문서를 복호화하는 방법을 보여줍니다.

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)