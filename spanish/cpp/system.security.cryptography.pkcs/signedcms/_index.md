---
title: "System::Security::Cryptography::Pkcs::SignedCms class"
linktitle: "SignedCms"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::Pkcs::SignedCms class. Firma el contenido según la norma CMS/PKCS #7. No implementado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.security.cryptography.pkcs/signedcms/
---
## SignedCms class


Firma el contenido según la norma CMS/PKCS #7. No implementado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class SignedCms : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ComputeSignature](./computesignature/)(const SharedPtr\<CmsSigner\>\&, bool) | Crea una firma. |
| [Encode](./encode/)() | Codifica el mensaje CMS/PKCS #7. |
| [SignedCms](./signedcms/)(const SharedPtr\<ContentInfo\>\&, bool) | Constructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
