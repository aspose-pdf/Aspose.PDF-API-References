---
title: "remove_javascripts"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan java betiklerini kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_javascripts/
---

_PDF-dokümandan java betiklerini kaldırır._

```rust
pub fn remove_javascripts(&self) -> Result<(), PdfError>
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

    // PDF-dokümanından java script'leri kaldır
    pdf.remove_javascripts()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_javascripts.pdf")?;

    Ok(())
}

```