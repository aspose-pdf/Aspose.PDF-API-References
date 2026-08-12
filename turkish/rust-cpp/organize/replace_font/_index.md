---
title: "replace_font"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dosyadaki yazı tipini değiştirir."
type: docs
url: /tr/rust-cpp/organize/replace_font/
---

_PDF-dosyadaki yazı tipini değiştirir._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Bir PDF-document'teki yazı tipini değiştir.
    pdf.replace_font("Helvetica", "Courier")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```