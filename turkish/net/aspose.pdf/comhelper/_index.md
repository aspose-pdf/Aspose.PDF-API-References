---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ComHelper sınıfı. COM istemcilerinin bir belgeyi Aspose.Pdf'ye yüklemesi için yöntemler sağlar.
type: docs
weight: 3130
url: /tr/net/aspose.pdf/comhelper/
---
## ComHelper sınıfı

COM istemcilerinin bir belgeyi Aspose.Pdf'ye yüklemesi için yöntemler sağlar.

```csharp
public class ComHelper
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ComHelper](comhelper/)() | Varsayılan yapıcı. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | Sadece *dosya adı* kullanarak belge oluşturur ve döndürür. [`Document`](../document/document/) ile aynıdır. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | Gerekli dönüştürme seçeneklerini sağlayarak bir dosyadan mevcut bir belgeyi açar. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | Şifreli belge ile çalışmak için [`Document`](../document/) sınıfının yeni bir örneğini başlatır ve döndürür. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | Şifreli belge ile çalışmak için [`Document`](../document/) sınıfının yeni bir örneğini başlatır. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | *girdi* akışından yeni bir Belge örneğini başlatır ve döndürür. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | *girdi* akışından yeni bir Belge örneğini başlatır ve döndürür. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | Gerekli dönüştürmeyi sağlayarak bir akıştan mevcut bir belgeyi açar ve döndürür. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | *girdi* akışından yeni bir Belge örneğini başlatır ve döndürür. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | *girdi* akışından yeni bir Belge örneğini başlatır ve döndürür. |

## Açıklamalar

ComHelper sınıfını, bir dosyadan veya akıştan bir belgeyi COM uygulamasında bir Belge nesnesine yüklemek için kullanın. Document sınıfı, yeni bir belge oluşturmak için varsayılan bir yapıcı sağlar ve ayrıca bir dosyadan veya akıştan belge yüklemek için aşırı yüklenmiş yapıcılar sunar. Eğer bir .NET uygulamasından Aspose.Words kullanıyorsanız, tüm Document yapıcılarını doğrudan kullanabilirsiniz, ancak bir COM uygulamasından Aspose.Pdf kullanıyorsanız, yalnızca varsayılan Document yapıcısı mevcuttur.

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)