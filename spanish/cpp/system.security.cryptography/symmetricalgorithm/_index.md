---
title: "Clase System::Security::Cryptography::SymmetricAlgorithm"
linktitle: "SymmetricAlgorithm"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::SymmetricAlgorithm. Algoritmo simétrico que utiliza la misma clave para cifrado y descifrado, clase base. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 4900
url: /es/cpp/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm class


Algoritmo simétrico que utiliza la misma clave para cifrado y descifrado, clase base. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)(const String\&) | Crea una instancia del algoritmo. |
| virtual [CreateDecryptor](./createdecryptor/)() | Crea un descifrador con los parámetros asociados al objeto del algoritmo. |
| virtual [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Crea un descifrador con parámetros explícitos. |
| virtual [CreateEncryptor](./createencryptor/)() | Crea un cifrador con los parámetros asociados al objeto del algoritmo. |
| virtual [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Crea un cifrador con parámetros explícitos. |
| virtual [GenerateIV](./generateiv/)() | Genera un valor inicial aleatorio para el algoritmo. Sobrescribe el existente (si lo hay). |
| virtual [GenerateKey](./generatekey/)() | Genera una clave aleatoria para el algoritmo. Sobrescribe la existente (si la hay). |
| virtual [get_BlockSize](./get_blocksize/)() | Obtiene el tamaño de bloque de la operación criptográfica. |
| virtual [get_FeedbackSize](./get_feedbacksize/)() | Obtiene el tamaño de retroalimentación de la operación criptográfica. |
| virtual [get_IV](./get_iv/)() | Obtiene el valor inicial de la operación criptográfica. Crea uno nuevo si aún no se ha creado. |
| virtual [get_Key](./get_key/)() | Obtiene la clave de la operación criptográfica. Crea una nueva si aún no se ha creado. |
| virtual [get_KeySize](./get_keysize/)() | Obtiene el tamaño de la clave de la operación criptográfica. |
| virtual [get_Mode](./get_mode/)() | Obtiene el modo de la operación criptográfica. |
| virtual [get_Padding](./get_padding/)() | Obtiene el relleno de la operación criptográfica. |
| virtual [set_BlockSize](./set_blocksize/)(int) | Establece el tamaño de bloque de la operación criptográfica. |
| virtual [set_FeedbackSize](./set_feedbacksize/)(int) | Establece el tamaño de retroalimentación de la operación criptográfica. |
| virtual [set_IV](./set_iv/)(System::ArrayPtr\<uint8_t\>) | Establece el valor inicial de la operación criptográfica. |
| virtual [set_Key](./set_key/)(System::ArrayPtr\<uint8_t\>) | Establece la clave de la operación criptográfica. |
| virtual [set_KeySize](./set_keysize/)(int) | Establece el tamaño de la clave de la operación criptográfica. |
| virtual [set_Mode](./set_mode/)(CipherMode) | Establece el modo de la operación criptográfica. |
| virtual [set_Padding](./set_padding/)(PaddingMode) | Establece el relleno de la operación criptográfica. |
| [ValidKeySize](./validkeysize/)(int) | Comprueba si el tamaño de la clave es válido. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
