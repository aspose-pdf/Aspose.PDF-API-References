---
title: "System::Boolean-klass"
linktitle: "Boolesk"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Boolean-klass. Klass som innehåller statiska medlemmar av System.Boolean .Net-typen i C++."
type: docs
weight: 700
url: /sv/cpp/system/boolean/
---
## Boolean class


Klass som innehåller statiska medlemmar av [System.Boolean](./) .[Net](../../system.net/) typen.

```cpp
class Boolean
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Parse](./parse/)(const String\&) | Konverterar den angivna strängen till ett värde av bool-typ. |
| static [TryParse](./tryparse/)(const String\&, bool\&) | Konverterar den angivna strängen till ett värde av bool-typ. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representation av 'false' booleskt värde. |
| static [TrueString](./truestring/) | [String](../string/) representation av 'true' booleskt värde. |
## Anmärkningar



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Skapa den booleska variabeln.
  bool isWeekend = false;

  // Analysera indatasträngen och skriv ut resultatet.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
Is weekend: Yes
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
