---
title: "aspose.pdf.forms"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Пространство имён aspose.pdf.forms содержит классы, описывающие формы (стандартные, статические, динамические) и различные типы полей, такие как текстовое поле, список, переключатель и т.д."
type: docs
weight: 60
url: /ru/python-net/aspose.pdf.forms/
---


Пространство имён aspose.pdf.forms содержит классы, описывающие формы (стандартные, статические, динамические) и различные типы полей, такие как текстовое поле, список, переключатель и т.д.

## Классы
| Класс | Описание |
| :- | :- |
| [BarcodeField](/pdf/python-net/aspose.pdf.forms/barcodefield/) | Класс представляет поле штрихкода. |
| [ButtonField](/pdf/python-net/aspose.pdf.forms/buttonfield/) | Класс представляет поле кнопки. |
| [CheckboxField](/pdf/python-net/aspose.pdf.forms/checkboxfield/) | Класс, представляющий поле флажка. |
| [ChoiceField](/pdf/python-net/aspose.pdf.forms/choicefield/) | Представляет базовый класс для полей выбора. |
| [ComboBoxField](/pdf/python-net/aspose.pdf.forms/comboboxfield/) | Класс, представляющий поле комбобокса формы. |
| [DateField](/pdf/python-net/aspose.pdf.forms/datefield/) | Поле даты с представлением календаря. |
| [DocMDPSignature](/pdf/python-net/aspose.pdf.forms/docmdpsignature/) | Представляет класс типа подписи документа MDP (обнаружение и предотвращение изменений). |
| [ExternalSignature](/pdf/python-net/aspose.pdf.forms/externalsignature/) | Создаёт отдельную подпись PKCS#7Detached с использованием X509Certificate2. Поддерживает USB‑смарткарты, токены без экспортируемых закрытых ключей. |
| [Field](/pdf/python-net/aspose.pdf.forms/field/) | Базовый класс для полей AcroForm. |
| [FileSelectBoxField](/pdf/python-net/aspose.pdf.forms/fileselectboxfield/) | Поле для элемента выбора файла. |
| [Form](/pdf/python-net/aspose.pdf.forms/form/) | Класс, представляющий объект формы. |
| [IconFit](/pdf/python-net/aspose.pdf.forms/iconfit/) | Описывает, как значок аннотации виджета должен отображаться внутри её прямоугольника аннотации. |
| [ListBoxField](/pdf/python-net/aspose.pdf.forms/listboxfield/) | Класс представляет поле ListBox. |
| [NumberField](/pdf/python-net/aspose.pdf.forms/numberfield/) | Текстовое поле с указанными допустимыми символами |
| [Option](/pdf/python-net/aspose.pdf.forms/option/) | Класс представляет вариант поля выбора. |
| [OptionCollection](/pdf/python-net/aspose.pdf.forms/optioncollection/) | Класс, представляющий коллекцию вариантов поля выбора. |
| [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/) | Представляет объект подписи в соответствии со стандартом PKCS#1.<br/>            Для подписи используется алгоритм шифрования RSA и метод хеширования SHA-1. |
| [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) | Представляет объект PKCS#7, соответствующий спецификации PKCS#7 в Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, версия 1.5.<br/>            Хеш SHA1 диапазона байтов документа инкапсулируется в поле PKCS#7 SignedData. |
| [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) | Представляет объект PKCS#7, соответствующий спецификации PKCS#7 в Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, версия 1.5.<br/>            Оригинальный хеш подписанного сообщения диапазона байтов документа включается как обычное поле PKCS#7 SignedData. <br/>            Данные не инкапсулируются в поле PKCS#7 SignedData. |
| [PasswordBoxField](/pdf/python-net/aspose.pdf.forms/passwordboxfield/) | Класс описывает текстовое поле для ввода пароля. |
| [RadioButtonField](/pdf/python-net/aspose.pdf.forms/radiobuttonfield/) | Класс, представляющий поле переключателя. |
| [RadioButtonOptionField](/pdf/python-net/aspose.pdf.forms/radiobuttonoptionfield/) | Класс представляет элемент поля RadioButton. |
| [RichTextBoxField](/pdf/python-net/aspose.pdf.forms/richtextboxfield/) | Класс описывает компонент редактора форматированного текста. |
| [Signature](/pdf/python-net/aspose.pdf.forms/signature/) | Абстрактный класс, представляющий объект подписи в PDF‑документе. <br/>            Подписи — это поля со значениями объектов подписи, последние содержат данные, используемые для<br/>            проверки действительности документа. |
| [SignatureCustomAppearance](/pdf/python-net/aspose.pdf.forms/signaturecustomappearance/) | Абстрактный класс, представляющий объект пользовательского оформления подписи. |
| [SignatureField](/pdf/python-net/aspose.pdf.forms/signaturefield/) | Представляет поле формы подписи. |
| [TextBoxField](/pdf/python-net/aspose.pdf.forms/textboxfield/) | Класс, представляющий поле текстового блока. |
| [XFA](/pdf/python-net/aspose.pdf.forms/xfa/) | Представляет XML‑форму в соответствии с XML Forms Architecture (XFA). |
## Перечисления
| Перечисление | Описание |
| :- | :- |
| [BoxStyle](/pdf/python-net/aspose.pdf.forms/boxstyle/) | Представляет стили флажка. |
| [DocMDPAccessPermissions](/pdf/python-net/aspose.pdf.forms/docmdpaccesspermissions/) | Разрешения доступа, предоставленные для этого документа.<br/>            Допустимые значения:<br/>            1 - Изменения документа не разрешены; любое изменение документа аннулирует подпись.<br/>            2 - Разрешены изменения: заполнение форм, создание шаблонов страниц и подпись; другие изменения аннулируют подпись.<br/>            3 - Разрешены изменения, как в пункте 2, а также создание, удаление и изменение аннотаций; другие изменения аннулируют подпись. |
| [FormType](/pdf/python-net/aspose.pdf.forms/formtype/) | Перечисление возможных типов Acro Form. |
| [IconCaptionPosition](/pdf/python-net/aspose.pdf.forms/iconcaptionposition/) | Описывает положение значка. |
| [ScalingMode](/pdf/python-net/aspose.pdf.forms/scalingmode/) | Тип масштабирования, который должен использоваться. |
| [ScalingReason](/pdf/python-net/aspose.pdf.forms/scalingreason/) | Обстоятельства, при которых значок будет масштабироваться внутри прямоугольника аннотации. |
| [SubjectNameElements](/pdf/python-net/aspose.pdf.forms/subjectnameelements/) | Перечисление описывает элементы в строке темы подписи. |
| [Symbology](/pdf/python-net/aspose.pdf.forms/symbology/) | Символика (Barcode) определяет технические детали конкретного типа штрихкода:<br/>            ширина полос, набор символов, метод кодирования, спецификации контрольной суммы и т.д. |
