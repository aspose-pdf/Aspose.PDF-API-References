---
title: "aspose.pdf.forms"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "aspose.pdf.forms 命名空间包含描述表单（标准、静态、动态）以及文本框、列表框、单选按钮等各种字段类型的类。"
type: docs
weight: 60
url: /zh/python-net/aspose.pdf.forms/
---


aspose.pdf.forms 命名空间包含描述表单（标准、静态、动态）以及文本框、列表框、单选按钮等各种字段类型的类。

## 类
| 类 | 描述 |
| :- | :- |
| [BarcodeField](/pdf/python-net/aspose.pdf.forms/barcodefield/) | 类表示条形码字段。 |
| [ButtonField](/pdf/python-net/aspose.pdf.forms/buttonfield/) | 类表示推送按钮字段。 |
| [CheckboxField](/pdf/python-net/aspose.pdf.forms/checkboxfield/) | 表示复选框字段的类 |
| [ChoiceField](/pdf/python-net/aspose.pdf.forms/choicefield/) | 表示选择字段的基类。 |
| [ComboBoxField](/pdf/python-net/aspose.pdf.forms/comboboxfield/) | 表示表单中组合框字段的类。 |
| [DateField](/pdf/python-net/aspose.pdf.forms/datefield/) | 带日历视图的日期字段。 |
| [DocMDPSignature](/pdf/python-net/aspose.pdf.forms/docmdpsignature/) | 表示文档 MDP（修改检测与防止）签名类型的类。 |
| [ExternalSignature](/pdf/python-net/aspose.pdf.forms/externalsignature/) | 使用 X509Certificate2 创建分离的 PKCS#7Detached 签名。它支持 USB 智能卡、不可导出私钥的令牌。 |
| [Field](/pdf/python-net/aspose.pdf.forms/field/) | Acro 表单字段的基类。 |
| [FileSelectBoxField](/pdf/python-net/aspose.pdf.forms/fileselectboxfield/) | 文件选择框元素的字段。 |
| [Form](/pdf/python-net/aspose.pdf.forms/form/) | 表示表单对象的类。 |
| [IconFit](/pdf/python-net/aspose.pdf.forms/iconfit/) | 描述小部件注释的图标应如何在其注释矩形内显示。 |
| [ListBoxField](/pdf/python-net/aspose.pdf.forms/listboxfield/) | 表示 ListBox 字段的类。 |
| [NumberField](/pdf/python-net/aspose.pdf.forms/numberfield/) | 带有指定有效字符的文本字段 |
| [Option](/pdf/python-net/aspose.pdf.forms/option/) | 表示选择字段选项的类。 |
| [OptionCollection](/pdf/python-net/aspose.pdf.forms/optioncollection/) | 表示选择字段选项集合的类。 |
| [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/) | 表示符合 PKCS#1 标准的签名对象。<br/>            使用 RSA 加密算法和 SHA-1 摘要方法进行签名。 |
| [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) | 表示符合 Internet RFC 2315 中 PKCS#7 规范的 PKCS#7 对象，<br/>            PKCS #7：密码消息语法，版本 1.5。<br/>            文档字节范围的 SHA1 摘要被封装在 PKCS#7 SignedData 字段中。 |
| [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) | 表示符合 Internet RFC 2315 中 PKCS#7 规范的 PKCS#7 对象，<br/>            PKCS #7：密码消息语法，版本 1.5。<br/>            文档字节范围的原始已签名消息摘要被作为普通的 PKCS#7 SignedData 字段加入。<br/>            PKCS#7 SignedData 字段中不应封装任何数据。 |
| [PasswordBoxField](/pdf/python-net/aspose.pdf.forms/passwordboxfield/) | 描述用于输入密码的文本字段的类。 |
| [RadioButtonField](/pdf/python-net/aspose.pdf.forms/radiobuttonfield/) | 表示单选按钮字段的类。 |
| [RadioButtonOptionField](/pdf/python-net/aspose.pdf.forms/radiobuttonoptionfield/) | 表示 RadioButton 字段项的类。 |
| [RichTextBoxField](/pdf/python-net/aspose.pdf.forms/richtextboxfield/) | 描述富文本编辑器组件的类。 |
| [Signature](/pdf/python-net/aspose.pdf.forms/signature/) | 一个抽象类，表示 PDF 文档中的签名对象。<br/>            签名是包含签名对象值的字段，后者包含用于<br/>            验证文档有效性的数据。 |
| [SignatureCustomAppearance](/pdf/python-net/aspose.pdf.forms/signaturecustomappearance/) | 一个抽象类，表示签名自定义外观对象。 |
| [SignatureField](/pdf/python-net/aspose.pdf.forms/signaturefield/) | 表示签名表单字段。 |
| [TextBoxField](/pdf/python-net/aspose.pdf.forms/textboxfield/) | 表示文本框字段的类。 |
| [XFA](/pdf/python-net/aspose.pdf.forms/xfa/) | 表示符合 XML 表单架构 (XFA) 的 XML 表单。 |
## 枚举
| 枚举 | 描述 |
| :- | :- |
| [BoxStyle](/pdf/python-net/aspose.pdf.forms/boxstyle/) | 表示复选框的样式。 |
| [DocMDPAccessPermissions](/pdf/python-net/aspose.pdf.forms/docmdpaccesspermissions/) | 此文档授予的访问权限。<br/>            有效值为：<br/>            1 - 不允许对文档进行任何更改；对文档的任何更改都会使签名失效。<br/>            2 - 允许的更改包括填写表单、实例化页面模板和签名；其他更改会使签名失效。<br/>            3 - 允许的更改与 2 相同，此外还包括创建、删除和修改注释；其他更改会使签名失效。 |
| [FormType](/pdf/python-net/aspose.pdf.forms/formtype/) | Acro 表单可能类型的枚举。 |
| [IconCaptionPosition](/pdf/python-net/aspose.pdf.forms/iconcaptionposition/) | 描述图标的位置。 |
| [ScalingMode](/pdf/python-net/aspose.pdf.forms/scalingmode/) | 应使用的缩放类型。 |
| [ScalingReason](/pdf/python-net/aspose.pdf.forms/scalingreason/) | 在注释矩形内对图标进行缩放的情况。 |
| [SubjectNameElements](/pdf/python-net/aspose.pdf.forms/subjectnameelements/) | 枚举描述签名主题字符串中的元素。 |
| [Symbology](/pdf/python-net/aspose.pdf.forms/symbology/) | 一种（条形码）符号系统定义特定类型条形码的技术细节：<br/>            条的宽度、字符集、编码方法、校验和规范等。 |
