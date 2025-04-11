---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: El espacio de nombres Aspose.Pdf.Forms tiene clases que describen formularios (estáticos, dinámicos) y varios tipos de campos como cuadro de texto, cuadro de lista, botón de opción, etc.
type: docs
weight: 110
url: /es/net/aspose.pdf.forms/
---
El **Aspose.Pdf.Forms** namespace tiene clases que describen formularios (estándar, estáticos, dinámicos) y varios tipos de campos como cuadro de texto, cuadro de lista, botón de opción, etc.

## Clases

| Clase | Descripción |
| --- | --- |
| [BarcodeField](./barcodefield/) | Clase que representa el campo de código de barras. |
| [ButtonField](./buttonfield/) | Clase que representa el campo de botón pulsador. |
| [CheckboxField](./checkboxfield/) | Clase que representa el campo de casilla de verificación. |
| [ChoiceField](./choicefield/) | Representa la clase base para campos de elección. |
| [ComboBoxField](./comboboxfield/) | Clase que representa el campo ComboBox del formulario. |
| [DateField](./datefield/) | Campo de fecha con vista de calendario. |
| [DocMDPSignature](./docmdpsignature/) | Representa la clase de firma de documento MDP (detección y prevención de modificaciones). |
| [ExternalSignature](./externalsignature/) | Crea una firma PKCS#7 separada utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables. |
| [Field](./field/) | Clase base para campos de formulario acro. |
| [FileSelectBoxField](./fileselectboxfield/) | Campo para el elemento de cuadro de selección de archivos. |
| [Form](./form/) | Clase que representa el objeto formulario. |
| [IconFit](./iconfit/) | Describe cómo se debe mostrar el icono de la anotación del widget dentro de su rectángulo de anotación. |
| [ListBoxField](./listboxfield/) | Clase que representa el campo ListBox. |
| [NumberField](./numberfield/) | Campo de texto con caracteres válidos especificados. |
| [Option](./option/) | Clase que representa la opción del campo de elección. |
| [OptionCollection](./optioncollection/) | Clase que representa la colección de opciones del campo de elección. |
| [PasswordBoxField](./passwordboxfield/) | Clase que describe el campo de texto para ingresar la contraseña. |
| [PKCS1](./pkcs1/) | Representa el objeto de firma respecto al estándar PKCS#1. Se utilizan el algoritmo de cifrado RSA y el método de resumen SHA-1 para firmar. |
| [PKCS7](./pkcs7/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5. El `resumen SHA1` del rango de bytes del documento está encapsulado en el campo PKCS#7 SignedData. |
| [PKCS7Detached](./pkcs7detached/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5. El resumen del mensaje firmado original sobre el rango de bytes del documento se incorpora como el campo PKCS#7 SignedData normal. No se encapsula ningún dato en el campo PKCS#7 SignedData. |
| [RadioButtonField](./radiobuttonfield/) | Clase que representa el campo de botón de opción. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Clase que representa un elemento del campo de botón de opción. |
| [RichTextBoxField](./richtextboxfield/) | Clase que describe el componente del editor de texto enriquecido. |
| [Signature](./signature/) | Una clase abstracta que representa el objeto de firma en el documento PDF. Las firmas son campos con valores de objetos de firma, los últimos contienen datos que se utilizan para verificar la validez del documento. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Una clase abstracta que representa el objeto de apariencia personalizada de la firma. |
| [SignatureField](./signaturefield/) | Representa el campo de firma del formulario. |
| [SignHash](./signhash/) | Delegado para firmar el hash del documento de forma personalizada. |
| [TextBoxField](./textboxfield/) | Clase que representa el campo de cuadro de texto. |
| [XFA](./xfa/) | Representa el formulario XML respecto a la Arquitectura de Formularios XML (XFA). |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [BoxStyle](./boxstyle/) | Representa estilos para dibujar la marca en la casilla de verificación. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Los permisos de acceso otorgados para este documento. Los valores válidos son: 1 - No se permiten cambios en el documento; cualquier cambio en el documento invalida la firma. 2 - Los cambios permitidos son completar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma. 3 - Los cambios permitidos son los mismos que para 2, así como la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma. |
| [FormType](./formtype/) | Enumeración de posibles tipos de Acro Form. |
| [IconCaptionPosition](./iconcaptionposition/) | Describe la posición del icono. |
| [ScalingMode](./scalingmode/) | El tipo de escalado que se debe utilizar. |
| [ScalingReason](./scalingreason/) | Las circunstancias bajo las cuales el icono se debe escalar dentro del rectángulo de anotación. |
| [SubjectNameElements](./subjectnameelements/) | Enumeración que describe los elementos en la cadena de sujeto de la firma. |
| [Symbology](./symbology/) | Una (Código de barras) Simbología define los detalles técnicos de un tipo particular de código de barras: el ancho de las barras, conjunto de caracteres, método de codificación, especificaciones de suma de verificación, etc. |