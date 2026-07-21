---
title: "Espacio de nombres Aspose::Pdf::Forms"
linktitle: "Aspose::Pdf::Forms"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Espacio de nombres Aspose::Pdf::Forms. El espacio de nombres Aspose.Pdf.Forms tiene clases que describen formularios (estándar, estáticos, dinámicos) y varios tipos de campos como cuadro de texto, lista desplegable, botón de opción, etc. en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf.forms/
---

El espacio de nombres **[Aspose.Pdf.Forms](./)** tiene clases que describen formularios (estándar, estático, dinámico) y varios tipos de campos como cuadro de texto, lista desplegable, botón de opción, etc.

## Clases

| Clase | Descripción |
| --- | --- |
| [BarcodeField](./barcodefield/) | Clase que representa un campo de código de barras. |
| [ButtonField](./buttonfield/) | Clase que representa un campo de botón pulsador. |
| [CheckboxField](./checkboxfield/) | Clase que representa un campo de casilla de verificación. |
| [ChoiceField](./choicefield/) | Representa la clase base para campos de selección. |
| [ComboBoxField](./comboboxfield/) | Clase que representa un campo de cuadro combinado del formulario. |
| [DateField](./datefield/) | Campo de fecha con vista de calendario. |
| [DocMDPSignature](./docmdpsignature/) | Representa la clase del tipo de firma MDP (detección y prevención de modificaciones) de documento. |
| [ExternalSignature](./externalsignature/) | Crea una firma PKCS#7 separada usando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [Field](./field/) | Clase base para campos de formulario Acro. |
| [FileSelectBoxField](./fileselectboxfield/) | [Field](./field/) para elemento de cuadro de selección de archivo. |
| [Form](./form/) | Clase que representa un objeto de formulario. |
| [IconFit](./iconfit/) | Describe cómo se debe mostrar el ícono de la anotación del widget dentro de su rectángulo de anotación. |
| [ListBoxField](./listboxfield/) | Clase que representa el campo ListBox. |
| [NumberField](./numberfield/) | [Text](../aspose.pdf.text/)[Field](./field/) con caracteres válidos especificados. |
| [Option](./option/) | Clase que representa una opción del campo de elección. |
| [OptionCollection](./optioncollection/) | Clase que representa la colección de opciones del campo de elección. |
| [PasswordBoxField](./passwordboxfield/) | Clase que describe el campo de texto para ingresar la contraseña. |
| [PKCS1](./pkcs1/) | Representa un objeto de firma según el estándar PKCS#1. Se utilizan el algoritmo de cifrado RSA y el método de resumen SHA-1 para la firma. |
| [PKCS7](./pkcs7/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5. El **SHA1 digest** del rango de bytes del documento está encapsulado en el campo SignedData de PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5. El resumen del mensaje firmado original sobre el rango de bytes del documento se incorpora como el campo SignedData normal de PKCS#7. No se encapsulan datos en el campo SignedData de PKCS#7. |
| [RadioButtonField](./radiobuttonfield/) | Clase que representa el campo de botón de opción. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Clase que representa un elemento del campo RadioButton. |
| [RichTextBoxField](./richtextboxfield/) | Clase que describe el componente de editor de texto enriquecido. |
| [Signature](./signature/) | Una clase abstracta que representa un objeto de firma en el documento pdf. [Signatures](../aspose.pdf.signatures/) son campos con valores de objetos de firma, los cuales contienen datos que se utilizan para verificar la validez del documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Una clase abstracta que representa un objeto de apariencia personalizada de firma. |
| [SignatureField](./signaturefield/) | Representa el campo de formulario de firma. |
| [SignatureSubjectFormatter](./signaturesubjectformatter/) |  |
| [SymbologyConverter](./symbologyconverter/) |  |
| [TextBoxField](./textboxfield/) | Clase que representa el campo de cuadro de texto. |
| [XFA](./xfa/) | Representa un formulario XML respecto a la Arquitectura XML [Forms](./) ([XFA](./xfa/)). |
## Enums

| Enumeración | Descripción |
| --- | --- |
| [BoxStyle](./boxstyle/) | Representa los estilos para dibujar la marca de verificación en una casilla de verificación. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Los permisos de acceso otorgados para este documento. Los valores válidos son: 1 - No se permiten cambios al documento; cualquier cambio al documento invalida la firma. 2 - Los cambios permitidos son rellenar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma. 3 - Los cambios permitidos son los mismos que para 2, además de la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma. |
| [FormType](./formtype/) | Enumeración de los posibles tipos de Acro [Form](./form/). |
| [IconCaptionPosition](./iconcaptionposition/) | Describe la posición del ícono. |
| [ScalingMode](./scalingmode/) | El tipo de escalado que se debe usar. |
| [ScalingReason](./scalingreason/) | Las circunstancias bajo las cuales el ícono debe escalarse dentro del rectángulo de anotación. |
| [SubjectNameElements](./subjectnameelements/) | La enumeración describe los elementos en la cadena de asunto de la firma. |
| [Symbology](./symbology/) | Un (Código de barras) [Symbology](./symbology/) define los detalles técnicos de un tipo particular de código de barras: el ancho de las barras, el conjunto de caracteres, el método de codificación, las especificaciones de suma de verificación, etc. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [SignHash](./signhash/) | Delegado para firmar de forma personalizada el hash del documento. |
