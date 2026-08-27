---
title: "aspose.pdf.forms"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "El espacio de nombres aspose.pdf.forms contiene clases que describen formularios (estándar, estáticos, dinámicos) y varios tipos de campos como cuadro de texto, lista desplegable, botón de opción, etc."
type: docs
weight: 60
url: /es/python-net/aspose.pdf.forms/
---


El espacio de nombres aspose.pdf.forms contiene clases que describen formularios (estándar, estáticos, dinámicos) y varios tipos de campos como cuadro de texto, lista desplegable, botón de opción, etc.

## Clases
| Clase | Descripción |
| :- | :- |
| [BarcodeField](/pdf/python-net/aspose.pdf.forms/barcodefield/) | Clase que representa un campo de código de barras. |
| [ButtonField](/pdf/python-net/aspose.pdf.forms/buttonfield/) | Clase que representa un campo de botón pulsador. |
| [CheckboxField](/pdf/python-net/aspose.pdf.forms/checkboxfield/) | Clase que representa un campo de casilla de verificación |
| [ChoiceField](/pdf/python-net/aspose.pdf.forms/choicefield/) | Representa la clase base para campos de selección. |
| [ComboBoxField](/pdf/python-net/aspose.pdf.forms/comboboxfield/) | Clase que representa un campo de cuadro combinado del formulario. |
| [DateField](/pdf/python-net/aspose.pdf.forms/datefield/) | Campo de fecha con vista de calendario. |
| [DocMDPSignature](/pdf/python-net/aspose.pdf.forms/docmdpsignature/) | Representa la clase del tipo de firma de documento MDP (detección y prevención de modificaciones). |
| [ExternalSignature](/pdf/python-net/aspose.pdf.forms/externalsignature/) | Crea una firma PKCS#7Detached separada usando un X509Certificate2. Soporta tarjetas inteligentes usb, tokens sin claves privadas exportables. |
| [Field](/pdf/python-net/aspose.pdf.forms/field/) | Clase base para campos de formulario acro. |
| [FileSelectBoxField](/pdf/python-net/aspose.pdf.forms/fileselectboxfield/) | Campo para elemento de cuadro de selección de archivo. |
| [Form](/pdf/python-net/aspose.pdf.forms/form/) | Clase que representa un objeto de formulario. |
| [IconFit](/pdf/python-net/aspose.pdf.forms/iconfit/) | Describe cómo se debe mostrar el ícono de la anotación del widget dentro de su rectángulo de anotación. |
| [ListBoxField](/pdf/python-net/aspose.pdf.forms/listboxfield/) | Clase que representa el campo ListBox. |
| [NumberField](/pdf/python-net/aspose.pdf.forms/numberfield/) | Campo de texto con caracteres válidos especificados |
| [Option](/pdf/python-net/aspose.pdf.forms/option/) | Clase que representa una opción del campo de elección. |
| [OptionCollection](/pdf/python-net/aspose.pdf.forms/optioncollection/) | Clase que representa la colección de opciones del campo de elección. |
| [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/) | Representa el objeto de firma según el estándar PKCS#1.<br/>            Se utilizan el algoritmo de cifrado RSA y el método de resumen SHA-1 para la firma. |
| [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, <br/>            PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5.<br/>            El resumen SHA1 del rango de bytes del documento está encapsulado en el campo SignedData de PKCS#7. |
| [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) | Representa el objeto PKCS#7 que se ajusta a la especificación PKCS#7 en el RFC 2315 de Internet, <br/>            PKCS #7: Sintaxis de Mensaje Criptográfico, Versión 1.5.<br/>            El resumen original del mensaje firmado sobre el rango de bytes del documento se incorpora como el campo SignedData normal de PKCS#7. <br/>            No se encapsula ningún dato en el campo SignedData de PKCS#7. |
| [PasswordBoxField](/pdf/python-net/aspose.pdf.forms/passwordboxfield/) | Clase que describe el campo de texto para introducir la contraseña. |
| [RadioButtonField](/pdf/python-net/aspose.pdf.forms/radiobuttonfield/) | Clase que representa el campo de botón de opción. |
| [RadioButtonOptionField](/pdf/python-net/aspose.pdf.forms/radiobuttonoptionfield/) | Clase que representa un elemento del campo RadioButton. |
| [RichTextBoxField](/pdf/python-net/aspose.pdf.forms/richtextboxfield/) | Clase que describe el componente de editor de texto enriquecido. |
| [Signature](/pdf/python-net/aspose.pdf.forms/signature/) | Una clase abstracta que representa el objeto de firma en el documento pdf. <br/>            Las firmas son campos con valores de objetos de firma, los cuales contienen datos que se utilizan para<br/>            verificar la validez del documento. |
| [SignatureCustomAppearance](/pdf/python-net/aspose.pdf.forms/signaturecustomappearance/) | Una clase abstracta que representa el objeto de apariencia personalizada de la firma. |
| [SignatureField](/pdf/python-net/aspose.pdf.forms/signaturefield/) | Representa el campo de formulario de firma. |
| [TextBoxField](/pdf/python-net/aspose.pdf.forms/textboxfield/) | Clase que representa el campo de cuadro de texto. |
| [XFA](/pdf/python-net/aspose.pdf.forms/xfa/) | Representa el formulario XML según la Arquitectura de Formularios XML (XFA). |
## Enumeraciones
| Enumeración | Descripción |
| :- | :- |
| [BoxStyle](/pdf/python-net/aspose.pdf.forms/boxstyle/) | Representa los estilos de casilla de verificación. |
| [DocMDPAccessPermissions](/pdf/python-net/aspose.pdf.forms/docmdpaccesspermissions/) | Los permisos de acceso concedidos para este documento.<br/>            Valores válidos son:<br/>            1 - No se permiten cambios al documento; cualquier cambio al documento invalida la firma.<br/>            2 - Los cambios permitidos son rellenar formularios, instanciar plantillas de página y firmar; otros cambios invalidan la firma.<br/>            3 - Los cambios permitidos son los mismos que en el 2, además de la creación, eliminación y modificación de anotaciones; otros cambios invalidan la firma. |
| [FormType](/pdf/python-net/aspose.pdf.forms/formtype/) | Enumeración de posibles tipos de Acro Form. |
| [IconCaptionPosition](/pdf/python-net/aspose.pdf.forms/iconcaptionposition/) | Describe la posición del icono. |
| [ScalingMode](/pdf/python-net/aspose.pdf.forms/scalingmode/) | El tipo de escalado que se debe usar. |
| [ScalingReason](/pdf/python-net/aspose.pdf.forms/scalingreason/) | Las circunstancias bajo las cuales el icono debe escalarse dentro del rectángulo de anotación. |
| [SubjectNameElements](/pdf/python-net/aspose.pdf.forms/subjectnameelements/) | La enumeración describe los elementos en la cadena de asunto de la firma. |
| [Symbology](/pdf/python-net/aspose.pdf.forms/symbology/) | Una simbología (Código de barras) define los detalles técnicos de un tipo particular de código de barras:<br/>            el ancho de las barras, conjunto de caracteres, método de codificación, especificaciones de suma de verificación, etc. |
