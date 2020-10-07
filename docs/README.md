# Introduction

## What is wgpu?
[Wgpu](https://github.com/gfx-rs/wgpu) is a Rust implementation of the [WebGPU API spec](https://gpuweb.github.io/gpuweb/). WebGPU is a specification published by the GPU for the Web Community Group. It aims to allow web code access to GPU functions in a safe and reliable manner. It does this by mimicking the Vulkan API, and translating that down to whatever API the host hardware is using (ie. DirectX, Metal, Vulkan).

Wgpu is still in development, so some of this doc is subject to change.

## Support

Want to support development? I have a Patreon for that! [https://www.patreon.com/sotrh](https://www.patreon.com/sotrh)

## Why Rust?
Wgpu actually has C bindings to allow you to write C/C++ code with it, as well as use other languages that interface with C. That being said, wgpu is written in Rust, and it has some convient Rust bindings that don't have to jump through any hoops. On top of that, I've been enjoying writing in Rust.

You should be fairly familiar with Rust before using this tutorial as I won't go into much detail on Rust syntax. If you're not super comfortable with Rust you can review the [Rust tutorial](https://www.rust-lang.org/learn). You should also be familiar about [Cargo](https://doc.rust-lang.org/cargo/).

I'm using this project as a way to learn wgpu myself, so I might miss some important details, or explain things wrong. I'm always open to constructive feedback. That being said, let's get started!
