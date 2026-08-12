---
title: "remove_images"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan görüntüleri kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_images/
---

_PDF-dokümandan görüntüleri kaldırır._

```rust
pub fn remove_images(&self) -> Result<(), PdfError>
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

    // PDF-dokümanından görüntüleri kaldır
    pdf.remove_images()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_images.pdf")?;

    Ok(())
}

```