---
title: RunThreadCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest özelliği. Model tarafından çağrılan herhangi bir aracın hangisi olduğunu alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. "type": "file_search" veya "type": "function", "function": "name": "my_function" gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar.
type: docs
weight: 120
url: /tr/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice özelliği

Model tarafından çağrılan herhangi bir aracın hangisi olduğunu alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. {"type": "file_search"} veya {"type": "function", "function": {"name": "my_function"}} gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar.

```csharp
public string ToolChoice { get; set; }
```

### Ayrıca Bakınız

* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)