---
title: "page_delete"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Belirtilen sayfayı PDF-document'ten siler."
type: docs
url: /tr/rust-cpp/core/page_delete/
---

_Belirtilen sayfayı PDF-document'ten siler._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-document'te belirtilen sayfayı sil
    pdf.page_delete(1)?;

    // Önceden açılmış PDF-document'i kaydet
    pdf.save()?;

    Ok(())
}

```