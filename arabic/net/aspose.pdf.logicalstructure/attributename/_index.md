---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.LogicalStructure.AttributeName. تمثل فئة لقيم اسم السمة
type: docs
weight: 6220
url: /ar/net/aspose.pdf.logicalstructure/attributename/
---
## فئة AttributeName

تمثل فئة لقيم اسم السمة.

```csharp
public sealed class AttributeName
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | يحصل على مفتاح السمة. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | يحصل على قيمة اسم السمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | يحصل على اسم السمة لمفتاح السمة. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | سمة BlockAlign: بعد - حافة بعد تخصيص آخر طفل متوافقة مع حافة مستطيل محتوى خلية الجدول. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | سمة BlockAlign: قبل - حافة قبل تخصيص أول طفل متوافقة مع حافة مستطيل محتوى خلية الجدول. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | سمة BlockAlign: تبرير - الأطفال متوافقون مع كل من الحواف قبل وبعد مستطيل محتوى خلية الجدول. يجب وضع الطفل الأول كما هو موصوف لـ قبل والطفل الأخير كما هو موصوف لـ بعد، مع تباعد متساوي بين الأطفال. إذا كان هناك طفل واحد فقط، يجب أن يكون متوافقًا مع الحافة قبل فقط، كما هو الحال في قبل. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | سمة BlockAlign: وسط - الأطفال مركزيون داخل خلية الجدول. يجب أن تكون المسافة بين الحافة قبل مستطيل تخصيص الطفل الأول وتلك الخاصة بمستطيل محتوى خلية الجدول هي نفسها المسافة بين الحافة بعد مستطيل تخصيص آخر طفل وتلك الخاصة بمستطيل محتوى خلية الجدول. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | سمة BorderStyle: متقطع - الحدود عبارة عن سلسلة من مقاطع الخط القصيرة. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | سمة BorderStyle: منقط - الحدود عبارة عن سلسلة من النقاط. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | سمة BorderStyle: مزدوج - الحدود عبارة عن خطين صلبين. مجموع الخطين والمسافة بينهما يساوي قيمة BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | سمة BorderStyle: تجويف - تبدو الحدود كما لو كانت محفورة في القماش. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | سمة BorderStyle: مخفي - نفس الشيء مثل لا شيء، باستثناء من حيث حل النزاع على الحدود لعناصر الجدول. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | سمة BorderStyle: مدرج - تجعل الحدود الصندوق بالكامل يبدو كما لو كان مدفونا في القماش. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | سمة BorderStyle: لا شيء - لا توجد حدود. يجبر القيمة المحسوبة لـ BorderThickness على أن تكون 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | سمة BorderStyle: بارز - تجعل الحدود الصندوق بالكامل يبدو كما لو كان يخرج من القماش (عكس المدخل). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | سمة BorderStyle: حافة - تبدو الحدود كما لو كانت تخرج من القماش (عكس التجويف). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | سمة BorderStyle: صلب - الحدود عبارة عن مقطع خط واحد. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | سمة checked: محايد - حالة زر الراديو أو حقل مربع الاختيار. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | سمة checked: إيقاف - حالة زر الراديو أو حقل مربع الاختيار. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | سمة checked: تشغيل - حالة زر الراديو أو حقل مربع الاختيار. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | سمة GlyphOrientationVertical: تلقائي - يحدد اتجاهًا افتراضيًا للنص، اعتمادًا على ما إذا كان عريضًا بالكامل (بقدر ما هو مرتفع). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | سمة Height: تلقائي - سيتم تحديد ارتفاع العنصر بواسطة الارتفاع الداخلي لمحتواه. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | سمة InlineAlign: مركز - كل طفل مركزي داخل خلية الجدول. يجب أن تكون المسافة بين الحواف الابتدائية لمستطيل تخصيص الطفل ومستطيل محتوى خلية الجدول هي نفسها المسافة بين حوافها النهائية. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | سمة InlineAlign: نهاية - الحافة النهائية لمستطيل تخصيص كل طفل متوافقة مع تلك الخاصة بمستطيل محتوى خلية الجدول. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | سمة InlineAlign: بداية - الحافة الابتدائية لمستطيل تخصيص كل طفل متوافقة مع تلك الخاصة بمستطيل محتوى خلية الجدول. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | سمة LineHeight: تلقائي - لن يتم إجراء تعديل لقيمة BaselineShift. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | سمة LineHeight: عادي - ضبط ارتفاع السطر ليشمل أي قيمة غير صفرية محددة لـ BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | سمة ListNumbering: دائرة - نقطة دائرية مفتوحة. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | سمة ListNumbering: عشري - أرقام عربية عشرية (1-9، 10-99، ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | سمة ListNumbering: قرص - نقطة دائرية صلبة. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | سمة ListNumbering: أحرف صغيرة - أحرف صغيرة (أ، ب، ج، ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | سمة ListNumbering: روماني صغير - أرقام رومانية صغيرة (i، ii، iii، iv، ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | سمة ListNumbering: لا شيء - لا يوجد ترقيم تلقائي؛ تحتوي عناصر Lbl (إذا كانت موجودة) على نص عشوائي غير خاضع لأي نظام ترقيم. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | سمة ListNumbering: مربع - نقطة مربعة صلبة. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | سمة ListNumbering: أحرف كبيرة - أحرف كبيرة (أ، ب، ج، ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | سمة ListNumbering: روماني كبير - أرقام رومانية كبيرة (I، II، III، IV، ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | سمة Placement: قبل - موضوعة بحيث تتوافق الحافة قبل مستطيل تخصيص العنصر مع تلك الخاصة بأقرب منطقة مرجعية محيطة. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | سمة Placement: كتلة - مكدسة في اتجاه تقدم الكتلة داخل منطقة مرجعية محيطة أو BLSE الوالد. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | سمة Placement: نهاية - موضوعة بحيث تتوافق الحافة النهائية لمستطيل تخصيص العنصر مع تلك الخاصة بأقرب منطقة مرجعية محيطة. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | سمة Placement: داخل السطر - محشورة في اتجاه تقدم السطر داخل BLSE محيط. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | سمة Placement: بداية - موضوعة بحيث تتوافق الحافة الابتدائية لمستطيل تخصيص العنصر مع تلك الخاصة بأقرب منطقة مرجعية محيطة. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | سمة Role: cb - مربع الاختيار. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | سمة Role: pb - زر دفع. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | سمة Role: rb - زر راديو. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | سمة Role: tv - حقل نص-قيمة. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | سمة RubyAlign: مركز - يجب أن يكون المحتوى مركزيًا في اتجاه تقدم السطر. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | سمة RubyAlign: توزيع - يجب توسيع المحتوى لملء العرض المتاح في اتجاه تقدم السطر. ومع ذلك، يجب أيضًا إدراج مساحة عند الحافة الابتدائية والحافة النهائية للنص. يجب توزيع التباعد باستخدام نسبة 1:2:1 (بداية:داخل:نهاية). يجب تغييرها إلى نسبة 0:1:1 إذا ظهر الروبي في بداية سطر النص أو إلى نسبة 1:1:0 إذا ظهر الروبي في نهاية سطر النص. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | سمة RubyAlign: نهاية - يجب أن يكون المحتوى متوافقًا مع الحافة النهائية في اتجاه تقدم السطر. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | سمة RubyAlign: تبرير - يجب توسيع المحتوى لملء العرض المتاح في اتجاه تقدم السطر. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | سمة RubyAlign: بداية - يجب أن يكون المحتوى متوافقًا مع الحافة الابتدائية في اتجاه تقدم السطر. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | سمة RubyPosition: بعد - يجب أن يكون محتوى RT متوافقًا مع الحافة بعد العنصر. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | سمة RubyPosition: قبل - يجب أن يكون محتوى RT متوافقًا مع الحافة قبل العنصر. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | سمة RubyPosition: داخل السطر - يجب تنسيق عناصر RT وRP المرتبطة كتعليق بين قوسين، بعد عنصر RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | سمة RubyPosition: واريتشو - يجب تنسيق عناصر RT وRP المرتبطة كواريتشو، بعد عنصر RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | سمة Scope: كلاهما. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | سمة Scope: عمود. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | سمة Scope: صف. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | سمة TextAlign: مركز - مركزي بين الحواف الابتدائية والنهائية. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | سمة TextAlign: نهاية - متوافق مع الحافة النهائية. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | سمة TextAlign: تبرير - متوافق مع كل من الحواف الابتدائية والنهائية، مع توسيع التباعد الداخلي داخل كل سطر، إذا لزم الأمر، لتحقيق مثل هذا التوافق. يجب أن يكون السطر الأخير (أو الوحيد) متوافقًا مع الحافة الابتدائية فقط. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | سمة TextAlign: بداية - متوافق مع الحافة الابتدائية. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | سمة TextDecorationType: خط من خلال - خط عبر منتصف النص. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | سمة TextDecorationType: لا شيء - لا توجد زخرفة نصية. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | سمة TextDecorationType: خط فوق - خط فوق النص. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | سمة TextDecorationType: خط تحت - خط تحت النص. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | سمة Width: تلقائي - سيتم تحديد عرض العنصر بواسطة العرض الداخلي لمحتواه. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | سمة WritingMode: LrTb - تقدم السطر من اليسار إلى اليمين؛ تقدم الكتلة من الأعلى إلى الأسفل. هذه هي وضع الكتابة النموذجي للأنظمة الكتابية الغربية. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | سمة WritingMode: RlTb - تقدم السطر من اليمين إلى اليسار؛ تقدم الكتلة من الأعلى إلى الأسفل. هذه هي وضع الكتابة النموذجي للأنظمة الكتابية العربية والعبرية. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | سمة WritingMode: TbRl - تقدم السطر من الأعلى إلى الأسفل؛ تقدم الكتلة من اليمين إلى اليسار. هذه هي وضع الكتابة النموذجي للأنظمة الكتابية الصينية واليابانية. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* التجميع [Aspose.PDF](../../)