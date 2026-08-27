---
title: "split"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "ينشئ مستندات PDF متعددة جديدة عن طريق استخراج الصفحات من مستند PDF الحالي."
type: docs
url: /ar/rust-cpp/core/split/
---

_ينشئ مستندات PDF متعددة جديدة عن طريق استخراج الصفحات من مستند PDF الحالي._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document باسم "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // إنشاء مستندات PDF متعددة جديدة عن طريق استخراج الصفحات من مستند PDF الحالي
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // احفظ كل جزء مقسّم كملف PDF-document منفصل
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```