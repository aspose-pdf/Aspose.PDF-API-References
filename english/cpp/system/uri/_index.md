---
title: System::Uri class
linktitle: Uri
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri class. Unified resource identifier. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 6700
url: /cpp/system/uri/
---
## Uri class


Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [CheckHostName](./checkhostname/)(String) | Determines the type of the specified host name. |
| static [CheckSchemeName](./checkschemename/)(const String\&) | Determines if the specified scheme is valid. |
| static [Compare](./compare/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) | Compares the specified [Uri](./) objects using the specified comparison rules. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Determines if the URIs represented by the current and specified objects are equal. |
| static [EscapeDataString](./escapedatastring/)(const String\&) | Converts a string to its escaped representation. |
| static [EscapeUriString](./escapeuristring/)(const String\&) | Converts a URI string to its escaped representation. |
| static [FromHex](./fromhex/)(char16_t) | Gets the decimal value of a hexadecimal digit. |
| [get_AbsolutePath](./get_absolutepath/)() const | Returns the absolute path of the URI. |
| [get_AbsoluteUri](./get_absoluteuri/)() const | Returns the absolute URI. |
| [get_Authority](./get_authority/)() const | Returns the host name and the port number for a server. |
| [get_DnsSafeHost](./get_dnssafehost/)() const | Returns an unescaped host name. |
| [get_Fragment](./get_fragment/)() const | Returns the escaped URI fragment. |
| [get_Host](./get_host/)() const | Returns the host name. |
| [get_HostNameType](./get_hostnametype/)() const | Returns the host name type. |
| [get_IdnHost](./get_idnhost/)() const | Returns an International Domain Name of the host. |
| [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Determines if the URI represented by the current object is absolute. |
| [get_IsDefaultPort](./get_isdefaultport/)() const | Determines if the URI represented by the current object has default port for the URI's scheme. |
| [get_IsFile](./get_isfile/)() const | Determines if the URI represented by the current object is a file. |
| [get_IsLoopback](./get_isloopback/)() const | Determines if the URI represented by the current object references a local host. |
| [get_IsUnc](./get_isunc/)() const | Determines if the URI represented by the current object is a UNC path. |
| [get_LocalPath](./get_localpath/)() const | Returns the operating system representation of the file name referenced by the URI represented by the current object. |
| [get_OriginalString](./get_originalstring/)() const | Returns the URI string that was passed to the constructor when current object was constructed. |
| [get_PathAndQuery](./get_pathandquery/)() const | Returns the absolute path and query components of the URI represented by the current object separated by a question mark (?). |
| [get_Port](./get_port/)() const | Returns the port number of the URI represented by the current object. |
| [get_Query](./get_query/)() const | Returns the query information included in the URI represented by the current object. |
| [get_Scheme](./get_scheme/)() const | Returns the scheme of the URI represented by the current object. |
| [get_Segments](./get_segments/)() const | Returns an array of strings containing the path segments of the URI represented by the current object. |
| [get_UserEscaped](./get_userescaped/)() const | Determines if the URI string passed to the constructor of the current object was fully escaped. |
| [get_UserInfo](./get_userinfo/)() const | Returns a uer name, password and other user information associated with the URI represented by the current object. |
| [GetComponents](./getcomponents/)(UriComponents, UriFormat) const | Returns the specified components of the URI represented by the current object using the specified escaping. |
| [GetHashCode](./gethashcode/)() const override | Gets the hash code for the URI. |
| [GetLeftPart](./getleftpart/)(UriPartial) | Returns the specified portion of the URI represented by the current object. |
| static [HexEscape](./hexescape/)(char16_t) | Returns a hexadecimal equivalent of the specified character. |
| static [HexUnescape](./hexunescape/)(const String\&, int32_t\&) | Converts the specified hexadecimal representation of a character to a character. |
| [IsBaseOf](./isbaseof/)(const SharedPtr\<Uri\>\&) const | Determines of the URI represented by the current [Uri](./) object is a base of URI represented by the specified [Uri](./) object. |
| static [IsHexDigit](./ishexdigit/)(char16_t) | Determines if the specified character represents a valid hexadecimal digit. |
| static [IsHexEncoding](./ishexencoding/)(const String\&, int32_t) | Determines if a character in the specified string at the specified position is hexadecimal encoded. |
| [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indicates whether the string used to construct this [Uri](./) was well-formed and is not required to be further escaped. |
| static [IsWellFormedUriString](./iswellformeduristring/)(const String\&, UriKind) | Determines if the specified string is a well-formed URI. |
| [MakeRelative](./makerelative/)(const SharedPtr\<Uri\>\&) | Determines the difference between two [Uri](./) instances. |
| [MakeRelativeUri](./makerelativeuri/)(const SharedPtr\<Uri\>\&) | Determines the difference between URIs represented by the current and the specified [Uri](./) objects. |
| [ToString](./tostring/)() const override | Returns the string representation of the URI represented by the current object. |
| static [TryCreate](./trycreate/)(const String\&, UriKind, SharedPtr\<Uri\>\&) | Constructs a [Uri](./) object that represents the specified URI; an argument specifies the URI kind. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) | Constructs an [Uri](./) abject from the specified [Uri](./) object representing the base URI and the string representation of relative URI. |
| static [TryCreate](./trycreate/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) | Constructs an [Uri](./) abject from the specified base and relative URIs. |
| static [UnescapeDataString](./unescapedatastring/)(const String\&) | Unescapes the specified escaped string. |
| [Uri](./uri/)(const String\&) | Constructs a [Uri](./) object that represents the specified URI. |
| [Uri](./uri/)(const String\&, bool) | Constructs a [Uri](./) object that represents the specified URI; an argument specifies if the URI should be escaped. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&, bool) | Constructs an [Uri](./) abject from the specified [Uri](./) object representing the base URI and the string representation of relative URI; an argument specifies if the URI should be escaped. |
| [Uri](./uri/)(const String\&, UriKind) | Constructs a [Uri](./) object that represents the specified URI; an argument specifies the URI kind. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const String\&) | Constructs an [Uri](./) abject from the specified base and relative URIs. |
| [Uri](./uri/)(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) | Constructs an [Uri](./) abject from the specified base and relative URIs. |
## Fields

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Specifies the characters that separate the communication protocol scheme from the address portion of the [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Specifies that the [Uri](./) is a pointer to a file. |
| static [UriSchemeFtp](./urischemeftp/) | Specifies that the [Uri](./) is accessed through the File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Specifies that the [Uri](./) is accessed through the Gopher protocol. |
| static [UriSchemeHttp](./urischemehttp/) | Specifies that the [Uri](./) is accessed through the Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Specifies that the [Uri](./) is accessed through the Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Specifies that the [Uri](./) is an email address and is accessed through the Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Specifies that the [Uri](./) is accessed through the NetPipe scheme used by [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Specifies that the [Uri](./) is accessed through the NetTcp scheme used by [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Specifies that the [Uri](./) is an Internet news group and is accessed through the Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Specifies that the [Uri](./) is an Internet news group and is accessed through the Network News Transport Protocol. |
## Remarks



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

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
