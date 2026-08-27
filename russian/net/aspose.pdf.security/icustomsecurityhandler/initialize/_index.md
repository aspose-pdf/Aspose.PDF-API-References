---
title: "ICustomSecurityHandler.Initialize"
second_title: "Справочник API Aspose.PDF для .NET"
description: "метод ICustomSecurityHandler. Вызывается для инициализации текущего экземпляра для шифрования. Обратите внимание, что при шифровании он будет заполнен данными переданных свойств ICustomSecurityHandler и при открытии Document из словаря шифрования. Если метод вызывается во время нового шифрования, то UserKey и OwnerKey будут null."
type: docs
weight: 120
url: /ru/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Вызывается для инициализации текущего экземпляра для шифрования. Обратите внимание, что при шифровании он будет заполнен данными переданных свойств [`ICustomSecurityHandler`](../), а при открытии Document из словаря шифрования. Если метод вызывается во время нового шифрования, то [`UserKey`](../../encryptionparameters/userkey/) и [`OwnerKey`](../../encryptionparameters/ownerkey/) будут null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| параметры | EncryptionParameters | Параметры шифрования. |

### См. также

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


