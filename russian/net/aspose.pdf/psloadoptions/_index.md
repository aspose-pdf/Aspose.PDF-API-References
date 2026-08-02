---
title: "Класс PsLoadOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.PsLoadOptions. Представляет параметры загрузки/импорта .mhtfile в PDF‑документ."
type: docs
weight: 9880
url: /ru/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

Представляет параметры загрузки/импорта .mht-файла в pdf document.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | Указывает, сохранять ли шрифты, не являющиеся TrueType, в TTF. Это значительно уменьшает объём получаемого документа при конвертации PS в PDF и повышает скорость преобразования PS‑файлов с большим количеством текста в шрифтах, не являющихся TrueType, в любой формат вывода. Однако при конвертации файла PostSctipt в изображение наблюдается небольшое вертикальное смещение текста. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Получает или задаёт флаг, отключающий любые лицензионные ограничения для всех шрифтов при загрузке файла. Когда `true`, позволяет выполнять операции с шрифтом, запрещённые лицензией этого шрифта, например, позволяет встраивать шрифт в PDF‑документ, даже если правила лицензии запрещают встраивание. По умолчанию `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Получает или задаёт пути к папкам шрифтов. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Представляет формат файла, который описывается [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий Continue или Abort. Continue является действием по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть Abort, в этом случае операция загрузки должна быть прекращена. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


