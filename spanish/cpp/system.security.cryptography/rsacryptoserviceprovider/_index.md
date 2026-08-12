---
title: "System::Security::Cryptography::RSACryptoServiceProvider class"
linktitle: "RSACryptoServiceProvider"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::RSACryptoServiceProvider. Algoritmo RSA en forma CSP. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3500
url: /es/cpp/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider class


[RSA](../rsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Decrypt](./decrypt/)(const ByteArrayPtr\&, bool) | Descifra mensaje. No implementado. |
| [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Descifra los datos de entrada usando el modo de relleno especificado. |
| [Dispose](./dispose/)() override | Libera los datos asociados al objeto. |
| [Encrypt](./encrypt/)(const ByteArrayPtr\&, bool) | Encripta mensaje. No implementado. |
| [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Cifra los datos de entrada usando el modo de relleno especificado. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Exporta blob con información de la clave. No implementado. |
| [ExportParameters](./exportparameters/)(bool) override | Exporta parámetros CSP. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Obtiene un objeto [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Comprueba el algoritmo de intercambio de claves asociado al objeto. |
| [get_KeySize](./get_keysize/)() override | Obtiene el tamaño de clave usado por el algoritmo. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Comprueba si la clave se persiste en el objeto CSP. |
| [get_PublicOnly](./get_publiconly/)() const | Comprueba si solo la clave pública está presente en el objeto CSP. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtiene el algoritmo de firma asociado al objeto CSP. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Comprueba si la clave se almacena en el almacén de la máquina en lugar del almacén del usuario. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Importa un blob con información sobre la clave. No implementado. |
| [ImportParameters](./importparameters/)(RSAParameters) override | Importa parámetros CSP. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | Información RTTI. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Constructor. No implementado. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const RSAParameters\&) | Constructor. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t) | Constructor. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Constructor. No implementado. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Define si la clave se persiste en el objeto CSP. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Define si la clave se almacena en el almacén de la máquina en lugar del almacén del usuario. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) | Calcula la firma del valor de entrada especificado. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) | Calcula la firma del valor de entrada especificado. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) | Calcula la firma del valor de entrada especificado. |
| [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) override | Calcula la firma para el valor hash especificado. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Calcula la firma del valor de entrada especificado. No implementado. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) | Comprueba la firma de los datos. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Comprueba la firma de los datos. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) override | Verifica que la firma del hash especificado sea válida. |
## Ver también

* Class [RSA](../rsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
