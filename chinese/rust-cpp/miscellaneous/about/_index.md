---
title: "关于"
second_title: "Aspose.PDF for Rust via C++"
description: "返回关于 Aspose.PDF for Rust 通过 C++ 的元数据信息。"
type: docs
url: /zh/rust-cpp/miscellaneous/about/
---

_返回关于 Aspose.PDF for Rust 通过 C++ 的元数据信息。_

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 创建一个新的 PDF-document
    let pdf = Document::new()?;

    // 返回关于 Aspose.PDF for Go 通过 C++ 的元数据信息。
    let info = pdf.about()?;

    // 打印元数据字段
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```