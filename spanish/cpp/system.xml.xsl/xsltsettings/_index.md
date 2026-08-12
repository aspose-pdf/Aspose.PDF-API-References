---
title: "System::Xml::Xsl::XsltSettings class"
linktitle: "XsltSettings"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XsltSettings class. Especifica las características XSLT que se deben admitir durante la ejecución de la hoja de estilo XSLT en C++."
type: docs
weight: 800
url: /es/cpp/system.xml.xsl/xsltsettings/
---
## XsltSettings class


Especifica las características XSLT que se deben admitir durante la ejecución de la hoja de estilo XSLT.

```cpp
class XsltSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [get_Default](./get_default/)() | Devuelve un objeto [XsltSettings](./) con la configuración predeterminada. El soporte para la función XSLT **document()** y los bloques de script incrustados está deshabilitado. |
| [get_EnableDocumentFunction](./get_enabledocumentfunction/)() | Devuelve un valor que indica si se debe habilitar el soporte para la función XSLT **document()**. |
| [get_EnableScript](./get_enablescript/)() | Devuelve un valor que indica si se debe habilitar el soporte para bloques de script incrustados. |
| static [get_TrustedXslt](./get_trustedxslt/)() | Devuelve un objeto [XsltSettings](./) que habilita el soporte para la función XSLT **document()** y los bloques de script incrustados. |
| [set_EnableDocumentFunction](./set_enabledocumentfunction/)(bool) | Establece un valor que indica si se debe habilitar el soporte para la función XSLT **document()**. |
| [set_EnableScript](./set_enablescript/)(bool) | Establece un valor que indica si se debe habilitar el soporte para bloques de script incrustados. |
| [XsltSettings](./xsltsettings/)() | Inicializa una nueva instancia de la clase [XsltSettings](./) con la configuración predeterminada. |
| [XsltSettings](./xsltsettings/)(bool, bool) | Inicializa una nueva instancia de la clase [XsltSettings](./) con la configuración especificada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
