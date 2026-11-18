---
title: System::Text::Json::ThrowHelper class
linktitle: ThrowHelper
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Text::Json::ThrowHelper class in C++.'
type: docs
weight: 2600
url: /cpp/system.text.json/throwhelper/
---
## ThrowHelper class




```cpp
class ThrowHelper
```

## Methods

| Method | Description |
| --- | --- |
| static [AddJsonExceptionInformation](./addjsonexceptioninformation/)(ReadStack\&, Utf8JsonReader\&, JsonException) |  |
| static [AddJsonExceptionInformation](./addjsonexceptioninformation/)(WriteStack\&, JsonException) |  |
| static [AppendMissingProperty](./appendmissingproperty/)(System::SharedPtr\<StringBuilder\>, String) |  |
| static [GetArgumentException_ReadInvalidUTF16](./getargumentexception_readinvalidutf16/)(EncoderFallbackException) |  |
| static [GetInvalidOperationException](./getinvalidoperationexception/)(String, Exception) |  |
| static [GetInvalidOperationException](./getinvalidoperationexception/)(ExceptionResource, int32_t, int32_t, uint8_t, JsonTokenType) |  |
| static [GetInvalidOperationException_ExpectedArray](./getinvalidoperationexception_expectedarray/)(JsonTokenType) |  |
| static [GetInvalidOperationException_ExpectedObject](./getinvalidoperationexception_expectedobject/)(JsonTokenType) |  |
| static [GetInvalidOperationException_NoMetadataForTypeProperties](./getinvalidoperationexception_nometadatafortypeproperties/)(System::SharedPtr\<Serialization::Metadata::IJsonTypeInfoResolver\>, const TypeInfo\&) |  |
| static [GetInvalidOperationException_ReadInvalidUTF8](./getinvalidoperationexception_readinvalidutf8/)(DecoderFallbackException) |  |
| static [GetJsonElementWrongTypeException](./getjsonelementwrongtypeexception/)(JsonValueKind, JsonValueKind) |  |
| static [GetJsonElementWrongTypeException](./getjsonelementwrongtypeexception/)(String, JsonValueKind) |  |
| static [GetJsonReaderException](./getjsonreaderexception/)(Utf8JsonReader\&, ExceptionResource, uint8_t, ReadOnlySpan\<uint8_t\>) |  |
| static [GetNotSupportedException_AmbiguousMetadataForType](./getnotsupportedexception_ambiguousmetadatafortype/)(const TypeInfo\&, const TypeInfo\&, const TypeInfo\&) |  |
| static [GetPrintableString](./getprintablestring/)(uint8_t) |  |
| static [ReThrowWithPath](./rethrowwithpath/)(ReadStack\&, JsonReaderException) |  |
| static [ReThrowWithPath](./rethrowwithpath/)(ReadStack\&, Utf8JsonReader\&, Exception) |  |
| static [ReThrowWithPath](./rethrowwithpath/)(WriteStack\&, Exception) |  |
| static [ThrowArgumentException](./throwargumentexception/)(String) |  |
| static [ThrowArgumentException](./throwargumentexception/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowArgumentException](./throwargumentexception/)(ReadOnlySpan\<uint8_t\>, ReadOnlySpan\<char16_t\>) |  |
| static [ThrowArgumentException](./throwargumentexception/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowArgumentException](./throwargumentexception/)(ReadOnlySpan\<char16_t\>, ReadOnlySpan\<char16_t\>) |  |
| static [ThrowArgumentException_CannotSerializeInvalidType](./throwargumentexception_cannotserializeinvalidtype/)(String, const TypeInfo\&, const TypeInfo\&, String) |  |
| static [ThrowArgumentException_DeserializeWrongType](./throwargumentexception_deserializewrongtype/)(const TypeInfo\&, System::SharedPtr\<Object\>) |  |
| static [ThrowArgumentException_DestinationTooShort](./throwargumentexception_destinationtooshort/)() |  |
| static [ThrowArgumentException_InvalidOffLen](./throwargumentexception_invalidofflen/)() |  |
| static [ThrowArgumentException_InvalidUTF16](./throwargumentexception_invalidutf16/)(int32_t) |  |
| static [ThrowArgumentException_InvalidUTF8](./throwargumentexception_invalidutf8/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowArgumentException_JsonPolymorphismOptionsAssociatedWithDifferentJsonTypeInfo](./throwargumentexception_jsonpolymorphismoptionsassociatedwithdifferentjsontypeinfo/)(String) |  |
| static [ThrowArgumentException_NodeValueNotAllowed](./throwargumentexception_nodevaluenotallowed/)(String) |  |
| static [ThrowArgumentException_PropertyNameTooLarge](./throwargumentexception_propertynametoolarge/)(int32_t) |  |
| static [ThrowArgumentException_SerializerDoesNotSupportComments](./throwargumentexception_serializerdoesnotsupportcomments/)(String) |  |
| static [ThrowArgumentException_ValueNotSupported](./throwargumentexception_valuenotsupported/)() |  |
| static [ThrowArgumentException_ValueTooLarge](./throwargumentexception_valuetoolarge/)(int64_t) |  |
| static [ThrowArgumentNullException](./throwargumentnullexception/)(ExceptionArgument) |  |
| static [ThrowArgumentNullException](./throwargumentnullexception/)(String) |  |
| static [ThrowArgumentOutOfRangeException_CommentEnumMustBeInRange](./throwargumentoutofrangeexception_commentenummustbeinrange/)(String) |  |
| static [ThrowArgumentOutOfRangeException_IndentCharacter](./throwargumentoutofrangeexception_indentcharacter/)(String) |  |
| static [ThrowArgumentOutOfRangeException_IndentSize](./throwargumentoutofrangeexception_indentsize/)(String, int32_t, int32_t) |  |
| static [ThrowArgumentOutOfRangeException_JsonNumberExponentTooLarge](./throwargumentoutofrangeexception_jsonnumberexponenttoolarge/)(String) |  |
| static [ThrowArgumentOutOfRangeException_MaxDepthMustBePositive](./throwargumentoutofrangeexception_maxdepthmustbepositive/)(String) |  |
| static [ThrowArgumentOutOfRangeException_NeedNonNegNum](./throwargumentoutofrangeexception_neednonnegnum/)(String) |  |
| static [ThrowArgumentOutOfRangeException_NewLine](./throwargumentoutofrangeexception_newline/)(String) |  |
| static [ThrowFormatException](./throwformatexception/)() |  |
| static [ThrowFormatException](./throwformatexception/)(NumericType) |  |
| static [ThrowFormatException](./throwformatexception/)(DataType) |  |
| [ThrowHelper](./throwhelper/)() |  |
| static [ThrowInvalidCastException_DeserializeUnableToAssignValue](./throwinvalidcastexception_deserializeunabletoassignvalue/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException](./throwinvalidoperationexception/)(int32_t, int32_t) |  |
| static [ThrowInvalidOperationException](./throwinvalidoperationexception/)(String) |  |
| static [ThrowInvalidOperationException](./throwinvalidoperationexception/)(ExceptionResource, int32_t, int32_t, uint8_t, JsonTokenType) |  |
| static [ThrowInvalidOperationException_CannotMixEncodings](./throwinvalidoperationexception_cannotmixencodings/)(Utf8JsonWriter::EnclosingContainerType, Utf8JsonWriter::EnclosingContainerType) |  |
| static [ThrowInvalidOperationException_CannotSerializeInvalidType](./throwinvalidoperationexception_cannotserializeinvalidtype/)(const TypeInfo\&, const TypeInfo\&, System::SharedPtr\<Reflection::MemberInfo\>) |  |
| static [ThrowInvalidOperationException_CannotSkipOnPartial](./throwinvalidoperationexception_cannotskiponpartial/)() |  |
| static [ThrowInvalidOperationException_ConstructorParameterIncompleteBinding](./throwinvalidoperationexception_constructorparameterincompletebinding/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_CreateObjectConverterNotCompatible](./throwinvalidoperationexception_createobjectconverternotcompatible/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_DerivedTypeIsAlreadySpecified](./throwinvalidoperationexception_derivedtypeisalreadyspecified/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_DerivedTypeNotSupported](./throwinvalidoperationexception_derivedtypenotsupported/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_DeserializeUnableToAssignNull](./throwinvalidoperationexception_deserializeunabletoassignnull/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_ExpectedBoolean](./throwinvalidoperationexception_expectedboolean/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExpectedChar](./throwinvalidoperationexception_expectedchar/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExpectedComment](./throwinvalidoperationexception_expectedcomment/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExpectedNumber](./throwinvalidoperationexception_expectednumber/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExpectedPropertyName](./throwinvalidoperationexception_expectedpropertyname/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExpectedString](./throwinvalidoperationexception_expectedstring/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExpectedStringComparison](./throwinvalidoperationexception_expectedstringcomparison/)(JsonTokenType) |  |
| static [ThrowInvalidOperationException_ExtensionDataCannotBindToCtorParam](./throwinvalidoperationexception_extensiondatacannotbindtoctorparam/)(String, System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_IgnoreConditionOnValueTypeInvalid](./throwinvalidoperationexception_ignoreconditiononvaluetypeinvalid/)(String, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_InvalidChainedResolver](./throwinvalidoperationexception_invalidchainedresolver/)() |  |
| static [ThrowInvalidOperationException_InvalidCustomTypeDiscriminatorPropertyName](./throwinvalidoperationexception_invalidcustomtypediscriminatorpropertyname/)() |  |
| static [ThrowInvalidOperationException_JsonIncludeOnInaccessibleProperty](./throwinvalidoperationexception_jsonincludeoninaccessibleproperty/)(String, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_JsonPropertyInfoIsBoundToDifferentJsonTypeInfo](./throwinvalidoperationexception_jsonpropertyinfoisboundtodifferentjsontypeinfo/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_JsonPropertyRequiredAndExtensionData](./throwinvalidoperationexception_jsonpropertyrequiredandextensiondata/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_JsonPropertyRequiredAndNotDeserializable](./throwinvalidoperationexception_jsonpropertyrequiredandnotdeserializable/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_JsonSerializerOptionsNoTypeInfoResolverSpecified](./throwinvalidoperationexception_jsonserializeroptionsnotypeinforesolverspecified/)() |  |
| static [ThrowInvalidOperationException_JsonTypeInfoOnDeserializingCallbacksNotSupported](./throwinvalidoperationexception_jsontypeinfoondeserializingcallbacksnotsupported/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_JsonTypeInfoOperationNotPossibleForKind](./throwinvalidoperationexception_jsontypeinfooperationnotpossibleforkind/)(Serialization::Metadata::JsonTypeInfoKind) |  |
| static [ThrowInvalidOperationException_MultiplePropertiesBindToConstructorParameters](./throwinvalidoperationexception_multiplepropertiesbindtoconstructorparameters/)(const TypeInfo\&, String, String, String) |  |
| static [ThrowInvalidOperationException_NamingPolicyReturnNull](./throwinvalidoperationexception_namingpolicyreturnnull/)(System::SharedPtr\<JsonNamingPolicy\>) |  |
| static [ThrowInvalidOperationException_NeedLargerSpan](./throwinvalidoperationexception_needlargerspan/)() |  |
| static [ThrowInvalidOperationException_NodeAlreadyHasParent](./throwinvalidoperationexception_nodealreadyhasparent/)() |  |
| static [ThrowInvalidOperationException_NodeCycleDetected](./throwinvalidoperationexception_nodecycledetected/)() |  |
| static [ThrowInvalidOperationException_NodeElementCannotBeObjectOrArray](./throwinvalidoperationexception_nodeelementcannotbeobjectorarray/)() |  |
| static [ThrowInvalidOperationException_NodeJsonObjectCustomConverterNotAllowedOnExtensionProperty](./throwinvalidoperationexception_nodejsonobjectcustomconverternotallowedonextensionproperty/)() |  |
| static [ThrowInvalidOperationException_NodeParentWrongType](./throwinvalidoperationexception_nodeparentwrongtype/)(String) |  |
| static [ThrowInvalidOperationException_NodeUnableToConvert](./throwinvalidoperationexception_nodeunabletoconvert/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_NodeUnableToConvertElement](./throwinvalidoperationexception_nodeunabletoconvertelement/)(JsonValueKind, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_NodeWrongType](./throwinvalidoperationexception_nodewrongtype/)(const System::SharedPtr\<Array\<String\>\>\&) |  |
| static [ThrowInvalidOperationException_NoMetadataForType](./throwinvalidoperationexception_nometadatafortype/)(const TypeInfo\&, System::SharedPtr\<Serialization::Metadata::IJsonTypeInfoResolver\>) |  |
| static [ThrowInvalidOperationException_NoMetadataForTypeProperties](./throwinvalidoperationexception_nometadatafortypeproperties/)(System::SharedPtr\<Serialization::Metadata::IJsonTypeInfoResolver\>, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_NumberHandlingOnPropertyInvalid](./throwinvalidoperationexception_numberhandlingonpropertyinvalid/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_PolymorphicTypeConfigurationDoesNotSpecifyDerivedTypes](./throwinvalidoperationexception_polymorphictypeconfigurationdoesnotspecifyderivedtypes/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_PropertyConflictsWithMetadataPropertyName](./throwinvalidoperationexception_propertyconflictswithmetadatapropertyname/)(const TypeInfo\&, String) |  |
| static [ThrowInvalidOperationException_PropertyTypeNotNullable](./throwinvalidoperationexception_propertytypenotnullable/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_ReadIncompleteUTF16](./throwinvalidoperationexception_readincompleteutf16/)() |  |
| static [ThrowInvalidOperationException_ReadInvalidUTF16](./throwinvalidoperationexception_readinvalidutf16/)(int32_t) |  |
| static [ThrowInvalidOperationException_ResolverTypeInfoOptionsNotCompatible](./throwinvalidoperationexception_resolvertypeinfooptionsnotcompatible/)() |  |
| static [ThrowInvalidOperationException_ResolverTypeNotCompatible](./throwinvalidoperationexception_resolvertypenotcompatible/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_SerializationDataExtensionPropertyInvalid](./throwinvalidoperationexception_serializationdataextensionpropertyinvalid/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_SerializationDuplicateTypeAttribute](./throwinvalidoperationexception_serializationduplicatetypeattribute/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_SerializationDuplicateTypeAttribute](./throwinvalidoperationexception_serializationduplicatetypeattribute/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_SerializerConverterFactoryReturnsJsonConverterFactory](./throwinvalidoperationexception_serializerconverterfactoryreturnsjsonconverterfactory/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_SerializerConverterFactoryReturnsNull](./throwinvalidoperationexception_serializerconverterfactoryreturnsnull/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_SerializerCycleDetected](./throwinvalidoperationexception_serializercycledetected/)(int32_t) |  |
| static [ThrowInvalidOperationException_SerializerOptionsReadOnly](./throwinvalidoperationexception_serializeroptionsreadonly/)(System::SharedPtr\<Serialization::JsonSerializerContext\>) |  |
| static [ThrowInvalidOperationException_SerializerPropertyNameConflict](./throwinvalidoperationexception_serializerpropertynameconflict/)(const TypeInfo\&, String) |  |
| static [ThrowInvalidOperationException_SerializerPropertyNameNull](./throwinvalidoperationexception_serializerpropertynamenull/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowInvalidOperationException_TypeClassifierNotSupported](./throwinvalidoperationexception_typeclassifiernotsupported/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_TypeDicriminatorIdIsAlreadySpecified](./throwinvalidoperationexception_typedicriminatoridisalreadyspecified/)(const TypeInfo\&, System::SharedPtr\<Object\>) |  |
| static [ThrowInvalidOperationException_TypeDoesNotSupportPolymorphism](./throwinvalidoperationexception_typedoesnotsupportpolymorphism/)(const TypeInfo\&) |  |
| static [ThrowInvalidOperationException_TypeInfoImmutable](./throwinvalidoperationexception_typeinfoimmutable/)() |  |
| static [ThrowInvalidOperationException_TypeInfoResolverChainImmutable](./throwinvalidoperationexception_typeinforesolverchainimmutable/)() |  |
| static [ThrowInvalidOperationException_UnsupportedEnumIdentifier](./throwinvalidoperationexception_unsupportedenumidentifier/)(const TypeInfo\&, String) |  |
| static [ThrowInvalidOperationOrArgumentException](./throwinvalidoperationorargumentexception/)(ReadOnlySpan\<uint8_t\>, int32_t, int32_t) |  |
| static [ThrowInvalidOperationOrArgumentException](./throwinvalidoperationorargumentexception/)(ReadOnlySpan\<char16_t\>, int32_t, int32_t) |  |
| static [ThrowJsonElementWrongTypeException](./throwjsonelementwrongtypeexception/)(JsonTokenType, JsonTokenType) |  |
| static [ThrowJsonException](./throwjsonexception/)(String) |  |
| static [ThrowJsonException_DeserializeUnableToConvertValue](./throwjsonexception_deserializeunabletoconvertvalue/)(const TypeInfo\&) |  |
| static [ThrowJsonException_DuplicateMetadataProperty](./throwjsonexception_duplicatemetadataproperty/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowJsonException_DuplicatePropertyNotAllowed](./throwjsonexception_duplicatepropertynotallowed/)(System::SharedPtr\<Serialization::Metadata::JsonPropertyInfoBase\>) |  |
| static [ThrowJsonException_DuplicatePropertyNotAllowed](./throwjsonexception_duplicatepropertynotallowed/)() |  |
| static [ThrowJsonException_DuplicatePropertyNotAllowed](./throwjsonexception_duplicatepropertynotallowed/)(String) |  |
| static [ThrowJsonException_DuplicatePropertyNotAllowed](./throwjsonexception_duplicatepropertynotallowed/)(ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowJsonException_JsonRequiredPropertyMissing](./throwjsonexception_jsonrequiredpropertymissing/)(System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>, System::SharedPtr\<Collections::BitArray\>) |  |
| static [ThrowJsonException_JsonRequiredPropertyMissing](./throwjsonexception_jsonrequiredpropertymissing/)(const TypeInfo\&, String) |  |
| static [ThrowJsonException_MetadataInvalidPropertyInArrayMetadata](./throwjsonexception_metadatainvalidpropertyinarraymetadata/)(ReadStack\&, const TypeInfo\&, Utf8JsonReader\&) |  |
| static [ThrowJsonException_MetadataInvalidPropertyWithLeadingDollarSign](./throwjsonexception_metadatainvalidpropertywithleadingdollarsign/)(ReadOnlySpan\<uint8_t\>, ReadStack\&, Utf8JsonReader\&) |  |
| static [ThrowJsonException_MetadataPreservedArrayValuesNotFound](./throwjsonexception_metadatapreservedarrayvaluesnotfound/)(ReadStack\&, const TypeInfo\&) |  |
| static [ThrowJsonException_MetadataStandaloneValuesProperty](./throwjsonexception_metadatastandalonevaluesproperty/)(ReadStack\&, ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowJsonException_MetadataUnexpectedProperty](./throwjsonexception_metadataunexpectedproperty/)(ReadOnlySpan\<uint8_t\>, ReadStack\&) |  |
| static [ThrowJsonException_MetadataValuesInvalidToken](./throwjsonexception_metadatavaluesinvalidtoken/)(JsonTokenType) |  |
| static [ThrowJsonException_MetadataValueWasNotString](./throwjsonexception_metadatavaluewasnotstring/)(JsonTokenType) |  |
| static [ThrowJsonException_MetadataValueWasNotString](./throwjsonexception_metadatavaluewasnotstring/)(JsonValueKind) |  |
| static [ThrowJsonException_SerializationConverterRead](./throwjsonexception_serializationconverterread/)(System::SharedPtr\<Serialization::JsonConverterBase\>) |  |
| static [ThrowJsonException_SerializationConverterWrite](./throwjsonexception_serializationconverterwrite/)(System::SharedPtr\<Serialization::JsonConverterBase\>) |  |
| static [ThrowJsonException_SerializerCycleDetected](./throwjsonexception_serializercycledetected/)(int32_t) |  |
| static [ThrowJsonException_UnrecognizedTypeDiscriminator](./throwjsonexception_unrecognizedtypediscriminator/)(System::SharedPtr\<Object\>) |  |
| static [ThrowJsonReaderException](./throwjsonreaderexception/)(Utf8JsonReader\&, ExceptionResource, uint8_t, ReadOnlySpan\<uint8_t\>) |  |
| static [ThrowNotSupportedException](./thrownotsupportedexception/)(ReadStack\&, Utf8JsonReader\&, Exception) |  |
| static [ThrowNotSupportedException](./thrownotsupportedexception/)(WriteStack\&, Exception) |  |
| static [ThrowNotSupportedException_BaseConverterDoesNotSupportMetadata](./thrownotsupportedexception_baseconverterdoesnotsupportmetadata/)(const TypeInfo\&) |  |
| static [ThrowNotSupportedException_CannotPopulateCollection](./thrownotsupportedexception_cannotpopulatecollection/)(const TypeInfo\&, Utf8JsonReader\&, ReadStack\&) |  |
| static [ThrowNotSupportedException_DerivedConverterDoesNotSupportMetadata](./thrownotsupportedexception_derivedconverterdoesnotsupportmetadata/)(const TypeInfo\&) |  |
| static [ThrowNotSupportedException_DeserializeNoConstructor](./thrownotsupportedexception_deserializenoconstructor/)(System::SharedPtr\<Serialization::Metadata::JsonTypeInfoBase\>, Utf8JsonReader\&, ReadStack\&) |  |
| static [ThrowNotSupportedException_DictionaryKeyTypeNotSupported](./thrownotsupportedexception_dictionarykeytypenotsupported/)(const TypeInfo\&, System::SharedPtr\<Serialization::JsonConverterBase\>) |  |
| static [ThrowNotSupportedException_NoMetadataForType](./thrownotsupportedexception_nometadatafortype/)(const TypeInfo\&, System::SharedPtr\<Serialization::Metadata::IJsonTypeInfoResolver\>) |  |
| static [ThrowNotSupportedException_RuntimeTypeDiamondAmbiguity](./thrownotsupportedexception_runtimetypediamondambiguity/)(const TypeInfo\&, const TypeInfo\&, const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowNotSupportedException_RuntimeTypeNotSupported](./thrownotsupportedexception_runtimetypenotsupported/)(const TypeInfo\&, const TypeInfo\&) |  |
| static [ThrowNotSupportedException_SerializationNotSupported](./thrownotsupportedexception_serializationnotsupported/)(const TypeInfo\&) |  |
| static [ThrowObjectDisposedException_JsonDocument](./throwobjectdisposedexception_jsondocument/)() |  |
| static [ThrowObjectDisposedException_Utf8JsonWriter](./throwobjectdisposedexception_utf8jsonwriter/)() |  |
| static [ThrowOutOfMemoryException](./throwoutofmemoryexception/)(uint32_t) |  |
| static [ThrowPropertyNameTooLargeArgumentException](./throwpropertynametoolargeargumentexception/)(int32_t) |  |
| static [ThrowUnexpectedMetadataException](./throwunexpectedmetadataexception/)(ReadOnlySpan\<uint8_t\>, Utf8JsonReader\&, ReadStack\&) |  |
## Fields

| Field | Description |
| --- | --- |
| static [ExceptionSourceValueToRethrowAsJsonException](./exceptionsourcevaluetorethrowasjsonexception/) |  |
## See Also

* Namespace [System::Text::Json](../)
* Library [Aspose.PDF for C++](../../)
