---
title: "page_merge_layers"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan."
type: docs
url: /id/rust-cpp/organize/page_merge_layers/
---

_Menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document dari file
    let pdf = Document::open("sample.pdf")?;

    // Gabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```