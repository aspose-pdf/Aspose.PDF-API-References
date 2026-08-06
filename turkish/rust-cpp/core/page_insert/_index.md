---
title: "page_insert"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document içinde belirtilen konuma yeni bir sayfa ekler."
type: docs
url: /tr/rust-cpp/core/page_insert/
---

_PDF-document içinde belirtilen konuma yeni bir sayfa ekler._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
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

    // PDF-document içinde belirtilen konuma yeni sayfa ekle
    pdf.page_insert(1)?;

    // Önceden açılmış PDF-document'i kaydet
    pdf.save()?;

    Ok(())
}

```