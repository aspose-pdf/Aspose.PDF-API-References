---
title: "System::Security::Cryptography::Pkcs::CmsSigner class"
linktitle: "CmsSigner"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::Pkcs::CmsSigner class. Proporciona una API para firmar objetos usando CMS. No firma objetos por sí mismo, use la clase SignedCMS para hacerlo. No implementado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography.pkcs/cmssigner/
---
## CmsSigner class


Proporciona una API para firmar objetos usando CMS. No firma objetos por sí mismo, use la clase SignedCMS para hacerlo. No implementado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class CmsSigner : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CmsSigner](./cmssigner/)(const SharedPtr\<X509Certificates::X509Certificate2\>\&) | Inicializa el firmante con un certificado X509. |
| [get_DigestAlgorithm](./get_digestalgorithm/)() const | Obtiene el algoritmo de hash utilizado con la firma. |
| [get_IncludeOption](./get_includeoption/)() const | Comprueba qué certificados de la cadena se incluirán en la firma. |
| [set_DigestAlgorithm](./set_digestalgorithm/)(const SharedPtr\<Oid\>\&) | Establece el algoritmo de hash utilizado con la firma. |
| [set_IncludeOption](./set_includeoption/)(X509Certificates::X509IncludeOption) | Especifica qué certificados de la cadena se incluirán en la firma. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
