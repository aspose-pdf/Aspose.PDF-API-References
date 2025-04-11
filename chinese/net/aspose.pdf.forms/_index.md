---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms 命名空间包含描述表单（标准、静态、动态）和各种类型字段（如文本框、列表框、单选按钮等）的类
type: docs
weight: 110
url: /zh/net/aspose.pdf.forms/
---
**Aspose.Pdf.Forms** 命名空间包含描述表单（标准、静态、动态）和各种类型字段（如文本框、列表框、单选按钮等）的类。

## 类

| 类 | 描述 |
| --- | --- |
| [BarcodeField](./barcodefield/) | 类表示条形码字段。 |
| [ButtonField](./buttonfield/) | 类表示按钮字段。 |
| [CheckboxField](./checkboxfield/) | 类表示复选框字段。 |
| [ChoiceField](./choicefield/) | 表示选择字段的基类。 |
| [ComboBoxField](./comboboxfield/) | 类表示表单的组合框字段。 |
| [DateField](./datefield/) | 带日历视图的日期字段。 |
| [DocMDPSignature](./docmdpsignature/) | 表示文档 MDP（修改检测和防止）签名类型的类。 |
| [ExternalSignature](./externalsignature/) | 使用 X509Certificate2 创建分离的 PKCS#7 签名。支持 USB 智能卡和不可导出的私钥令牌。 |
| [Field](./field/) | Acrobat 表单字段的基类。 |
| [FileSelectBoxField](./fileselectboxfield/) | 文件选择框元素的字段。 |
| [Form](./form/) | 类表示表单对象。 |
| [IconFit](./iconfit/) | 描述小部件注释的图标应如何在其注释矩形内显示。 |
| [ListBoxField](./listboxfield/) | 类表示列表框字段。 |
| [NumberField](./numberfield/) | 带有指定有效字符的文本字段。 |
| [Option](./option/) | 类表示选择字段的选项。 |
| [OptionCollection](./optioncollection/) | 类表示选择字段的选项集合。 |
| [PasswordBoxField](./passwordboxfield/) | 类描述用于输入密码的文本字段。 |
| [PKCS1](./pkcs1/) | 表示与 PKCS#1 标准相关的签名对象。用于签名的 RSA 加密算法和 SHA-1 摘要方法。 |
| [PKCS7](./pkcs7/) | 表示符合互联网 RFC 2315 中 PKCS#7 规范的 PKCS#7 对象，PKCS #7：加密消息语法，版本 1.5。文档字节范围的 `SHA1 摘要` 被封装在 PKCS#7 SignedData 字段中。 |
| [PKCS7Detached](./pkcs7detached/) | 表示符合互联网 RFC 2315 中 PKCS#7 规范的 PKCS#7 对象，PKCS #7：加密消息语法，版本 1.5。文档字节范围的原始签名消息摘要作为正常的 PKCS#7 SignedData 字段包含。PKCS#7 SignedData 字段中不应封装任何数据。 |
| [RadioButtonField](./radiobuttonfield/) | 类表示单选按钮字段。 |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | 类表示单选按钮字段的项。 |
| [RichTextBoxField](./richtextboxfield/) | 类描述富文本编辑器组件。 |
| [Signature](./signature/) | 一个抽象类，表示 PDF 文档中的签名对象。签名是具有签名对象值的字段，最后一个包含用于验证文档有效性的数据。 |
| [SignatureCustomAppearance](./signaturecustomappearance/) | 一个抽象类，表示签名自定义外观对象。 |
| [SignatureField](./signaturefield/) | 表示签名表单字段。 |
| [SignHash](./signhash/) | 自定义签名文档哈希的委托。 |
| [TextBoxField](./textboxfield/) | 类表示文本框字段。 |
| [XFA](./xfa/) | 表示与 XML 表单架构（XFA）相关的 XML 表单。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BoxStyle](./boxstyle/) | 表示绘制复选框中勾选的样式。 |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | 授予此文档的访问权限。有效值为：1 - 不允许对文档进行更改；对文档的任何更改都会使签名无效。2 - 允许的更改为填写表单、实例化页面模板和签名；其他更改会使签名无效。3 - 允许的更改与 2 相同，以及注释的创建、删除和修改；其他更改会使签名无效。 |
| [FormType](./formtype/) | Acrobat 表单的可能类型的枚举。 |
| [IconCaptionPosition](./iconcaptionposition/) | 描述图标的位置。 |
| [ScalingMode](./scalingmode/) | 应使用的缩放类型。 |
| [ScalingReason](./scalingreason/) | 描述图标在注释矩形内缩放的情况。 |
| [SubjectNameElements](./subjectnameelements/) | 枚举描述签名主题字符串中的元素。 |
| [Symbology](./symbology/) | （条形码）符号定义特定类型条形码的技术细节：条形的宽度、字符集、编码方法、校验和规范等。 |