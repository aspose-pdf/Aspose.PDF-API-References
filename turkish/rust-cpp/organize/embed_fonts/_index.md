---
title: "embed_fonts"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dosyaya yazı tiplerini gömer."
type: docs
url: /tr/rust-cpp/organize/embed_fonts/
---

_PDF-dosyaya yazı tiplerini gömer._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
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

    // PDF-dosyaya yazı tiplerini gömer
    pdf.embed_fonts()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```