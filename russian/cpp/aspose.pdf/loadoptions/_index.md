---
title: "Aspose::Pdf::LoadOptions class"
linktitle: "LoadOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LoadOptions class. Тип LoadOptions содержит уровень абстракции отдельных параметров загрузки в C++."
type: docs
weight: 10500
url: /ru/cpp/aspose.pdf/loadoptions/
---
## LoadOptions class


[LoadOptions](./) type holds level of abstraction on individual load options.

```cpp
class LoadOptions : public virtual System::Object
```

## Nested classes

* Class [ResourceLoadingResult](./resourceloadingresult/)
## Enums

| Перечисление | Описание |
| --- | --- |
| [MarginsAreaUsageModes](./marginsareausagemodes/) | Представляет режим использования области полей при конвертации (например HTML, EPUB и т.д.), определяет обработку инструкций импортированного формата, связанных с использованием полей. |
| [PageSizeAdjustmentModes](./pagesizeadjustmentmodes/) | ВНИМАНИЕ! Функция реализована, но ещё не добавлена в публичный API, поскольку в слое OSHARED обнаружена блокирующая проблема для образца документа. |
## Методы

| Метод | Описание |
| --- | --- |
|  | [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Получает флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда **true** |

, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание этого шрифта. По умолчанию **false**

. |
| [get_LoadFormat](./get_loadformat/)() const | Представляет формат файла, который описывается в [LoadOptions](./). |
| [get_WarningHandler](./get_warninghandler/)() const | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../returnaction/), указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |
| [LoadOptions](./loadoptions/)() |  |
|  | [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Устанавливает флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда **true** |

, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание этого шрифта. По умолчанию **false**

. |
| [set_WarningHandler](./set_warninghandler/)(const System::SharedPtr\<IWarningCallback\>\&) | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../returnaction/), указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь также может вернуть Abort, в этом случае операция загрузки должна прекратиться. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ResourceLoadingStrategy](./resourceloadingstrategy/) | Иногда необходимо избежать использования внутреннего загрузчика внешних ресурсов (например изображений или CSS) и предоставить пользовательский метод, который будет получать запрошенные ресурсы откуда‑то. Например, при использовании [Aspose.Pdf](../) в облаке прямой доступ к ссылочным файлам невозможен, и следует использовать пользовательский код, помещённый в специальный метод. Этот делегат определяет сигнатуру такого пользовательского метода. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
