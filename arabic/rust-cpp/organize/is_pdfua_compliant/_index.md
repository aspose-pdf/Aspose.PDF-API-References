---
title: "is_pdfua_compliant"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحصل على ما إذا كان PDF-document متوافقًا مع PDF/UA."
type: docs
url: /ar/rust-cpp/organize/is_pdfua_compliant/
---

_يحصل على ما إذا كان PDF-document متوافقًا مع PDF/UA._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // احصل على حالة توافق PDF/UA لـ PDF-document
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```