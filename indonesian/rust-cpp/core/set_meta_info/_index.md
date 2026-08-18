---
title: "set_meta_info"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengatur nilai meta informasi dari PDF-document."
type: docs
url: /id/rust-cpp/core/set_meta_info/
---

_Mengatur nilai meta informasi dari PDF-document._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Atur nilai meta informasi dari PDF-document
    pdf.set_meta_info("Author", "Aspose")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```