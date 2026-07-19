---
title: "Aspose::Pdf::LoadOptions::get_DisableFontLicenseVerifications method"
linktitle: "get_DisableFontLicenseVerifications"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LoadOptions::get_DisableFontLicenseVerifications method. Получает флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. При значении true позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет внедрять шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание данного шрифта. По умолчанию false в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/loadoptions/get_disablefontlicenseverifications/
---
## LoadOptions::get_DisableFontLicenseVerifications method


Получает флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда **true**

, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание этого шрифта. По умолчанию **false**

.

```cpp
bool Aspose::Pdf::LoadOptions::get_DisableFontLicenseVerifications() const
```

## Примечания


Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он действует на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторские права.
## См. также

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
