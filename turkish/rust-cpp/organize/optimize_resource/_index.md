---
title: "optimize_resource"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanın kaynaklarını optimize eder."
type: docs
url: /tr/rust-cpp/organize/optimize_resource/
---

_PDF-dökümanın kaynaklarını optimize eder._

```rust
pub fn optimize_resource(&self) -> Result<(), PdfError>
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

    // PDF-dökümanın kaynaklarını optimize et
    pdf.optimize_resource()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```