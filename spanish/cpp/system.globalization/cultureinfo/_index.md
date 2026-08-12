---
title: "System::Globalization::CultureInfo class"
linktitle: "CultureInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::CultureInfo. Colección de valores y algoritmos específicos de la cultura. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.globalization/cultureinfo/
---
## CultureInfo class


Colección de valores y algoritmos específicos de la cultura. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ClearCachedData](./clearcacheddata/)() | Actualiza la información de cultura en caché. |
| [Clone](./clone/)() override | Clona la información de cultura. |
| static [CreateSpecificCulture](./createspecificculture/)(const String\&) | Crea una cultura por nombre. |
| explicit [CultureInfo](./cultureinfo/)(int) | Información RTTI. |
| [CultureInfo](./cultureinfo/)(int, bool) | Constructor. |
| explicit [CultureInfo](./cultureinfo/)(const String\&) | Constructor. |
| [CultureInfo](./cultureinfo/)(const String\&, bool) | Constructor. |
| [CultureInfo](./cultureinfo/)(std::nullptr_t) | Siempre lanza ArgumentNullException. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compara objetos. |
| virtual [get_Calendar](./get_calendar/)() const | Obtiene el calendario usado por la cultura. |
| virtual [get_CompareInfo](./get_compareinfo/)() const | Obtiene el comparador de cadenas que se adhiere a las reglas de la cultura. |
| [get_CultureTypes](./get_culturetypes/)() const | Obtiene la combinación bit a bit de tipos de cultura que describen la cultura actual. |
| static [get_CurrentCulture](./get_currentculture/)() | Obtiene la cultura establecida para el hilo actual. |
| static [get_CurrentUICulture](./get_currentuiculture/)() | Obtiene la cultura UI del hilo actual. |
| virtual [get_DateTimeFormat](./get_datetimeformat/)() const | Obtiene la información de formato de fecha. |
| static [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Obtiene la cultura predeterminada en el dominio de aplicación actual. |
| static [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Obtiene la cultura UI predeterminada en el dominio de aplicación actual. |
| virtual [get_DisplayName](./get_displayname/)() const | Obtiene el nombre para mostrar de la cultura. |
| virtual [get_EnglishName](./get_englishname/)() const | Obtiene el nombre en inglés de la cultura. |
| [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Obtiene el nombre RFC 4646 para un idioma. |
| static [get_InstalledUICulture](./get_installeduiculture/)() | Obtiene la cultura instalada con el sistema operativo. |
| static [get_InvariantCulture](./get_invariantculture/)() | Obtiene la cultura invariante. |
| virtual [get_IsNeutralCulture](./get_isneutralculture/)() const | Comprueba si la cultura es neutral. |
| [get_IsReadOnly](./get_isreadonly/)() const | Comprueba si el objeto de cultura es de solo lectura. |
| virtual [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Obtiene el identificador de configuración regional de entrada activo. |
| virtual [get_LCID](./get_lcid/)() const | Obtiene el identificador de la cultura. |
| virtual [get_Name](./get_name/)() const | Obtiene el nombre de la cultura. |
| virtual [get_NativeName](./get_nativename/)() const | Obtiene el nombre nativo de la cultura. |
| virtual [get_NumberFormat](./get_numberformat/)() const | Obtiene información de formato numérico. |
| virtual [get_OptionalCalendars](./get_optionalcalendars/)() const | Lista de calendarios que se pueden usar con la cultura. |
| virtual [get_Parent](./get_parent/)() const | Obtiene la cultura principal. |
| virtual [get_TextInfo](./get_textinfo/)() const | Obtiene los parámetros de texto utilizados por la cultura. |
| virtual [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Obtiene el código de idioma ISO 639-2 de tres letras. |
| virtual [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Obtiene el código de tres letras para el idioma según lo definido en la API de [Windows](../../system.windows/). |
| virtual [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Obtiene el nombre de idioma ISO de dos letras asociado a la cultura. |
| [get_UseUserOverride](./get_useuseroverride/)() const | Obtiene una bandera que indica si el [CultureInfo](./) usa configuraciones de cultura seleccionadas por el usuario. |
| [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Obtiene una cultura alternativa adecuada para aplicaciones de consola. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&) | Obtiene la cultura por su nombre. Igual que CreateSpecificCulture. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&, const String\&) | Obtiene la cultura por su nombre. |
| static [GetCultureInfo](./getcultureinfo/)(int32_t) | Obtiene la cultura por id. |
| static [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const String\&) | Obsoleto. Obtiene un objeto [CultureInfo](./) de solo lectura mediante la etiqueta de idioma RFC 4646 especificada. |
| static [GetCultures](./getcultures/)(CultureTypes) | Obtiene las culturas que pertenecen a los tipos especificados. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Obtiene el objeto de formato para un tipo específico. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash del objeto. |
| [IsInherited](./isinherited/)() const | Obtiene la bandera de herencia. SOLO USO INTERNO. |
| [operator=](./operator=/)(const CultureInfo\&) |  |
| [operator==](./operator==/)(const CultureInfo\&) const | Compara los parámetros de la cultura. |
| static [ReadOnly](./readonly/)(const CultureInfoPtr\&) | Obtiene una versión de solo lectura de la cultura. |
| static [set_CurrentCulture](./set_currentculture/)(const CultureInfoPtr\&) | Establece la cultura para el hilo actual. |
| static [set_CurrentUICulture](./set_currentuiculture/)(const CultureInfoPtr\&) | Establece la cultura UI del hilo actual. |
| virtual [set_DateTimeFormat](./set_datetimeformat/)(DateTimeFormatInfoPtr) | Establece la información de formato de fecha. |
| static [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const CultureInfoPtr\&) | Establece la cultura predeterminada en el dominio de aplicación actual. |
| static [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const CultureInfoPtr\&) | Establece la cultura UI predeterminada en el dominio de aplicación actual. |
| virtual [set_NumberFormat](./set_numberformat/)(NumberFormatInfoPtr) | Obtiene información de formato numérico. |
| [ToString](./tostring/)() const override | Convierte la cultura a cadena. |
## Ver también

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
