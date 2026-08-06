---
title: "remove_hidden_text"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan gizli metni kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_hidden_text/
---

_PDF-dokümandan gizli metni kaldırır._

```rust
pub fn remove_hidden_text(&self) -> Result<(), PdfError>
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

    // PDF-dokümanından gizli metni kaldır
    pdf.remove_hidden_text()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_hidden_text.pdf")?;

    Ok(())
}

```