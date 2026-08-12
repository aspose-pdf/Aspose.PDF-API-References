---
title: "System::Security::Cryptography::RSAPKCS1SignatureFormatter clase"
linktitle: "RSAPKCS1SignatureFormatter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSAPKCS1SignatureFormatter clase. Firma datos con una firma RSA PKCS # 1 v1.5. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3800
url: /es/cpp/system.security.cryptography/rsapkcs1signatureformatter/
---
## RSAPKCS1SignatureFormatter class


Firma datos con una firma [RSA](../rsa/) PKCS # 1 v1.5. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class RSAPKCS1SignatureFormatter : public System::Security::Cryptography::AsymmetricSignatureFormatter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) override | Firma datos. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)() | Información RTTI. |
| [RSAPKCS1SignatureFormatter](./rsapkcs1signatureformatter/)(const System::SharedPtr\<AsymmetricAlgorithm\>\&) | Constructor. |
| [SetHashAlgorithm](./sethashalgorithm/)(System::String) override | Establece el algoritmo hash a usar. |
| [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) override | Establece el valor de la clave. No implementado. |
| [~RSAPKCS1SignatureFormatter](./~rsapkcs1signatureformatter/)() | Destructor. |
## Ver también

* Class [AsymmetricSignatureFormatter](../asymmetricsignatureformatter/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
