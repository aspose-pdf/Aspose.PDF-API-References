---
title: "unembed_fonts"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'tan yazı tiplerini ayıklar."
type: docs
url: /tr/rust-cpp/organize/unembed_fonts/
---

_PDF-document'tan yazı tiplerini ayıklar._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // PDF-document'tan yazı tiplerini ayıkla
    pdf.unembed_fonts()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```