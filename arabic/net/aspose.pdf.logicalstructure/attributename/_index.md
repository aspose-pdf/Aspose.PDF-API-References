---
title: "الفئة AttributeName."
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.LogicalStructure.AttributeName. تمثل فئة لقيم أسماء السمات."
type: docs
weight: 6360
url: /ar/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

يمثل فئة لقيم أسماء السمات.

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
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | السمة BlockAlign: After - الحافة بعد للطفل الأخير في المستطيل المخصص محاذاة مع حافة مستطيل محتوى خلية الجدول. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | السمة BlockAlign: Before - الحافة قبل للطفل الأول في المستطيل المخصص محاذاة مع حافة مستطيل محتوى خلية الجدول. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | السمة BlockAlign: Justify - يتم محاذاة الأطفال مع كل من الحافتين قبل وبعد مستطيل محتوى خلية الجدول. يُوضع الطفل الأول كما هو موضح في Before والطفل الأخير كما هو موضح في After، مع مسافات متساوية بين الأطفال. إذا كان هناك طفل واحد فقط، يتم محاذاته مع الحافة قبل فقط، كما في Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | السمة BlockAlign: Middle - يتم توسيط الأطفال داخل خلية الجدول. يجب أن تكون المسافة بين الحافة قبل للطفل الأول في المستطيل المخصص وحافة مستطيل محتوى خلية الجدول مساوية للمسافة بين الحافة بعد للطفل الأخير في المستطيل المخصص وحافة مستطيل محتوى خلية الجدول. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | السمة BorderStyle: Dashed - الحد هو سلسلة من المقاطع الخطية القصيرة. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | السمة BorderStyle: Dotted - الحد هو سلسلة من النقاط. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | السمة BorderStyle: Double - الحد هو خطان صلبان. مجموع الخطين والمسافة بينهما يساوي قيمة BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | السمة BorderStyle: Groove - يبدو الحد كما لو أنه محفور في القماش. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | السمة BorderStyle: Hidden - نفس القيمة كـ None، باستثناء حل تعارض الحدود لعناصر الجدول. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | السمة BorderStyle: Inset - يجعل الحد الصندوق بأكمله يبدو كما لو أنه مدمج في القماش. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | السمة BorderStyle: None - لا حد. يجبر القيمة المحسوبة لـ BorderThickness أن تكون 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | السمة BorderStyle: Outset - يجعل الحد الصندوق بأكمله يبدو كما لو أنه يخرج من القماش (العكس من Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | السمة BorderStyle: Ridge - يبدو الحد كما لو أنه يخرج من القماش (العكس من Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | السمة BorderStyle: Solid - الحد هو مقطع خط واحد. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | السمة checked: Neutral - حالة زر الراديو أو حقل خانة الاختيار. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | السمة checked: Off - حالة زر الراديو أو حقل خانة الاختيار. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | السمة checked: On - حالة زر الراديو أو حقل خانة الاختيار. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | السمة GlyphOrientationVertical: Auto - يحدد توجيهًا افتراضيًا للنص، بناءً على ما إذا كان بعرض كامل (عرضه يساوي ارتفاعه). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | السمة Height: Auto - يجب تحديد ارتفاع العنصر بناءً على الارتفاع الداخلي لمحتواه. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | السمة InlineAlign: Center - يتم توسيط كل عنصر فرعي داخل خلية الجدول. يجب أن تكون المسافة بين حواف البداية لمستطيل تخصيص العنصر الفرعي ومستطيل محتوى خلية الجدول مساوية للمسافة بين حواف النهاية. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | السمة InlineAlign: End - حافة النهاية لمستطيل تخصيص كل عنصر فرعي تتطابق مع حافة محتوى خلية الجدول. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | السمة InlineAlign: Start - حافة البداية لمستطيل تخصيص كل عنصر فرعي تتطابق مع حافة محتوى خلية الجدول. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | السمة LineHeight: Auto - لا يتم تعديل قيمة BaselineShift. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | السمة LineHeight: Normal - ضبط ارتفاع السطر ليشمل أي قيمة غير صفرية محددة لـ BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | السمة ListNumbering: Circle - نقطه دائرية مفتوحة. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | السمة ListNumbering: Decimal - أرقام عربية عشرية (1-9، 10-99، ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | السمة ListNumbering: Disc - نقطه دائرية صلبة. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | السمة ListNumbering: LowerAlpha - أحرف صغيرة (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | السمة ListNumbering: LowerRoman - أرقام رومانية صغيرة (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | السمة ListNumbering: None - لا ترقيم تلقائي؛ عناصر Lbl (إن وجدت) تحتوي على نص عشوائي غير خاضع لأي مخطط ترقيم. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | السمة ListNumbering: Square - نقطه مربعة صلبة. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | السمة ListNumbering: UpperAlpha - أحرف كبيرة (A, B, C, ...) |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | السمة ListNumbering: UpperRoman - أرقام رومانية كبيرة (I, II, III, IV, ...) |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | السمة Placement: Before - يتم وضعه بحيث يتطابق الحافة السابقة لمستطيل تخصيص العنصر مع حافة أقرب منطقة مرجعية محيطة. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | السمة Placement: Block - يتم تكديسه في اتجاه تقدم الكتلة داخل منطقة مرجعية محيطة أو BLSE الأصل. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | السمة Placement: End - يتم وضعه بحيث يتطابق الحافة النهائية لمستطيل تخصيص العنصر مع حافة أقرب منطقة مرجعية محيطة. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | السمة Placement: Inline - يتم تعبئته في اتجاه تقدم السطر داخل BLSE محيط. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | السمة Placement: Start - يتم وضعه بحيث يتطابق الحافة البداية لمستطيل تخصيص العنصر مع حافة أقرب منطقة مرجعية محيطة. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | السمة Role: cb - مربع اختيار. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | السمة Role: pb - زر ضغط. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | السمة Role: rb - زر راديو. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | السمة Role: tv - حقل نصي. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | السمة RubyAlign: Center - يجب أن يكون المحتوى مركّزًا في اتجاه تقدم السطر. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | السمة RubyAlign: Distribute - يجب توسيع المحتوى لملء العرض المتاح في اتجاه تقدم السطر. ومع ذلك، يجب إدراج مساحة أيضًا عند الحافة البداية والحافة النهاية للنص. سيتم توزيع التباعد باستخدام نسبة 1:2:1 (بداية:وسط:نهاية). سيتغير إلى نسبة 0:1:1 إذا ظهر الروبي في بداية سطر النص أو إلى نسبة 1:1:0 إذا ظهر الروبي في نهاية سطر النص. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | السمة RubyAlign: End - يجب محاذاة المحتوى على الحافة النهائية في اتجاه تقدم السطر. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | السمة RubyAlign: Justify - يجب توسيع المحتوى لملء العرض المتاح في اتجاه تقدم السطر. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | السمة RubyAlign: Start - يجب محاذاة المحتوى على الحافة البداية في اتجاه تقدم السطر. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | السمة RubyPosition: After - يجب محاذاة محتوى RT على الحافة التالية للعنصر. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | السمة RubyPosition: Before - يجب محاذاة محتوى RT على الحافة السابقة للعنصر. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | السمة RubyPosition: Inline - يجب تنسيق عناصر RT و RP المرتبطة كتعليق داخل أقواس، بعد عنصر RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | السمة RubyPosition: Warichu - يجب تنسيق عناصر RT و RP المرتبطة كـ warichu، بعد عنصر RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | السمة Scope: كلاهما. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | السمة Scope: عمود. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | السمة Scope: صف. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | السمة TextAlign: Center - مركّز بين الحافتين البداية والنهاية. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | السمة TextAlign: End - محاذى مع الحافة النهائية. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | السمة TextAlign: Justify - محاذاة مع حافة البداية والنهاية مع توسيع المسافات الداخلية داخل كل سطر إذا لزم الأمر لتحقيق هذه المحاذاة. السطر الأخير (أو الوحيد) يجب أن يكون محاذيًا مع حافة البداية فقط. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | السمة TextAlign: Start - محاذاة مع حافة البداية. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | السمة TextDecorationType: LineThrough - خط يمر عبر منتصف النص. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | السمة TextDecorationType: None - لا توجد زخرفة للنص. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | السمة TextDecorationType: Overline - خط فوق النص. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | السمة TextDecorationType: Underline - خط تحت النص. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | السمة Width: Auto - عرض العنصر يُحدَّد بواسطة العرض الداخلي لمحتواه. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | السمة WritingMode: LrTb - تقدم داخل السطر من اليسار إلى اليمين؛ تقدم الكتلة من الأعلى إلى الأسفل. هذا هو نمط الكتابة المعتاد للأنظمة الكتابية الغربية. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | السمة WritingMode: RlTb - تقدم داخل السطر من اليمين إلى اليسار؛ تقدم الكتلة من الأعلى إلى الأسفل. هذا هو نمط الكتابة المعتاد للأنظمة الكتابية العربية والعبرية. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | السمة WritingMode: TbRl - تقدم داخل السطر من الأعلى إلى الأسفل؛ تقدم الكتلة من اليمين إلى اليسار. هذا هو نمط الكتابة المعتاد للأنظمة الكتابية الصينية واليابانية. |

### انظر أيضًا

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


