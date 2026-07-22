---
title: "System‑namnutrymme"
linktitle: "System"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System‑namnutrymmet i C++."
type: docs
weight: 2800
url: /sv/cpp/system/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Activator](./activator/) | Innehåller metoder för att skapa objekt‑typer. |
| [Array](./array/) | Klass som representerar en array‑datastruktur. Objekt av denna klass bör endast allokeras med hjälp av funktionerna [System::MakeArray()](./makearray/) och [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [ArrayBase](./arraybase/) | Dummy‑klassen för [System.Array](./array/) (abstrakt basklass för alla arrayer) kan fyllas med funktionalitet på begäran. |
| [ArraySegment](./arraysegment/) | Representerar ett segment av den endimensionella arrayen. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Attribute](./attribute/) | En basklass för anpassade attribut. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BitConverter](./bitconverter/) | Innehåller metoder som utför konverteringar av en sekvens av byte till en värdetyp och vice‑versa. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt. |
| [Boolean](./boolean/) | Klass som behåller statiska medlemmar av typen [System.Boolean](./boolean/) .[Net](../system.net/). |
| [BoxedEnum](./boxedenum/) | Representerar ett inbäddat uppräkningsvärde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BoxedValue](./boxedvalue/) | Representerar ett inbäddat värde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [BoxedValueBase](./boxedvaluebase/) | En basklass som definierar ett gränssnitt och implementerar några grundläggande metoder för en underklass som representerar ett inbäddat värde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Buffer](./buffer/) | Innehåller metoder som manipulerar råa byte‑arrayer. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt. |
| [Byte](./byte/) | Innehåller metoder för att arbeta med den osignerade 8‑bitars heltalet. |
| [Char](./char/) | Tillhandahåller metoder för manipulation av tecken representerade som UTF-16‑kodenheter. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt. |
| [Comparison](./comparison/) | Representerar en pekare till metoden som jämför två objekt av samma typ. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Console](./console/) | Tillhandahåller metoder för att skriva ut data till standardutmatningsströmmen. Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt. |
| [ConsoleOutput](./consoleoutput/) | Representerar standardutmatningsströmmen. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [DateTime](./datetime/) | Representerar ett specifikt datum‑ och tidsvärde på tidslinjen. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [DateTimeOffset](./datetimeoffset/) | Innehåller datum och tid på dagen i förhållande till koordinerad universell tid (UTC). Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [DBNull](./dbnull/) | Representerar ett icke‑existerande värde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det leder till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Decimal](./decimal/) | Representerar ett decimaltal. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) klassimplementation. Tillåter att BoxingValue‑specialiseringar deklareras utan att duplicera gemensam kod. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_returntype(argumenttypes...)_/) | Representerar en pekare till en funktion, metod eller ett funktionsobjekt. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [DynamicWeakPtr](./dynamicweakptr/) | Smartpekarklass som spårar pekarlägen för mallargumenten i det lagrade objektet och uppdaterar dem efter varje tilldelning. Denna typ är en pekare för att hantera raderingen av ett annat objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens. |
| [EnumValues](./enumvalues/) | Tillhandahåller metainformation om uppräkningskonstanter för uppräkningstypen **E**. |
| [EnumValuesBase](./enumvaluesbase/) | En basklass för en klass som representerar metainformation om en uppräkningstyp. |
| [EventArgs](./eventargs/) | Basklassen för klasser som representerar ett sammanhang som skickas till händelseprenumeranter när en händelse utlöses. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [ExceptionWrapper](./exceptionwrapper/) | Mall som representerar en omslag för undantag som är avledda från klassen [Exception](./exception/). |
| [FlagsAttribute](./flagsattribute/) | Indikerar att en uppräkningsvärde kan behandlas som ett bitfält; det vill säga, en mängd av. |
| [Func](./func/) | Funktionsdelegat. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [GC](./gc/) | Representerar en emulerad skräpsamling som fungerar mer som en stub som i praktiken inte gör någonting. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [Guid](./guid/) | Representerar en globalt unik identifierare. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [IAsyncResult](./iasyncresult/) | Representerar statusen för en asynkron operation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [ICloneable](./icloneable/) | Definierar en metod som möjliggör objektkloning – att skapa en kopia av ett objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IComparable](./icomparable/) | Definierar en metod som jämför två objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IConvertible](./iconvertible/) | Definierar metoder som konverterar värdet av den implementerande referens‑ eller värdetypen till en Common Language Runtime‑typ som har ett motsvarande värde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [ICustomFormatter](./icustomformatter/) | Definierar en metod som utför anpassad formatering av en strängrepresentation av ett värde som representeras av det angivna objektet. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IDisposable](./idisposable/) | Definierar en metod som frigör resurser som ägs av det aktuella objektet. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IEquatable](./iequatable/) | Definierar en metod som avgör likheten mellan två objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IFormatProvider](./iformatprovider/) | Definierar en metod som tillhandahåller formateringsinformation. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IFormattable](./iformattable/) | Definierar en metod som formaterar värdet av det aktuella objektet med den angivna formatsträngen och formatleverantören. |
| [Index](./index/) | Representerar ett index i en samling. Indexet kan vara från början eller från slutet. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Int16](./int16/) | Innehåller metoder för att arbeta med 16‑bitars heltal. |
| [Int32](./int32/) | Innehåller metoder för att arbeta med 32‑bitars heltal. |
| [Int64](./int64/) | Innehåller metoder för att arbeta med 64‑bitars heltal. |
| [LockContext](./lockcontext/) | Väktarobjekt som implementerar C# lock()-satsen. |
| [MarshalByRefObject](./marshalbyrefobject/) | Tillhandahåller åtkomst till objekt över applikationsdomänsgränser i fjärranrop‑aktiverade applikationer. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_returntype(argumenttypes...)_/) | Representerar en samling delegater. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Nullable](./nullable/) | Framåtriktad deklaration. |
| [NullableUtils](./nullableutils/) | Representerar C# [System.Nullable](./nullable/) (utan typargument) som en statisk klass. Det går inte att använda det ursprungliga namnet på grund av oförmåga att överbelasta klassmallar i C++. Stöder en värdetyp som kan tilldelas null. Denna klass kan inte ärvas. |
| [Object](./object/) | Basklass som möjliggör användning av metoder som finns tillgängliga för klassen [System.Object](./object/) i C#. Alla icke‑triviala klasser som används i den översatta miljön bör ärva den. |
| [ObjectExt](./objectext/) | Tillhandahåller statiska metoder som efterliknar C#-metoderna i [Object](./object/) för icke‑Object C++‑typer (strängar, tal osv.). Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [ObjectType](./objecttype/) | Tillhandahåller statiska metoder som implementerar getter‑funktioner för objekttyper. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [OperatingSystem](./operatingsystem/) | Representerar ett specifikt operativsystem och tillhandahåller information om det. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Random](./random/) | Representerar en pseudo‑slumpmässig talgenerator. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Range](./range/) | Representerar ett intervall med ett start‑ och slutindex. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [ReadOnlySpan](./readonlyspan/) | Framåtriktad för användning inom klassen [Span](./span/). |
| [ScopedCulture](./scopedculture/) | Representerar en kultur som används inom scopet. |
| [SmartPtr](./smartptr/) | Pekarklass för att omsluta typer som allokeras på heapen. Använd den för att hantera minne för klasser som ärver [Object](./object/). Denna pekartyp följer intrusiva pekarsemantik. Referensräknaren lagras antingen i själva [Object](./object/) eller i en räknarstruktur som är tätt knuten till [Object](./object/)-instansen. I vilket fall som helst bildar alla [SmartPtr](./smartptr/)-instanser en enda ägarskapsgrupp oavsett hur de skapades, vilket skiljer sig från hur std::shared_ptr beter sig. Att konvertera en råpekare till [SmartPtr](./smartptr/) är säkert så länge det finns andra [SmartPtr](./smartptr/)-instanser som håller delade referenser till samma objekt. En [SmartPtr](./smartptr/)-klassinstans kan vara i ett av två tillstånd: delad pekare och svag pekare. För att hålla objektet levande bör antalet delade referenser vara positivt. Både svaga och delade pekare kan användas för att komma åt det pekade objektet (för att anropa metoder, läsa eller skriva fält osv.), men svaga pekare deltar inte i referensräkningen för delade pekare. [Object](./object/) tas bort när den sista 'delade' [SmartPtr](./smartptr/)-pekaren till den förstörs. Se därför till att detta inte händer när inga andra delade [SmartPtr](./smartptr/)-pekare till objektet finns, t.ex. under objektkonstruktion eller destruktion. Använd System::Object::ThisProtector‑vaktobjekt (i C++‑kod) eller CppCTORSelfReference eller CppSelfReference‑attributet (i C#‑kod som översätts) för att åtgärda problemet. På liknande sätt, se till att bryta loopreferenser genom att använda [System::WeakPtr](./weakptr/) pekarklass eller [System::SmartPtrMode::Weak](./smartptrmode/) pekarläge (i C++‑kod) eller CppWeakPtr‑attributet (i C#‑kod som översätts). Om två eller fler objekt refererar till varandra med 'delade' pekare, kommer de aldrig att tas bort. Om pekartypen (svag eller delad) ska bytas vid körning, använd metoden [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) eller klassen [System::DynamicWeakPtr](./dynamicweakptr/). Klassen [SmartPtr](./smartptr/) innehåller inga virtuella metoder. Du bör bara ärva den om du skapar en egen minneshanteringsstrategi. Denna typ är en pekare för att hantera andra objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens. |
| [SmartPtrInfo](./smartptrinfo/) | Tjänsteklass för att testa och ändra innehållet i [SmartPtr](./smartptr/) utan att känna till den slutliga typen. Används för skräpsamling och upptäckt av loopreferenser osv. Tänk på den som en 'pekare till pekare'. Vi kan inte använda [SmartPtr](./smartptr/)-bastypen eftersom den saknar någon; istället använder vi denna 'info'-klass. |
| [Span](./span/) | Representerar ett sammanhängande område av godtyckligt minne, liknande C++20:s std::span. |
| [String](./string/) | [String](./string/)-klassen som används i hela biblioteket. Den är en ersättning för C# [System.String](./string/) vid kodöversättning. Av optimeringsskäl betraktas den inte som en [Object](./object/)-subklass. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [StringComparer](./stringcomparer/) | Jämför strängar med olika jämförelselägen. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StringHashCompiletime](./stringhashcompiletime/) | En hjälparklass som genererar ett hashvärde från en C‑sträng. |
| [TimeSpan](./timespan/) | Representerar ett tidsintervall. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [TimeZone](./timezone/) | Representerar en tidszon. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [TimeZoneInfo](./timezoneinfo/) | Representerar information som beskriver en specifik tidszon. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [Tuple](./tuple/) | Klass som representerar en tupel‑datastruktur. Maximalt antal element är 8. |
| [TupleFactory](./tuplefactory/) | Tillhandahåller statiska metoder för att skapa tupel‑objekt. |
| [TypeInfo](./typeinfo/) | Representerar en specifik typ och tillhandahåller information om den. |
| [Uri](./uri/) | Enhetlig resursidentifierare. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [UriBuilder](./uribuilder/) | Tillhandahåller metoder för att konstruera och modifiera universella resursidentifierare (URI:er). Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [UriParser](./uriparser/) | Används för att tolka ett nytt URI-schema. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](./makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](./smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument. |
| [UriShim](./urishim/) | Tjänsteklass. |
| [ValueTuple](./valuetuple/) | Klass som representerar en [ValueTuple](./valuetuple/) datastruktur. |
| [ValueType](./valuetype/) | Basisklass för värdetyper med [Object](./object/) arv som trunkeras av prestandaskäl. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Version](./version/) | Representerar ett versionsnummer. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Underklass till [System::SmartPtr](./smartptr/) som sätter sig själv i svagt läge vid konstruktion. Observera att denna klass inte garanterar att dess instans alltid förblir i svagt läge eftersom [set_Mode()](./smartptr/set_mode/) fortfarande är tillgänglig. Denna typ är en pekare för att hantera raderingen av andra objekt. Den bör allokeras på stacken och överföras till funktioner antingen som värde eller som konstant referens. |
| [WeakReference](./weakreference/) | Representerar en svag referens som refererar ett objekt samtidigt som objektet fortfarande kan tas bort. |
| [WeakReference< T >](./weakreference_t_/) | Representerar en svag referens som refererar ett objekt samtidigt som objektet fortfarande kan tas bort. |
| [WeakReference<>](./weakreference__/) | Representerar en svag referens som refererar ett objekt samtidigt som objektet fortfarande kan tas bort. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Enumeration som innehåller värden som representerar olika format av base-64-kodad data. |
| [DateTimeKind](./datetimekind/) | Enumerationsvärden som representerar typer av datum och tid. |
| [DayOfWeek](./dayofweek/) | Enumeration som representerar en veckodag. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Anger platsen för miljövariabeln. |
| [MidpointRounding](./midpointrounding/) | Anger beteendet för avrundningsfunktioner. |
| [PlatformID](./platformid/) | Representerar en operativsystemplattform. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) pekartyp: svag eller delad. Definierar om pekaren räknas när det avgörs om objektet ska tas bort eller inte. |
| [StringComparison](./stringcomparison/) | Definierar strängjämförelsestil. |
| [StringSplitOptions](./stringsplitoptions/) | Bestämmer beteendet för stränguppdelning. |
| [TypeCode](./typecode/) | Representerar typen av ett objekt. |
| [UriComponents](./uricomponents/) | Representerar URI-komponenter. |
| [UriFormat](./uriformat/) | Anger hur URI:n är escapad. |
| [UriHostNameType](./urihostnametype/) | Representerar typen av värdnamn. |
| [UriKind](./urikind/) | Representerar typerna av URI:er. |
| [UriPartial](./uripartial/) | Representerar delarna av en URI för metoden [Uri.GetLeftPart](./uri/getleftpart/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Action](./action/) | Delegattyp som refererar metoder som inte har något returvärde. |
| [AggregateException](./aggregateexception/) |  |
| [ArrayPtr](./arrayptr/) | Alias för typen 'pekare till array'. |
| [AsyncCallback](./asynccallback/) | En delegattyp som representerar en metod som ska anropas när en asynkron operation slutförs. |
| [BadImageFormatException](./badimageformatexception/) | Undantaget som kastas när filavbilden för ett dynamiskt länkbibliotek (DLL) eller ett körbart program är ogiltig. Inslå aldrig [BadImageFormatException](./badimageformatexception/) klassinstanser i [System::SmartPtr](./smartptr/). |
| [ByteArrayPtr](./bytearrayptr/) | Ett alias för ett smart pekarobjekt som pekar på en array av osignerade 8-bitars heltal. |
| [Converter](./converter/) | Representerar en pekare till den anropbara enheten som accepterar ett enda argument av typen **TInput** och returnerar ett värde av typen **TOutput**. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/). |
| [DecoderFallbackPtr](./decoderfallbackptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::DecoderFallback](../system.text/decoderfallback/). |
| [DecoderPtr](./decoderptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::Decoder](../system.text/decoder/). |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/). |
| [DirectoryInfoPtr](./directoryinfoptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::DirectoryInfo](../system.io/directoryinfo/). |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/). |
| [EncoderFallbackPtr](./encoderfallbackptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::EncoderFallback](../system.text/encoderfallback/). |
| [EncoderPtr](./encoderptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::Encoder](../system.text/encoder/). |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/). |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/). |
| [EncodingInfoPtr](./encodinginfoptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::EncodingInfo](../system.text/encodinginfo/). |
| [EncodingPtr](./encodingptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Text::Encoding](../system.text/encoding/). |
| [Event](./event/) | Representerar en händelse – en mekanism genom vilken prenumeranter meddelas om en intressant förekomst via ett delegatanrop. |
| [EventArgsPtr](./eventargsptr/) | Delad pekare till en instans av klassen [EventArgs](./eventargs/). |
| [EventHandler](./eventhandler/) | Representerar en metod som reagerar på och bearbetar en händelse. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](./smartptr/) för att hantera objekt av denna typ. |
| [Exception](./exception/) | Alias att använda istället för Details::Exception. |
| [ExceptionPtr](./exceptionptr/) | Typalias som används av undantagsomslag. |
| [FileInfoPtr](./fileinfoptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::FileInfo](../system.io/fileinfo/). |
| [FileStreamPtr](./filestreamptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::FileStream](../system.io/filestream/). |
| [FileSystemInfoPtr](./filesysteminfoptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::FileSystemInfo](../system.io/filesysteminfo/). |
| [FunctionPtr](./functionptr/) | Ett alias för funktionstyp med standardanropskonvention. |
| [IAsyncResultPtr](./iasyncresultptr/) | Delad pekare till [IAsyncResult](./iasyncresult/). |
| [IFormatProviderPtr](./iformatproviderptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IFormatProvider](./iformatprovider/) . |
| [MakeConstRef_t](./makeconstref_t/) | Hjälptyp för [MakeConstRef](./makeconstref/) modifieraren. |
| [MemoryStreamPtr](./memorystreamptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::MemoryStream](../system.io/memorystream/) . |
| [Predicate](./predicate/) | Representerar en pekare till ett predikat – en anropbar entitet som accepterar ett enda argument och returnerar ett booleskt värde. |
| [RTaskPtr](./rtaskptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) . |
| [SharedPtr](./sharedptr/) | Alias för smart pekare som används flitigt i biblioteket. |
| [StreamPtr](./streamptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::Stream](../system.io/stream/) . |
| [StreamReaderPtr](./streamreaderptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::StreamReader](../system.io/streamreader/) . |
| [StreamWriterPtr](./streamwriterptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::IO::StreamWriter](../system.io/streamwriter/) . |
| [StringComparerPtr](./stringcomparerptr/) | Ett alias för en delad pekare till en instans av klassen [StringComparer](./stringcomparer/) . |
| [SystemException](./systemexception/) |  |
| [TaskPtr](./taskptr/) | Ett alias för en smart pekare som pekar på en instans av klassen [System::Threading::Tasks::Task](../system.threading.tasks/task/) . |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Alias för delad pekare till en instans av klassen [TimeZoneInfo](./timezoneinfo/) . |
| [TimeZonePtr](./timezoneptr/) | Delad pekare till en instans av klassen [TimeZone](./timezone/) . |
## Functions

| Funktion | Beskrivning |
| --- | --- |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Build | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| BuildArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| BuildObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CheckedCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| const_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConstCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Standard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Standard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Kasta bort | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| dynamic_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< double, double > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< float, float > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForceStaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForEachMemberGVName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GEqual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Get | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| get_pointer | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Greater | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| InitObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Is | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Is | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Is | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_parametrized_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_vp_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNaN | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNegativeInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNull | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPositiveInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| LEqual | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Less | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeScopeGuard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeValueAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeValueAsync | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeYieldEnumerable | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeYieldEnumerator | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MemberwiseClone | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::DateTime > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::String > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator* | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator/ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| SafeInvoke | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Set | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_add_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_and_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_div_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_exor_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mod_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_mul_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_or_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shl_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_shr_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_sub_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| static_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| TieTuple | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| With | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| With | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
