---
title: "is_linearized"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحصل على قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا."
type: docs
url: /ar/rust-cpp/core/is_linearized/
---

_يحصل على قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // احصل على قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```