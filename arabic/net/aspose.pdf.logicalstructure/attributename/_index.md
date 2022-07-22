---
title: AttributeName
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لقيم اسم السمة.
type: docs
weight: 4050
url: /ar/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

يمثل فئة لقيم اسم السمة.

```csharp
public sealed class AttributeName
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | يحصل على مفتاح السمة . |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | يحصل على قيمة اسم السمة . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | يحصل على اسم السمة لمفتاح السمة . |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | كتلة السمة: بعد - بعد حافة مستطيل تخصيص الطفل الأخير بمحاذاة مستطيل محتوى خلية الجدول. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Attribute BlockAlign: قبل - قبل حافة مستطيل تخصيص الطفل الأول بمحاذاة مستطيل محتوى خلية الجدول . |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | سمة BlockAlign: ضبط - محاذاة الأطفال مع كل من الحواف السابقة واللاحقة لمستطيل محتوى خلية الجدول. يتم وضع الطفل الأول كما هو موصوف لـ "قبل" والطفل الأخير كما هو موصوف لـ "بعد" ، مع تباعد مسافات متساوية بين الأطفال. إذا كان هناك طفل واحد فقط ، فيجب محاذاته مع الحافة السابقة فقط ، كما في السابق. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Attribute BlockAlign: الأوسط- الأطفال المتمركزون داخل خلية الجدول. يجب أن تكون المسافة بين الحافة السابقة لمستطيل تخصيص الطفل الأول ومسافة مستطيل محتوى خلية الجدول هي نفس المسافة بين الحافة التالية لمستطيل تخصيص الطفل الأخير وحافة مستطيل محتوى خلية الجدول. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | سمة BorderStyle: متقطع - الحد عبارة عن سلسلة من مقاطع الخطوط القصيرة . |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | نمط حدود السمة: منقط - الحد عبارة عن سلسلة من النقاط . |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | سمة BorderStyle: مزدوج - الحد عبارة عن خطين متصلين. مجموع الخطين والمسافة بينهما يساوي قيمة BorderThickness . |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | سمة BorderStyle: Groove - يبدو الحد كما لو كان محفورًا في اللوحة القماشية . |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | نمط حدود السمة: مخفي - مثل لا شيء ، باستثناء ما يتعلق بحل تعارض الحدود لعناصر الجدول. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | سمة BorderStyle: داخلي - تجعل الحدود المربع بأكمله يبدو كما لو كان مضمنًا في اللوحة القماشية. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | سمة BorderStyle: بلا - بلا حدود. يفرض أن تكون قيمة BorderThicknes المحسوبة 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | سمة BorderStyle: البداية - تجعل الحدود المربع بأكمله يبدو كما لو كان يخرج من اللوحة القماشية (عكس Inset) . |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | نمط حدود السمة: ريدج - يبدو الحد وكأنه يخرج من اللوحة القماشية (عكس Groove) . |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | سمة BorderStyle: متصل - الحد عبارة عن مقطع من سطر واحد . |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | تحديد السمة: محايد - حالة زر الاختيار أو حقل خانة الاختيار. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | تحديد السمة: إيقاف التشغيل - حالة زر الاختيار أو حقل خانة الاختيار. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | تحديد السمة: تشغيل - حالة زر الاختيار أو حقل خانة الاختيار. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | السمة GlyphOrientationVertical: تلقائي - تحدد اتجاهًا افتراضيًا للنص ، اعتمادًا على ما إذا كان العرض كاملًا (بالعرض بقدر ارتفاعه) . |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | ارتفاع السمة: تلقائي - يتم تحديد ارتفاع العنصر من خلال الارتفاع الجوهري لمحتواه. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Attribute InlineAlign: Center - تمركز كل طفل داخل خلية الجدول. يجب أن تكون المسافة بين حواف البداية لمستطيل تخصيص الطفل ومستطيل محتوى خلية الجدول هي نفس المسافة بين حواف النهاية. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | محاذاة السمة المضمنة: النهاية - حافة نهاية مستطيل تخصيص كل طفل بمحاذاة مستطيل محتوى خلية الجدول. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | محاذاة السمة المضمنة: البداية - حافة البداية لمستطيل تخصيص كل طفل بمحاذاة مستطيل محتوى خلية الجدول. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | ارتفاع خط السمة: يجب عدم إجراء تعديل تلقائي لقيمة BaselineShift . |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | ارتفاع خط السمة: عادي - اضبط ارتفاع السطر لتضمين أي قيمة غير صفرية محددة لـ BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | قائمة السمات الترقيم: الدائرة - فتح رمز نقطي دائري . |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | قائمة السمات الترقيم: عشري - الأرقام العربية العشرية (1-9 ، 10-99 ، ...) . |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | قائمة السمات الترقيم: قرص - رمز نقطي دائري خالص . |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | قائمة السمات الترقيم: LowerAlpha - أحرف صغيرة (a ، b ، c ، ...) . |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | قائمة السمات الترقيم: روماني صغير - أرقام رومانية صغيرة (i، ii، iii، iv، ...) . |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | قائمة السمات الترقيم: بلا - لا يوجد ترقيم تلقائي تحتوي عناصر Lbl (إن وجدت) على نص عشوائي لا يخضع لأي نظام ترقيم. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | قائمة السمات الترقيم: مربع - رمز نقطي مربع خالص . |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | قائمة السمات الترقيم: UpperAlpha - الأحرف الكبيرة (A ، B ، C ، ...) . |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | قائمة السمات الترقيم: UpperRoman - أرقام رومانية كبيرة (I ، II ، III ، IV ، ...) . |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | موضع السمة: قبل ذلك - يتم وضعه بحيث تتطابق الحافة السابقة لمستطيل تخصيص العنصر مع تلك الخاصة بأقرب منطقة مرجعية مرفقة . |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | وضع السمة: كتلة - مكدسة في اتجاه تقدم الكتلة داخل منطقة مرجعية مُضمنة أو BLSE الأصل . |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | موضع السمة: نهاية - يتم وضعه بحيث تتطابق حافة نهاية مستطيل تخصيص العنصر مع تلك الخاصة بأقرب منطقة مرجعية متضمنة . |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | موضع السمة: مضمن - معبأ في اتجاه التقدم المضمن داخل BLSE مرفق . |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | موضع السمة: البدء - يتم وضعه بحيث تتوافق حافة البداية لمستطيل تخصيص العنصر مع تلك الخاصة بأقرب منطقة مرجعية مرفقة . |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | دور السمة: cb - خانة اختيار . |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | دور السمة: pb - زر الضغط . |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | دور السمة: rb - زر الاختيار . |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | دور السمة: tv - حقل قيمة النص . |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | السمة RubyAlign: المركز - يجب أن يتركز المحتوى في اتجاه التقدم المضمن . |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | السمة RubyAlign: التوزيع - يجب توسيع المحتوى لملء العرض المتاح في اتجاه التقدم المضمن. ومع ذلك ، يجب أيضًا إدخال مسافة عند حافة بداية النص وحافة نهايته. يجب توزيع المسافات باستخدام نسبة 1: 2: 1 (البداية: اللاحق: النهاية). يجب تغييره إلى نسبة 0: 1: 1 إذا ظهر الياقوت في بداية سطر النص أو إلى نسبة 1: 1: 0 إذا ظهر الياقوت في نهاية سطر النص. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | السمة RubyAlign: النهاية - يجب محاذاة المحتوى على حافة النهاية في اتجاه التقدم المضمن . |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | السمة RubyAlign: ضبط - يجب توسيع المحتوى لملء العرض المتاح في اتجاه التقدم المضمن . |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | السمة RubyAlign: البدء - يجب محاذاة المحتوى عند حافة البداية في اتجاه التقدم المضمن . |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | سمة RubyPosition: بعد - يجب محاذاة محتوى RT على طول الحافة التالية للعنصر. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | سمة RubyPosition: قبل - يجب محاذاة محتوى RT على طول الحافة السابقة للعنصر. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | سمة RubyPosition: مضمنة - يجب تنسيق RT وعناصر RP المرتبطة بها كتعليق قوس ، بعد عنصر RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | سمة RubyPosition: Warichu - يجب تنسيق RT وعناصر RP المرتبطة بها على أنها warichu ، وفقًا لعنصر RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | نطاق السمة: كلاهما . |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | نطاق السمة: العمود . |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | نطاق السمة: الصف . |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | محاذاة نص السمة: الوسط - تتم توسيطه بين حافتي البداية والنهاية . |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | محاذاة نص السمة: النهاية - محاذاة مع حافة النهاية . |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | محاذاة نص السمة: ضبط - محاذاة مع كل من حواف البداية والنهاية ، مع توسيع التباعد الداخلي داخل كل سطر ، إذا لزم الأمر ، لتحقيق هذه المحاذاة. يجب محاذاة السطر الأخير (أو الوحيد) مع حافة البداية فقط. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | محاذاة نص السمة: ابدأ - محاذاة مع حافة البداية. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | نوع السمة TextDecoration: LineThrough - خط يمر بمنتصف النص. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | نوع السمة TextDecoration: لا شيء - لا يوجد زخرفة نصية . |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | نوع السمة TextDecorationType: Overline - سطر أعلى النص . |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | نوع السمة TextDecoration: تسطير - سطر أسفل النص. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | عرض السمة: تلقائي - يتم تحديد عرض العنصر من خلال العرض الجوهري لمحتواه. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | سمة WritingMode: LrTb - تقدم مضمن من اليسار إلى اليمين منع التقدم من أعلى إلى أسفل. هذا هو وضع الكتابة النموذجي لأنظمة الكتابة الغربية. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | سمة WritingMode: RlTb - تقدم مضمن من اليمين إلى اليسار منع التقدم من أعلى إلى أسفل. هذا هو وضع الكتابة النموذجي لأنظمة الكتابة العربية والعبرية. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | سمة WritingMode: TbRl - تقدم مضمن من أعلى إلى أسفل منع التقدم من اليمين إلى اليسار. هذا هو وضع الكتابة النموذجي لأنظمة الكتابة الصينية واليابانية. |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
