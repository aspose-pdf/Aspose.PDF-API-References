---
title: AutoFiller
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لتلقي البيانات من قاعدة البيانات أو مصدر بيانات آخر  ويملأها في الحقول المصممة لقالب pdf  وفي النهاية ينشئ ملف أو دفق pdf جديدًا. . يحتوي على أربعة أنواع من أوضاع الإخراج دفق واحد مدمج  ملف مدمج واحد  العديد من التدفقات الصغيرة  العديد من الملفات الصغيرة.
type: docs
weight: 2170
url: /ar/net/aspose.pdf.facades/autofiller/
---
## AutoFiller class

يمثل فئة لتلقي البيانات من قاعدة البيانات أو مصدر بيانات آخر ، ويملأها في الحقول المصممة لقالب pdf ، وفي النهاية ينشئ ملف أو دفق pdf جديدًا. . يحتوي على أربعة أنواع من أوضاع الإخراج: دفق واحد مدمج ، ملف مدمج واحد ، العديد من التدفقات الصغيرة ، العديد من الملفات الصغيرة.

```csharp
public sealed class AutoFiller : ISaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AutoFiller](autofiller)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BasicFileName](../../aspose.pdf.facades/autofiller/basicfilename) { get; set; } | الحصول على أو تحديد اسم الملف الأساسي في حالة إنشاء العديد من الملفات الصغيرة. سيكون الملف الذي تم إنشاؤه مثل "BasicFileName0" ، "BasicFileName1" ، ... إنه يعمل مع خاصية أخرى[`GeneratingPath`](./generatingpath) GeneratingPath. |
| [GeneratingPath](../../aspose.pdf.facades/autofiller/generatingpath) { get; set; } | الحصول على أو تعيين مسار إنشاء ملفات pdf الصغيرة في حالة إنشاء العديد من ملفات pdf الصغيرة. إنه يعمل مع خاصية أخرى[`BasicFileName`](./basicfilename)BasicFileName. أحد أوضاع الإخراج الأربعة. |
| [OutputStreams](../../aspose.pdf.facades/autofiller/outputstreams) { get; set; } | الحصول على أو تعيين العديد من تدفقات الإخراج. أحد أوضاع الإخراج الأربعة. |
| [UnFlattenFields](../../aspose.pdf.facades/autofiller/unflattenfields) { set; } | يضبط الحقول التي لن يتم تسويتها . إذا لم يتم تعيين هذه الخاصية ، فسيتم تسوية جميع الحقول. |

## طُرق

| اسم | وصف |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf)(Document) | ربط مستند PDF . |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_1)(Stream) | يربط ملف PDF . |
| [BindPdf](../../aspose.pdf.facades/autofiller/bindpdf#bindpdf_2)(string) | يربط ملف PDF . |
| [Close](../../aspose.pdf.facades/autofiller/close)() | لإغلاق الكائن وتدفقات الإخراج. |
| [Dispose](../../aspose.pdf.facades/autofiller/dispose)() | لإغلاق الكائن وتدفقات الإخراج. |
| [ImportDataTable](../../aspose.pdf.facades/autofiller/importdatatable)(DataTable) | استيراد بيانات من نوع DataTable. يجب أن يكون اسم كل عمود من dataTable هو نفسه اسم حقل واحد لقالب pdf في حالة الحساسية. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_1)(Stream) | يحفظ جميع ملفات pdfs. |
| [Save](../../aspose.pdf.facades/autofiller/save#save_2)(string) | يحفظ جميع ملفات pdfs. |

### أمثلة

```csharp
[C#]
// ملاحظة: mail.pdf هو نموذج بتنسيق pdf يحتوي على سبعة حقول نصية. NorthWind.mdb هو Microsoft Access db.
//// Common part: احصل على البيانات من قاعدة البيانات NorthWind.mdb وقم بتعبئتها في DataTable.
			
OleDbCommand mQueryCommand;
OleDbDataAdapter mDbDataAdapter;
OleDbConnection mDbConnection;

// بناء جدول البيانات.
DataTable mDataTable = new DataTable("MailMerge");
DataColumnCollection columns = mDataTable.Columns;
columns.Add("CompanyName",typeof(string));
columns.Add("ContactName",typeof(string));
columns.Add("Address",typeof(string));
columns.Add("PostalCode",typeof(string));
columns.Add("City",typeof(string));
columns.Add("Country",typeof(string));
columns.Add("Heading",typeof(string));


// الاتصال بمصدر قاعدة البيانات والاستعلام عن البيانات.
mDbConnection = new OleDbConnection();
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + 
DbPath + "NorthWind.mdb";
mQueryCommand = new OleDbCommand();
mQueryCommand.Connection = mDbConnection;
mDbConnection.Open();


mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;";
mDbDataAdapter = new OleDbDataAdapter(mQueryCommand);
		
mDbDataAdapter.Fill(mDataTable);

for (int i = 0; i<mDataTable.Rows.Count;i++)
{
	mDataTable.Rows[i][mDataTable.Columns.Count - 1] = "Dear " + mDataTable.Rows[i][0].ToString() + ",";
	System.Console.WriteLine("postalCode:" + mDataTable.Rows[i][3].ToString());
	System.Console.WriteLine("Heading:" + mDataTable.Rows[i][mDataTable.Columns.Count - 1].ToString());
}

mDbDataAdapter.Dispose();
mDbConnection.Close();
//// نهاية الجزء المشترك.

//// الحالة الأولى:
//// Input template pdf هو ملف pdf والإخراج عبارة عن دفق مدمج كبير.		
 
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.OutputStream = Response.OutputStream;

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

//// الحالة الثانية:
//// Input template pdf هو ملف pdf والإخراج عبارة عن الكثير من الملفات الصغيرة.
AutoFiller autoFiller = new AutoFiller();
		
autoFiller.InputFileName = "mail.pdf";
autoFiller.GeneratingPath = ".\\";
autoFiller.BasicFileName = "outputFile";

autoFiller.ImportDataTable(mDataTable);
autoFiller.Save();

[Visual Basic]
'ملاحظة: mail.pdf هو نموذج بتنسيق pdf يحتوي على سبعة حقول نصية. NorthWind.mdb هو Microsoft Access db.
'الجزء المشترك: احصل على البيانات من قاعدة البيانات NorthWind.mdb وقم بتعبئتها في DataTable. 
mQueryCommand As OleDbCommand = Nothing
mDbDataAdapter As OleDbDataAdapter = Nothing
mDbConnection As OleDbConnection = Nothing

mDataTable As DataTable = Nothing

mPath As String = Nothing
mTemplatePdf As String = Nothing

'أنشئ جدول البيانات.
mDataTable = New DataTable("MailMerge")
Dim columns As DataColumnCollection = mDataTable.Columns
'إنشاء أعمدة لجدول البيانات. 
'Every column's  name should be the same as one field's name of the templatePdf.
columns.Add("CompanyName", Type.GetType("System.String"))

columns.Add("ContactName", Type.GetType("System.String"))
columns.Add("Address", Type.GetType("System.String"))
columns.Add("PostalCode", Type.GetType("System.String"))
columns.Add("City", Type.GetType("System.String"))
columns.Add("Country", Type.GetType("System.String"))
columns.Add("Heading", Type.GetType("System.String"))


'الاتصال بمصدر قاعدة البيانات والاستعلام عن البيانات.
mDbConnection = New OleDbConnection
mDbConnection.ConnectionString = "Provider=Microsoft.Jet.OLEDB.4.0;Data Source=" + DbPath + "NorthWind.mdb"
mQueryCommand = New OleDbCommand
mQueryCommand.Connection = mDbConnection
mDbConnection.Open()

'الاستعلام عن البيانات وإدراجها في جدول البيانات.
mQueryCommand.CommandText = "select CompanyName, ContactName, Address, PostalCode, City, Country from Customers;"
mDbDataAdapter = New OleDbDataAdapter(mQueryCommand)
mDbDataAdapter.Fill(mDataTable)

'أنشئ العمود الأخير من جدول البيانات.
Dim i As Integer
For i = 0 To mDataTable.Rows.Count - 1 Step i + 1
	mDataTable.Rows(i)(mDataTable.Columns.Count - 1) = "Dear " + mDataTable.Rows(i)(0).ToString() + ","
	System.Console.WriteLine("postalCode:" + mDataTable.Rows(i)(3).ToString())
	System.Console.WriteLine("Heading:" + mDataTable.Rows(i)(mDataTable.Columns.Count - 1).ToString())
Next

mDbDataAdapter.Dispose()
mDbConnection.Close()
'نهاية الجزء المشترك.

'الحالة الأولى:
'نموذج الإدخال pdf هو ملف pdf والإخراج عبارة عن دفق مدمج كبير.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.OutputStream = Response.OutputStream

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()

'الحالة الثانية:
'نموذج الإدخال pdf هو ملف pdf والإخراج كثير من الملفات الصغيرة.
Dim autoFiller As AutoFiller = New AutoFiller

autoFiller.InputFileName = "mail.pdf"
autoFiller.GeneratingPath = ".\";
autoFiller.BasicFileName = "outputFile"

autoFiller.ImportDataTable(mDataTable)
autoFiller.Save()
```

### أنظر أيضا

* interface [ISaveableFacade](../isaveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
