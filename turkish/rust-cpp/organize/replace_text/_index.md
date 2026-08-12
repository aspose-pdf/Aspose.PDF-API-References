---
title: "replace_text"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Metni değiştirir."
type: docs
url: /tr/rust-cpp/organize/replace_text/
---

_Metni değiştirir._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dokümanındaki metni değiştir
    pdf.replace_text("PDF", "TXT")?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```