---
title: "remove_text_footers"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan metin altbilgilerini kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_text_footers/
---

_PDF-dokümandan metin altbilgilerini kaldırır._

```rust
pub fn remove_text_footers(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dokümandan metin altbilgilerini kaldır
    pdf.remove_text_footers()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_text_footers.pdf")?;

    Ok(())
}

```