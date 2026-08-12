---
title: "Clase System::Net::Cookie"
linktitle: "Cookie"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Cookie. Representa una cookie HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.net/cookie/
---
## Cookie class


Representa una cookie HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Cookie : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Crea una copia de la instancia actual. |
| [Cookie](./cookie/)() | Construye una nueva instancia. |
| [Cookie](./cookie/)(String, String) | Construye una nueva instancia. |
| [Cookie](./cookie/)(String, String, String) | Construye una nueva instancia. |
| [Cookie](./cookie/)(String, String, String, String) | Construye una nueva instancia. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Comment](./get_comment/)() const | Obtiene el valor del atributo 'Comment'. |
| [get_CommentUri](./get_commenturi/)() const | Obtiene el valor del atributo 'CommentURL'. |
| [get_Discard](./get_discard/)() const | Obtiene el valor del atributo 'Discard'. |
| [get_Domain](./get_domain/)() const | Obtiene el valor del atributo 'Domain'. |
| [get_DomainImplicit](./get_domainimplicit/)() | Obtiene un valor que indica si el dominio es implícito. |
| [get_DomainKey](./get_domainkey/)() const | Devuelve la clave del dominio. |
| [get_Expired](./get_expired/)() | Obtiene un valor que indica si la cookie ha expirado. |
| [get_Expires](./get_expires/)() | Obtiene el valor del atributo 'Expires'. |
| [get_HttpOnly](./get_httponly/)() const | Obtiene el valor del atributo 'HttpOnly'. |
| [get_Name](./get_name/)() const | Obtiene el nombre de la cookie. |
| [get_Path](./get_path/)() const | Obtiene el valor del atributo 'Path'. |
| [get_Plain](./get_plain/)() const | Devuelve un valor que indica si la especificación de la cookie es 'Plain'. |
| [get_Port](./get_port/)() const | Obtiene el valor del atributo 'Port'. |
| [get_PortList](./get_portlist/)() const | Devuelve la colección de valores del atributo 'Port'. |
| [get_Secure](./get_secure/)() const | Obtiene el valor del atributo 'Secure'. |
| [get_TimeStamp](./get_timestamp/)() const | Devuelve la hora en que se creó la cookie. |
| [get_Value](./get_value/)() const | Obtiene el valor de la cookie. |
| [get_Variant](./get_variant/)() const | Obtiene la especificación de la cookie. |
| [get_Version](./get_version/)() const | Obtiene el valor del atributo '[Version](../../system/version/)'. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [InternalSetName](./internalsetname/)(String) | Este método es llamado por otros métodos para establecer un nombre de método. |
| [set_Comment](./set_comment/)(String) | Establece el valor del atributo 'Comment'. |
| [set_CommentUri](./set_commenturi/)(System::SharedPtr\<Uri\>) | Establece el valor del atributo 'CommentURL'. |
| [set_Discard](./set_discard/)(bool) | Establece el valor del atributo 'Discard'. |
| [set_Domain](./set_domain/)(String) | Establece el valor del atributo 'Domain'. |
| [set_DomainImplicit](./set_domainimplicit/)(bool) | Establece un valor que indica si el dominio es implícito. |
| [set_Expired](./set_expired/)(bool) | Establece un valor que indica si la cookie ha expirado. |
| [set_Expires](./set_expires/)(DateTime) | Establece el valor del atributo 'Expires'. |
| [set_HttpOnly](./set_httponly/)(bool) | Establece el valor del atributo 'HttpOnly'. |
| [set_Name](./set_name/)(String) | Establece el nombre de la cookie. |
| [set_Path](./set_path/)(String) | Establece el valor del atributo 'Path'. |
| [set_Port](./set_port/)(String) | Establece el valor del atributo 'Port'. |
| [set_Secure](./set_secure/)(bool) | Establece el valor del atributo 'Secure'. |
| [set_Value](./set_value/)(String) | Establece el valor de la cookie. |
| [set_Variant](./set_variant/)(CookieVariant) | Establece la especificación de la cookie. |
| [set_Version](./set_version/)(int32_t) | Establece el valor del atributo '[Version](../../system/version/)'. |
| [ToServerString](./toserverstring/)() | Serializa la instancia actual a la representación en cadena. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| [VerifySetDefaults](./verifysetdefaults/)(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) | Verifica y establece los valores predeterminados del atributo. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | El nombre del atributo 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | El nombre del atributo 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | El nombre del atributo 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | El nombre del atributo 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | El separador que se usa para separar el nombre y el valor de un atributo. |
| static [ExpiresAttributeName](./expiresattributename/) | El nombre del atributo 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | El nombre del atributo 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | El nombre del atributo 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Información RTTI. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | La representación en cadena de la versión máxima soportada. |
| static [PathAttributeName](./pathattributename/) | El nombre del atributo 'Path'. |
| static [PortAttributeName](./portattributename/) | El nombre del atributo 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | El arreglo que contiene los delimitadores de los valores del atributo 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | El símbolo usado para envolver las partes del atributo. |
| static [ReservedToName](./reservedtoname/) | Un valor que está reservado para el nombre de la cookie. |
| static [ReservedToValue](./reservedtovalue/) | Un valor que está reservado para el valor de la cookie. |
| static [SecureAttributeName](./secureattributename/) | El nombre del atributo 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | El separador de atributos. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | El prefijo de los nombres de los atributos especiales. |
| static [VersionAttributeName](./versionattributename/) | El nombre del atributo '[Version](../../system/version/)'. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
