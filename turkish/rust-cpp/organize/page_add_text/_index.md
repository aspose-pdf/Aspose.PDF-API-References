---
title: "page_add_text"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Bir sayfaya metin ekler."
type: docs
url: /tr/rust-cpp/organize/page_add_text/
---

_Bir sayfaya metin ekler._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Sayfaya metin ekle
    pdf.page_add_text(1, "added text")?;

    // Önceden açılmış PDF-document'i kaydet
    pdf.save()?;

    Ok(())
}

```