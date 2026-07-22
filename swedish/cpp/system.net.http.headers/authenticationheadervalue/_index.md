---
title: "System::Net::Http::Headers::AuthenticationHeaderValue klass"
linktitle: "AuthenticationHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::AuthenticationHeaderValue klass. Representerar värden för ''Authorization'', ''ProxyAuthorization'', ''WWW-Authenticate'' och ''Proxy-Authenticate''-huvuden. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.net.http.headers/authenticationheadervalue/
---
## AuthenticationHeaderValue class


Representerar värden för 'Authorization', 'ProxyAuthorization', 'WWW-Authenticate' och 'Proxy-Authenticate'-huvuden. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class AuthenticationHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String) | Konstruktor. |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String, String) | Konstruktor. |
| [Clone](./clone/)() override | RTTI-information. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Parameter](./get_parameter/)() | Hämtar autentiseringsuppgifterna som innehåller autentiseringsinformationen. |
| [get_Scheme](./get_scheme/)() | RTTI-information. |
| static [GetAuthenticationLength](./getauthenticationlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Analyserar den angivna strängen och returnerar det sista indexet för strängrepresentationen. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [AuthenticationHeaderValue](./). |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [AuthenticationHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
