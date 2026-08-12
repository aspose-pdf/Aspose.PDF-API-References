---
title: "Clase System::Uri"
linktitle: "Uri"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Uri. Identificador uniforme de recursos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 7000
url: /es/cpp/system/uri/
---
## Uri class


Identificador uniforme de recursos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Uri : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [CheckHostName](./checkhostname/)(String) | Determina el tipo del nombre de host especificado. |
| static [CheckSchemeName](./checkschemename/)(const String\&) | Determina si el esquema especificado es válido. |
| static [Compare](./compare/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) | Compara los objetos [Uri](./) especificados usando las reglas de comparación especificadas. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Determina si los URIs representados por los objetos actual y especificado son iguales. |
| static [EscapeDataString](./escapedatastring/)(const String\&) | Convierte una cadena a su representación escapada. |
| static [EscapeUriString](./escapeuristring/)(const String\&) | Convierte una cadena URI a su representación escapada. |
| static [FromHex](./fromhex/)(char16_t) | Obtiene el valor decimal de un dígito hexadecimal. |
| [get_AbsolutePath](./get_absolutepath/)() const | Devuelve la ruta absoluta del URI. |
| [get_AbsoluteUri](./get_absoluteuri/)() const | Devuelve el URI absoluto. |
| [get_Authority](./get_authority/)() const | Devuelve el nombre de host y el número de puerto para un servidor. |
| [get_DnsSafeHost](./get_dnssafehost/)() const | Devuelve un nombre de host sin escapar. |
| [get_Fragment](./get_fragment/)() const | Devuelve el fragmento del URI escapado. |
| [get_Host](./get_host/)() const | Devuelve el nombre de host. |
| [get_HostNameType](./get_hostnametype/)() const | Devuelve el tipo de nombre de host. |
| [get_IdnHost](./get_idnhost/)() const | Devuelve un Nombre de Dominio Internacional del host. |
| [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Determina si el URI representado por el objeto actual es absoluto. |
| [get_IsDefaultPort](./get_isdefaultport/)() const | Determina si el URI representado por el objeto actual tiene el puerto predeterminado para el esquema del URI. |
| [get_IsFile](./get_isfile/)() const | Determina si el URI representado por el objeto actual es un archivo. |
| [get_IsLoopback](./get_isloopback/)() const | Determina si el URI representado por el objeto actual hace referencia a un host local. |
| [get_IsUnc](./get_isunc/)() const | Determina si el URI representado por el objeto actual es una ruta UNC. |
| [get_LocalPath](./get_localpath/)() const | Devuelve la representación del sistema operativo del nombre de archivo referenciado por el URI representado por el objeto actual. |
| [get_OriginalString](./get_originalstring/)() const | Devuelve la cadena URI que se pasó al constructor cuando se construyó el objeto actual. |
| [get_PathAndQuery](./get_pathandquery/)() const | Devuelve la ruta absoluta y los componentes de consulta del URI representado por el objeto actual, separados por un signo de interrogación (?). |
| [get_Port](./get_port/)() const | Devuelve el número de puerto del URI representado por el objeto actual. |
| [get_Query](./get_query/)() const | Devuelve la información de consulta incluida en el URI representado por el objeto actual. |
| [get_Scheme](./get_scheme/)() const | Devuelve el esquema del URI representado por el objeto actual. |
| [get_Segments](./get_segments/)() const | Devuelve una matriz de cadenas que contiene los segmentos de ruta del URI representado por el objeto actual. |
| [get_UserEscaped](./get_userescaped/)() const | Determina si la cadena URI pasada al constructor del objeto actual estaba completamente escapada. |
| [get_UserInfo](./get_userinfo/)() const | Devuelve un nombre de usuario, contraseña y otra información de usuario asociada al URI representado por el objeto actual. |
| [GetComponents](./getcomponents/)(UriComponents, UriFormat) const | Devuelve los componentes especificados del URI representado por el objeto actual usando el escape especificado. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash del URI. |
| [GetLeftPart](./getleftpart/)(UriPartial) | Devuelve la porción especificada del URI representado por el objeto actual. |
| static [HexEscape](./hexescape/)(char16_t) | Devuelve un equivalente hexadecimal del carácter especificado. |
| static [HexUnescape](./hexunescape/)(const String\&, int32_t\&) | Convierte la representación hexadecimal especificada de un carácter a un carácter. |
| [IsBaseOf](./isbaseof/)(const SharedPtr\<Uri\>\&) const | Determina si el URI representado por el objeto [Uri](./) actual es una base del URI representado por el objeto [Uri](./) especificado. |
| static [IsHexDigit](./ishexdigit/)(char16_t) | Determina si el carácter especificado representa un dígito hexadecimal válido. |
| static [IsHexEncoding](./ishexencoding/)(const String\&, int32_t) | Determina si un carácter en la cadena especificada en la posición especificada está codificado en hexadecimal. |
| [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indica si la cadena usada para construir este [Uri](./) estaba bien formada y no requiere ser escapada adicionalmente. |
| static [IsWellFormedUriString](./iswellformeduristring/)(const String\&, UriKind) | Determina si la cadena especificada es un URI bien formado. |
| [MakeRelative](./makerelative/)(const SharedPtr\<Uri\>\&) | Determina la diferencia entre dos instancias de [Uri](./). |
| [MakeRelativeUri](./makerelativeuri/)(const SharedPtr\<Uri\>\&) | Determina la diferencia entre los URIs representados por los objetos [Uri](./) actual y especificado. |
| [ToString](./tostring/)() const override | Devuelve la representación en cadena del URI representado por el objeto actual. |
| static [TryCreate](./trycreate/)(const String\&, UriKind, SharedPtr\<Uri\>\&) | Construye un objeto [Uri](./) que representa el URI especificado; un argumento indica el tipo de URI. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) | Construye un objeto [Uri](./) a partir del objeto [Uri](./) especificado que representa el URI base y la representación en cadena del URI relativo. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) | Construye un objeto [Uri](./) a partir de la base y los URIs relativos especificados. |
| static [UnescapeDataString](./unescapedatastring/)(const String\&) | Desescapa la cadena escapada especificada. |
| [Uri](./uri/)(const String\&) | Construye un objeto [Uri](./) que representa el URI especificado. |
| [Uri](./uri/)(const String\&, bool) | Construye un objeto [Uri](./) que representa el URI especificado; un argumento indica si el URI debe ser escapado. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&, bool) | Construye un [Uri](./) objeto a partir del [Uri](./) especificado que representa la URI base y la representación en cadena de la URI relativa; un argumento indica si la URI debe escaparse. |
| [Uri](./uri/)(const String\&, UriKind) | Construye un objeto [Uri](./) que representa el URI especificado; un argumento indica el tipo de URI. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&) | Construye un objeto [Uri](./) a partir de la base y los URIs relativos especificados. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) | Construye un objeto [Uri](./) a partir de la base y los URIs relativos especificados. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Especifica los caracteres que separan el esquema del protocolo de comunicación de la parte de dirección del [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Especifica que el [Uri](./) es un puntero a un archivo. |
| static [UriSchemeFtp](./urischemeftp/) | Especifica que el [Uri](./) se accede mediante el Protocolo de Transferencia de Archivos. |
| static [UriSchemeGopher](./urischemegopher/) | Especifica que el [Uri](./) se accede mediante el protocolo Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Especifica que el [Uri](./) se accede mediante el Protocolo de Transferencia de Hipertexto. |
| static [UriSchemeHttps](./urischemehttps/) | Especifica que el [Uri](./) se accede mediante el Protocolo Seguro de Transferencia de Hipertexto. |
| static [UriSchemeMailto](./urischememailto/) | Especifica que el [Uri](./) es una dirección de correo electrónico y se accede mediante el Protocolo Simple de Transporte de Correo. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Especifica que el [Uri](./) se accede mediante el esquema NetPipe utilizado por la Fundación de Comunicación de [Windows](../../system.windows/). |
| static [UriSchemeNetTcp](./urischemenettcp/) | Especifica que el [Uri](./) se accede mediante el esquema NetTcp utilizado por la Fundación de Comunicación de [Windows](../../system.windows/). |
| static [UriSchemeNews](./urischemenews/) | Especifica que el [Uri](./) es un grupo de noticias de Internet y se accede mediante el Protocolo de Transporte de Noticias de Red. |
| static [UriSchemeNntp](./urischemenntp/) | Especifica que el [Uri](./) es un grupo de noticias de Internet y se accede mediante el Protocolo de Transporte de Noticias de Red. |
## Observaciones



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
This code example produces the following output:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
