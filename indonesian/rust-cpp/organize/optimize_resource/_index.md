---
title: "optimize_resource"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengoptimalkan sumber daya dokumen PDF."
type: docs
url: /id/rust-cpp/organize/optimize_resource/
---

_Mengoptimalkan sumber daya dokumen PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Optimalkan sumber daya dokumen PDF
    pdf.optimize_resource()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_optimize_resource.pdf")?;

    Ok(())
}

```