---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство ValidationOptions. Возвращает или задает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки."
type: docs
weight: 20
url: /ru/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Получает или задаёт значение, указывающее, следует ли проверять цепочку сертификатов во время процесса валидации.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Примечания

Когда свойство установлено, будет проверяться наличие цепочки сертификатов; если её нет, результат проверки будет Undefined, что соответствует поведению Adobe Acrobat. Если вы хотите только проверить статус отзыва онлайн, установите поле в `false`. Значение по умолчанию — `false`.

### См. также

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


