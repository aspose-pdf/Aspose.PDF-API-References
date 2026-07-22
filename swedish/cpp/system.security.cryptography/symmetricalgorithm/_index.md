---
title: "System::Security::Cryptography::SymmetricAlgorithm klass"
linktitle: "SymmetricAlgorithm"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::SymmetricAlgorithm klass. Symmetrisk algoritm som använder samma nyckel för kryptering och dekryptering, basklass. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 4900
url: /sv/cpp/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm class


Symmetrisk algoritm som använder samma nyckel för kryptering och dekryptering, basklass. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)(const String\&) | Skapar algoritminstans. |
| virtual [CreateDecryptor](./createdecryptor/)() | Skapar avkrypterare med parametrar som är associerade med algoritmobjektet. |
| virtual [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Skapar avkrypterare med explicita parametrar. |
| virtual [CreateEncryptor](./createencryptor/)() | Skapar krypterare med parametrar som är associerade med algoritmobjektet. |
| virtual [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Skapar krypterare med explicita parametrar. |
| virtual [GenerateIV](./generateiv/)() | Genererar slumpmässigt initialt värde för algoritmen. Åsidosätter befintligt (om någon). |
| virtual [GenerateKey](./generatekey/)() | Genererar slumpmässig nyckel för algoritmen. Åsidosätter befintlig (om någon). |
| virtual [get_BlockSize](./get_blocksize/)() | Hämtar blockstorlek för den kryptografiska operationen. |
| virtual [get_FeedbackSize](./get_feedbacksize/)() | Hämtar återkopplingsstorlek för den kryptografiska operationen. |
| virtual [get_IV](./get_iv/)() | Hämtar startvärde för kryptografisk operation. Skapar ny om den ännu inte har skapats. |
| virtual [get_Key](./get_key/)() | Hämtar nyckel för kryptografisk operation. Skapar ny om den ännu inte har skapats. |
| virtual [get_KeySize](./get_keysize/)() | Hämtar nyckelstorlek för kryptografisk operation. |
| virtual [get_Mode](./get_mode/)() | Hämtar läge för kryptografisk operation. |
| virtual [get_Padding](./get_padding/)() | Hämtar utfyllnad för kryptografisk operation. |
| virtual [set_BlockSize](./set_blocksize/)(int) | Ställer in blockstorlek för kryptografisk operation. |
| virtual [set_FeedbackSize](./set_feedbacksize/)(int) | Ställer in återkopplingsstorlek för kryptografisk operation. |
| virtual [set_IV](./set_iv/)(System::ArrayPtr\<uint8_t\>) | Ställer in startvärde för kryptografisk operation. |
| virtual [set_Key](./set_key/)(System::ArrayPtr\<uint8_t\>) | Ställer in nyckel för kryptografisk operation. |
| virtual [set_KeySize](./set_keysize/)(int) | Ställer in nyckelstorlek för kryptografisk operation. |
| virtual [set_Mode](./set_mode/)(CipherMode) | Ställer in läge för kryptografisk operation. |
| virtual [set_Padding](./set_padding/)(PaddingMode) | Ställer in utfyllnad för kryptografisk operation. |
| [ValidKeySize](./validkeysize/)(int) | Kontrollerar om nyckelstorleken är giltig. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
