---
title: "page_add"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanına yeni bir sayfa ekler."
type: docs
url: /tr/rust-cpp/core/page_add/
---

_PDF-dökümanına yeni bir sayfa ekler._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosyadan bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümanına yeni sayfa ekle
    pdf.page_add()?;

    // Önceden açılmış PDF-document'i kaydet
    pdf.save()?;

    Ok(())
}

```