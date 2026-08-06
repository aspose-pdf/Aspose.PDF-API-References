---
title: "remove_annotations"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-belgesinden ek açıklamaları kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_annotations/
---

_PDF-belgesinden ek açıklamaları kaldırır._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
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

    // PDF-dokümanından ek açıklamaları kaldır
    pdf.remove_annotations()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```