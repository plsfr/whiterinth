# Third-party notices

This inventory lists the Windows launcher’s Rust dependency graph, Java agent libraries, and the installed JavaScript workspace package set. It includes build dependencies and packages outside the final bundle. Original license texts and copyright notices are retained in the source tree or linked to the collected copies below.

## Launcher workspace packages

- The Tauri shell and the Vue frontend are distributed under GPL-3.0-only. See [apps/app/LICENSE](apps/app/LICENSE) and [apps/app-frontend/LICENSE](apps/app-frontend/LICENSE).
- Skin-rendering attributions are preserved in [its third-party notice](packages/modrinth-skin-rendering/THIRD_PARTY.md).
- Some upstream Rust workspace crates have no package-level license declaration or license file at this revision. The inventory identifies these as “See package sources.” Their redistribution terms require clarification before a public binary release.
- The launcher library has its own [copying notes](packages/app-lib/COPYING.md).
- Shared package terms remain in their original directories. See [COPYING.md](COPYING.md).

## Native dependency inventory

| Package | Version | Declared license | Notices |
| --- | --- | --- | --- |
| adler2 | 2.0.1 | 0BSD OR MIT OR Apache-2.0 | [LICENSE-0BSD](apps/app/notices/861399f8c21c042b.txt), [LICENSE-APACHE](apps/app/notices/8ada45cd9f843acf.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| aead | 0.5.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b1cf9a3333ca7815.txt), [LICENSE-MIT](apps/app/notices/949ab7b3e7140fee.txt) |
| aead | 0.6.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b1cf9a3333ca7815.txt), [LICENSE-MIT](apps/app/notices/33b32a251d445c5c.txt) |
| aegis | 0.9.20 | MIT | [LICENSE](apps/app/notices/d4ea02a54d266337.txt) |
| aes | 0.8.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/f7e8ab639afef155.txt) |
| aes | 0.9.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/25f77efa393854f7.txt) |
| aes-gcm | 0.10.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/3c0dfa33fd2e6976.txt) |
| aes-gcm | 0.11.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/b8c6939380a400f5.txt) |
| aho-corasick | 1.1.5 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| aligned | 0.4.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/035e70219855119d.txt) |
| aligned-vec | 0.6.4 | MIT | [LICENSE](apps/app/notices/bf5a93d1014429b4.txt) |
| alloc-no-stdlib | 2.0.4 | BSD-3-Clause | [LICENSE](apps/app/notices/c0c56f26d9c051ca.txt) |
| alloc-no-stdlib | 3.0.0 | BSD-3-Clause | [LICENSE](apps/app/notices/c0c56f26d9c051ca.txt) |
| alloc-stdlib | 0.2.4 | BSD-3-Clause |  |
| alloc-stdlib | 0.3.0 | BSD-3-Clause |  |
| allocator-api2 | 0.2.21 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/20fe7b00e904ed69.txt), [LICENSE-MIT](apps/app/notices/36516aefdc84c5d5.txt) |
| allocator-api2 | 0.4.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/20fe7b00e904ed69.txt), [LICENSE-MIT](apps/app/notices/36516aefdc84c5d5.txt) |
| anyhow | 1.0.104 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| arc-swap | 1.9.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ff3f1cd12af8866d.txt) |
| arg_enum_proc_macro | 0.3.4 | MIT | [LICENSE](apps/app/notices/8eb4fb5a6505da47.txt) |
| ariadne | 0.1.0 | See package sources |  |
| aristo | 0.4.1 | MIT |  |
| aristo-macros | 0.4.1 | MIT |  |
| array-init | 2.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c8d9a0d15dd76ca3.txt), [LICENSE-MIT](apps/app/notices/e27fb2953c088c71.txt) |
| arrayvec | 0.7.8 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/4da95ec4ecb65b73.txt) |
| as-slice | 0.2.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c986bcdb83103d4d.txt) |
| async-channel | 2.5.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| async-compression | 0.4.51 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/88d1e3160df48926.txt) |
| async-fs | 2.2.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| async-lock | 3.4.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| async-minecraft-ping | 0.8.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| async-recursion | 1.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b8601fc79bdf8d80.txt), [LICENSE-MIT](apps/app/notices/cdbd06e25b8c9c5d.txt) |
| async-task | 4.7.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| async-trait | 0.1.92 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| async-tungstenite | 0.35.0 | MIT | [LICENSE](apps/app/notices/a281dd237dee5667.txt) |
| async-walkdir | 2.2.0 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| atoi | 2.0.0 | MIT | [LICENSE](apps/app/notices/afb11426e09da40a.txt) |
| atomic-waker | 1.1.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt), [LICENSE-THIRD-PARTY](apps/app/notices/6226d0632e2e1a80.txt) |
| autocfg | 1.5.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/27995d58ad5c1145.txt) |
| av-scenechange | 0.14.1 | MIT | [LICENSE](apps/app/notices/1e27e28eafbc439f.txt) |
| av1-grain | 0.2.5 | BSD-2-Clause | [LICENSE](apps/app/notices/acc9e236b0011c63.txt) |
| avif-serialize | 0.8.9 | BSD-3-Clause | [LICENSE](apps/app/notices/04556ac17ea72a59.txt) |
| aws-lc-rs | 1.18.2 | ISC AND (Apache-2.0 OR ISC) | [LICENSE](apps/app/notices/b50b376e7d24a059.txt) |
| aws-lc-sys | 0.46.0 | ISC AND (Apache-2.0 OR ISC) AND Apache-2.0 AND MIT AND BSD-3-Clause AND (Apache-2.0 OR ISC OR MIT) AND (Apache-2.0 OR ISC OR MIT-0) | [LICENSE](apps/app/notices/728536b4160e051f.txt) |
| base16ct | 1.0.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/54fb6dfe99a6906f.txt) |
| base64 | 0.13.1 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0dd882e53de11566.txt) |
| base64 | 0.22.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0dd882e53de11566.txt) |
| base64 | 0.23.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ab499c75a0f0da8e.txt) |
| base64ct | 1.8.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/2d1c57bff28344b9.txt) |
| bigdecimal | 0.4.11 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/74df43338fc1a37b.txt), [LICENSE-MIT](apps/app/notices/6067b257a0e8cb34.txt) |
| bindgen | 0.69.5 | BSD-3-Clause | [LICENSE](apps/app/notices/c23953d9deb0a331.txt) |
| bit-set | 0.11.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/f51ac2c59a222f74.txt) |
| bit-set | 0.8.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/f51ac2c59a222f74.txt) |
| bit-vec | 0.10.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/f51ac2c59a222f74.txt) |
| bit-vec | 0.8.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/f51ac2c59a222f74.txt) |
| bit_field | 0.10.3 | Apache-2.0/MIT | [LICENSE-APACHE](apps/app/notices/b40930bbcf80744c.txt), [LICENSE-MIT](apps/app/notices/2346961b4509d62a.txt) |
| bitflags | 1.3.2 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| bitflags | 2.13.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| bitstream-io | 4.10.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7a65c85c057a5538.txt) |
| block-buffer | 0.10.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/d5c22aa3118d240e.txt) |
| block-buffer | 0.12.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/98181e7249d0c017.txt) |
| blocking | 1.7.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| bon | 3.10.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/8f8dbb74f833dc8a.txt) |
| bon-macros | 3.10.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/8f8dbb74f833dc8a.txt) |
| borrow-or-share | 0.2.4 | MIT-0 | [LICENSE](apps/app/notices/010492e490b92ec8.txt) |
| borsh | 1.8.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/7b724c8fa4a82af7.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| borsh-derive | 1.8.1 | Apache-2.0 | [LICENSE-APACHE](apps/app/notices/7b724c8fa4a82af7.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| branches | 0.4.6 | MIT | [LICENSE](apps/app/notices/d8f1f902c91b718f.txt) |
| brotli | 8.0.4 | BSD-3-Clause AND MIT | [LICENSE.BSD-3-Clause](apps/app/notices/c0c56f26d9c051ca.txt), [LICENSE.MIT](apps/app/notices/3d180008e36922a4.txt) |
| brotli | 9.0.0 | BSD-3-Clause AND MIT | [LICENSE.BSD-3-Clause](apps/app/notices/c0c56f26d9c051ca.txt), [LICENSE.MIT](apps/app/notices/3d180008e36922a4.txt) |
| brotli-decompressor | 5.0.3 | BSD-3-Clause/MIT | [LICENSE](apps/app/notices/c0c56f26d9c051ca.txt) |
| brotli-decompressor | 6.0.1 | BSD-3-Clause/MIT | [LICENSE](apps/app/notices/c0c56f26d9c051ca.txt) |
| bs58 | 0.5.1 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/42d3bf7e7d4d49d7.txt) |
| built | 0.8.1 | MIT | [LICENSE](apps/app/notices/09ae9a35173439c7.txt) |
| bumpalo | 3.20.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/65f94e99ddaf4f5d.txt) |
| by_address | 1.2.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/daa94322de7eab88.txt) |
| bytemuck | 1.25.2 | Zlib OR Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/e3ba223bb1423f0a.txt), [LICENSE-MIT](apps/app/notices/9df9ba60a11af705.txt), [LICENSE-ZLIB](apps/app/notices/84b34dd7608f7fb9.txt) |
| bytemuck_derive | 1.12.1 | Zlib OR Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/e3ba223bb1423f0a.txt), [LICENSE-MIT](apps/app/notices/9df9ba60a11af705.txt), [LICENSE-ZLIB](apps/app/notices/84b34dd7608f7fb9.txt) |
| byteorder | 1.5.0 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| byteorder-lite | 0.1.0 | Unlicense OR MIT | [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| bytes | 1.12.1 | MIT | [LICENSE](apps/app/notices/45f522cacecb1023.txt) |
| bzip2 | 0.6.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c8c6324cf2f0f076.txt) |
| camino | 1.2.6 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| cargo-platform | 0.1.9 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8ada45cd9f843acf.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| cargo_metadata | 0.19.2 | MIT | [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| cargo_toml | 1.0.1 | Apache-2.0 OR MIT | [LICENSE](apps/app/notices/ee874098519e956c.txt) |
| cc | 1.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| cesu8 | 1.1.0 | Apache-2.0/MIT | [COPYRIGHT-RUST.txt](apps/app/notices/5ca77347e58205d3.txt) |
| cexpr | 0.6.0 | Apache-2.0/MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/d9771b8c6cf4426d.txt) |
| cfb | 0.14.0 | MIT | [LICENSE](apps/app/notices/ebaac853b53fec0e.txt) |
| cfb | 0.7.3 | MIT | [LICENSE](apps/app/notices/ebaac853b53fec0e.txt) |
| cfg-if | 1.0.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| cfg_aliases | 0.2.2 | MIT | [LICENSE](apps/app/notices/31b94860253d8ec7.txt) |
| cfg_block | 0.1.1 | See package sources | [LICENSE](apps/app/notices/408bbc4d10bdf74d.txt) |
| chacha20 | 0.10.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/b8c6939380a400f5.txt) |
| chardetng | 1.0.0 | Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/01a5b47e1a8a9a4d.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/3fa4ca83dcc92378.txt) |
| chrono | 0.4.45 | MIT OR Apache-2.0 | [LICENSE.txt](apps/app/notices/946c9835d8034d24.txt) |
| cipher | 0.4.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/5c7bd92d1f096f12.txt) |
| cipher | 0.5.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/950d712c518a02fc.txt) |
| clang-sys | 1.9.1 | Apache-2.0 | [LICENSE.txt](apps/app/notices/cfc7749b96f63bd3.txt) |
| cmake | 0.1.58 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| cmov | 0.5.4 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/70c9d40f1f9545c3.txt) |
| cobs | 0.3.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/e0cfa1006a645206.txt) |
| color_quant | 1.1.0 | MIT | [LICENSE](apps/app/notices/592dc80f1a865d20.txt) |
| compression-codecs | 0.4.46 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/88d1e3160df48926.txt) |
| compression-core | 0.4.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/88d1e3160df48926.txt) |
| concurrent-queue | 2.5.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| console | 0.16.6 | MIT | [LICENSE](apps/app/notices/2022c11b24fc1e50.txt) |
| const-oid | 0.10.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/73b9dc2e79c73089.txt) |
| const-oid | 0.9.6 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/bada9e7ed8dc00d6.txt) |
| convert_case | 0.10.0 | MIT | [LICENSE](apps/app/notices/aed7b1758e35afa0.txt) |
| convert_case | 0.4.0 | MIT |  |
| cookie | 0.18.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/2773e20df8f4c52a.txt), [LICENSE-MIT](apps/app/notices/f28420c1906af38b.txt) |
| cookie_store | 0.21.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b40930bbcf80744c.txt), [LICENSE-MIT](apps/app/notices/afb11426e09da40a.txt) |
| cookie_store | 0.22.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b40930bbcf80744c.txt), [LICENSE-MIT](apps/app/notices/afb11426e09da40a.txt) |
| core_detect | 1.0.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/769f80b5bcb42ed0.txt), [LICENSE-MIT](apps/app/notices/8569ebf6bf52937b.txt) |
| cpubits | 0.1.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/003736bc98408b53.txt) |
| cpufeatures | 0.2.17 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/ae9baa7beea91027.txt) |
| cpufeatures | 0.3.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/73b9dc2e79c73089.txt) |
| crc | 3.4.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/470355a7eed93fcc.txt), [LICENSE-MIT](apps/app/notices/3488679340a49ecc.txt) |
| crc-catalog | 2.5.0 | MIT OR Apache-2.0 |  |
| crc32c | 0.6.8 | Apache-2.0/MIT |  |
| crc32fast | 1.5.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/61d383b05b87d78f.txt) |
| critical-section | 1.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/fee6bdac4b917351.txt) |
| crossbeam-channel | 0.5.17 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/5734ed989dfca1f6.txt), [LICENSE-THIRD-PARTY](apps/app/notices/b16db96b93b1d7cf.txt) |
| crossbeam-deque | 0.8.8 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/5734ed989dfca1f6.txt) |
| crossbeam-epoch | 0.9.21 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/5734ed989dfca1f6.txt) |
| crossbeam-queue | 0.3.14 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/5734ed989dfca1f6.txt) |
| crossbeam-utils | 0.8.23 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/5734ed989dfca1f6.txt) |
| crypto-bigint | 0.7.5 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/57a4d75c1d095bb9.txt) |
| crypto-common | 0.1.7 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/3521672491a34794.txt) |
| crypto-common | 0.2.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/d2e7ec5355c96eea.txt) |
| crypto-primes | 0.7.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/1e860b66ad4646c4.txt) |
| cssparser | 0.29.6 | MPL-2.0 | [LICENSE](apps/app/notices/fab3dd6bdab226f1.txt) |
| cssparser | 0.37.0 | MPL-2.0 | [LICENSE](apps/app/notices/fab3dd6bdab226f1.txt) |
| cssparser-macros | 0.6.1 | MPL-2.0 | [LICENSE](apps/app/notices/fab3dd6bdab226f1.txt) |
| cssparser-macros | 0.7.1 | MPL-2.0 | [LICENSE](apps/app/notices/fab3dd6bdab226f1.txt) |
| ctor | 1.0.13 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a8ad31b1c3f40dca.txt), [LICENSE-MIT](apps/app/notices/bccaa8b6c09f94e8.txt) |
| ctr | 0.10.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/63af4bea227c94d0.txt) |
| ctr | 0.9.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/63af4bea227c94d0.txt) |
| ctutils | 0.4.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/91585c36e4fb9ab4.txt) |
| darling | 0.21.3 | MIT | [LICENSE](apps/app/notices/8ea93490d74a5a1b.txt) |
| darling | 0.24.1 | MIT | [LICENSE](apps/app/notices/8ea93490d74a5a1b.txt) |
| darling_core | 0.21.3 | MIT | [LICENSE](apps/app/notices/8ea93490d74a5a1b.txt) |
| darling_core | 0.24.1 | MIT | [LICENSE](apps/app/notices/8ea93490d74a5a1b.txt) |
| darling_macro | 0.21.3 | MIT | [LICENSE](apps/app/notices/8ea93490d74a5a1b.txt) |
| darling_macro | 0.24.1 | MIT | [LICENSE](apps/app/notices/8ea93490d74a5a1b.txt) |
| dashmap | 6.2.1 | MIT | [LICENSE](apps/app/notices/16692e8cee4aa06e.txt) |
| data-encoding | 2.11.1 | MIT | [LICENSE](apps/app/notices/b68ad1a3367b8254.txt) |
| data-url | 0.3.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/b38f11f6096706e6.txt) |
| deadpool | 0.13.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/23fac4edada8cdd7.txt), [LICENSE-MIT](apps/app/notices/8982e37af8078670.txt) |
| deadpool-runtime | 0.3.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/23fac4edada8cdd7.txt), [LICENSE-MIT](apps/app/notices/8982e37af8078670.txt) |
| deflate64 | 0.1.12 | MIT | [LICENSE](apps/app/notices/86b5aedec040ac6e.txt) |
| defmt | 1.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/2710a622a896bba6.txt) |
| defmt-macros | 1.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/2710a622a896bba6.txt) |
| defmt-parser | 1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/2710a622a896bba6.txt) |
| der | 0.7.10 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/ad64fcb9589f1627.txt) |
| der | 0.8.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/73b9dc2e79c73089.txt) |
| der_derive | 0.7.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/bada9e7ed8dc00d6.txt) |
| deranged | 0.5.9 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/edd65bdd88957a20.txt), [LICENSE-MIT](apps/app/notices/231c837c45eb53f1.txt) |
| derive_more | 0.99.20 | MIT | [LICENSE](apps/app/notices/8a35369f3ca263b3.txt) |
| derive_more | 2.1.1 | MIT | [LICENSE](apps/app/notices/8a35369f3ca263b3.txt) |
| derive_more-impl | 2.1.1 | MIT | [LICENSE](apps/app/notices/8a35369f3ca263b3.txt) |
| digest | 0.10.7 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/9e0dfd2dd4173a53.txt) |
| digest | 0.11.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/af59cea35d7f5e27.txt) |
| dirs | 6.0.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/d3174ad63e721d4c.txt), [LICENSE-MIT](apps/app/notices/6a2e0ade09a7d5f8.txt) |
| dirs | 7.0.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/d3174ad63e721d4c.txt), [LICENSE-MIT](apps/app/notices/6a2e0ade09a7d5f8.txt) |
| dirs-sys | 0.5.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/d3174ad63e721d4c.txt), [LICENSE-MIT](apps/app/notices/6a2e0ade09a7d5f8.txt) |
| discord-rich-presence | 1.1.0 | MIT | [LICENSE](apps/app/notices/4fc331f0241d685e.txt) |
| displaydoc | 0.2.7 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| document-features | 0.2.12 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/074e6e32c86a4c0e.txt), [LICENSE-MIT](apps/app/notices/aa893340d14b9844.txt) |
| dom_query | 0.28.0 | MIT | [LICENSE](apps/app/notices/7554701d1e74fc43.txt) |
| dotenvy | 0.15.7 | MIT | [LICENSE](apps/app/notices/37653ea50ac84bb5.txt) |
| dpi | 0.1.2 | Apache-2.0 AND MIT | [LICENSE](apps/app/notices/6dc0e068dcf3a5bc.txt), [LICENSE-LIBM-MIT](apps/app/notices/9eff396a99bafd20.txt) |
| dtoa | 1.0.11 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| dtoa-short | 0.3.5 | MPL-2.0 | [LICENSE](apps/app/notices/1f256ecad1928805.txt) |
| dunce | 1.0.5 | CC0-1.0 OR MIT-0 OR Apache-2.0 | [LICENSE](apps/app/notices/a2010f343487d3f7.txt) |
| dyn-clone | 1.0.20 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| ecdsa | 0.17.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/78779d420019e6b4.txt), [LICENSE-MIT](apps/app/notices/9aa4f92bfcde293e.txt) |
| either | 1.19.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7576269ea71f767b.txt) |
| elliptic-curve | 0.14.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/d8c4ab431f20da84.txt) |
| embed-resource | 3.0.12 | MIT | [LICENSE](apps/app/notices/1abdbbd4e3f95e56.txt) |
| embedded-io | 0.4.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/423e1c4900b3fbb4.txt) |
| embedded-io | 0.6.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/47674f8b7d98c232.txt) |
| encode_unicode | 1.0.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/da23be69ad3ccf7a.txt) |
| encoding_rs | 0.8.42 | (Apache-2.0 OR MIT) AND BSD-3-Clause | [COPYRIGHT](apps/app/notices/11789f45bb180841.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/3fa4ca83dcc92378.txt), [LICENSE-WHATWG](apps/app/notices/838118388fe5c2e7.txt) |
| endi | 1.1.1 | MIT | [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| enumset | 1.1.14 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c87c7f72fd595c10.txt) |
| enumset_derive | 0.15.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c87c7f72fd595c10.txt) |
| env_filter | 2.0.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| env_logger | 0.11.11 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| equator | 0.4.2 | MIT | [LICENSE](apps/app/notices/97d3424e347e8fa2.txt) |
| equator-macro | 0.4.2 | MIT | [LICENSE](apps/app/notices/97d3424e347e8fa2.txt) |
| equivalent | 1.0.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7365cc8878a1d7ce.txt) |
| erased-serde | 0.4.10 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| errno | 0.3.14 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/8764a597675778dd.txt) |
| etcetera | 0.11.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| event-listener | 5.4.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| event-listener-strategy | 0.5.4 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| exr | 1.74.2 | BSD-3-Clause | [LICENSE.md](apps/app/notices/97e4d3aa7a9e8ac3.txt) |
| fallible-iterator | 0.2.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/0816e154b159ba25.txt) |
| fallible-iterator | 0.3.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/0816e154b159ba25.txt) |
| fastbloom | 0.14.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/7cde763ba32b3ec2.txt), [LICENSE-MIT](apps/app/notices/7c86aec715e38bf0.txt) |
| fastrand | 2.5.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| fax | 0.2.7 | MIT | [LICENSE](apps/app/notices/7101390b4c8edd75.txt) |
| fdeflate | 0.3.7 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/c77a4cf9da729987.txt) |
| ff | 0.14.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/3708458dee7f359a.txt), [LICENSE-MIT](apps/app/notices/8d0c1d1d4b2bebf5.txt) |
| filetime | 0.2.29 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| find-msvc-tools | 0.1.15 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| flagset | 0.4.7 | Apache-2.0 | [LICENSE](apps/app/notices/cfc7749b96f63bd3.txt) |
| flate2 | 1.1.10 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/025436edff4cfcdd.txt) |
| fluent-uri | 0.4.1 | MIT | [LICENSE](apps/app/notices/9fa38f610a00115d.txt) |
| flume | 0.12.0 | Apache-2.0/MIT | [LICENSE-APACHE](apps/app/notices/d8621ec2eee5b9ca.txt), [LICENSE-MIT](apps/app/notices/30fefc3a7d6a0041.txt) |
| fnv | 1.0.7 | Apache-2.0 / MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/65fdb6c76cd61612.txt) |
| foldhash | 0.2.0 | Zlib | [LICENSE](apps/app/notices/b1181a40b2a7b25c.txt) |
| form_urlencoded | 1.2.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/20c7855c364d57ea.txt) |
| formatx | 0.2.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/1eb85fc97224598d.txt), [LICENSE-MIT](apps/app/notices/c80e7c0a5217451e.txt) |
| fs4 | 1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| fs_extra | 1.3.0 | MIT | [LICENSE](apps/app/notices/251ea8ccb1205ce5.txt) |
| futf | 0.1.5 | MIT / Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/60a7062291b01ba0.txt) |
| futures | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-channel | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-core | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-executor | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-intrusive | 0.5.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/4618209e13998293.txt), [LICENSE-MIT](apps/app/notices/161c4bcb09e94e97.txt) |
| futures-io | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-lite | 2.6.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt), [LICENSE-THIRD-PARTY](apps/app/notices/6226d0632e2e1a80.txt) |
| futures-macro | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-sink | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-task | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| futures-timer | 3.0.4 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| futures-util | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/275c491d6d116055.txt), [LICENSE-MIT](apps/app/notices/6652c868f35dfe5e.txt) |
| fxhash | 0.2.1 | Apache-2.0/MIT |  |
| genawaiter | 0.99.1 | MIT |  |
| genawaiter-macro | 0.99.1 | MIT/Apache-2.0 |  |
| generic-array | 0.14.7 | MIT | [LICENSE](apps/app/notices/c09aae9d3c77b531.txt) |
| gethostname | 1.1.0 | Apache-2.0 | [LICENSE](apps/app/notices/a60eea8175145316.txt) |
| getrandom | 0.1.16 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| getrandom | 0.2.17 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/42fa16951ce7f24b.txt) |
| getrandom | 0.3.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/29e9fe5074bd27e0.txt) |
| getrandom | 0.4.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/523a42c25d245dde.txt) |
| ghash | 0.5.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/c0fabcc308b450cb.txt) |
| ghash | 0.6.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/b8c6939380a400f5.txt) |
| gif | 0.14.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/769f80b5bcb42ed0.txt), [LICENSE-MIT](apps/app/notices/77257f3d2181236b.txt) |
| glam | 0.34.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/be33ddb87a30fd32.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| glob | 0.3.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| gltf | 1.4.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/3708458dee7f359a.txt), [LICENSE-MIT](apps/app/notices/0e6c282dfcb08a03.txt) |
| gltf-derive | 1.4.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/3708458dee7f359a.txt), [LICENSE-MIT](apps/app/notices/f71fd5946d6674af.txt) |
| gltf-json | 1.4.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/3708458dee7f359a.txt), [LICENSE-MIT](apps/app/notices/0e6c282dfcb08a03.txt) |
| governor | 0.10.4 | MIT |  |
| group | 0.14.0 | MIT/Apache-2.0 | [COPYRIGHT](apps/app/notices/7429802d3e67e330.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| h2 | 0.4.20 | MIT | [LICENSE](apps/app/notices/b21623012e6c453d.txt) |
| half | 1.8.3 | MIT OR Apache-2.0 | [LICENSE](apps/app/notices/36bb253818ac1376.txt) |
| half | 2.7.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a6cba85bc92e0cff.txt), [LICENSE-MIT](apps/app/notices/508a77d2e7b51d98.txt) |
| hashbrown | 0.12.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ff8f68cb076caf8c.txt) |
| hashbrown | 0.14.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ff8f68cb076caf8c.txt) |
| hashbrown | 0.16.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ff8f68cb076caf8c.txt) |
| hashbrown | 0.17.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ff8f68cb076caf8c.txt) |
| hashlink | 0.11.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c144680885b29e47.txt), [LICENSE-MIT](apps/app/notices/e915669a595b11a2.txt) |
| heck | 0.5.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| hex | 0.4.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/f7bdb3426d045cd5.txt) |
| hickory-net | 0.26.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/6b9522191b8cb712.txt), [LICENSE-MIT](apps/app/notices/dc470946f0a12750.txt) |
| hickory-proto | 0.26.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/6b9522191b8cb712.txt), [LICENSE-MIT](apps/app/notices/dc470946f0a12750.txt) |
| hickory-resolver | 0.26.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/6b9522191b8cb712.txt), [LICENSE-MIT](apps/app/notices/dc470946f0a12750.txt) |
| hkdf | 0.13.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/59013a5c8d3a19c2.txt), [LICENSE-MIT](apps/app/notices/d288f9c9b4590446.txt) |
| hmac | 0.13.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/9e0dfd2dd4173a53.txt) |
| home | 0.5.12 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8ada45cd9f843acf.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| html5ever | 0.29.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/86dd7f026f916daf.txt) |
| html5ever | 0.39.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/86dd7f026f916daf.txt) |
| http | 1.5.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8bb1b50b0e5c9399.txt), [LICENSE-MIT](apps/app/notices/dc91f8200e4b2a1f.txt) |
| http-body | 1.1.0 | MIT | [LICENSE](apps/app/notices/248378d0a3383c17.txt) |
| http-body-util | 0.1.5 | MIT | [LICENSE](apps/app/notices/248378d0a3383c17.txt) |
| http-range | 0.1.6 | MIT | [LICENSE](apps/app/notices/f5e1170ad72f951b.txt) |
| httparse | 1.10.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/391a5396cec6230b.txt) |
| httpdate | 1.0.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/4d10fe5f3aa176b0.txt), [LICENSE-MIT](apps/app/notices/934887691e05d69d.txt) |
| hybrid-array | 0.4.15 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/70c9d40f1f9545c3.txt) |
| hyper | 1.12.0 | MIT | [LICENSE](apps/app/notices/2d01890414494742.txt) |
| hyper-rustls | 0.27.10 | Apache-2.0 OR ISC OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-ISC](apps/app/notices/7cfafc877eccc46c.txt), [LICENSE-MIT](apps/app/notices/709e3175b4212f7b.txt) |
| hyper-util | 0.1.21 | MIT | [LICENSE](apps/app/notices/9e0a97848ea543ae.txt) |
| ico | 0.5.0 | MIT | [LICENSE](apps/app/notices/41ca90213441b294.txt) |
| icu_collator | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_collator_data | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_collections | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_locale | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_locale_core | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_locale_data | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_locale_fallback | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_locale_fallback_data | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_normalizer | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_normalizer_data | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_properties | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_properties_data | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| icu_provider | 2.4.0 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| ident_case | 1.0.1 | MIT/Apache-2.0 | [LICENSE](apps/app/notices/508a77d2e7b51d98.txt) |
| idna | 1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/b38f11f6096706e6.txt) |
| idna_adapter | 1.2.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/8b43ce8accd61e9d.txt) |
| image | 0.25.10 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/c77a4cf9da729987.txt) |
| image-webp | 0.2.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/c77a4cf9da729987.txt) |
| imgref | 1.12.3 | CC0-1.0 OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-CC0](apps/app/notices/a2010f343487d3f7.txt) |
| index_vec | 0.1.4 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a8a76b5fd1f1e532.txt), [LICENSE-MIT](apps/app/notices/30fefc3a7d6a0041.txt) |
| indexmap | 1.9.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ecc269ef87fd38a1.txt) |
| indexmap | 2.14.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ecc269ef87fd38a1.txt) |
| indicatif | 0.18.6 | MIT | [LICENSE](apps/app/notices/2022c11b24fc1e50.txt) |
| infer | 0.19.0 | MIT | [LICENSE](apps/app/notices/270b0d81891aa44c.txt) |
| infer | 0.22.0 | MIT | [LICENSE](apps/app/notices/270b0d81891aa44c.txt) |
| inflections | 1.1.1 | MIT | [LICENSE](apps/app/notices/fe5c9498374de795.txt) |
| inout | 0.1.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/304b898acad7f02e.txt) |
| inout | 0.2.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/a07fcacc3c60de4d.txt) |
| intrusive-collections | 0.9.7 | Apache-2.0/MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ff8f68cb076caf8c.txt) |
| inventory | 0.3.25 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| ipconfig | 0.3.4 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ca471051e1527e5f.txt) |
| ipnet | 2.12.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/87d9feb9238c6bd8.txt), [LICENSE-MIT](apps/app/notices/47dc9ff29128ddfb.txt) |
| itertools | 0.10.5 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7576269ea71f767b.txt) |
| itertools | 0.14.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7576269ea71f767b.txt) |
| itertools | 0.15.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7576269ea71f767b.txt) |
| itoa | 1.0.18 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| jiff | 0.2.38 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| jiff-core | 0.1.1 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| jiff-static | 0.2.38 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| jiff-tzdb | 0.1.9 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| jiff-tzdb-platform | 0.1.3 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| jobserver | 0.1.35 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| json-patch | 4.2.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b40930bbcf80744c.txt), [LICENSE-MIT](apps/app/notices/87f7527b10663377.txt) |
| json5 | 1.3.3 | MIT | [LICENSE](apps/app/notices/c931dca796a7d875.txt) |
| jsonptr | 0.7.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/2cf31f2ae7f3feba.txt), [LICENSE-MIT](apps/app/notices/2bc107bdc18a7426.txt) |
| keyboard-types | 0.7.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/769f80b5bcb42ed0.txt), [LICENSE-MIT](apps/app/notices/31dbbab009f1b2e5.txt) |
| kuchikiki | 0.8.8-speedreader | MIT | [LICENSE](apps/app/notices/23f18e03dc49df91.txt) |
| lazy_static | 1.5.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| lazycell | 1.3.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/03f6ccb4e6040abc.txt) |
| lebe | 0.5.3 | BSD-3-Clause | [LICENSE-BSD-3-Clause](apps/app/notices/f1b2855ae21da69e.txt) |
| libbz2-rs-sys | 0.2.5 | bzip2-1.0.6 | [LICENSE](apps/app/notices/54e1fd7bd53273e6.txt) |
| libc | 0.2.191 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/123a331b5dbf04c3.txt) |
| libloading | 0.8.9 | ISC | [LICENSE](apps/app/notices/b29f8b01452350c2.txt) |
| libm | 0.2.16 | MIT | [LICENSE.txt](apps/app/notices/3823dda7cf046602.txt) |
| libsqlite3-sys | 0.30.1 | MIT | [LICENSE](apps/app/notices/f59ba65550f2a5ad.txt) |
| litemap | 0.8.3 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| litrs | 1.0.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/7dc1552e88f49132.txt) |
| lock_api | 0.4.14 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c9a75f18b9ab2927.txt) |
| log | 0.4.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| loop9 | 0.1.5 | MIT | [LICENSE](apps/app/notices/af8a1cdcbe552c03.txt) |
| lru | 0.18.5 | MIT | [LICENSE](apps/app/notices/061dc50af2cd9340.txt) |
| lru-slab | 0.1.3 | MIT OR Apache-2.0 OR Zlib | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/1466d9b4f3a59bb8.txt), [LICENSE-ZLIB](apps/app/notices/09785877275ffada.txt) |
| mac | 0.1.1 | MIT/Apache-2.0 |  |
| markup5ever | 0.14.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/86dd7f026f916daf.txt) |
| markup5ever | 0.39.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/86dd7f026f916daf.txt) |
| match_token | 0.1.0 | MIT OR Apache-2.0 |  |
| matchers | 0.2.0 | MIT | [LICENSE](apps/app/notices/a47129d738752a6a.txt) |
| matches | 0.1.10 | MIT | [LICENSE](apps/app/notices/d7b49708075b5f43.txt) |
| maybe-rayon | 0.1.1 | MIT | [LICENSE](apps/app/notices/3b2dbf8684504281.txt) |
| md-5 | 0.11.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/831e0f43ad0bf014.txt) |
| memchr | 2.8.3 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| memoffset | 0.9.1 | MIT | [LICENSE](apps/app/notices/3234ac55816264ee.txt) |
| miette | 7.6.0 | Apache-2.0 | [LICENSE](apps/app/notices/cfc7749b96f63bd3.txt) |
| miette-derive | 7.6.0 | Apache-2.0 | [LICENSE](apps/app/notices/02872c3ff23e11da.txt) |
| mime | 0.3.17 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/df9cfd06d8a44d9a.txt) |
| mime_guess | 2.0.5 | MIT | [LICENSE](apps/app/notices/816000f9c28f7005.txt) |
| minecraft-meta-manifest | 0.1.0 | See package sources |  |
| minimal-lexical | 0.2.1 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt), [LICENSE.md](apps/app/notices/dbe1fff0fb1314b6.txt) |
| minisign-verify | 0.2.5 | MIT | [LICENSE](apps/app/notices/42c8695fbc468866.txt) |
| miniz_oxide | 0.8.9 | MIT OR Zlib OR Apache-2.0 | [LICENSE](apps/app/notices/4108245a1f2df9d4.txt), [LICENSE-APACHE.md](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT.md](apps/app/notices/799e9ca9d179295e.txt), [LICENSE-ZLIB.md](apps/app/notices/0a54e647fe541046.txt) |
| miniz_oxide | 0.9.1 | MIT OR Zlib OR Apache-2.0 | [LICENSE](apps/app/notices/4108245a1f2df9d4.txt), [LICENSE-APACHE.md](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT.md](apps/app/notices/799e9ca9d179295e.txt), [LICENSE-ZLIB.md](apps/app/notices/0a54e647fe541046.txt) |
| mio | 1.2.4 | MIT | [LICENSE](apps/app/notices/07919255c7e04793.txt) |
| modrinth-content-management | 0.0.0 | See package sources |  |
| modrinth-skin-rendering | 0.1.0 | See package sources |  |
| moka | 0.12.16 | (MIT OR Apache-2.0) AND Apache-2.0 | [LICENSE-APACHE](apps/app/notices/021f4a01e58372b8.txt), [LICENSE-MIT](apps/app/notices/7fe7e5e13e445074.txt), [NOTICE](apps/app/notices/f6d3f84b39d597c1.txt) |
| moxcms | 0.8.1 | BSD-3-Clause OR Apache-2.0 | [LICENSE-APACHE.md](apps/app/notices/90bf2d659c430451.txt), [LICENSE.md](apps/app/notices/2aa92cada6431e75.txt) |
| muda | 0.19.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/2ab5537b8c0cb1d4.txt), [LICENSE.spdx](apps/app/notices/b99f9d43803f2ac9.txt) |
| multiversion_no_op | 1.0.0 | Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/d2a809eafabba137.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/3fa4ca83dcc92378.txt) |
| native-dialog | 0.9.7 | MIT | [LICENSE](apps/app/notices/ecf07155bed8291e.txt) |
| new_debug_unreachable | 1.0.6 | MIT | [LICENSE-MIT](apps/app/notices/f7715d38a3fa1b4a.txt) |
| no_std_io2 | 0.9.4 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/f21c3bfdc47749b5.txt) |
| nodrop | 0.1.14 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0245ee104228a100.txt) |
| nom | 7.1.3 | MIT | [LICENSE](apps/app/notices/4dbda04344456f09.txt) |
| nom | 8.0.0 | MIT | [LICENSE](apps/app/notices/4dbda04344456f09.txt) |
| nonzero_ext | 0.3.0 | Apache-2.0 | [LICENSE.txt](apps/app/notices/3b842ae825a82c84.txt) |
| noop_proc_macro | 0.3.0 | MIT | [LICENSE](apps/app/notices/d69f24ad84ec2ade.txt) |
| notify | 8.2.0 | CC0-1.0 | [LICENSE-CC0](apps/app/notices/e0456cbab4f7b5e7.txt) |
| notify-debouncer-mini | 0.7.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b5b413d7421d728c.txt), [LICENSE-MIT](apps/app/notices/b63e167d61ced1d8.txt) |
| notify-types | 2.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b5b413d7421d728c.txt), [LICENSE-MIT](apps/app/notices/b63e167d61ced1d8.txt) |
| ntapi | 0.4.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cf90d659de5c1e64.txt), [LICENSE-MIT](apps/app/notices/11a7964ccc0dd115.txt) |
| nu-ansi-term | 0.50.3 | MIT | [LICENSE](apps/app/notices/2844658604074202.txt) |
| num-bigint | 0.4.8 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| num-complex | 0.4.6 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| num-conv | 0.2.2 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/e2e245f2b566d0bf.txt) |
| num-derive | 0.4.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| num-integer | 0.1.47 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| num-rational | 0.4.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| num-traits | 0.2.19 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| once_cell | 1.21.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| opaque-debug | 0.3.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/f59f5a78193597e0.txt) |
| open | 5.4.4 | MIT | [LICENSE.md](apps/app/notices/e63690624d604aa6.txt) |
| option-ext | 0.2.0 | MPL-2.0 | [LICENSE.txt](apps/app/notices/66a3107d5ad6a058.txt) |
| ordered-stream | 0.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| os_info | 3.15.0 | MIT | [LICENSE](apps/app/notices/44b62aa8f8a212f3.txt) |
| p256 | 0.14.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/d8c4ab431f20da84.txt) |
| pack1 | 1.1.0 | Zlib OR Apache-2.0 OR MIT |  |
| parking | 2.2.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt), [LICENSE-THIRD-PARTY](apps/app/notices/9a6d7a3c1b8edcc7.txt) |
| parking_lot | 0.12.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c9a75f18b9ab2927.txt) |
| parking_lot_core | 0.9.12 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c9a75f18b9ab2927.txt) |
| paste | 1.0.15 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| pastey | 0.1.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| pastey | 0.2.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| path-util | 0.0.0 | See package sources |  |
| pathdiff | 0.2.3 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/dd7818e575815db1.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| pem-rfc7468 | 1.0.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/4148e7b027fba018.txt) |
| percent-encoding | 2.3.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/b38f11f6096706e6.txt) |
| phf | 0.10.1 | MIT |  |
| phf | 0.11.3 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf | 0.13.1 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf | 0.14.0 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf | 0.8.0 | MIT |  |
| phf_codegen | 0.11.3 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_codegen | 0.13.1 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_codegen | 0.8.0 | MIT |  |
| phf_generator | 0.10.0 | MIT |  |
| phf_generator | 0.11.3 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_generator | 0.13.1 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_generator | 0.14.0 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_generator | 0.8.0 | MIT |  |
| phf_macros | 0.10.0 | MIT |  |
| phf_macros | 0.13.1 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_macros | 0.14.0 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_shared | 0.10.0 | MIT |  |
| phf_shared | 0.11.3 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_shared | 0.13.1 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_shared | 0.14.0 | MIT | [LICENSE](apps/app/notices/0ab4d106b6faac07.txt) |
| phf_shared | 0.8.0 | MIT |  |
| pin-project-lite | 0.2.17 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| piper | 0.2.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| pkcs1 | 0.8.0-rc.5 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/4148e7b027fba018.txt) |
| pkcs8 | 0.11.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/73b9dc2e79c73089.txt) |
| pkg-config | 0.3.34 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| plist | 1.10.2 | MIT | [LICENCE](apps/app/notices/5b0ae40d1a35f7ae.txt) |
| pluralizer | 0.5.0 | MIT/Apache-2.0 | [LICENSE](apps/app/notices/cf8a3836e9ca9d27.txt), [LICENSE-APACHE](apps/app/notices/769f80b5bcb42ed0.txt) |
| png | 0.17.16 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/eaf40297c75da471.txt) |
| png | 0.18.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/eaf40297c75da471.txt) |
| polyval | 0.6.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/a291b6910744d262.txt) |
| polyval | 0.7.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/b8c6939380a400f5.txt) |
| portable-atomic | 1.15.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| postcard | 1.1.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/177540cad091a40e.txt) |
| postgres-protocol | 0.6.12 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/4d033ae2577fa505.txt) |
| postgres-types | 0.2.14 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/4d033ae2577fa505.txt) |
| potential_utf | 0.1.6 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| powerfmt | 0.2.1 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/155420c6403d4e0f.txt), [LICENSE-MIT](apps/app/notices/070dbc7dda03a292.txt) |
| ppv-lite86 | 0.2.21 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/0218327e7a480793.txt), [LICENSE-MIT](apps/app/notices/4cada0bd02ea3692.txt) |
| precomputed-hash | 0.1.1 | MIT | [LICENSE](apps/app/notices/7ca6700600dfa9c9.txt) |
| prefix-trie | 0.8.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/87d9feb9238c6bd8.txt), [LICENSE-MIT](apps/app/notices/f646f5108c9cd674.txt) |
| prettyplease | 0.2.37 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| prettyplease | 0.3.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| primefield | 0.14.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/4621bda86773a67b.txt) |
| primeorder | 0.14.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/233b95ccbf90dc67.txt) |
| proc-macro-crate | 3.5.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8ada45cd9f843acf.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| proc-macro-hack | 0.5.20+deprecated | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/d59d2723bbc1627b.txt) |
| proc-macro2 | 1.0.107 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| profiling | 1.0.18 | MIT OR Apache-2.0 |  |
| profiling-procmacros | 1.0.18 | MIT OR Apache-2.0 |  |
| prost | 0.14.4 | Apache-2.0 | [LICENSE](apps/app/notices/a60eea8175145316.txt) |
| prost-derive | 0.14.4 | Apache-2.0 | [LICENSE](apps/app/notices/a60eea8175145316.txt) |
| psl-types | 2.0.11 | MIT/Apache-2.0 | [LICENSE](apps/app/notices/7b25e06666d37972.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt) |
| publicsuffix | 2.3.0 | MIT/Apache-2.0 | [LICENSE](apps/app/notices/f09adf500d35265e.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt) |
| pulp | 0.22.3 | MIT | [LICENSE](apps/app/notices/d64f878c89bd5f1e.txt) |
| pulp-wasm-simd-flag | 0.1.1 | MIT |  |
| pxfm | 0.1.30 | BSD-3-Clause OR Apache-2.0 | [LICENSE-APACHE.md](apps/app/notices/90bf2d659c430451.txt), [LICENSE.md](apps/app/notices/2aa92cada6431e75.txt) |
| qoi | 0.4.1 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/8173d5c29b4f956d.txt), [LICENSE-MIT](apps/app/notices/45adbcb6d50e4b28.txt) |
| quanta | 0.12.6 | MIT | [LICENSE](apps/app/notices/7bdd587c9ff64c56.txt) |
| quartz_nbt | 0.2.9 | MIT | [LICENSE](apps/app/notices/b7fc6e3427951c03.txt) |
| quartz_nbt_macros | 0.1.1 | MIT |  |
| quick-error | 2.0.1 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/058f01fe181608d0.txt) |
| quick-xml | 0.42.0 | MIT | [LICENSE-MIT.md](apps/app/notices/f0cf9b1c62bbe3bd.txt) |
| quinn | 0.11.12 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/4b2d0aca6789fa39.txt) |
| quinn-proto | 0.11.19 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/4b2d0aca6789fa39.txt) |
| quinn-udp | 0.5.16 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/4b2d0aca6789fa39.txt) |
| quote | 1.0.47 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| rand | 0.10.3 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/35242e7a83f69875.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand | 0.7.3 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand | 0.8.8 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/35242e7a83f69875.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand | 0.9.5 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/35242e7a83f69875.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_chacha | 0.2.2 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_chacha | 0.3.1 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_chacha | 0.9.0 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/35242e7a83f69875.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_core | 0.10.1 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/92b81db30f7ab6d6.txt), [LICENSE-APACHE](apps/app/notices/6df43f6f4b5d4587.txt), [LICENSE-MIT](apps/app/notices/8b6e9feec03e7c9a.txt) |
| rand_core | 0.5.1 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_core | 0.6.4 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/6df43f6f4b5d4587.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_core | 0.9.5 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/6df43f6f4b5d4587.txt), [LICENSE-MIT](apps/app/notices/209fbbe0ad52d923.txt) |
| rand_pcg | 0.10.2 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/6df43f6f4b5d4587.txt), [LICENSE-MIT](apps/app/notices/2234e3cefee876ae.txt) |
| rand_pcg | 0.2.1 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/90eb64f0279b0d94.txt), [LICENSE-APACHE](apps/app/notices/aaff376532ea30a0.txt), [LICENSE-MIT](apps/app/notices/2234e3cefee876ae.txt) |
| rapidhash | 4.5.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/d902d7d4433c0809.txt), [LICENSE-MIT](apps/app/notices/d7bb236e93b1117d.txt) |
| rav1e | 0.8.1 | BSD-2-Clause | [LICENSE](apps/app/notices/2dd0a109751e939d.txt) |
| ravif | 0.13.0 | BSD-3-Clause | [LICENSE](apps/app/notices/f78709143bb9643a.txt) |
| raw-cpuid | 11.6.0 | MIT | [LICENSE.md](apps/app/notices/cdd45f4d0c552c3a.txt) |
| raw-window-handle | 0.6.2 | MIT OR Apache-2.0 OR Zlib | [LICENSE-APACHE.md](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT.md](apps/app/notices/9c5a80639a57c1c9.txt), [LICENSE-ZLIB.md](apps/app/notices/ae895c8576e682f3.txt) |
| rayon | 1.12.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0621878e61f0d0fd.txt) |
| rayon-core | 1.13.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0621878e61f0d0fd.txt) |
| reborrow | 0.5.5 | MIT | [LICENSE](apps/app/notices/bf5a93d1014429b4.txt) |
| ref-cast | 1.0.27 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| ref-cast-impl | 1.0.27 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| regex | 1.13.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| regex-automata | 0.4.18 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| regex-syntax | 0.8.11 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/6485b8ed310d3f03.txt) |
| reqwest | 0.12.28 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/751963a8b88c0e3a.txt), [LICENSE-MIT](apps/app/notices/47d4e1803702728e.txt) |
| reqwest | 0.13.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/751963a8b88c0e3a.txt), [LICENSE-MIT](apps/app/notices/dd87e27dfbaa888c.txt) |
| resolv-conf | 0.7.6 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/c303b44873acb399.txt) |
| result | 1.0.0 | MIT | [COPYING](apps/app/notices/494d714b99fdedc1.txt) |
| rfc6979 | 0.6.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/78779d420019e6b4.txt), [LICENSE-MIT](apps/app/notices/9aa4f92bfcde293e.txt) |
| rfd | 0.15.4 | MIT | [LICENSE](apps/app/notices/65fc947f4bac882a.txt) |
| rgb | 0.8.53 | MIT | [LICENSE](apps/app/notices/457b464bc0fba8a3.txt) |
| ring | 0.17.14 | Apache-2.0 AND ISC | [LICENSE](apps/app/notices/b3d734001a94efff.txt), [LICENSE-BoringSSL](apps/app/notices/005fc765ddc5115d.txt), [LICENSE-other-bits](apps/app/notices/f025ccfb7dfb6bdf.txt) |
| roaring | 0.11.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/42d3bf7e7d4d49d7.txt) |
| rsa | 0.10.0-rc.19 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/769f80b5bcb42ed0.txt), [LICENSE-MIT](apps/app/notices/30fefc3a7d6a0041.txt) |
| rust_decimal | 1.43.0 | MIT | [LICENSE](apps/app/notices/f8218253704e3244.txt) |
| rust_decimal_macros | 1.40.0 | MIT | [LICENSE](apps/app/notices/f8218253704e3244.txt) |
| rustc-hash | 1.1.0 | Apache-2.0/MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| rustc-hash | 2.1.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/95bd3988beee069f.txt), [LICENSE-MIT](apps/app/notices/30fefc3a7d6a0041.txt) |
| rustc_version | 0.4.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c9a75f18b9ab2927.txt) |
| rustix | 0.38.44 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/377c2e7c53250cc5.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-Apache-2.0_WITH_LLVM-exception](apps/app/notices/268872b9816f90fd.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| rustls | 0.23.46 | Apache-2.0 OR ISC OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-ISC](apps/app/notices/7cfafc877eccc46c.txt), [LICENSE-MIT](apps/app/notices/709e3175b4212f7b.txt) |
| rustls-native-certs | 0.8.5 | Apache-2.0 OR ISC OR MIT | [LICENSE](apps/app/notices/d75967ce788187f8.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-ISC](apps/app/notices/7cfafc877eccc46c.txt), [LICENSE-MIT](apps/app/notices/709e3175b4212f7b.txt) |
| rustls-pemfile | 2.2.0 | Apache-2.0 OR ISC OR MIT | [LICENSE](apps/app/notices/c5dae4585d8520d1.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-ISC](apps/app/notices/7cfafc877eccc46c.txt), [LICENSE-MIT](apps/app/notices/709e3175b4212f7b.txt) |
| rustls-pki-types | 1.15.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/45fd05c4865e7c35.txt), [LICENSE-MIT](apps/app/notices/9117d922e6671255.txt) |
| rustls-platform-verifier | 0.7.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/1c7cf76689c837a6.txt) |
| rustls-webpki | 0.103.16 | ISC | [LICENSE](apps/app/notices/5b698ca13897be3a.txt) |
| rustversion | 1.0.23 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| ryu | 1.0.23 | Apache-2.0 OR BSL-1.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-BOOST](apps/app/notices/c9bff75738922193.txt) |
| same-file | 1.0.6 | Unlicense/MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/cb3c929a05e6cbc9.txt) |
| schannel | 0.1.30 | MIT | [LICENSE.md](apps/app/notices/aa72991ac35b4de0.txt) |
| schemars | 0.8.22 | MIT | [LICENSE](apps/app/notices/1954992a2b32e8a2.txt) |
| schemars | 0.9.0 | MIT | [LICENSE](apps/app/notices/1954992a2b32e8a2.txt) |
| schemars | 1.2.3 | MIT | [LICENSE](apps/app/notices/1954992a2b32e8a2.txt) |
| schemars_derive | 0.8.22 | MIT | [LICENSE](apps/app/notices/1954992a2b32e8a2.txt) |
| scopeguard | 1.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/fb77f0a9c53e473a.txt) |
| sec1 | 0.8.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/57a4d75c1d095bb9.txt) |
| selectors | 0.24.0 | MPL-2.0 |  |
| selectors | 0.38.0 | MPL-2.0 |  |
| semver | 1.0.28 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde | 1.0.229 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde-binhum | 0.1.0 | See package sources |  |
| serde-untagged | 0.1.9 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_bytes | 0.11.19 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_cbor | 0.11.2 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/e03e58ea9205f519.txt) |
| serde_core | 1.0.229 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_derive | 1.0.229 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_derive_internals | 0.29.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_ini | 0.2.0 | MIT | [COPYING](apps/app/notices/494d714b99fdedc1.txt) |
| serde_json | 1.0.154 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_path_to_error | 0.1.20 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_repr | 0.1.21 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| serde_spanned | 1.1.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/249fdb6694467dd6.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| serde_urlencoded | 0.7.1 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/b9eb266294324f67.txt) |
| serde_with | 3.24.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7576269ea71f767b.txt) |
| serde_with_macros | 3.24.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7576269ea71f767b.txt) |
| serdect | 0.4.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/2ca9996043628ad4.txt) |
| serialize-to-javascript | 0.1.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/e53a7165e8bc3ced.txt) |
| serialize-to-javascript-impl | 0.1.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/e53a7165e8bc3ced.txt) |
| servo_arc | 0.2.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| servo_arc | 0.4.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| sha1 | 0.11.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/831e0f43ad0bf014.txt) |
| sha1_smol | 1.0.1 | BSD-3-Clause | [LICENSE](apps/app/notices/282a21b0710441c3.txt) |
| sha2 | 0.10.9 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/b4eb00df6e2a4d22.txt) |
| sha2 | 0.11.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/831e0f43ad0bf014.txt) |
| sharded-slab | 0.1.7 | MIT | [LICENSE](apps/app/notices/eafbfa606bc005ed.txt) |
| shlex | 1.3.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/553fffcd9b1cb158.txt), [LICENSE-MIT](apps/app/notices/4455bf75a9115410.txt) |
| shlex | 2.0.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/553fffcd9b1cb158.txt), [LICENSE-MIT](apps/app/notices/4455bf75a9115410.txt) |
| signature | 3.0.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/9aa4f92bfcde293e.txt) |
| simd-adler32 | 0.3.10 | MIT | [LICENSE.md](apps/app/notices/42a35170233e83e1.txt) |
| simd_helpers | 0.1.0 | MIT |  |
| simdutf8 | 0.1.5 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE-MIT](apps/app/notices/1847e0e0698142ed.txt) |
| simsimd | 6.5.16 | Apache-2.0 |  |
| siphasher | 0.3.11 | MIT/Apache-2.0 | [COPYING](apps/app/notices/306b56d1a86d1ff3.txt) |
| siphasher | 1.0.4 | MIT OR Apache-2.0 | [COPYING](apps/app/notices/c962ee4d1d05ddc1.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/f9c4c77baa382800.txt) |
| slab | 0.4.12 | MIT | [LICENSE](apps/app/notices/8ce0830173fdac60.txt) |
| smallvec | 1.16.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0b28172679e0009b.txt) |
| socket2 | 0.6.5 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| softaes | 0.1.7 | MIT | [LICENSE](apps/app/notices/d4ea02a54d266337.txt) |
| softbuffer | 0.4.8 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a4445427440043e8.txt), [LICENSE-MIT](apps/app/notices/0463bfa47d6d763d.txt) |
| spin | 0.9.9 | MIT | [LICENSE](apps/app/notices/6ac8711fb340c62c.txt) |
| spinning_top | 0.3.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/984f3c74e72da2ff.txt) |
| spki | 0.7.3 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/c995204cc6bad2ed.txt) |
| spki | 0.8.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/57a4d75c1d095bb9.txt) |
| sqlx | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c8f5453612253e8e.txt), [LICENSE-MIT](apps/app/notices/5abbdd842310c8f1.txt) |
| sqlx-core | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/154397a08d0cb342.txt), [LICENSE-MIT](apps/app/notices/72af89a828df52a9.txt) |
| sqlx-macros | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/154397a08d0cb342.txt), [LICENSE-MIT](apps/app/notices/72af89a828df52a9.txt) |
| sqlx-macros-core | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/154397a08d0cb342.txt), [LICENSE-MIT](apps/app/notices/72af89a828df52a9.txt) |
| sqlx-mysql | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/154397a08d0cb342.txt), [LICENSE-MIT](apps/app/notices/72af89a828df52a9.txt) |
| sqlx-postgres | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/154397a08d0cb342.txt), [LICENSE-MIT](apps/app/notices/72af89a828df52a9.txt) |
| sqlx-sqlite | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/154397a08d0cb342.txt), [LICENSE-MIT](apps/app/notices/72af89a828df52a9.txt) |
| stable_deref_trait | 1.2.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/5e05b024f653a5ce.txt) |
| string_cache | 0.8.9 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/62065228e42caebc.txt) |
| string_cache | 0.9.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/62065228e42caebc.txt) |
| string_cache_codegen | 0.5.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/62065228e42caebc.txt) |
| string_cache_codegen | 0.6.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/62065228e42caebc.txt) |
| stringprep | 0.1.5 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/a07450fd4496cb8b.txt) |
| strsim | 0.11.1 | MIT | [LICENSE](apps/app/notices/1e697ce8d21401fb.txt) |
| strum | 0.26.3 | MIT | [LICENSE](apps/app/notices/8bce3b45e49ecd14.txt) |
| strum_macros | 0.26.4 | MIT | [LICENSE](apps/app/notices/8bce3b45e49ecd14.txt) |
| subtle | 2.6.1 | BSD-3-Clause | [LICENSE](apps/app/notices/d1fc1bc0d155df60.txt) |
| symlink | 0.1.0 | MIT/Apache-2.0 | [COPYRIGHT](apps/app/notices/edb9885b41e48517.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/b85cb7b51c3f8d60.txt) |
| syn | 1.0.109 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| syn | 2.0.119 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| syn | 3.0.9 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| sync_wrapper | 1.0.2 | Apache-2.0 | [LICENSE](apps/app/notices/0d542e0c8804e39a.txt) |
| synstructure | 0.14.0 | MIT | [LICENSE](apps/app/notices/219920e865eee70b.txt) |
| sys-locale | 0.3.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/5cc390ab5e5e6507.txt) |
| sysinfo | 0.38.4 | MIT | [LICENSE](apps/app/notices/1f14f9ce70a5fded.txt) |
| tagptr | 0.2.0 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a2b15e1e90041431.txt), [LICENSE-MIT](apps/app/notices/175d33d2e88fc394.txt) |
| tao | 0.36.0 | Apache-2.0 | [LICENSE](apps/app/notices/6dc0e068dcf3a5bc.txt), [LICENSE.spdx](apps/app/notices/02b6448337b75777.txt) |
| tar | 0.4.46 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/8ca6b96cea9e67c6.txt) |
| tauri | 2.11.5 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-build | 2.6.3 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-codegen | 2.6.3 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-macros | 2.6.3 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-plugin | 2.5.3 | Apache-2.0 OR MIT |  |
| tauri-plugin-deep-link | 2.4.3 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-dialog | 2.4.0 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-fs | 2.4.5 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-http | 2.5.7 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-opener | 2.5.0 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-os | 2.3.1 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-single-instance | 2.3.4 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/b7f455413bfe5f9d.txt) |
| tauri-plugin-updater | 2.10.1 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-plugin-window-state | 2.4.0 | Apache-2.0 OR MIT | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt), [LICENSE_APACHE-2.0](apps/app/notices/0cec06e0e55fbc3d.txt), [LICENSE_MIT](apps/app/notices/89ff9689dcf9dd53.txt) |
| tauri-runtime | 2.11.3 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-runtime-wry | 2.11.4 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-utils | 2.9.3 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| tauri-winres | 0.3.3 | MIT | [LICENSE](apps/app/notices/d9fa6b0e6fed50d4.txt) |
| tempfile | 3.27.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/8b427f5bc5017645.txt) |
| tendril | 0.4.3 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/60a7062291b01ba0.txt) |
| tendril | 0.5.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/60a7062291b01ba0.txt) |
| theseus | 1.0.0-local | See package sources | [COPYING.md](apps/app/notices/fabd5a699e02c4e5.txt) |
| theseus_gui | 1.0.0-local | GPL-3.0-only | [COPYING.md](apps/app/notices/3116729145c0da98.txt), [LICENSE](apps/app/notices/3972dc9744f6499f.txt) |
| thiserror | 2.0.21 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| thiserror-impl | 2.0.21 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| thread_local | 1.1.10 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/c9a75f18b9ab2927.txt) |
| tiff | 0.11.3 | MIT | [LICENSE](apps/app/notices/20c097d0de27e2ad.txt) |
| time | 0.3.55 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/2537228d9a1b44a5.txt) |
| time-core | 0.1.9 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/2537228d9a1b44a5.txt) |
| time-macros | 0.2.32 | MIT OR Apache-2.0 | [LICENSE-Apache](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/2537228d9a1b44a5.txt) |
| tinystr | 0.8.5 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| tinyvec | 1.13.3 | Zlib OR Apache-2.0 OR MIT | [LICENSE-APACHE.md](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT.md](apps/app/notices/fd80a26fbb3f644a.txt), [LICENSE-ZLIB.md](apps/app/notices/84b34dd7608f7fb9.txt) |
| tls_codec | 0.4.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/904801faf3f18503.txt) |
| tls_codec_derive | 0.4.2 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/904801faf3f18503.txt) |
| toasty | 0.11.0 | MIT | [LICENSE](apps/app/notices/e1fe7d495b6f85a0.txt) |
| toasty-core | 0.11.0 | MIT |  |
| toasty-driver-mysql | 0.11.0 | MIT |  |
| toasty-driver-postgresql | 0.11.0 | MIT |  |
| toasty-driver-turso | 0.11.0 | MIT |  |
| toasty-macros | 0.11.0 | MIT |  |
| toasty-sql | 0.11.0 | MIT |  |
| tokio | 1.54.0 | MIT | [LICENSE](apps/app/notices/253cd04c6714889d.txt) |
| tokio-macros | 2.7.2 | MIT | [LICENSE](apps/app/notices/0b83dc40cba89b99.txt) |
| tokio-postgres | 0.7.18 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/4d033ae2577fa505.txt) |
| tokio-postgres-rustls | 0.14.0 | MIT | [LICENSE](apps/app/notices/66765d2624face69.txt) |
| tokio-rustls | 0.26.6 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/cc117d90b498b32b.txt), [LICENSE-MIT](apps/app/notices/e20fa2b8e0a2565f.txt) |
| tokio-stream | 0.1.19 | MIT | [LICENSE](apps/app/notices/253cd04c6714889d.txt) |
| tokio-util | 0.7.20 | MIT | [LICENSE](apps/app/notices/253cd04c6714889d.txt) |
| toml | 0.9.12+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| toml | 1.1.8+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/249fdb6694467dd6.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| toml_datetime | 0.7.5+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/c6596eb7be8581c1.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| toml_datetime | 1.1.2+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/249fdb6694467dd6.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| toml_edit | 0.25.17+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/249fdb6694467dd6.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| toml_parser | 1.1.5+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/249fdb6694467dd6.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| toml_writer | 1.1.3+spec-1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/249fdb6694467dd6.txt), [LICENSE-MIT](apps/app/notices/6efb0476a1cc0850.txt) |
| tower | 0.5.3 | MIT | [LICENSE](apps/app/notices/4249c8e6c5ebb85f.txt) |
| tower-http | 0.6.11 | MIT | [LICENSE](apps/app/notices/5049cf464977eff4.txt) |
| tower-layer | 0.3.3 | MIT | [LICENSE](apps/app/notices/4249c8e6c5ebb85f.txt) |
| tower-service | 0.3.3 | MIT | [LICENSE](apps/app/notices/4249c8e6c5ebb85f.txt) |
| tracing | 0.1.44 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tracing-appender | 0.2.5 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tracing-attributes | 0.1.31 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tracing-core | 0.1.36 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tracing-error | 0.2.1 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tracing-log | 0.2.0 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tracing-subscriber | 0.3.23 | MIT | [LICENSE](apps/app/notices/898b1ae9821e98da.txt) |
| tray-icon | 0.24.2 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/2ab5537b8c0cb1d4.txt), [LICENSE.spdx](apps/app/notices/6c1e5d0ccf5e8951.txt) |
| try-lock | 0.2.5 | MIT | [LICENSE](apps/app/notices/c816a0749cdc6bf0.txt) |
| tungstenite | 0.30.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7fea0ee51a4ca5d5.txt) |
| turso | 0.7.2 | MIT |  |
| turso_core | 0.7.2 | MIT |  |
| turso_ext | 0.7.2 | MIT |  |
| turso_macros | 0.7.2 | MIT |  |
| turso_parser | 0.7.2 | MIT |  |
| turso_sdk_kit | 0.7.2 | MIT |  |
| turso_sdk_kit_macros | 0.7.2 | MIT |  |
| turso_sync_engine | 0.7.2 | MIT |  |
| turso_sync_sdk_kit | 0.7.2 | MIT |  |
| twox-hash | 2.1.5 | MIT | [LICENSE.txt](apps/app/notices/f59bcb1c02654665.txt) |
| typed-path | 0.12.4 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| typed-path | 0.13.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| typeid | 1.0.3 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| typenum | 1.20.1 | MIT OR Apache-2.0 | [LICENSE](apps/app/notices/db11fec9946737df.txt), [LICENSE-APACHE](apps/app/notices/516b24e051bf5630.txt), [LICENSE-MIT](apps/app/notices/a825bd853ab71619.txt) |
| ucd-trie | 0.1.7 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| uds_windows | 1.2.1 | MIT | [LICENSE](apps/app/notices/27ebda9d51f0a56b.txt) |
| uncased | 0.9.10 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/361df454e66f5cd7.txt) |
| unic-char-property | 0.9.0 | MIT/Apache-2.0 |  |
| unic-char-range | 0.9.0 | MIT/Apache-2.0 |  |
| unic-common | 0.9.0 | MIT/Apache-2.0 |  |
| unic-ucd-ident | 0.9.0 | MIT/Apache-2.0 |  |
| unic-ucd-version | 0.9.0 | MIT/Apache-2.0 |  |
| unicase | 2.10.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/4f6bd11a0f17fe5b.txt) |
| unicode-bidi | 0.3.18 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/edb20b474f6cbd4f.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| unicode-ident | 1.0.27 | (MIT OR Apache-2.0) AND Unicode-3.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt), [LICENSE-UNICODE](apps/app/notices/f7db81051789b729.txt) |
| unicode-normalization | 0.1.26 | (MIT OR Apache-2.0) AND Unicode-3.0 | [COPYRIGHT](apps/app/notices/23860c2a7b5d96b2.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt), [LICENSE-UNICODE](apps/app/notices/f7db81051789b729.txt) |
| unicode-properties | 0.1.4 | MIT/Apache-2.0 | [COPYRIGHT](apps/app/notices/23860c2a7b5d96b2.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| unicode-segmentation | 1.13.3 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/23860c2a7b5d96b2.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| unicode-width | 0.1.14 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/23860c2a7b5d96b2.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| unicode-width | 0.2.2 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/23860c2a7b5d96b2.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| unicode-xid | 0.2.6 | MIT OR Apache-2.0 | [COPYRIGHT](apps/app/notices/23860c2a7b5d96b2.txt), [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/7b63ecd5f1902af1.txt) |
| unit-prefix | 0.5.2 | MIT | [LICENSE](apps/app/notices/b39b755692699226.txt) |
| universal-hash | 0.5.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/6b50510a0400c721.txt) |
| universal-hash | 0.6.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/efa52eb70a774b62.txt) |
| untrusted | 0.9.0 | ISC | [LICENSE.txt](apps/app/notices/7abd9b6960dcf7d4.txt) |
| url | 2.5.8 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/b38f11f6096706e6.txt) |
| urlencoding | 2.1.3 | MIT | [LICENSE](apps/app/notices/5a952e4a62a3022a.txt) |
| urlpattern | 0.3.0 | MIT | [LICENSE](apps/app/notices/5cf1c9dc617e4cad.txt) |
| urlpattern | 0.6.0 | MIT | [LICENSE](apps/app/notices/5cf1c9dc617e4cad.txt) |
| utf-8 | 0.7.6 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| utf16_iter | 1.0.5 | Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/b84efe109a420fa3.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/3fa4ca83dcc92378.txt) |
| utf8_iter | 1.0.4 | Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/c30152c94a6d75e0.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/3fa4ca83dcc92378.txt) |
| utoipa | 6.0.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/43070e2d4e532684.txt), [LICENSE-MIT](apps/app/notices/82b13fb25622b195.txt) |
| utoipa-gen | 6.0.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/43070e2d4e532684.txt), [LICENSE-MIT](apps/app/notices/82b13fb25622b195.txt) |
| uuid | 0.8.2 | Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/807242105c35b459.txt), [LICENSE-APACHE](apps/app/notices/7cfd738c53d61c79.txt), [LICENSE-MIT](apps/app/notices/dd23b9037fa9f086.txt) |
| uuid | 1.28.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/436bc5a105d8e57d.txt) |
| v_frame | 0.3.9 | BSD-2-Clause | [LICENSE](apps/app/notices/02b80951ce6c1dd2.txt) |
| vcpkg | 0.2.15 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/60c93a31f490375a.txt), [LICENSE-MIT](apps/app/notices/016d20f335060a70.txt) |
| version_check | 0.9.5 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/b7e650f3fce5c532.txt) |
| void | 1.0.2 | MIT |  |
| vswhom | 0.1.0 | MIT | [LICENSE](apps/app/notices/b9b7e5d4bf885706.txt) |
| vswhom-sys | 0.1.3 | MIT | [LICENSE](apps/app/notices/b9b7e5d4bf885706.txt) |
| walkdir | 2.5.0 | Unlicense/MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/0f96a83840e146e4.txt) |
| want | 0.3.2 | MIT | [LICENSE](apps/app/notices/a65f5d0a945d2677.txt) |
| wasm-bindgen | 0.2.129 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| wasm-bindgen-macro | 0.2.129 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| wasm-bindgen-macro-support | 0.2.129 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| wasm-bindgen-shared | 0.2.129 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/378f5840b258e277.txt) |
| web-time | 1.1.0 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/54a744942eb3fa63.txt), [LICENSE-MIT](apps/app/notices/f428305bbf2e70fb.txt) |
| web_atoms | 0.2.6 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/86dd7f026f916daf.txt) |
| webpki-roots | 1.0.10 | CDLA-Permissive-2.0 | [LICENSE](apps/app/notices/e271993808fec50a.txt) |
| webview2-com | 0.38.2 | MIT |  |
| webview2-com-macros | 0.8.1 | MIT |  |
| webview2-com-sys | 0.38.2 | MIT |  |
| weezl | 0.1.12 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/769f80b5bcb42ed0.txt), [LICENSE-MIT](apps/app/notices/573f5227db835cd3.txt) |
| wfd | 0.1.8 | MIT | [LICENSE](apps/app/notices/4597731f0b63633b.txt) |
| which | 4.4.2 | MIT | [LICENSE.txt](apps/app/notices/0041560f5d419c30.txt) |
| whoami | 2.1.3 | Apache-2.0 OR BSL-1.0 OR MIT | [LICENSE_APACHE](apps/app/notices/62c7a1e35f564068.txt), [LICENSE_BOOST](apps/app/notices/c9bff75738922193.txt), [LICENSE_MIT](apps/app/notices/508a77d2e7b51d98.txt) |
| widestring | 1.2.1 | MIT OR Apache-2.0 | [LICENSE-APACHE](apps/app/notices/a6cba85bc92e0cff.txt), [LICENSE-MIT](apps/app/notices/508a77d2e7b51d98.txt) |
| winapi | 0.3.9 | MIT/Apache-2.0 | [LICENSE-APACHE](apps/app/notices/b40930bbcf80744c.txt), [LICENSE-MIT](apps/app/notices/ce7bc3499fee93d5.txt) |
| winapi-util | 0.1.11 | Unlicense OR MIT | [COPYING](apps/app/notices/01c266bced4a434d.txt), [LICENSE-MIT](apps/app/notices/cb3c929a05e6cbc9.txt) |
| window-vibrancy | 0.6.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/617b85f62a4f1b6a.txt), [LICENSE.spdx](apps/app/notices/7ccef0d35e8507fa.txt) |
| windows | 0.61.3 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows | 0.62.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-collections | 0.2.0 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-collections | 0.3.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-core | 0.61.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-core | 0.62.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-future | 0.2.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-future | 0.3.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-implement | 0.60.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-interface | 0.59.3 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-link | 0.1.3 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-link | 0.2.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-numerics | 0.2.0 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-numerics | 0.3.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-registry | 0.5.3 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-registry | 0.6.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-result | 0.3.4 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-result | 0.4.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-strings | 0.4.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-strings | 0.5.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-sys | 0.59.0 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-sys | 0.60.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-sys | 0.61.2 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-targets | 0.52.6 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-targets | 0.53.5 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-threading | 0.1.0 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-threading | 0.2.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows-version | 0.1.7 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows_x86_64_msvc | 0.52.6 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| windows_x86_64_msvc | 0.53.1 | MIT OR Apache-2.0 | [license-apache-2.0](apps/app/notices/c16f8dcf1a368b83.txt), [license-mit](apps/app/notices/c2cfccb812fe4821.txt) |
| winnow | 0.7.15 | MIT | [LICENSE-MIT](apps/app/notices/cb5aedb296c5246d.txt) |
| winnow | 1.0.4 | MIT | [LICENSE-MIT](apps/app/notices/cb5aedb296c5246d.txt) |
| winreg | 0.56.0 | MIT | [LICENSE](apps/app/notices/ea021d8c6383c84d.txt) |
| wnaf | 0.14.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/c1c9d5ca65122bab.txt) |
| write16 | 1.0.0 | Apache-2.0 OR MIT | [COPYRIGHT](apps/app/notices/3210be7332b5bdf4.txt), [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/3fa4ca83dcc92378.txt) |
| writeable | 0.6.4 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| wry | 0.56.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a60eea8175145316.txt), [LICENSE-MIT](apps/app/notices/ef88893533af22ff.txt), [LICENSE.spdx](apps/app/notices/26235c41e314fb0d.txt) |
| x509-cert | 0.2.5 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/a9040321c3712d8f.txt), [LICENSE-MIT](apps/app/notices/90c503b61dee04e1.txt) |
| y4m | 0.8.0 | MIT | [LICENSE](apps/app/notices/1327309babc5f345.txt) |
| yoke | 0.8.4 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| yoke-derive | 0.8.4 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| zbus | 6.0.0 | MIT | [LICENSE](apps/app/notices/260e4ff3fc493695.txt) |
| zbus_macros | 6.0.0 | MIT | [LICENSE](apps/app/notices/260e4ff3fc493695.txt) |
| zbus_utils | 6.0.0 | MIT | [LICENSE](apps/app/notices/260e4ff3fc493695.txt) |
| zcheapstr | 1.1.0 | MIT | [LICENSE](apps/app/notices/59871bb1612f8a05.txt) |
| zerocopy | 0.8.63 | BSD-2-Clause OR Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/9d185ac6703c4b04.txt), [LICENSE-BSD](apps/app/notices/83c1763356e822ad.txt), [LICENSE-MIT](apps/app/notices/1a2f5c12ddc934d5.txt) |
| zerocopy-derive | 0.8.63 | BSD-2-Clause OR Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/9d185ac6703c4b04.txt), [LICENSE-BSD](apps/app/notices/83c1763356e822ad.txt), [LICENSE-MIT](apps/app/notices/1a2f5c12ddc934d5.txt) |
| zerofrom | 0.1.8 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| zerofrom-derive | 0.1.8 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| zeroize | 1.9.1 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/8c7516d4b27b1e49.txt) |
| zeroize_derive | 1.5.0 | Apache-2.0 OR MIT | [LICENSE-APACHE](apps/app/notices/cfc7749b96f63bd3.txt), [LICENSE-MIT](apps/app/notices/b8c6939380a400f5.txt) |
| zerotrie | 0.2.5 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| zerovec | 0.11.9 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| zerovec-derive | 0.11.7 | Unicode-3.0 | [LICENSE](apps/app/notices/f367c1b8e1aa2624.txt) |
| zip | 9.0.5 | MIT | [LICENSE](apps/app/notices/58545fed1565e42d.txt) |
| zlib-rs | 0.6.8 | Zlib | [LICENSE](apps/app/notices/e72111c52b7d96eb.txt) |
| zmij | 1.0.23 | MIT | [LICENSE-MIT](apps/app/notices/23f18e03dc49df91.txt) |
| zopfli | 0.8.4 | Apache-2.0 | [COPYING](apps/app/notices/018b1cb87efdf7a0.txt) |
| zruntime | 0.2.0 | MIT | [LICENSE](apps/app/notices/ec2e030f7cd75edb.txt) |
| zstd | 0.14.3 | BSD-3-Clause | [LICENSE](apps/app/notices/ce4868c8e4ebe47a.txt) |
| zstd-safe | 8.2.0 | BSD-3-Clause | [LICENSE](apps/app/notices/ce4868c8e4ebe47a.txt) |
| zstd-sys | 2.1.2+zstd.1.5.7 | BSD-3-Clause | [LICENSE](apps/app/notices/ce4868c8e4ebe47a.txt), [LICENSE.BSD-3-Clause](apps/app/notices/bf7017a73a95ea63.txt) |
| zune-core | 0.5.3 | MIT OR Apache-2.0 OR Zlib | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/d30047bca3b51663.txt), [LICENSE-ZLIB](apps/app/notices/d201d14804d3bcd3.txt) |
| zune-inflate | 0.2.54 | MIT OR Apache-2.0 OR Zlib |  |
| zune-jpeg | 0.5.15 | MIT OR Apache-2.0 OR Zlib | [LICENSE-APACHE](apps/app/notices/c71d239df91726fc.txt), [LICENSE-MIT](apps/app/notices/d30047bca3b51663.txt), [LICENSE-ZLIB](apps/app/notices/d201d14804d3bcd3.txt) |

## Java agent

The shaded Java agent embeds ASM 9.9, ASM Tree 9.9 (BSD-3-Clause), and Gson 2.13.2 (Apache-2.0). The original project metadata is available at [ASM](https://central.sonatype.com/artifact/org.ow2.asm/asm/9.9), [ASM Tree](https://central.sonatype.com/artifact/org.ow2.asm/asm-tree/9.9), and [Gson](https://central.sonatype.com/artifact/com.google.code.gson/gson/2.13.2).



- [ASM and ASM Tree license](apps/app/notices/java-asm-9.9.txt)
- [Gson license](apps/app/notices/java-gson-2.13.2.txt)

## JavaScript workspace dependency inventory

| Package | Version | Declared license | Notices |
| --- | --- | --- | --- |
| @adobe/css-tools | 4.4.4 | MIT | [LICENSE](apps/app/notices/326ff38500622860.txt) |
| @alloc/quick-lru | 5.2.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| @apidevtools/swagger-methods | 3.0.2 | MIT | [LICENSE](apps/app/notices/c21f6ea22d94fe6b.txt) |
| @asamuzakjp/css-color | 3.2.0 | MIT | [LICENSE](apps/app/notices/1156c4bf9aa3982f.txt) |
| @astrojs/check | 0.9.6 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/compiler | 2.13.0 | MIT | [LICENSE](apps/app/notices/41bf89dd8dffe96c.txt) |
| @astrojs/internal-helpers | 0.7.5 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/language-server | 2.16.3 | MIT | [LICENSE](apps/app/notices/90e270c8f7a1029e.txt) |
| @astrojs/markdown-remark | 6.3.10 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/mdx | 4.3.13 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/prism | 3.3.0 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/sitemap | 3.7.0 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/starlight | 0.32.6 | MIT | [LICENSE](apps/app/notices/a0ee39c239b80f63.txt) |
| @astrojs/telemetry | 3.3.0 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| @astrojs/yaml2ts | 0.2.2 | MIT | [LICENSE](apps/app/notices/c345508b6ee877e1.txt) |
| @babel/code-frame | 7.29.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/code-frame | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/compat-data | 7.29.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/core | 7.29.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/generator | 7.29.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/generator | 7.29.8 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-annotate-as-pure | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-compilation-targets | 7.28.6 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-create-class-features-plugin | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-globals | 7.28.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-globals | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-member-expression-to-functions | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-module-imports | 7.28.6 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-module-transforms | 7.28.6 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-optimise-call-expression | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-plugin-utils | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-replace-supers | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-skip-transparent-expression-wrappers | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-string-parser | 7.27.1 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-string-parser | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-validator-identifier | 7.28.5 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-validator-identifier | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helper-validator-option | 7.27.1 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/helpers | 7.28.6 | MIT | [LICENSE](apps/app/notices/4be9d87b56a30629.txt) |
| @babel/parser | 7.29.0 | MIT | [LICENSE](apps/app/notices/2e97627cb278aa75.txt) |
| @babel/parser | 7.29.9 | MIT | [LICENSE](apps/app/notices/2e97627cb278aa75.txt) |
| @babel/plugin-syntax-jsx | 7.28.6 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/plugin-syntax-typescript | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/plugin-transform-typescript | 7.29.9 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/runtime | 7.28.6 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/template | 7.28.6 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/template | 7.29.7 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/traverse | 7.29.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/traverse | 7.29.8 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/types | 7.29.0 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @babel/types | 7.29.8 | MIT | [LICENSE](apps/app/notices/117da2af0d4ce0fe.txt) |
| @bomb.sh/tab | 0.0.19 | MIT |  |
| @capsizecss/unpack | 4.0.0 | MIT | [LICENSE](apps/app/notices/f5162df964aa2bf1.txt) |
| @clack/core | 1.1.0 | MIT | [LICENSE](apps/app/notices/6b3c03752a3f3642.txt) |
| @clack/core | 1.5.1 | MIT | [LICENSE](apps/app/notices/3e873d2aba8b76bc.txt) |
| @clack/prompts | 1.1.0 | MIT | [LICENSE](apps/app/notices/6b3c03752a3f3642.txt) |
| @clack/prompts | 1.8.1 | MIT | [LICENSE](apps/app/notices/3e873d2aba8b76bc.txt) |
| @cloudflare/kv-asset-handler | 0.4.2 | MIT OR Apache-2.0 |  |
| @cloudflare/kv-asset-handler | 0.5.0 | MIT OR Apache-2.0 |  |
| @cloudflare/unenv-preset | 2.16.1 | MIT OR Apache-2.0 |  |
| @cloudflare/workerd-windows-64 | 1.20260730.1 | Apache-2.0 |  |
| @codemirror/autocomplete | 6.20.0 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/commands | 6.10.1 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/lang-css | 6.3.1 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/lang-html | 6.4.11 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/lang-javascript | 6.2.4 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/lang-markdown | 6.5.0 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/language | 6.12.1 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/lint | 6.9.3 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/state | 6.5.4 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @codemirror/view | 6.39.12 | MIT | [LICENSE](apps/app/notices/05c6130cda97e760.txt) |
| @colordx/core | 5.8.0 | MIT | [LICENSE](apps/app/notices/4268a4be5cd2c898.txt) |
| @contentauth/c2pa-types | 0.7.2 | See package sources | [LICENSE](apps/app/notices/5aeea31bc245dd31.txt) |
| @contentauth/c2pa-wasm | 0.11.0 | MIT | [LICENSE](apps/app/notices/5aeea31bc245dd31.txt) |
| @contentauth/c2pa-web | 0.13.1 | MIT | [LICENSE](apps/app/notices/5aeea31bc245dd31.txt) |
| @crowdin/crowdin-api-client | 1.55.2 | MIT | [LICENSE](apps/app/notices/28804c967d95f6f9.txt) |
| @cspotcode/source-map-support | 0.8.1 | MIT | [LICENSE.md](apps/app/notices/3a7d3bb198e909ed.txt) |
| @csstools/color-helpers | 5.1.0 | MIT-0 | [LICENSE.md](apps/app/notices/947e32047a166cd0.txt) |
| @csstools/css-calc | 2.1.4 | MIT | [LICENSE.md](apps/app/notices/d00d032f517721b4.txt) |
| @csstools/css-color-parser | 3.1.0 | MIT | [LICENSE.md](apps/app/notices/d00d032f517721b4.txt) |
| @csstools/css-parser-algorithms | 3.0.5 | MIT | [LICENSE.md](apps/app/notices/d00d032f517721b4.txt) |
| @csstools/css-tokenizer | 3.0.4 | MIT | [LICENSE.md](apps/app/notices/d00d032f517721b4.txt) |
| @ctrl/tinycolor | 4.2.0 | MIT | [LICENSE](apps/app/notices/40623170cffa9289.txt) |
| @dnd-kit/abstract | 0.5.0 | MIT | [LICENSE](apps/app/notices/537607e3f1533ad2.txt) |
| @dnd-kit/collision | 0.5.0 | MIT | [LICENSE](apps/app/notices/537607e3f1533ad2.txt) |
| @dnd-kit/dom | 0.5.0 | MIT | [LICENSE](apps/app/notices/537607e3f1533ad2.txt) |
| @dnd-kit/geometry | 0.5.0 | MIT | [LICENSE](apps/app/notices/537607e3f1533ad2.txt) |
| @dnd-kit/state | 0.5.0 | MIT | [LICENSE](apps/app/notices/537607e3f1533ad2.txt) |
| @dnd-kit/vue | 0.5.0 | MIT | [LICENSE](apps/app/notices/537607e3f1533ad2.txt) |
| @dxup/nuxt | 0.2.2 | MIT | [LICENSE](apps/app/notices/e7abe7df70c01054.txt) |
| @dxup/unimport | 0.1.2 | MIT | [LICENSE](apps/app/notices/e7abe7df70c01054.txt) |
| @emmetio/abbreviation | 2.3.3 | MIT | [LICENSE](apps/app/notices/72dd5a0ed7d2d2fd.txt) |
| @emmetio/css-abbreviation | 2.1.8 | MIT | [LICENSE](apps/app/notices/72dd5a0ed7d2d2fd.txt) |
| @emmetio/css-parser | 0.4.1 | MIT | [LICENSE](apps/app/notices/a906db7c2a7424f1.txt) |
| @emmetio/html-matcher | 1.3.0 | ISC | [LICENSE](apps/app/notices/a906db7c2a7424f1.txt) |
| @emmetio/scanner | 1.0.4 | MIT | [LICENSE](apps/app/notices/72dd5a0ed7d2d2fd.txt) |
| @emmetio/stream-reader | 2.2.0 | MIT | [LICENSE](apps/app/notices/a906db7c2a7424f1.txt) |
| @emmetio/stream-reader-utils | 0.1.0 | MIT | [LICENSE](apps/app/notices/a906db7c2a7424f1.txt) |
| @es-joy/jsdoccomment | 0.50.2 | MIT | [LICENSE-MIT.txt](apps/app/notices/cccd79e17a98d190.txt) |
| @esbuild/win32-x64 | 0.21.5 | MIT |  |
| @esbuild/win32-x64 | 0.25.12 | MIT |  |
| @esbuild/win32-x64 | 0.27.2 | MIT |  |
| @esbuild/win32-x64 | 0.28.1 | MIT |  |
| @eslint-community/eslint-utils | 4.9.1 | MIT | [LICENSE](apps/app/notices/fcf6eabf68ca9698.txt) |
| @eslint-community/regexpp | 4.12.2 | MIT | [LICENSE](apps/app/notices/fcf6eabf68ca9698.txt) |
| @eslint/compat | 1.4.1 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @eslint/config-array | 0.21.1 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @eslint/config-helpers | 0.4.2 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @eslint/core | 0.17.0 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @eslint/eslintrc | 3.3.3 | MIT | [LICENSE](apps/app/notices/3b6be04f862a077a.txt) |
| @eslint/js | 9.39.2 | MIT | [LICENSE](apps/app/notices/3b6be04f862a077a.txt) |
| @eslint/object-schema | 2.1.7 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @eslint/plugin-kit | 0.4.1 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @expressive-code/core | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| @expressive-code/plugin-frames | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| @expressive-code/plugin-shiki | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| @expressive-code/plugin-text-markers | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| @floating-ui/core | 1.8.0 | MIT | [LICENSE](apps/app/notices/0e4c9a9b6c71019c.txt) |
| @floating-ui/dom | 1.8.0 | MIT | [LICENSE](apps/app/notices/0e4c9a9b6c71019c.txt) |
| @floating-ui/utils | 0.2.12 | MIT | [LICENSE](apps/app/notices/0e4c9a9b6c71019c.txt) |
| @floating-ui/vue | 2.0.1 | MIT | [LICENSE](apps/app/notices/46c97b198a78dc0b.txt) |
| @formatjs/cli | 6.12.2 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/ecma402-abstract | 2.2.4 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/ecma402-abstract | 2.3.6 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/fast-memoize | 2.2.3 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/fast-memoize | 2.2.7 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/icu-messageformat-parser | 2.11.4 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/icu-messageformat-parser | 2.9.4 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/icu-skeleton-parser | 1.8.16 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/icu-skeleton-parser | 1.8.8 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/intl | 2.10.15 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/intl-displaynames | 6.8.5 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/intl-listformat | 7.7.5 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/intl-localematcher | 0.5.10 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/intl-localematcher | 0.5.8 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @formatjs/intl-localematcher | 0.6.2 | MIT | [LICENSE.md](apps/app/notices/b1cc980e28e9e48f.txt) |
| @humanfs/core | 0.19.1 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @humanfs/node | 0.16.7 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @humanwhocodes/module-importer | 1.0.1 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @humanwhocodes/momoa | 2.0.4 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @humanwhocodes/retry | 0.4.3 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @img/colour | 1.1.0 | MIT | [LICENSE.md](apps/app/notices/e2eaa4603c14cb26.txt) |
| @img/sharp-win32-x64 | 0.33.5 | Apache-2.0 AND LGPL-3.0-or-later | [LICENSE](apps/app/notices/73ba74dfaa520b49.txt) |
| @img/sharp-win32-x64 | 0.34.5 | Apache-2.0 AND LGPL-3.0-or-later | [LICENSE](apps/app/notices/dc1f5d2d43c5531d.txt) |
| @img/sharp-win32-x64 | 0.35.2 | Apache-2.0 AND LGPL-3.0-or-later | [LICENSE](apps/app/notices/dc1f5d2d43c5531d.txt) |
| @intercom/messenger-js-sdk | 0.0.14 | MIT | [LICENSE](apps/app/notices/2a77c814c3700e2a.txt) |
| @intlify/core-base | 10.0.8 | MIT | [LICENSE](apps/app/notices/403a4d6f9815ae33.txt) |
| @intlify/message-compiler | 10.0.8 | MIT | [LICENSE](apps/app/notices/403a4d6f9815ae33.txt) |
| @intlify/shared | 10.0.8 | MIT | [LICENSE](apps/app/notices/403a4d6f9815ae33.txt) |
| @ioredis/commands | 1.10.0 | MIT | [LICENSE](apps/app/notices/d6c8d3da280f25f5.txt) |
| @isaacs/cliui | 8.0.2 | ISC | [LICENSE.txt](apps/app/notices/2dc0465729366c3a.txt) |
| @isaacs/fs-minipass | 4.0.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| @jridgewell/gen-mapping | 0.3.13 | MIT | [LICENSE](apps/app/notices/769d154fbde32a91.txt) |
| @jridgewell/remapping | 2.3.5 | MIT | [LICENSE](apps/app/notices/769d154fbde32a91.txt) |
| @jridgewell/resolve-uri | 3.1.2 | MIT | [LICENSE](apps/app/notices/b8778b155bfde5a2.txt) |
| @jridgewell/source-map | 0.3.11 | MIT | [LICENSE](apps/app/notices/769d154fbde32a91.txt) |
| @jridgewell/sourcemap-codec | 1.5.5 | MIT | [LICENSE](apps/app/notices/769d154fbde32a91.txt) |
| @jridgewell/sourcemap-codec | 1.6.0 | MIT | [LICENSE](apps/app/notices/769d154fbde32a91.txt) |
| @jridgewell/trace-mapping | 0.3.31 | MIT | [LICENSE](apps/app/notices/769d154fbde32a91.txt) |
| @jridgewell/trace-mapping | 0.3.9 | MIT | [LICENSE](apps/app/notices/0daa3c2445c4bfaa.txt) |
| @jsdevtools/ono | 7.1.3 | MIT | [LICENSE](apps/app/notices/8f7fe359ab18923b.txt) |
| @kurkle/color | 0.3.4 | MIT | [LICENSE.md](apps/app/notices/89ba003273148915.txt) |
| @kwsites/file-exists | 1.1.1 | MIT | [LICENSE](apps/app/notices/f52b03f3b77f5d1f.txt) |
| @kwsites/promise-deferred | 1.1.1 | MIT | [LICENSE](apps/app/notices/31be59a9f7c38321.txt) |
| @lezer/common | 1.5.0 | MIT | [LICENSE](apps/app/notices/568902fb66eaf1f1.txt) |
| @lezer/css | 1.3.0 | MIT | [LICENSE](apps/app/notices/568902fb66eaf1f1.txt) |
| @lezer/highlight | 1.2.3 | MIT | [LICENSE](apps/app/notices/568902fb66eaf1f1.txt) |
| @lezer/html | 1.3.13 | MIT | [LICENSE](apps/app/notices/568902fb66eaf1f1.txt) |
| @lezer/javascript | 1.5.4 | MIT | [LICENSE](apps/app/notices/568902fb66eaf1f1.txt) |
| @lezer/lr | 1.4.8 | MIT | [LICENSE](apps/app/notices/568902fb66eaf1f1.txt) |
| @lezer/markdown | 1.6.3 | MIT | [LICENSE](apps/app/notices/54bd812a6d334e0c.txt) |
| @ltd/j-toml | 1.38.0 | LGPL-3.0 | [LICENSE](apps/app/notices/2d175f9654b89bef.txt) |
| @mapbox/node-pre-gyp | 2.0.3 | BSD-3-Clause | [LICENSE](apps/app/notices/5e3b2b8138f20dbf.txt) |
| @marijn/find-cluster-break | 1.0.2 | MIT | [LICENSE](apps/app/notices/9360b00fdd091f05.txt) |
| @mdx-js/mdx | 3.1.1 | MIT | [license](apps/app/notices/a68016580b554a54.txt) |
| @microsoft/api-extractor | 7.58.9 | MIT | [LICENSE](apps/app/notices/5515f89b040fb889.txt) |
| @microsoft/api-extractor-model | 7.33.8 | MIT | [LICENSE](apps/app/notices/68456bb41127857b.txt) |
| @microsoft/tsdoc | 0.16.0 | MIT | [LICENSE](apps/app/notices/c5ff7150f61127f5.txt) |
| @microsoft/tsdoc-config | 0.18.1 | MIT | [LICENSE](apps/app/notices/c5ff7150f61127f5.txt) |
| @nodelib/fs.scandir | 2.1.5 | MIT | [LICENSE](apps/app/notices/9363d160bf41d46d.txt) |
| @nodelib/fs.stat | 2.0.5 | MIT | [LICENSE](apps/app/notices/9363d160bf41d46d.txt) |
| @nodelib/fs.walk | 1.2.8 | MIT | [LICENSE](apps/app/notices/9363d160bf41d46d.txt) |
| @nuxt/cli | 3.37.0 | MIT | [LICENSE](apps/app/notices/48a8c150d3fb6f62.txt) |
| @nuxt/devalue | 2.0.2 | MIT | [LICENSE](apps/app/notices/c52bd24ed7e82cad.txt) |
| @nuxt/devtools | 3.4.2 | MIT | [LICENSE](apps/app/notices/093ed239e02c92f3.txt) |
| @nuxt/devtools-kit | 3.4.2 | MIT | [LICENSE](apps/app/notices/093ed239e02c92f3.txt) |
| @nuxt/devtools-wizard | 3.4.2 | MIT | [LICENSE](apps/app/notices/093ed239e02c92f3.txt) |
| @nuxt/eslint-config | 0.5.7 | MIT | [LICENSE](apps/app/notices/2c2d40c5ab1981ef.txt) |
| @nuxt/eslint-plugin | 0.5.7 | MIT | [LICENSE](apps/app/notices/2c2d40c5ab1981ef.txt) |
| @nuxt/kit | 3.20.2 | MIT | [LICENSE](apps/app/notices/947a111b1c579718.txt) |
| @nuxt/kit | 4.5.2 | MIT | [LICENSE](apps/app/notices/947a111b1c579718.txt) |
| @nuxt/nitro-server | 3.20.2 | MIT | [LICENSE](apps/app/notices/947a111b1c579718.txt) |
| @nuxt/schema | 3.20.2 | MIT | [LICENSE](apps/app/notices/947a111b1c579718.txt) |
| @nuxt/telemetry | 2.9.1 | MIT | [LICENSE](apps/app/notices/b021c5bd3a72502c.txt) |
| @nuxt/vite-builder | 3.20.2 | MIT | [LICENSE](apps/app/notices/947a111b1c579718.txt) |
| @one-ini/wasm | 0.1.1 | MIT | [LICENSE](apps/app/notices/8bff7c96e66561af.txt) |
| @oslojs/encoding | 1.1.0 | MIT | [LICENSE](apps/app/notices/37765ef8cf5691a0.txt) |
| @oxc-minify/binding-win32-x64-msvc | 0.102.0 | MIT |  |
| @oxc-parser/binding-win32-x64-msvc | 0.102.0 | MIT |  |
| @oxc-project/types | 0.102.0 | MIT | [LICENSE](apps/app/notices/95ced5ecf1133fbf.txt) |
| @oxc-project/types | 0.122.0 | MIT | [LICENSE](apps/app/notices/95ced5ecf1133fbf.txt) |
| @oxc-transform/binding-win32-x64-msvc | 0.102.0 | MIT |  |
| @pagefind/default-ui | 1.4.0 | MIT |  |
| @pagefind/windows-x64 | 1.4.0 | MIT |  |
| @parcel/watcher | 2.5.6 | MIT | [LICENSE](apps/app/notices/5cfba9d5711264d4.txt) |
| @parcel/watcher-wasm | 2.5.6 | MIT |  |
| @parcel/watcher-win32-x64 | 2.5.6 | MIT | [LICENSE](apps/app/notices/5cfba9d5711264d4.txt) |
| @pkgjs/parseargs | 0.11.0 | MIT | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| @pkgr/core | 0.2.9 | MIT |  |
| @polka/url | 1.0.0-next.29 | MIT |  |
| @poppinss/colors | 4.1.6 | MIT | [LICENSE.md](apps/app/notices/c21feb678df81fa8.txt) |
| @poppinss/dumper | 0.6.5 | MIT | [LICENSE.md](apps/app/notices/bba2399e2c617b05.txt) |
| @poppinss/dumper | 0.7.0 | MIT | [LICENSE.md](apps/app/notices/bba2399e2c617b05.txt) |
| @poppinss/exception | 1.2.3 | MIT | [LICENSE.md](apps/app/notices/bba2399e2c617b05.txt) |
| @preact/signals-core | 1.14.4 | MIT | [LICENSE](apps/app/notices/a11fc89e4c6b1188.txt) |
| @prettier/plugin-xml | 3.4.2 | MIT | [LICENSE](apps/app/notices/a9e5631b7af03f7c.txt) |
| @readme/better-ajv-errors | 2.4.0 | Apache-2.0 | [LICENSE](apps/app/notices/822c00d3553f37e3.txt) |
| @readme/json-schema-ref-parser | 1.2.0 | MIT | [LICENSE](apps/app/notices/c21f6ea22d94fe6b.txt) |
| @readme/openapi-parser | 2.7.0 | MIT | [LICENSE](apps/app/notices/c21f6ea22d94fe6b.txt) |
| @readme/openapi-schemas | 3.1.0 | MIT | [LICENSE](apps/app/notices/1a06eef8fa5a2190.txt) |
| @rolldown/binding-win32-x64-msvc | 1.0.0-rc.12 | MIT |  |
| @rolldown/pluginutils | 1.0.0-rc.12 | MIT | [LICENSE](apps/app/notices/23ecfff35a5a2e80.txt) |
| @rolldown/pluginutils | 1.0.1 | MIT | [LICENSE](apps/app/notices/e1919b3b98b8bf6c.txt) |
| @rollup/plugin-alias | 6.0.0 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/plugin-commonjs | 29.0.3 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/plugin-inject | 5.0.5 | MIT |  |
| @rollup/plugin-json | 6.1.0 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/plugin-node-resolve | 16.0.3 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/plugin-replace | 6.0.3 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/plugin-terser | 1.0.0 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/pluginutils | 5.3.0 | MIT | [LICENSE](apps/app/notices/7b8136f76c483d03.txt) |
| @rollup/rollup-win32-x64-gnu | 4.57.1 | MIT |  |
| @rollup/rollup-win32-x64-gnu | 4.63.6 | MIT |  |
| @rollup/rollup-win32-x64-msvc | 4.57.1 | MIT |  |
| @rollup/rollup-win32-x64-msvc | 4.63.6 | MIT |  |
| @rushstack/node-core-library | 5.23.1 | MIT | [LICENSE](apps/app/notices/ce1c368a1ce0827e.txt) |
| @rushstack/problem-matcher | 0.2.1 | MIT | [LICENSE](apps/app/notices/9ad5296a3777922b.txt) |
| @rushstack/rig-package | 0.7.3 | MIT | [LICENSE](apps/app/notices/7c322fd0a0417f0c.txt) |
| @rushstack/terminal | 0.24.0 | MIT | [LICENSE](apps/app/notices/01b7a8a851d7080d.txt) |
| @rushstack/ts-command-line | 5.3.10 | MIT | [LICENSE](apps/app/notices/12c0be55654d17aa.txt) |
| @selderee/plugin-htmlparser2 | 0.11.0 | MIT | [LICENSE](apps/app/notices/07e82387dc9c036f.txt) |
| @sentry-internal/browser-utils | 8.55.0 | MIT | [LICENSE](apps/app/notices/334b116857e8bbba.txt) |
| @sentry-internal/feedback | 8.55.0 | MIT | [LICENSE](apps/app/notices/4a94ce14953994e3.txt) |
| @sentry-internal/replay | 8.55.0 | MIT | [LICENSE](apps/app/notices/71e9fc3ffb996839.txt) |
| @sentry-internal/replay-canvas | 8.55.0 | MIT | [LICENSE](apps/app/notices/7d6562781128956f.txt) |
| @sentry/browser | 8.55.0 | MIT | [LICENSE](apps/app/notices/f5b8ff1424ed5b08.txt) |
| @sentry/core | 8.55.0 | MIT | [LICENSE](apps/app/notices/f5b8ff1424ed5b08.txt) |
| @sentry/vue | 8.55.0 | MIT | [LICENSE](apps/app/notices/f5b8ff1424ed5b08.txt) |
| @sfirew/minecraft-motd-parser | 1.1.6 | MIT | [LICENSE](apps/app/notices/429403bb7b2eaebc.txt) |
| @shikijs/core | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/core | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/engine-javascript | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/engine-javascript | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/engine-oniguruma | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/engine-oniguruma | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/langs | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/langs | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/themes | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/themes | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/types | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/types | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| @shikijs/vscode-textmate | 10.0.2 | MIT | [LICENSE.md](apps/app/notices/b5cb7ff7859e7d28.txt) |
| @simple-git/args-pathspec | 1.0.4 | MIT | [LICENSE](apps/app/notices/3a31277abe4e0a30.txt) |
| @simple-git/argv-parser | 1.1.1 | MIT |  |
| @sindresorhus/is | 7.2.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| @sindresorhus/merge-streams | 4.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| @speed-highlight/core | 1.2.14 | CC0-1.0 | [LICENSE](apps/app/notices/a2010f343487d3f7.txt) |
| @storybook/addon-a11y | 10.2.4 | MIT |  |
| @storybook/addon-themes | 10.2.4 | MIT |  |
| @storybook/builder-vite | 10.2.4 | MIT |  |
| @storybook/csf-plugin | 10.2.4 | MIT |  |
| @storybook/global | 5.0.0 | MIT | [LICENSE](apps/app/notices/576f0541c45448ed.txt) |
| @storybook/icons | 2.0.1 | MIT | [LICENSE.md](apps/app/notices/a884e287f0e37d3e.txt) |
| @storybook/vue3 | 10.2.4 | MIT |  |
| @storybook/vue3-vite | 10.2.4 | MIT |  |
| @stripe/stripe-js | 7.9.0 | MIT | [LICENSE](apps/app/notices/f5ecc63f26b1bf79.txt) |
| @stylistic/eslint-plugin | 2.13.0 | MIT | [LICENSE](apps/app/notices/a429d52d537b871f.txt) |
| @svgdotjs/svg.draggable.js | 3.0.6 | MIT | [LICENSE](apps/app/notices/84bdfb8badd110ba.txt) |
| @svgdotjs/svg.filter.js | 3.0.9 | MIT | [LICENSE](apps/app/notices/83f4546bf5c1573b.txt) |
| @svgdotjs/svg.js | 3.2.5 | MIT | [LICENSE.txt](apps/app/notices/455113977c98c54d.txt) |
| @svgdotjs/svg.resize.js | 2.0.5 | MIT | [LICENSE](apps/app/notices/f6618a078e20c80b.txt) |
| @svgdotjs/svg.select.js | 4.0.3 | MIT | [LICENSE](apps/app/notices/993c7ee35618ca08.txt) |
| @taijased/vue-render-tracker | 1.0.7 | MIT |  |
| @tailwindcss/container-queries | 0.1.1 | MIT |  |
| @tailwindcss/node | 4.1.18 | MIT | [LICENSE](apps/app/notices/60e0b68c0f35c078.txt) |
| @tailwindcss/oxide | 4.1.18 | MIT | [LICENSE](apps/app/notices/60e0b68c0f35c078.txt) |
| @tailwindcss/oxide-win32-x64-msvc | 4.1.18 | MIT | [LICENSE](apps/app/notices/60e0b68c0f35c078.txt) |
| @tailwindcss/vite | 4.1.18 | MIT | [LICENSE](apps/app/notices/60e0b68c0f35c078.txt) |
| @tanstack/match-sorter-utils | 8.19.4 | MIT | [LICENSE](apps/app/notices/9db3f8ddd7031ab2.txt) |
| @tanstack/query-core | 5.101.4 | MIT | [LICENSE](apps/app/notices/a405ee70c632bb93.txt) |
| @tanstack/vue-query | 5.101.4 | MIT | [LICENSE](apps/app/notices/a405ee70c632bb93.txt) |
| @taplo/core | 0.2.0 | MIT |  |
| @taplo/lib | 0.5.0 | MIT |  |
| @tauri-apps/api | 2.10.1 | Apache-2.0 OR MIT | [LICENSE_APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE_MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| @tauri-apps/cli | 2.12.0 | Apache-2.0 OR MIT | [LICENSE-APACHE-2.0](apps/app/notices/0d542e0c8804e39a.txt), [LICENSE-MIT](apps/app/notices/9dd42ea92cff2ede.txt) |
| @tauri-apps/cli-win32-x64-msvc | 2.12.0 | Apache-2.0 OR MIT |  |
| @tauri-apps/plugin-dialog | 2.6.0 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @tauri-apps/plugin-fs | 2.4.5 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @tauri-apps/plugin-http | 2.5.7 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @tauri-apps/plugin-opener | 2.5.3 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @tauri-apps/plugin-os | 2.3.2 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @tauri-apps/plugin-updater | 2.10.0 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @tauri-apps/plugin-window-state | 2.4.1 | MIT OR Apache-2.0 | [LICENSE.spdx](apps/app/notices/eb8a6c84630461b3.txt) |
| @testing-library/dom | 10.4.1 | MIT | [LICENSE](apps/app/notices/bf8fd38056b7606d.txt) |
| @testing-library/jest-dom | 6.9.1 | MIT | [LICENSE](apps/app/notices/bf8fd38056b7606d.txt) |
| @testing-library/user-event | 14.6.1 | MIT | [LICENSE](apps/app/notices/b5a4028c49c48f82.txt) |
| @trysound/sax | 0.2.0 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| @turbo/windows-64 | 2.11.5 | MIT | [LICENSE](apps/app/notices/f7ac4712aa30551d.txt) |
| @tweenjs/tween.js | 23.1.3 | MIT | [LICENSE](apps/app/notices/c95fecd88f2709bf.txt) |
| @types/argparse | 1.0.38 | MIT | [LICENSE](apps/app/notices/dea9265341829002.txt) |
| @types/aria-query | 5.0.4 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/chai | 5.2.3 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/debug | 4.1.12 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/deep-eql | 4.0.2 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/dompurify | 3.2.0 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/estree | 1.0.8 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/estree | 1.0.9 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/estree-jsx | 1.0.5 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/glob | 9.0.0 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/hast | 3.0.4 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/html-minifier-terser | 7.0.2 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/iso-3166-2 | 1.0.4 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/js-yaml | 4.0.9 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/json-schema | 7.0.15 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/linkify-it | 5.0.0 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/markdown-it | 14.1.2 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/mdast | 4.0.4 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/mdurl | 2.0.0 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/mdx | 2.0.13 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/ms | 2.1.0 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/nlcst | 2.0.3 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/node | 17.0.45 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/node | 24.12.2 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/normalize-package-data | 2.4.4 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/resolve | 1.20.2 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/rss | 0.0.32 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/sax | 1.2.7 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/semver | 7.7.1 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/stats.js | 0.17.4 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/three | 0.172.0 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/trusted-types | 2.0.7 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/unist | 2.0.11 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/unist | 3.0.3 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/web-bluetooth | 0.0.16 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/web-bluetooth | 0.0.20 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/webxr | 0.5.24 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @types/xml2js | 0.4.14 | MIT | [LICENSE](apps/app/notices/c2cfccb812fe4821.txt) |
| @typescript-eslint/eslint-plugin | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/parser | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/project-service | 8.54.0 | MIT | [LICENSE](apps/app/notices/053a75a14b7508a8.txt) |
| @typescript-eslint/project-service | 8.65.0 | MIT | [LICENSE](apps/app/notices/053a75a14b7508a8.txt) |
| @typescript-eslint/scope-manager | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/tsconfig-utils | 8.54.0 | MIT | [LICENSE](apps/app/notices/053a75a14b7508a8.txt) |
| @typescript-eslint/tsconfig-utils | 8.65.0 | MIT | [LICENSE](apps/app/notices/053a75a14b7508a8.txt) |
| @typescript-eslint/type-utils | 8.54.0 | MIT | [LICENSE](apps/app/notices/f3c51ace7f159b21.txt) |
| @typescript-eslint/types | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/types | 8.65.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/typescript-estree | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/typescript-estree | 8.65.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/utils | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/visitor-keys | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @typescript-eslint/visitor-keys | 8.65.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| @ungap/structured-clone | 1.3.0 | ISC | [LICENSE](apps/app/notices/dc6d4961d8b6ee74.txt) |
| @unhead/vue | 2.1.17 | MIT | [LICENSE](apps/app/notices/d06451530138de11.txt) |
| @unrs/resolver-binding-win32-x64-msvc | 1.11.1 | MIT |  |
| @vercel/nft | 1.11.0 | MIT | [LICENSE](apps/app/notices/0b31f3a6ab66b272.txt) |
| @vintl/how-ago | 3.0.1 | MIT | [LICENSE](apps/app/notices/c9e05e7f4ccf81e2.txt) |
| @vitejs/plugin-vue | 5.2.4 | MIT | [LICENSE](apps/app/notices/29b68325fe026047.txt) |
| @vitejs/plugin-vue | 6.0.9 | MIT | [LICENSE](apps/app/notices/29b68325fe026047.txt) |
| @vitejs/plugin-vue-jsx | 5.1.6 | MIT | [LICENSE](apps/app/notices/29b68325fe026047.txt) |
| @vitest/expect | 3.2.4 | MIT | [LICENSE](apps/app/notices/ddc110f3b89cc397.txt) |
| @vitest/pretty-format | 3.2.4 | MIT | [LICENSE](apps/app/notices/ddc110f3b89cc397.txt) |
| @vitest/spy | 3.2.4 | MIT | [LICENSE](apps/app/notices/ddc110f3b89cc397.txt) |
| @vitest/utils | 3.2.4 | MIT | [LICENSE](apps/app/notices/ddc110f3b89cc397.txt) |
| @volar/kit | 2.4.28 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/language-core | 2.4.15 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/language-core | 2.4.27 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/language-core | 2.4.28 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/language-server | 2.4.28 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/language-service | 2.4.28 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/source-map | 2.4.15 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/source-map | 2.4.27 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/source-map | 2.4.28 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/typescript | 2.4.15 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @volar/typescript | 2.4.28 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @vscode/emmet-helper | 2.11.0 | MIT | [LICENSE](apps/app/notices/d0e26984080b12c7.txt) |
| @vscode/l10n | 0.0.18 | MIT |  |
| @vue-email/body | 0.0.3 | MIT |  |
| @vue-email/button | 0.0.3 | MIT |  |
| @vue-email/code-block | 0.0.3 | MIT |  |
| @vue-email/code-inline | 0.0.3 | MIT |  |
| @vue-email/column | 0.0.3 | MIT |  |
| @vue-email/components | 0.0.21 | MIT |  |
| @vue-email/container | 0.0.3 | MIT |  |
| @vue-email/font | 0.0.3 | MIT |  |
| @vue-email/head | 0.0.3 | MIT |  |
| @vue-email/heading | 0.0.3 | MIT |  |
| @vue-email/hr | 0.0.3 | MIT |  |
| @vue-email/html | 0.0.3 | MIT |  |
| @vue-email/img | 0.0.3 | MIT |  |
| @vue-email/link | 0.0.3 | MIT |  |
| @vue-email/markdown | 0.0.7 | MIT |  |
| @vue-email/preview | 0.0.3 | MIT |  |
| @vue-email/render | 0.0.9 | MIT | [LICENSE](apps/app/notices/6f0238c020468c67.txt) |
| @vue-email/row | 0.0.3 | MIT |  |
| @vue-email/section | 0.0.3 | MIT |  |
| @vue-email/style | 0.0.3 | MIT |  |
| @vue-email/tailwind | 0.2.0 | MIT |  |
| @vue-email/text | 0.0.3 | MIT |  |
| @vue-macros/common | 3.1.2 | MIT | [LICENSE](apps/app/notices/4041048344f1a45d.txt) |
| @vue/babel-helper-vue-transform-on | 2.0.1 | MIT | [LICENSE](apps/app/notices/4f7e6756ef3bf1f8.txt) |
| @vue/babel-plugin-jsx | 2.0.1 | MIT | [LICENSE](apps/app/notices/4f7e6756ef3bf1f8.txt) |
| @vue/babel-plugin-resolve-type | 2.0.1 | MIT | [LICENSE](apps/app/notices/4f7e6756ef3bf1f8.txt) |
| @vue/compiler-core | 3.5.27 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-core | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-dom | 3.5.27 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-dom | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-sfc | 3.5.27 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-sfc | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-ssr | 3.5.27 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-ssr | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/compiler-vue2 | 2.7.16 | MIT |  |
| @vue/devtools-api | 6.6.4 | MIT |  |
| @vue/devtools-core | 8.2.1 | MIT | [LICENSE](apps/app/notices/d0ac09e8df2b5462.txt) |
| @vue/devtools-kit | 8.2.1 | MIT | [LICENSE](apps/app/notices/d0ac09e8df2b5462.txt) |
| @vue/devtools-shared | 8.2.1 | MIT | [LICENSE](apps/app/notices/d0ac09e8df2b5462.txt) |
| @vue/language-core | 2.2.12 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @vue/language-core | 3.2.4 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| @vue/reactivity | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/runtime-core | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/runtime-dom | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/server-renderer | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/shared | 3.5.27 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/shared | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| @vue/tsconfig | 0.7.0 | MIT | [LICENSE](apps/app/notices/a8b93ecd961a4cd7.txt) |
| @vueuse/core | 11.3.0 | MIT | [LICENSE](apps/app/notices/0f844b1160603552.txt) |
| @vueuse/core | 9.13.0 | MIT | [LICENSE](apps/app/notices/0f844b1160603552.txt) |
| @vueuse/metadata | 11.3.0 | MIT | [LICENSE](apps/app/notices/0f844b1160603552.txt) |
| @vueuse/metadata | 9.13.0 | MIT | [LICENSE](apps/app/notices/0f844b1160603552.txt) |
| @vueuse/shared | 11.3.0 | MIT | [LICENSE](apps/app/notices/0f844b1160603552.txt) |
| @vueuse/shared | 9.13.0 | MIT | [LICENSE](apps/app/notices/0f844b1160603552.txt) |
| @webgpu/types | 0.1.69 | BSD-3-Clause | [LICENSE](apps/app/notices/ad88400fc55c2871.txt) |
| @xml-tools/parser | 1.0.11 | Apache-2.0 | [LICENSE](apps/app/notices/44b0a56e80b41a1b.txt) |
| @xterm/addon-fit | 0.11.0 | MIT | [LICENSE](apps/app/notices/e256f01188af527e.txt) |
| @xterm/addon-search | 0.16.0 | MIT | [LICENSE](apps/app/notices/689ceb10716bd7a8.txt) |
| @xterm/xterm | 6.0.0 | MIT | [LICENSE](apps/app/notices/b569f629d00f2626.txt) |
| @yr/monotone-cubic-spline | 1.0.3 | MIT | [LICENSE](apps/app/notices/fce0d6476ff220c9.txt) |
| @zip.js/zip.js | 2.8.34 | BSD-3-Clause | [LICENSE](apps/app/notices/1b7ebc8d7889ed25.txt) |
| abbrev | 2.0.0 | ISC | [LICENSE](apps/app/notices/9e0d5c7989f7e9f0.txt) |
| abbrev | 3.0.1 | ISC | [LICENSE](apps/app/notices/9e0d5c7989f7e9f0.txt) |
| abort-controller | 3.0.0 | MIT | [LICENSE](apps/app/notices/dbbf03317f0101fe.txt) |
| ace-builds | 1.43.6 | BSD-3-Clause | [LICENSE](apps/app/notices/850f545c5254e8c0.txt) |
| acorn | 7.4.1 | MIT | [LICENSE](apps/app/notices/cb3984acf8a000bc.txt) |
| acorn | 8.15.0 | MIT | [LICENSE](apps/app/notices/76a876cf886ff9be.txt) |
| acorn | 8.18.0 | MIT | [LICENSE](apps/app/notices/76a876cf886ff9be.txt) |
| acorn-import-attributes | 1.9.5 | MIT | [LICENSE](apps/app/notices/68d38391fb464a7f.txt) |
| acorn-jsx | 5.3.2 | MIT | [LICENSE](apps/app/notices/cfa72b62b9ae1730.txt) |
| agent-base | 6.0.2 | MIT |  |
| agent-base | 7.1.4 | MIT | [LICENSE](apps/app/notices/8d8c55319c7729d5.txt) |
| ajv | 6.12.6 | MIT | [LICENSE](apps/app/notices/e85e131fa4ed2553.txt) |
| ajv | 8.18.0 | MIT | [LICENSE](apps/app/notices/a05350a88e318e4f.txt) |
| ajv-draft-04 | 1.0.0 | MIT | [LICENSE](apps/app/notices/6e737548e1fc84ae.txt) |
| ajv-formats | 3.0.1 | MIT | [LICENSE](apps/app/notices/9df3bb69929a3b65.txt) |
| alien-signals | 1.0.13 | MIT | [LICENSE](apps/app/notices/75863f712f8f0603.txt) |
| alien-signals | 3.1.2 | MIT | [LICENSE](apps/app/notices/75863f712f8f0603.txt) |
| ansi-align | 3.0.1 | ISC | [LICENSE](apps/app/notices/852bf81203aa93aa.txt) |
| ansi-regex | 5.0.1 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| ansi-regex | 6.2.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| ansi-styles | 4.3.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| ansi-styles | 5.2.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| ansi-styles | 6.2.3 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| ansi-to-html | 0.7.2 | MIT | [LICENSE-MIT.txt](apps/app/notices/fae97f83563e6033.txt) |
| ansis | 4.4.0 | ISC | [LICENSE](apps/app/notices/d80713a740590fd0.txt) |
| any-promise | 1.3.0 | MIT | [LICENSE](apps/app/notices/bd54a6ab4e3ad0f7.txt) |
| anymatch | 3.1.3 | ISC | [LICENSE](apps/app/notices/5a3b0007c4203f10.txt) |
| apexcharts | 4.7.0 | MIT | [LICENSE](apps/app/notices/4db98d106f5a157d.txt) |
| archiver | 7.0.1 | MIT | [LICENSE](apps/app/notices/9e23899170d96e70.txt) |
| archiver-utils | 5.0.2 | MIT | [LICENSE](apps/app/notices/9fe335fb097fbff0.txt) |
| are-docs-informative | 0.0.2 | MIT | [LICENSE.md](apps/app/notices/76c9d5f5ea942054.txt) |
| arg | 5.0.2 | MIT | [LICENSE.md](apps/app/notices/91887c62d26f64b8.txt) |
| argparse | 1.0.10 | MIT | [LICENSE](apps/app/notices/c8442419dc614089.txt) |
| argparse | 2.0.1 | Python-2.0 | [LICENSE](apps/app/notices/de4d1f2d2ad5ad0c.txt) |
| aria-query | 5.3.0 | Apache-2.0 | [LICENSE](apps/app/notices/c8df456c7ccba74b.txt) |
| aria-query | 5.3.2 | Apache-2.0 | [LICENSE](apps/app/notices/c8df456c7ccba74b.txt) |
| array-iterate | 2.0.1 | MIT | [license](apps/app/notices/05811400116ed61f.txt) |
| asap | 2.0.6 | MIT | [LICENSE.md](apps/app/notices/e80373b1ed0f33ce.txt) |
| assert-never | 1.4.0 | MIT | [LICENSE](apps/app/notices/d11d1efc8124721d.txt) |
| assertion-error | 2.0.1 | MIT | [LICENSE](apps/app/notices/2130216d5ab4c021.txt) |
| ast-kit | 2.2.0 | MIT | [LICENSE](apps/app/notices/704c496aa9642217.txt) |
| ast-types | 0.16.1 | MIT | [LICENSE](apps/app/notices/a374b737c41b30b1.txt) |
| ast-walker-scope | 0.8.3 | MIT | [LICENSE](apps/app/notices/164fe042c92ff99f.txt) |
| astring | 1.9.0 | MIT | [LICENSE](apps/app/notices/d7e882d386050a13.txt) |
| astro | 5.17.1 | MIT | [LICENSE](apps/app/notices/4aa72be797aad0e5.txt) |
| astro-expressive-code | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| async | 3.2.6 | MIT | [LICENSE](apps/app/notices/d9fed24f13298593.txt) |
| async-sema | 3.1.1 | MIT | [license.md](apps/app/notices/bce93741cc2c519c.txt) |
| asynckit | 0.4.0 | MIT | [LICENSE](apps/app/notices/1953150d5d4b10c7.txt) |
| autoprefixer | 10.6.1 | MIT | [LICENSE](apps/app/notices/5be1f3465bba68a6.txt) |
| axe-core | 4.11.1 | MPL-2.0 | [LICENSE](apps/app/notices/af175b9d96ee93c2.txt), [LICENSE-3RD-PARTY.txt](apps/app/notices/4f8563870d0fca38.txt) |
| axios | 1.16.1 | MIT | [LICENSE](apps/app/notices/82761059eaedacb3.txt) |
| axobject-query | 4.1.0 | Apache-2.0 | [LICENSE](apps/app/notices/c8df456c7ccba74b.txt) |
| b4a | 1.7.3 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| babel-walk | 3.0.0-canary-5 | MIT | [LICENSE.md](apps/app/notices/4a388ace81f44d9c.txt) |
| bail | 2.0.2 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| balanced-match | 1.0.2 | MIT | [LICENSE.md](apps/app/notices/a1bd5deadb6a06dd.txt) |
| balanced-match | 4.0.4 | MIT | [LICENSE.md](apps/app/notices/d408f38ffa3355c5.txt) |
| bare-events | 2.8.2 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| base-64 | 1.0.0 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| base64-js | 1.5.1 | MIT | [LICENSE](apps/app/notices/5b37224c080cdcc9.txt) |
| baseline-browser-mapping | 2.11.27 | Apache-2.0 | [LICENSE.txt](apps/app/notices/c71d239df91726fc.txt) |
| baseline-browser-mapping | 2.9.19 | Apache-2.0 | [LICENSE.txt](apps/app/notices/c71d239df91726fc.txt) |
| bcp-47 | 2.1.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| bcp-47-match | 2.0.3 | MIT | [license](apps/app/notices/3deefaee9d13b2f5.txt) |
| binary-extensions | 2.3.0 | MIT | [license](apps/app/notices/96f0820026bd6dad.txt) |
| bindings | 1.5.0 | MIT | [LICENSE.md](apps/app/notices/85fde19744c84cfa.txt) |
| birpc | 2.9.0 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| birpc | 4.2.0 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| bl | 4.1.0 | MIT | [LICENSE.md](apps/app/notices/9377db95383c8bef.txt) |
| blake3-wasm | 2.1.5 | MIT | [LICENSE](apps/app/notices/6ae51be712bd278c.txt) |
| boolbase | 1.0.0 | ISC |  |
| boxen | 8.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| brace-expansion | 1.1.12 | MIT | [LICENSE](apps/app/notices/68f12f6e2c336886.txt) |
| brace-expansion | 2.0.2 | MIT | [LICENSE](apps/app/notices/68f12f6e2c336886.txt) |
| brace-expansion | 5.0.7 | MIT | [LICENSE](apps/app/notices/9c63a23124d68cd3.txt) |
| braces | 3.0.3 | MIT | [LICENSE](apps/app/notices/35bdd8a443397194.txt) |
| browserslist | 4.28.1 | MIT | [LICENSE](apps/app/notices/f25bf9bf3ae8984b.txt) |
| browserslist | 4.29.3 | MIT | [LICENSE](apps/app/notices/21c2679a63d7699c.txt) |
| buffer | 5.7.1 | MIT | [LICENSE](apps/app/notices/06bafa45fdad2579.txt) |
| buffer | 6.0.3 | MIT | [LICENSE](apps/app/notices/06bafa45fdad2579.txt) |
| buffer-crc32 | 1.0.0 | MIT | [LICENSE](apps/app/notices/ddc9158fa20e427b.txt) |
| buffer-from | 1.1.2 | MIT | [LICENSE](apps/app/notices/14275f5c8139d020.txt) |
| builtin-modules | 3.3.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| bundle-name | 4.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| c12 | 3.3.4 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| cac | 6.7.14 | MIT | [LICENSE](apps/app/notices/709131d7af352b81.txt) |
| cac | 7.0.0 | MIT | [LICENSE](apps/app/notices/709131d7af352b81.txt) |
| call-bind-apply-helpers | 1.0.2 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| call-bound | 1.0.4 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| call-me-maybe | 1.0.2 | MIT | [LICENSE](apps/app/notices/b179d2c6f886021a.txt) |
| callsites | 3.1.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| camel-case | 4.1.2 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| camelcase | 8.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| camelcase-css | 2.0.1 | MIT | [license](apps/app/notices/4c97d11c3d10dded.txt) |
| caniuse-api | 3.0.0 | MIT | [LICENSE](apps/app/notices/6dba40acdc8df5c9.txt) |
| caniuse-lite | 1.0.30001767 | CC-BY-4.0 | [LICENSE](apps/app/notices/fd3a263fe19ed8fa.txt) |
| caniuse-lite | 1.0.30001814 | CC-BY-4.0 | [LICENSE](apps/app/notices/fd3a263fe19ed8fa.txt) |
| canvas | 3.2.3 | MIT |  |
| ccount | 2.0.1 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| chai | 5.3.3 | MIT | [LICENSE](apps/app/notices/b181da80336ff9dd.txt) |
| chalk | 4.1.2 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| chalk | 5.6.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| character-entities | 2.0.2 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| character-entities-html4 | 2.1.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| character-entities-legacy | 3.0.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| character-parser | 2.2.0 | MIT | [LICENSE](apps/app/notices/9b95ff43defd6ae6.txt) |
| character-reference-invalid | 2.0.1 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| chart.js | 4.5.1 | MIT | [LICENSE.md](apps/app/notices/41a84aa2caba645f.txt) |
| check-error | 2.1.3 | MIT | [LICENSE](apps/app/notices/e5aee0714b6ecc41.txt) |
| chevrotain | 7.1.1 | Apache-2.0 | [LICENSE.txt](apps/app/notices/cfc7749b96f63bd3.txt) |
| chokidar | 3.6.0 | MIT | [LICENSE](apps/app/notices/db9ba183d4cbfbaf.txt) |
| chokidar | 4.0.3 | MIT | [LICENSE](apps/app/notices/bdfd5e0edb6089e6.txt) |
| chokidar | 5.0.0 | MIT | [LICENSE](apps/app/notices/bdfd5e0edb6089e6.txt) |
| chownr | 1.1.4 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| chownr | 3.0.0 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/a49c9ba464796f65.txt) |
| ci-info | 4.4.0 | MIT | [LICENSE](apps/app/notices/f58943cb354fb270.txt) |
| citty | 0.1.6 | MIT | [LICENSE](apps/app/notices/8c342219f3330894.txt) |
| citty | 0.2.2 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| clean-css | 5.3.3 | MIT | [LICENSE](apps/app/notices/7b43b9a905703305.txt) |
| clean-regexp | 1.0.0 | MIT | [license](apps/app/notices/3d3fba5375126ff3.txt) |
| cli-boxes | 3.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| cliui | 8.0.1 | ISC | [LICENSE.txt](apps/app/notices/2dc0465729366c3a.txt) |
| cliui | 9.0.1 | ISC | [LICENSE.txt](apps/app/notices/2dc0465729366c3a.txt) |
| clsx | 2.1.1 | MIT | [license](apps/app/notices/9a9edad7baae5262.txt) |
| cluster-key-slot | 1.1.1 | Apache-2.0 | [LICENSE](apps/app/notices/0ea1dc735df3fd3f.txt) |
| collapse-white-space | 2.1.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| color | 4.2.3 | MIT | [LICENSE](apps/app/notices/4c0844caafd3db9a.txt) |
| color-convert | 2.0.1 | MIT | [LICENSE](apps/app/notices/693866fc419c6f61.txt) |
| color-name | 1.1.4 | MIT | [LICENSE](apps/app/notices/c064f7a3e353bc1b.txt) |
| color-string | 1.9.1 | MIT | [LICENSE](apps/app/notices/8984783ab2478bbe.txt) |
| colord | 2.9.3 | MIT | [LICENSE.md](apps/app/notices/7613d4594ee8b616.txt) |
| combined-stream | 1.0.8 | MIT | [License](apps/app/notices/47eb8ca82c798246.txt) |
| comma-separated-tokens | 2.0.3 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| commander | 10.0.1 | MIT | [LICENSE](apps/app/notices/04512a63dce4d2d5.txt) |
| commander | 11.1.0 | MIT | [LICENSE](apps/app/notices/04512a63dce4d2d5.txt) |
| commander | 2.20.3 | MIT | [LICENSE](apps/app/notices/04512a63dce4d2d5.txt) |
| commander | 4.1.1 | MIT | [LICENSE](apps/app/notices/04512a63dce4d2d5.txt) |
| commander | 7.2.0 | MIT | [LICENSE](apps/app/notices/04512a63dce4d2d5.txt) |
| comment-parser | 1.4.1 | MIT | [LICENSE](apps/app/notices/1de040b1722b3816.txt) |
| comment-parser | 1.4.5 | MIT | [LICENSE](apps/app/notices/1de040b1722b3816.txt) |
| common-ancestor-path | 1.0.1 | ISC | [LICENSE](apps/app/notices/05dc4d785ac3a488.txt) |
| commondir | 1.0.1 | MIT | [LICENSE](apps/app/notices/8bb16db1b047019e.txt) |
| compare-versions | 6.1.1 | MIT | [LICENSE](apps/app/notices/4c247e0dce60c6a2.txt) |
| compatx | 0.2.0 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| compress-commons | 6.0.2 | MIT | [LICENSE](apps/app/notices/79bad9f51738814f.txt) |
| concat-map | 0.0.1 | MIT | [LICENSE](apps/app/notices/435a6722c786b0a5.txt) |
| confbox | 0.1.8 | MIT | [LICENSE](apps/app/notices/2b2bbe4244586c06.txt) |
| confbox | 0.2.2 | MIT | [LICENSE](apps/app/notices/b745584e685e10a0.txt) |
| confbox | 0.2.4 | MIT | [LICENSE](apps/app/notices/c6e83b9be7af3b90.txt) |
| confbox | 0.3.1 | MIT | [LICENSE](apps/app/notices/c6e83b9be7af3b90.txt) |
| config-chain | 1.1.13 | MIT | [LICENCE](apps/app/notices/8937affb1fac8425.txt) |
| consola | 3.4.2 | MIT | [LICENSE](apps/app/notices/df0e3cef4a42bae7.txt) |
| constantinople | 4.0.1 | MIT | [LICENSE](apps/app/notices/e21b0992cd8a2e8b.txt) |
| convert-source-map | 2.0.0 | MIT | [LICENSE](apps/app/notices/1fa6ee8bb95a81ae.txt) |
| cookie | 1.1.1 | MIT | [LICENSE](apps/app/notices/c02110eedc16c711.txt) |
| cookie-es | 1.2.2 | MIT | [LICENSE](apps/app/notices/f57270b85c392241.txt) |
| cookie-es | 1.2.3 | MIT | [LICENSE](apps/app/notices/f57270b85c392241.txt) |
| cookie-es | 2.0.1 | MIT | [LICENSE](apps/app/notices/f57270b85c392241.txt) |
| cookie-es | 3.1.1 | MIT | [LICENSE](apps/app/notices/f57270b85c392241.txt) |
| core-js-compat | 3.48.0 | MIT | [LICENSE](apps/app/notices/b87653fff2d44426.txt) |
| core-util-is | 1.0.3 | MIT | [LICENSE](apps/app/notices/33b734d60042d0fe.txt) |
| crc-32 | 1.2.2 | Apache-2.0 | [LICENSE](apps/app/notices/c542ba7851b5d39a.txt) |
| crc32-stream | 6.0.0 | MIT | [LICENSE](apps/app/notices/79bad9f51738814f.txt) |
| crelt | 1.0.6 | MIT | [LICENSE](apps/app/notices/23852ebf6aef7fad.txt) |
| croner | 10.0.1 | MIT | [LICENSE](apps/app/notices/d1c89d2de9ab5785.txt) |
| cross-spawn | 7.0.6 | MIT | [LICENSE](apps/app/notices/aaa78451b6fecd1b.txt) |
| crossws | 0.3.5 | MIT | [LICENSE](apps/app/notices/7aef9ff475a591e0.txt) |
| crossws | 0.4.12 | MIT | [LICENSE](apps/app/notices/7aef9ff475a591e0.txt) |
| css-declaration-sorter | 7.3.1 | ISC | [license.md](apps/app/notices/856056b95b052cd0.txt) |
| css-select | 5.2.2 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| css-select | 6.0.0 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| css-selector-parser | 3.3.0 | MIT | [LICENSE](apps/app/notices/f8bcf3c7ea910a26.txt) |
| css-tree | 2.2.1 | MIT | [LICENSE](apps/app/notices/be1fdbf86bfd2c72.txt) |
| css-tree | 2.3.1 | MIT | [LICENSE](apps/app/notices/be1fdbf86bfd2c72.txt) |
| css-tree | 3.1.0 | MIT | [LICENSE](apps/app/notices/a7d4ce7343a169d6.txt) |
| css-what | 6.2.2 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| css-what | 7.0.0 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| css.escape | 1.5.1 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| cssesc | 3.0.0 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| cssfilter | 0.0.10 | MIT | [LICENSE](apps/app/notices/6b16a2f12f0ebe66.txt) |
| cssnano | 7.1.9 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| cssnano-preset-default | 7.0.17 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| cssnano-utils | 5.0.3 | MIT | [LICENSE](apps/app/notices/2998094b38f7ace2.txt) |
| csso | 5.0.5 | MIT | [LICENSE](apps/app/notices/911677be83816200.txt) |
| cssstyle | 4.6.0 | MIT | [LICENSE](apps/app/notices/768faff9f6908c78.txt) |
| csstype | 3.2.3 | MIT | [LICENSE](apps/app/notices/11d55bd4541c75ee.txt) |
| data-urls | 5.0.0 | MIT | [LICENSE.txt](apps/app/notices/528eec83cb836a0a.txt) |
| dayjs | 1.11.19 | MIT | [LICENSE](apps/app/notices/5faab7526d055651.txt) |
| db0 | 0.3.4 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| de-indent | 1.0.2 | MIT |  |
| debounce | 1.2.1 | MIT | [LICENSE](apps/app/notices/87c2f96d275cd4fb.txt) |
| debug | 4.4.3 | MIT | [LICENSE](apps/app/notices/3a61c6c96caf5c1d.txt) |
| decimal.js | 10.6.0 | MIT | [LICENCE.md](apps/app/notices/3108b546bcff5d34.txt) |
| decode-named-character-reference | 1.3.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| decompress-response | 6.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| deep-eql | 5.0.2 | MIT | [LICENSE](apps/app/notices/e5aee0714b6ecc41.txt) |
| deep-extend | 0.6.0 | MIT | [LICENSE](apps/app/notices/e17120ad3deff741.txt) |
| deep-is | 0.1.4 | MIT | [LICENSE](apps/app/notices/f2042f3634c4136d.txt) |
| deepmerge | 4.3.1 | MIT | [license.txt](apps/app/notices/6cfc4687cb2f2d86.txt) |
| default-browser | 5.5.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| default-browser | 5.5.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| default-browser-id | 5.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| define-lazy-prop | 2.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| define-lazy-prop | 3.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| defu | 6.1.4 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| defu | 6.1.7 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| delayed-stream | 1.0.0 | MIT | [License](apps/app/notices/47eb8ca82c798246.txt) |
| denque | 2.1.0 | Apache-2.0 | [LICENSE](apps/app/notices/cd9809cec53323a3.txt) |
| depd | 2.0.0 | MIT | [LICENSE](apps/app/notices/bd134b41da59e452.txt) |
| dequal | 2.0.3 | MIT | [license](apps/app/notices/306fa513e39b23a6.txt) |
| destr | 2.0.5 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| detect-libc | 2.1.2 | Apache-2.0 | [LICENSE](apps/app/notices/b40930bbcf80744c.txt) |
| deterministic-object-hash | 2.0.2 | MIT | [LICENSE](apps/app/notices/2a5be161c4e6e740.txt) |
| devalue | 5.6.2 | MIT | [LICENSE](apps/app/notices/e399db7e952e45ca.txt) |
| devalue | 5.9.4 | MIT | [LICENSE](apps/app/notices/e399db7e952e45ca.txt) |
| devlop | 1.1.0 | MIT | [license](apps/app/notices/6f296a5eccc1dc96.txt) |
| didyoumean | 1.2.2 | Apache-2.0 | [LICENSE](apps/app/notices/614a7a948ca1b4fa.txt) |
| diff | 8.0.3 | BSD-3-Clause | [LICENSE](apps/app/notices/eda81a415869e678.txt) |
| diff | 8.0.4 | BSD-3-Clause | [LICENSE](apps/app/notices/eda81a415869e678.txt) |
| direction | 2.0.1 | MIT | [license](apps/app/notices/9966260ba3ea9d6a.txt) |
| dlv | 1.1.3 | MIT |  |
| dockview | 8.2.0 | MIT | [LICENCE.md](apps/app/notices/1d56757fdc06c9b3.txt) |
| dockview-core | 8.2.0 | MIT | [LICENCE.md](apps/app/notices/1d56757fdc06c9b3.txt) |
| dockview-vue | 8.2.0 | MIT | [LICENCE.md](apps/app/notices/1d56757fdc06c9b3.txt) |
| doctypes | 1.1.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| dom-accessibility-api | 0.5.16 | MIT | [LICENSE.md](apps/app/notices/0ffe67fe630169de.txt) |
| dom-accessibility-api | 0.6.3 | MIT | [LICENSE.md](apps/app/notices/0ffe67fe630169de.txt) |
| dom-serializer | 2.0.0 | MIT | [LICENSE](apps/app/notices/94cfe87de9b178e8.txt) |
| domelementtype | 2.3.0 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| domhandler | 5.0.3 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| dompurify | 3.3.1 | (MPL-2.0 OR Apache-2.0) | [LICENSE](apps/app/notices/1b02e03c3fb4f87d.txt) |
| domutils | 3.2.2 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| dot-case | 3.0.4 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| dot-prop | 10.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| dotenv | 16.0.3 | BSD-2-Clause | [LICENSE](apps/app/notices/74b629b24865e1e8.txt) |
| dotenv | 17.4.2 | BSD-2-Clause | [LICENSE](apps/app/notices/74b629b24865e1e8.txt) |
| dset | 3.1.4 | MIT | [license](apps/app/notices/306fa513e39b23a6.txt) |
| dunder-proto | 1.0.1 | MIT | [LICENSE](apps/app/notices/2b770a704c15de23.txt) |
| duplexer | 0.1.2 | MIT | [LICENCE](apps/app/notices/19338d17a974d1c7.txt) |
| eastasianwidth | 0.2.0 | MIT |  |
| editorconfig | 1.0.4 | MIT | [LICENSE](apps/app/notices/bc6944d7fe185cc5.txt) |
| ee-first | 1.1.1 | MIT | [LICENSE](apps/app/notices/965ef284f7f4c176.txt) |
| electron-to-chromium | 1.5.286 | ISC | [LICENSE](apps/app/notices/25ba5c59dad3e0dd.txt) |
| electron-to-chromium | 1.5.443 | ISC | [LICENSE](apps/app/notices/25ba5c59dad3e0dd.txt) |
| emmet | 2.4.11 | MIT | [LICENSE](apps/app/notices/72dd5a0ed7d2d2fd.txt) |
| emoji-regex | 10.6.0 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| emoji-regex | 8.0.0 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| emoji-regex | 9.2.2 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| emoji-regex-xs | 1.0.0 | MIT | [LICENSE](apps/app/notices/8ca7af4f6c753e5a.txt) |
| encodeurl | 2.0.0 | MIT | [LICENSE](apps/app/notices/7585ea7bba616ccb.txt) |
| end-of-stream | 1.4.5 | MIT | [LICENSE](apps/app/notices/3fe8d55a98dbf260.txt) |
| enhanced-resolve | 5.19.0 | MIT | [LICENSE](apps/app/notices/9068a8782d2fb4c6.txt) |
| entities | 2.2.0 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| entities | 3.0.1 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| entities | 4.5.0 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| entities | 6.0.1 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| entities | 7.0.1 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| error-ex | 1.3.4 | MIT | [LICENSE](apps/app/notices/92b07a2e5b0e051d.txt) |
| error-stack-parser-es | 1.0.5 | MIT | [LICENSE](apps/app/notices/fe99ed9e40901449.txt) |
| error-stack-parser-es | 2.0.1 | MIT | [LICENSE](apps/app/notices/fe99ed9e40901449.txt) |
| errx | 0.1.2 | MIT | [LICENCE](apps/app/notices/a174fd5d58dfec7a.txt) |
| es-define-property | 1.0.1 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| es-errors | 1.3.0 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| es-module-lexer | 1.7.0 | MIT | [LICENSE](apps/app/notices/fecc38b5e10d8896.txt) |
| es-module-lexer | 2.0.0 | MIT | [LICENSE](apps/app/notices/fecc38b5e10d8896.txt) |
| es-object-atoms | 1.1.1 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| es-set-tostringtag | 2.1.0 | MIT | [LICENSE](apps/app/notices/1a3aeb1f1398bd69.txt) |
| es-toolkit | 1.44.0 | MIT | [LICENSE](apps/app/notices/ed68888a2a28f32a.txt) |
| esast-util-from-estree | 2.0.0 | MIT | [license](apps/app/notices/807a88522a850092.txt) |
| esast-util-from-js | 2.0.1 | MIT | [license](apps/app/notices/e620971c29d750df.txt) |
| esbuild | 0.21.5 | MIT | [LICENSE.md](apps/app/notices/b40ec5baec7bb34f.txt) |
| esbuild | 0.25.12 | MIT | [LICENSE.md](apps/app/notices/b40ec5baec7bb34f.txt) |
| esbuild | 0.27.2 | MIT | [LICENSE.md](apps/app/notices/b40ec5baec7bb34f.txt) |
| esbuild | 0.28.1 | MIT | [LICENSE.md](apps/app/notices/b40ec5baec7bb34f.txt) |
| escalade | 3.2.0 | MIT | [license](apps/app/notices/9a9edad7baae5262.txt) |
| escape-html | 1.0.3 | MIT | [LICENSE](apps/app/notices/255aa557a1f55224.txt) |
| escape-string-regexp | 1.0.5 | MIT | [license](apps/app/notices/6fb9754611c20f66.txt) |
| escape-string-regexp | 4.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| escape-string-regexp | 5.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| eslint | 9.39.2 | MIT | [LICENSE](apps/app/notices/3b6be04f862a077a.txt) |
| eslint-config-flat-gitignore | 0.3.0 | MIT | [LICENSE](apps/app/notices/af32efdd008a371c.txt) |
| eslint-config-prettier | 10.1.8 | MIT | [LICENSE](apps/app/notices/607754a0e9fd7166.txt) |
| eslint-flat-config-utils | 0.4.0 | MIT | [LICENSE](apps/app/notices/af32efdd008a371c.txt) |
| eslint-import-context | 0.1.9 | MIT | [LICENSE](apps/app/notices/6b2ba6ac4aa455c1.txt) |
| eslint-plugin-import-x | 4.16.1 | MIT | [LICENSE](apps/app/notices/7829efc4266fad5f.txt) |
| eslint-plugin-jsdoc | 50.8.0 | BSD-3-Clause | [LICENSE](apps/app/notices/37b6932865726cf5.txt) |
| eslint-plugin-prettier | 5.5.5 | MIT | [LICENSE.md](apps/app/notices/20e80c18f6f0a93b.txt) |
| eslint-plugin-regexp | 2.10.0 | MIT | [LICENSE](apps/app/notices/23724e00c4527ece.txt) |
| eslint-plugin-simple-import-sort | 12.1.1 | MIT | [LICENSE](apps/app/notices/49aa9150885ec7b2.txt) |
| eslint-plugin-storybook | 10.2.4 | MIT | [LICENSE](apps/app/notices/cd498eccb06619b3.txt) |
| eslint-plugin-turbo | 2.8.2 | MIT | [LICENSE](apps/app/notices/f7ac4712aa30551d.txt) |
| eslint-plugin-unicorn | 55.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| eslint-plugin-vue | 10.7.0 | MIT | [LICENSE](apps/app/notices/dbbf03317f0101fe.txt) |
| eslint-plugin-vue | 9.33.0 | MIT | [LICENSE](apps/app/notices/dbbf03317f0101fe.txt) |
| eslint-scope | 7.2.2 | BSD-2-Clause | [LICENSE](apps/app/notices/d3a724e2ed749f17.txt) |
| eslint-scope | 8.4.0 | BSD-2-Clause | [LICENSE](apps/app/notices/d3a724e2ed749f17.txt) |
| eslint-visitor-keys | 3.4.3 | Apache-2.0 | [LICENSE](apps/app/notices/d8bf34ff6d190640.txt) |
| eslint-visitor-keys | 4.2.1 | Apache-2.0 | [LICENSE](apps/app/notices/d8bf34ff6d190640.txt) |
| eslint-visitor-keys | 5.0.1 | Apache-2.0 | [LICENSE](apps/app/notices/d8bf34ff6d190640.txt) |
| esm-resolve | 1.0.11 | Apache-2.0 | [LICENSE](apps/app/notices/b40930bbcf80744c.txt) |
| espree | 10.4.0 | BSD-2-Clause | [LICENSE](apps/app/notices/26c95937762a3dc1.txt) |
| espree | 9.6.1 | BSD-2-Clause | [LICENSE](apps/app/notices/26c95937762a3dc1.txt) |
| esprima | 4.0.1 | BSD-2-Clause | [LICENSE.BSD](apps/app/notices/94bcb9959136723a.txt) |
| esquery | 1.7.0 | BSD-3-Clause | [license.txt](apps/app/notices/ac68116ae73740de.txt) |
| esrecurse | 4.3.0 | BSD-2-Clause |  |
| estraverse | 5.3.0 | BSD-2-Clause | [LICENSE.BSD](apps/app/notices/0e74697a68cebdcd.txt) |
| estree-util-attach-comments | 3.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| estree-util-build-jsx | 3.0.1 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| estree-util-is-identifier-name | 3.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| estree-util-scope | 1.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| estree-util-to-js | 2.0.0 | MIT | [license](apps/app/notices/e620971c29d750df.txt) |
| estree-util-visit | 2.0.0 | MIT | [license](apps/app/notices/807a88522a850092.txt) |
| estree-walker | 2.0.2 | MIT | [LICENSE](apps/app/notices/8a6dcbabe7179f9c.txt) |
| estree-walker | 3.0.3 | MIT | [LICENSE](apps/app/notices/8a6dcbabe7179f9c.txt) |
| esutils | 2.0.3 | BSD-2-Clause | [LICENSE.BSD](apps/app/notices/0e74697a68cebdcd.txt) |
| etag | 1.8.1 | MIT | [LICENSE](apps/app/notices/a7996721249a136f.txt) |
| event-target-shim | 5.0.1 | MIT | [LICENSE](apps/app/notices/97d87142793695cd.txt) |
| eventemitter3 | 5.0.4 | MIT | [LICENSE](apps/app/notices/3aecc12b1cb28832.txt) |
| events | 3.3.0 | MIT | [LICENSE](apps/app/notices/631987b7616a325a.txt) |
| events-universal | 1.0.1 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| execa | 8.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| expand-template | 2.0.3 | (MIT OR WTFPL) | [LICENSE](apps/app/notices/0967624813244bf4.txt) |
| expressive-code | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| exsolve | 1.0.8 | MIT | [LICENSE](apps/app/notices/d37af134e0d0b998.txt) |
| exsolve | 1.1.1 | MIT | [LICENSE](apps/app/notices/d37af134e0d0b998.txt) |
| extend | 3.0.2 | MIT | [LICENSE](apps/app/notices/97af7428f93afbab.txt) |
| extend-shallow | 2.0.1 | MIT | [LICENSE](apps/app/notices/daca23d50b0f54d3.txt) |
| externality | 1.0.2 | MIT | [LICENSE](apps/app/notices/c638918c6f664dec.txt) |
| fabric | 7.4.0 | MIT | [LICENSE](apps/app/notices/eda412692b739829.txt) |
| fast-deep-equal | 3.1.3 | MIT | [LICENSE](apps/app/notices/7bf9b2de73a6b356.txt) |
| fast-diff | 1.3.0 | Apache-2.0 | [LICENSE](apps/app/notices/20430d7ea026abdb.txt) |
| fast-fifo | 1.3.2 | MIT | [LICENSE](apps/app/notices/41a2aa55a9ebad3d.txt) |
| fast-glob | 3.3.3 | MIT | [LICENSE](apps/app/notices/9363d160bf41d46d.txt) |
| fast-json-stable-stringify | 2.1.0 | MIT | [LICENSE](apps/app/notices/a833d366242c298c.txt) |
| fast-levenshtein | 2.0.6 | MIT | [LICENSE.md](apps/app/notices/942a98cb8846a635.txt) |
| fast-npm-meta | 2.2.0 | MIT | [LICENSE](apps/app/notices/af32efdd008a371c.txt) |
| fast-string-truncated-width | 3.0.3 | MIT | [license](apps/app/notices/2547dead17a32b1e.txt) |
| fast-string-width | 3.0.2 | MIT | [license](apps/app/notices/2547dead17a32b1e.txt) |
| fast-uri | 3.1.0 | BSD-3-Clause | [LICENSE](apps/app/notices/185ef4f377743572.txt) |
| fast-wrap-ansi | 0.2.2 | MIT | [LICENSE](apps/app/notices/9235f5ebfd80d419.txt) |
| fastq | 1.20.1 | ISC | [LICENSE](apps/app/notices/c3367f6d01a79d36.txt) |
| fdir | 6.5.0 | MIT | [LICENSE](apps/app/notices/9a39f2aadab11a36.txt) |
| fflate | 0.8.2 | MIT | [LICENSE](apps/app/notices/805f6cb28bb8b6d3.txt) |
| file-entry-cache | 8.0.0 | MIT | [LICENSE](apps/app/notices/a0e2f73971f663b4.txt) |
| file-uri-to-path | 1.0.0 | MIT | [LICENSE](apps/app/notices/75070206e4ee2a74.txt) |
| fill-range | 7.1.1 | MIT | [LICENSE](apps/app/notices/35bdd8a443397194.txt) |
| find-up | 4.1.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| find-up | 5.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| find-up-simple | 1.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| flat-cache | 4.0.1 | MIT | [LICENSE](apps/app/notices/a6a23fb76d91d986.txt) |
| flatpickr | 4.6.13 | MIT | [LICENSE.md](apps/app/notices/5fd57afc39056511.txt) |
| flatted | 3.3.3 | ISC | [LICENSE](apps/app/notices/148718606d34f467.txt) |
| flattie | 1.1.1 | MIT | [license](apps/app/notices/306fa513e39b23a6.txt) |
| follow-redirects | 1.16.0 | MIT | [LICENSE](apps/app/notices/bfa8a54bb952ccda.txt) |
| fontace | 0.4.1 | MIT | [LICENSE](apps/app/notices/04796fd226d26cbc.txt) |
| fontkitten | 1.0.2 | MIT | [LICENSE](apps/app/notices/e626e38b2081908f.txt) |
| foreground-child | 3.3.1 | ISC | [LICENSE](apps/app/notices/93f5d82a8d59442f.txt) |
| form-data | 4.0.5 | MIT | [License](apps/app/notices/e5b780d4f38d1d33.txt) |
| fraction.js | 5.3.4 | MIT | [LICENSE](apps/app/notices/ea6916b674c353de.txt) |
| framer-motion | 12.38.0 | MIT | [LICENSE.md](apps/app/notices/5ff46083b8856382.txt) |
| fresh | 2.0.0 | MIT | [LICENSE](apps/app/notices/a0ec0dab16b3666f.txt) |
| fs-constants | 1.0.0 | MIT | [LICENSE](apps/app/notices/2281f2db407bdbb5.txt) |
| fs-extra | 11.3.6 | MIT | [LICENSE](apps/app/notices/c6a7de1428955aa5.txt) |
| function-bind | 1.1.2 | MIT | [LICENSE](apps/app/notices/773e131a76847260.txt) |
| fuse.js | 6.6.2 | Apache-2.0 | [LICENSE](apps/app/notices/cc807e3caa26cdee.txt) |
| fuse.js | 7.5.0 | Apache-2.0 | [LICENSE](apps/app/notices/cc807e3caa26cdee.txt) |
| fzf | 0.5.2 | BSD-3-Clause | [license.txt](apps/app/notices/2097f666f88f859e.txt) |
| gensync | 1.0.0-beta.2 | MIT | [LICENSE](apps/app/notices/e3a956681ee067f9.txt) |
| get-caller-file | 2.0.5 | ISC | [LICENSE.md](apps/app/notices/902dbb4154679fb2.txt) |
| get-east-asian-width | 1.4.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| get-east-asian-width | 1.7.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| get-intrinsic | 1.3.0 | MIT | [LICENSE](apps/app/notices/39c5ec504cf6bd5c.txt) |
| get-port-please | 3.2.0 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| get-proto | 1.0.1 | MIT | [LICENSE](apps/app/notices/be46ce1e3b0479af.txt) |
| get-stream | 8.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| get-tsconfig | 4.13.1 | MIT | [LICENSE](apps/app/notices/10c904a49af44409.txt) |
| giget | 3.3.1 | MIT | [LICENSE](apps/app/notices/858a63872e40ca76.txt) |
| github-from-package | 0.0.0 | MIT | [LICENSE](apps/app/notices/435a6722c786b0a5.txt) |
| github-slugger | 2.0.0 | ISC | [LICENSE](apps/app/notices/542aefa994568329.txt) |
| glob | 10.5.0 | ISC | [LICENSE](apps/app/notices/cdbc258d13806538.txt) |
| glob | 13.0.1 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/a49c9ba464796f65.txt) |
| glob-parent | 5.1.2 | ISC | [LICENSE](apps/app/notices/2c46f1325bd3822a.txt) |
| glob-parent | 6.0.2 | ISC | [LICENSE](apps/app/notices/fc68eb8f1c8e1d6b.txt) |
| global-directory | 4.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| globals | 13.24.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| globals | 14.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| globals | 15.15.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| globals | 16.5.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| globby | 16.2.4 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| gopd | 1.2.0 | MIT | [LICENSE](apps/app/notices/d90bf0a089da4cf4.txt) |
| graceful-fs | 4.2.11 | ISC | [LICENSE](apps/app/notices/f65c5d9f22a317b2.txt) |
| gray-matter | 4.0.3 | MIT | [LICENSE](apps/app/notices/e70ff771504ba41f.txt) |
| gzip-size | 7.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| h3 | 1.15.11 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| h3 | 1.15.5 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| has-flag | 4.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| has-symbols | 1.1.0 | MIT | [LICENSE](apps/app/notices/206c1adcf206dc00.txt) |
| has-tostringtag | 1.0.2 | MIT | [LICENSE](apps/app/notices/e2560e002e132815.txt) |
| hash-sum | 2.0.0 | MIT | [license](apps/app/notices/8e07dd904e9341d5.txt) |
| hasown | 2.0.2 | MIT | [LICENSE](apps/app/notices/bf9b0d665be2a689.txt) |
| hast-util-embedded | 3.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| hast-util-format | 1.1.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-from-html | 2.0.3 | MIT | [license](apps/app/notices/e620971c29d750df.txt) |
| hast-util-from-parse5 | 8.0.3 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-has-property | 3.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| hast-util-is-body-ok-link | 3.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| hast-util-is-element | 3.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| hast-util-minify-whitespace | 1.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| hast-util-parse-selector | 4.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| hast-util-phrasing | 3.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| hast-util-raw | 9.1.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-select | 6.0.4 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-to-estree | 3.1.3 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-to-html | 9.0.5 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-to-jsx-runtime | 2.3.6 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-to-parse5 | 8.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| hast-util-to-string | 3.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| hast-util-to-text | 4.0.2 | MIT | [license](apps/app/notices/691115fe0234b1f0.txt) |
| hast-util-whitespace | 3.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| hastscript | 9.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| he | 1.2.0 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| hey-listen | 1.0.8 | MIT | [LICENSE](apps/app/notices/770141e45620e899.txt) |
| highgain | 0.1.0 | ISC |  |
| highlight.js | 11.11.1 | BSD-3-Clause | [LICENSE](apps/app/notices/6c081431591d9df6.txt) |
| highlightjs-mcfunction | 1.0.0 | MIT | [LICENSE](apps/app/notices/9e2e038effde595f.txt) |
| hookable | 5.5.3 | MIT | [LICENSE.md](apps/app/notices/3555f8c47cbff86d.txt) |
| hookable | 6.1.2 | MIT | [LICENSE.md](apps/app/notices/3555f8c47cbff86d.txt) |
| hosted-git-info | 2.8.9 | ISC | [LICENSE](apps/app/notices/c1476ec53119cd4c.txt) |
| html-encoding-sniffer | 4.0.0 | MIT | [LICENSE.txt](apps/app/notices/528eec83cb836a0a.txt) |
| html-escaper | 3.0.3 | MIT | [LICENSE.txt](apps/app/notices/27d06bbb2eb031be.txt) |
| html-minifier-terser | 7.2.0 | MIT | [LICENSE](apps/app/notices/20cc01510a65e1d0.txt) |
| html-to-text | 9.0.5 | MIT | [LICENSE](apps/app/notices/a5d0cbcaf58a469f.txt) |
| html-void-elements | 3.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| html-whitespace-sensitive-tag-names | 3.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| htmlparser2 | 8.0.2 | MIT | [LICENSE](apps/app/notices/204cfa747341660e.txt) |
| http-cache-semantics | 4.2.0 | BSD-2-Clause | [LICENSE](apps/app/notices/ab868ad5a2ef5068.txt) |
| http-errors | 2.0.1 | MIT | [LICENSE](apps/app/notices/dcb94ff9b1e037a8.txt) |
| http-proxy-agent | 7.0.2 | MIT | [LICENSE](apps/app/notices/71368fd0f5b41291.txt) |
| http-shutdown | 1.2.2 | MIT | [LICENSE](apps/app/notices/db0bf2d637229fb4.txt) |
| https-proxy-agent | 5.0.1 | MIT |  |
| https-proxy-agent | 7.0.6 | MIT | [LICENSE](apps/app/notices/8d8c55319c7729d5.txt) |
| httpxy | 0.5.5 | MIT | [LICENSE](apps/app/notices/4249bd020d1b5c50.txt) |
| human-signals | 5.0.0 | Apache-2.0 | [LICENSE](apps/app/notices/d82dccd4a42e5a02.txt) |
| i18next | 23.16.8 | MIT | [LICENSE](apps/app/notices/c83b2035d5a4740f.txt) |
| iconv-lite | 0.6.3 | MIT | [LICENSE](apps/app/notices/ac779f7314c74f23.txt) |
| ieee754 | 1.2.1 | BSD-3-Clause | [LICENSE](apps/app/notices/18d45466ba3253de.txt) |
| ignore | 5.3.2 | MIT | [LICENSE-MIT](apps/app/notices/9c94db23dc4b1e9a.txt) |
| ignore | 7.0.11 | MIT | [LICENSE-MIT](apps/app/notices/9c94db23dc4b1e9a.txt) |
| ignore | 7.0.5 | MIT | [LICENSE-MIT](apps/app/notices/9c94db23dc4b1e9a.txt) |
| image-meta | 0.2.2 | MIT | [LICENSE](apps/app/notices/0c5a0a0853f1fc42.txt) |
| immediate | 3.0.6 | MIT | [LICENSE.txt](apps/app/notices/809e66de579fb7d9.txt) |
| immutable | 5.1.4 | MIT | [LICENSE](apps/app/notices/784fd7232e106901.txt) |
| import-fresh | 3.3.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| import-lazy | 4.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| import-meta-resolve | 4.2.0 | MIT | [license](apps/app/notices/8770a1a4b69ee722.txt) |
| impound | 1.2.0 | MIT | [LICENCE](apps/app/notices/a174fd5d58dfec7a.txt) |
| imurmurhash | 0.1.4 | MIT |  |
| indent-string | 4.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| inherits | 2.0.4 | ISC | [LICENSE](apps/app/notices/5ffe28e7ade7d8f1.txt) |
| ini | 1.3.8 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| ini | 4.1.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| ini | 6.0.0 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| inline-style-parser | 0.2.7 | MIT | [LICENSE](apps/app/notices/395c95f20598da65.txt) |
| intl-messageformat | 10.7.18 | BSD-3-Clause | [LICENSE.md](apps/app/notices/cc4143615b27c66e.txt) |
| intl-messageformat | 10.7.7 | BSD-3-Clause | [LICENSE.md](apps/app/notices/cc4143615b27c66e.txt) |
| ioredis | 5.11.1 | MIT | [LICENSE](apps/app/notices/7c1ed12e0891c08e.txt) |
| iron-webcrypto | 1.2.1 | MIT | [LICENSE.md](apps/app/notices/1b191ca798543815.txt) |
| is-alphabetical | 2.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| is-alphanumerical | 2.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| is-arrayish | 0.2.1 | MIT | [LICENSE](apps/app/notices/92b07a2e5b0e051d.txt) |
| is-arrayish | 0.3.4 | MIT | [LICENSE](apps/app/notices/92b07a2e5b0e051d.txt) |
| is-binary-path | 2.1.0 | MIT | [license](apps/app/notices/85fe65eefab89e2a.txt) |
| is-builtin-module | 3.2.1 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| is-core-module | 2.16.1 | MIT | [LICENSE](apps/app/notices/5c496ce5ae47eb8e.txt) |
| is-decimal | 2.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| is-docker | 2.2.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-docker | 3.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-expression | 4.0.0 | MIT | [LICENSE.md](apps/app/notices/75cc7144f2e5c789.txt) |
| is-extendable | 0.1.1 | MIT | [LICENSE](apps/app/notices/0798f37cff4a3f43.txt) |
| is-extglob | 2.1.1 | MIT | [LICENSE](apps/app/notices/73b5283588baa142.txt) |
| is-fullwidth-code-point | 3.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| is-glob | 4.0.3 | MIT | [LICENSE](apps/app/notices/4cd903859549d4b2.txt) |
| is-hexadecimal | 2.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| is-in-ssh | 1.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-inside-container | 1.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-installed-globally | 1.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-module | 1.0.0 | MIT |  |
| is-number | 7.0.0 | MIT | [LICENSE](apps/app/notices/35bdd8a443397194.txt) |
| is-path-inside | 4.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-plain-obj | 4.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-potential-custom-element-name | 1.0.1 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| is-promise | 2.2.2 | MIT | [LICENSE](apps/app/notices/44191656d296391e.txt) |
| is-reference | 1.2.1 | MIT |  |
| is-regex | 1.2.1 | MIT | [LICENSE](apps/app/notices/dc0fe5a22d9336f3.txt) |
| is-stream | 2.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-stream | 3.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| is-wsl | 2.2.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| is-wsl | 3.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| isarray | 1.0.0 | MIT |  |
| isexe | 2.0.0 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| isexe | 4.0.0 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| iso-3166-2 | 1.0.0 | See package sources | [LICENSE](apps/app/notices/25c0309972a0ac7e.txt) |
| jackspeak | 3.4.3 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/2c7c5d22ed5a8ee9.txt) |
| jiti | 1.21.7 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| jiti | 2.6.1 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| jiti | 2.7.0 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| jju | 1.4.0 | MIT | [LICENSE](apps/app/notices/68181abfb468c8eb.txt) |
| jose | 6.2.2 | MIT | [LICENSE.md](apps/app/notices/8078b0829d6c3e9e.txt) |
| js-beautify | 1.15.4 | MIT | [LICENSE](apps/app/notices/2829716775dfdac4.txt) |
| js-cookie | 3.0.5 | MIT | [LICENSE](apps/app/notices/eff040f4184445a6.txt) |
| js-stringify | 1.0.2 | MIT | [LICENSE](apps/app/notices/44191656d296391e.txt) |
| js-tokens | 10.0.0 | MIT | [LICENSE](apps/app/notices/3b07ef3fdd96c7f4.txt) |
| js-tokens | 4.0.0 | MIT | [LICENSE](apps/app/notices/2213d91c606205c7.txt) |
| js-tokens | 9.0.1 | MIT | [LICENSE](apps/app/notices/33038d552d766f45.txt) |
| js-yaml | 3.14.2 | MIT | [LICENSE](apps/app/notices/a07bc24468b9654c.txt) |
| js-yaml | 4.1.1 | MIT | [LICENSE](apps/app/notices/a07bc24468b9654c.txt) |
| jsdoc-type-pratt-parser | 4.1.0 | MIT | [LICENSE](apps/app/notices/759d6638ccefa554.txt) |
| jsdoc-type-pratt-parser | 4.8.0 | MIT | [LICENSE](apps/app/notices/759d6638ccefa554.txt) |
| jsdom | 26.1.0 | MIT | [LICENSE.txt](apps/app/notices/242d37e7cab25cba.txt) |
| jsesc | 0.5.0 | See package sources | [LICENSE-MIT.txt](apps/app/notices/1e234f86ba3f213f.txt) |
| jsesc | 3.1.0 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| json-buffer | 3.0.1 | MIT | [LICENSE](apps/app/notices/715f1f0f2eb7688e.txt) |
| json-parse-even-better-errors | 2.3.1 | MIT | [LICENSE.md](apps/app/notices/50627796eb4236cd.txt) |
| json-schema-traverse | 0.4.1 | MIT | [LICENSE](apps/app/notices/7bf9b2de73a6b356.txt) |
| json-schema-traverse | 1.0.0 | MIT | [LICENSE](apps/app/notices/7bf9b2de73a6b356.txt) |
| json-stable-stringify-without-jsonify | 1.0.1 | MIT | [LICENSE](apps/app/notices/435a6722c786b0a5.txt) |
| json5 | 2.2.3 | MIT | [LICENSE.md](apps/app/notices/53e59feb13058722.txt) |
| jsonc-parser | 2.3.1 | MIT | [LICENSE.md](apps/app/notices/c3a24c02d678e5f0.txt) |
| jsonc-parser | 3.3.1 | MIT | [LICENSE.md](apps/app/notices/c3a24c02d678e5f0.txt) |
| jsonfile | 6.2.1 | MIT | [LICENSE](apps/app/notices/a9801fb52ba22ef8.txt) |
| jsonpointer | 5.0.1 | MIT | [LICENSE.md](apps/app/notices/3c79924aa8d99d94.txt) |
| jstransformer | 1.0.0 | MIT | [LICENSE.md](apps/app/notices/3fd3c7b3a632b5b4.txt) |
| jszip | 3.10.1 | (MIT OR GPL-3.0-or-later) | [LICENSE.markdown](apps/app/notices/566c953c6090b121.txt) |
| keep-a-changelog | 3.0.2 | MIT | [LICENSE](apps/app/notices/2fb6e74f645ba7d3.txt) |
| keyv | 4.5.4 | MIT |  |
| kind-of | 6.0.3 | MIT | [LICENSE](apps/app/notices/4cd903859549d4b2.txt) |
| kleur | 3.0.3 | MIT | [license](apps/app/notices/306fa513e39b23a6.txt) |
| kleur | 4.1.5 | MIT | [license](apps/app/notices/306fa513e39b23a6.txt) |
| klona | 2.0.6 | MIT | [license](apps/app/notices/9a9edad7baae5262.txt) |
| knitwork | 1.3.0 | MIT | [LICENSE](apps/app/notices/c638918c6f664dec.txt) |
| kolorist | 1.8.0 | MIT | [LICENSE](apps/app/notices/34633a99cb90325a.txt) |
| launch-editor | 2.14.1 | MIT | [LICENSE](apps/app/notices/225c881a16d4be4f.txt) |
| lazystream | 1.0.1 | MIT | [LICENSE](apps/app/notices/e7f5d28405c9fe65.txt) |
| leac | 0.6.0 | MIT | [LICENSE](apps/app/notices/07e82387dc9c036f.txt) |
| leven | 3.1.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| levn | 0.4.1 | MIT | [LICENSE](apps/app/notices/b9eb082c39fe245e.txt) |
| lie | 3.3.0 | MIT | [license.md](apps/app/notices/5c81b0caa9859340.txt) |
| lightningcss | 1.30.2 | MPL-2.0 | [LICENSE](apps/app/notices/5eba353fe5076ac3.txt) |
| lightningcss | 1.32.0 | MPL-2.0 | [LICENSE](apps/app/notices/5eba353fe5076ac3.txt) |
| lightningcss-win32-x64-msvc | 1.30.2 | MPL-2.0 | [LICENSE](apps/app/notices/5eba353fe5076ac3.txt) |
| lightningcss-win32-x64-msvc | 1.32.0 | MPL-2.0 | [LICENSE](apps/app/notices/5eba353fe5076ac3.txt) |
| lilconfig | 3.1.3 | MIT | [LICENSE](apps/app/notices/d70f9e316930b433.txt) |
| lines-and-columns | 1.2.4 | MIT | [LICENSE](apps/app/notices/456fe85ad3e71db9.txt) |
| linkify-it | 4.0.1 | MIT | [LICENSE](apps/app/notices/95e3f7f0e81e9b49.txt) |
| linkify-it | 5.0.0 | MIT | [LICENSE](apps/app/notices/95e3f7f0e81e9b49.txt) |
| listhen | 1.10.1 | MIT | [LICENSE](apps/app/notices/b3a54d652da04f9b.txt) |
| local-pkg | 0.5.1 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| local-pkg | 1.1.2 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| local-pkg | 1.2.1 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| locate-path | 5.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| locate-path | 6.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| lodash | 4.17.21 | MIT | [LICENSE](apps/app/notices/f71e8ed126b46346.txt) |
| lodash | 4.17.23 | MIT | [LICENSE](apps/app/notices/f71e8ed126b46346.txt) |
| lodash.memoize | 4.1.2 | MIT | [LICENSE](apps/app/notices/ffd8b33b354585f4.txt) |
| lodash.merge | 4.6.2 | MIT | [LICENSE](apps/app/notices/f71e8ed126b46346.txt) |
| lodash.uniq | 4.5.0 | MIT | [LICENSE](apps/app/notices/ffd8b33b354585f4.txt) |
| longest-streak | 3.1.0 | MIT | [license](apps/app/notices/9f084fac69d8cf1e.txt) |
| loupe | 3.2.1 | MIT | [LICENSE](apps/app/notices/592141f7b861426c.txt) |
| lower-case | 2.0.2 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| lru-cache | 10.4.3 | ISC | [LICENSE](apps/app/notices/451ec07eeb9c4e1b.txt) |
| lru-cache | 11.2.5 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| lru-cache | 11.5.3 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| lru-cache | 5.1.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| lru-cache | 8.0.5 | ISC | [LICENSE](apps/app/notices/451ec07eeb9c4e1b.txt) |
| lucide-static | 0.562.0 | ISC | [LICENSE](apps/app/notices/3c57143f22dac950.txt) |
| lz-string | 1.5.0 | MIT | [LICENSE](apps/app/notices/433fc9dfe659dbfb.txt) |
| magic-regexp | 0.10.0 | MIT | [LICENCE](apps/app/notices/f1d5e25fdad81ebc.txt) |
| magic-string | 0.30.21 | MIT | [LICENSE](apps/app/notices/1cbe51b907662f6c.txt) |
| magic-string | 1.4.2 | MIT | [LICENSE](apps/app/notices/1cbe51b907662f6c.txt) |
| magic-string-ast | 1.0.3 | MIT | [LICENSE](apps/app/notices/704c496aa9642217.txt) |
| magicast | 0.5.1 | MIT | [LICENSE](apps/app/notices/7917b04272f3f7c1.txt) |
| magicast | 0.5.5 | MIT | [LICENSE](apps/app/notices/7917b04272f3f7c1.txt) |
| markdown-extensions | 2.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| markdown-it | 13.0.2 | MIT | [LICENSE](apps/app/notices/792c48c5a849a15f.txt) |
| markdown-it | 14.1.0 | MIT | [LICENSE](apps/app/notices/792c48c5a849a15f.txt) |
| markdown-table | 3.0.4 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| marked | 7.0.4 | MIT | [LICENSE.md](apps/app/notices/8e3a3f82f59a6095.txt) |
| math-intrinsics | 1.1.0 | MIT | [LICENSE](apps/app/notices/2b770a704c15de23.txt) |
| mdast-util-definitions | 6.0.0 | MIT | [license](apps/app/notices/c7bac77e21a64800.txt) |
| mdast-util-directive | 3.1.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| mdast-util-find-and-replace | 3.0.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| mdast-util-from-markdown | 2.0.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| mdast-util-gfm | 3.1.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| mdast-util-gfm-autolink-literal | 2.0.1 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-gfm-footnote | 2.1.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| mdast-util-gfm-strikethrough | 2.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-gfm-table | 2.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-gfm-task-list-item | 2.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-mdx | 3.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-mdx-expression | 2.0.1 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-mdx-jsx | 3.2.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-mdxjs-esm | 2.0.1 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| mdast-util-phrasing | 4.1.0 | MIT | [license](apps/app/notices/b6d1a4e1831b177a.txt) |
| mdast-util-to-hast | 13.2.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| mdast-util-to-markdown | 2.1.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| mdast-util-to-string | 4.0.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| mdn-data | 2.0.28 | CC0-1.0 | [LICENSE](apps/app/notices/36ffd9dc085d529a.txt) |
| mdn-data | 2.0.30 | CC0-1.0 | [LICENSE](apps/app/notices/36ffd9dc085d529a.txt) |
| mdn-data | 2.12.2 | CC0-1.0 | [LICENSE](apps/app/notices/36ffd9dc085d529a.txt) |
| mdurl | 1.0.1 | MIT | [LICENSE](apps/app/notices/6b6a356c4337e244.txt) |
| mdurl | 2.0.0 | MIT | [LICENSE](apps/app/notices/6b6a356c4337e244.txt) |
| merge-stream | 2.0.0 | MIT | [LICENSE](apps/app/notices/2cee71bf4612fc2e.txt) |
| merge2 | 1.4.1 | MIT | [LICENSE](apps/app/notices/b2590e53ea6e0505.txt) |
| meshoptimizer | 0.18.1 | MIT | [LICENSE.md](apps/app/notices/063805e3b8e24cea.txt) |
| micromark | 4.0.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-core-commonmark | 2.0.3 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-extension-directive | 3.0.2 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-gfm | 3.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-gfm-autolink-literal | 2.1.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-gfm-footnote | 2.1.0 | MIT | [license](apps/app/notices/807a88522a850092.txt) |
| micromark-extension-gfm-strikethrough | 2.1.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-gfm-table | 2.1.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-extension-gfm-tagfilter | 2.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-gfm-task-list-item | 2.1.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-mdx-expression | 3.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-extension-mdx-jsx | 3.0.2 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-mdx-md | 2.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-mdxjs | 3.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-extension-mdxjs-esm | 3.0.0 | MIT | [license](apps/app/notices/536804b3adbff17d.txt) |
| micromark-factory-destination | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-factory-label | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-factory-mdx-expression | 2.0.3 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-factory-space | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-factory-title | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-factory-whitespace | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-character | 2.1.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-chunked | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-classify-character | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-combine-extensions | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-decode-numeric-character-reference | 2.0.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-decode-string | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-encode | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-events-to-acorn | 2.0.3 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-html-tag-name | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-normalize-identifier | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-resolve-all | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-sanitize-uri | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-subtokenize | 2.1.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-symbol | 2.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromark-util-types | 2.0.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| micromatch | 4.0.8 | MIT | [LICENSE](apps/app/notices/35bdd8a443397194.txt) |
| mime | 4.1.0 | MIT | [LICENSE](apps/app/notices/68e28d2ab9d180b8.txt) |
| mime-db | 1.25.0 | MIT | [LICENSE](apps/app/notices/965ef284f7f4c176.txt) |
| mime-db | 1.54.0 | MIT | [LICENSE](apps/app/notices/cc1dfd4dafa27271.txt) |
| mime-types | 2.1.13 | MIT | [LICENSE](apps/app/notices/71f83c4c0621102a.txt) |
| mime-types | 3.0.2 | MIT | [LICENSE](apps/app/notices/71f83c4c0621102a.txt) |
| mimic-fn | 4.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| mimic-response | 3.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| min-indent | 1.0.1 | MIT | [license](apps/app/notices/9638fa87f845af6c.txt) |
| miniflare | 4.20260730.0 | MIT |  |
| minimatch | 10.2.3 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/2c7c5d22ed5a8ee9.txt) |
| minimatch | 3.1.2 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| minimatch | 5.1.6 | ISC | [LICENSE](apps/app/notices/d11323827fa4edea.txt) |
| minimatch | 9.0.1 | ISC | [LICENSE](apps/app/notices/d11323827fa4edea.txt) |
| minimatch | 9.0.5 | ISC | [LICENSE](apps/app/notices/d11323827fa4edea.txt) |
| minimist | 1.2.8 | MIT | [LICENSE](apps/app/notices/435a6722c786b0a5.txt) |
| minipass | 7.1.2 | ISC | [LICENSE](apps/app/notices/833faa18ac4b83a6.txt) |
| minizlib | 3.1.0 | MIT | [LICENSE](apps/app/notices/df05697a04b8997c.txt) |
| mitt | 2.1.0 | MIT |  |
| mitt | 3.0.1 | MIT | [LICENSE](apps/app/notices/1cab22f196264195.txt) |
| mkdirp-classic | 0.5.3 | MIT | [LICENSE](apps/app/notices/a255b85c1a510ecf.txt) |
| mlly | 1.8.0 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| mlly | 1.8.2 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| mocked-exports | 0.1.1 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| motion-dom | 12.38.0 | MIT | [LICENSE.md](apps/app/notices/1bf0dc3f7727723e.txt) |
| motion-utils | 12.36.0 | MIT | [LICENSE.md](apps/app/notices/1bf0dc3f7727723e.txt) |
| motion-v | 2.2.1 | MIT | [LICENSE](apps/app/notices/cd2d7f6dc6b1c382.txt) |
| mrmime | 2.0.1 | MIT | [license](apps/app/notices/ba573393f24555ac.txt) |
| ms | 2.1.3 | MIT | [license.md](apps/app/notices/1662fae9b5314d11.txt) |
| muggle-string | 0.4.1 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| mz | 2.7.0 | MIT | [LICENSE](apps/app/notices/b54cad06af80663a.txt) |
| nanoid | 3.3.11 | MIT | [LICENSE](apps/app/notices/da4db1480d9beea3.txt) |
| nanoid | 3.3.19 | MIT | [LICENSE](apps/app/notices/da4db1480d9beea3.txt) |
| nanotar | 0.2.1 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| napi-build-utils | 2.0.0 | MIT | [LICENSE](apps/app/notices/9c6a91d2847bd9bf.txt) |
| napi-postinstall | 0.3.4 | MIT | [LICENSE](apps/app/notices/6b2ba6ac4aa455c1.txt) |
| natural-compare | 1.4.0 | MIT |  |
| neotraverse | 0.6.18 | MIT | [LICENSE](apps/app/notices/50810ca34b3c662b.txt) |
| nitropack | 2.13.4 | MIT | [LICENSE](apps/app/notices/b8569278a55eb519.txt) |
| nlcst-to-string | 4.0.0 | MIT | [license](apps/app/notices/9966260ba3ea9d6a.txt) |
| no-case | 3.0.4 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| node-abi | 3.94.0 | MIT | [LICENSE](apps/app/notices/9a508cd4122f2dc1.txt) |
| node-addon-api | 7.1.1 | MIT | [LICENSE.md](apps/app/notices/89024017b88a9f2b.txt) |
| node-fetch | 2.7.0 | MIT | [LICENSE.md](apps/app/notices/84eaa985e1ef71b8.txt) |
| node-fetch-native | 1.6.7 | MIT | [LICENSE](apps/app/notices/22a1b925621a4fb6.txt) |
| node-forge | 1.4.0 | (BSD-3-Clause OR GPL-2.0) | [LICENSE](apps/app/notices/f63ff0e4e239244a.txt) |
| node-gyp-build | 4.8.4 | MIT | [LICENSE](apps/app/notices/7b3638496004b2da.txt) |
| node-mock-http | 1.0.4 | MIT | [LICENSE](apps/app/notices/a12c3d66c90212bd.txt) |
| node-releases | 2.0.27 | MIT | [LICENSE](apps/app/notices/3706296ed6118881.txt) |
| node-releases | 2.0.57 | MIT | [LICENSE](apps/app/notices/3706296ed6118881.txt) |
| nopt | 7.2.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| nopt | 8.1.0 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| normalize-package-data | 2.5.0 | BSD-2-Clause | [LICENSE](apps/app/notices/d16b2b8c511d9f2b.txt) |
| normalize-path | 3.0.0 | MIT | [LICENSE](apps/app/notices/e70ff771504ba41f.txt) |
| nostics | 1.3.0 | MIT | [LICENSE](apps/app/notices/acf17aff719bfab7.txt) |
| npm-run-path | 5.3.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| npm-run-path | 6.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| nth-check | 2.1.1 | BSD-2-Clause | [LICENSE](apps/app/notices/cb992345949ccd6e.txt) |
| nuxt | 3.20.2 | MIT | [LICENSE](apps/app/notices/947a111b1c579718.txt) |
| nwsapi | 2.2.24 | MIT | [LICENSE](apps/app/notices/2aebdf8ae67777cc.txt) |
| nypm | 0.6.10 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| object-assign | 4.1.1 | MIT | [license](apps/app/notices/6fb9754611c20f66.txt) |
| object-hash | 3.0.0 | MIT | [LICENSE](apps/app/notices/ea9e6806c48a8a04.txt) |
| object-inspect | 1.13.4 | MIT | [LICENSE](apps/app/notices/bd40cc437e28a3ad.txt) |
| obscenity | 0.4.6 | MIT | [LICENSE.md](apps/app/notices/c828a9313d9b0f6b.txt) |
| obug | 2.1.1 | MIT | [LICENSE](apps/app/notices/ee48679d379ca6b4.txt) |
| ofetch | 1.5.1 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| ohash | 2.0.11 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| on-change | 6.0.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| on-finished | 2.4.1 | MIT | [LICENSE](apps/app/notices/8089bcc08845ec14.txt) |
| once | 1.4.0 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| onetime | 6.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| oniguruma-parser | 0.12.1 | MIT | [LICENSE](apps/app/notices/3d19c2b6246b3072.txt) |
| oniguruma-to-es | 2.3.0 | MIT | [LICENSE](apps/app/notices/3d19c2b6246b3072.txt) |
| oniguruma-to-es | 4.3.4 | MIT | [LICENSE](apps/app/notices/3d19c2b6246b3072.txt) |
| open | 10.2.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| open | 11.0.4 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| open | 8.4.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| openapi-types | 12.1.3 | MIT | [LICENSE](apps/app/notices/a5b243ddbec533f2.txt) |
| optionator | 0.9.4 | MIT | [LICENSE](apps/app/notices/b9eb082c39fe245e.txt) |
| overlayscrollbars | 2.15.1 | MIT |  |
| oxc-minify | 0.102.0 | MIT | [LICENSE](apps/app/notices/95ced5ecf1133fbf.txt) |
| oxc-parser | 0.102.0 | MIT | [LICENSE](apps/app/notices/95ced5ecf1133fbf.txt) |
| oxc-transform | 0.102.0 | MIT | [LICENSE](apps/app/notices/95ced5ecf1133fbf.txt) |
| oxc-walker | 0.6.0 | MIT | [LICENCE](apps/app/notices/561e7050b24b064e.txt) |
| p-limit | 2.3.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| p-limit | 3.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| p-limit | 6.2.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| p-locate | 4.1.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| p-locate | 5.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| p-queue | 8.1.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| p-timeout | 6.1.4 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| p-try | 2.2.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| package-json-from-dist | 1.0.1 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/a49c9ba464796f65.txt) |
| package-manager-detector | 1.6.0 | MIT | [LICENSE](apps/app/notices/05c365176db3cc00.txt) |
| pagefind | 1.4.0 | MIT |  |
| pako | 1.0.11 | (MIT AND Zlib) | [LICENSE](apps/app/notices/a04665b3b2de56c6.txt) |
| param-case | 3.0.4 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| parent-module | 1.0.1 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| parse-entities | 4.0.2 | MIT | [license](apps/app/notices/5d0698266086f217.txt) |
| parse-imports-exports | 0.2.4 | MIT | [LICENSE](apps/app/notices/186cbe83d485dc94.txt) |
| parse-json | 5.2.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| parse-latin | 7.0.0 | MIT | [license](apps/app/notices/9966260ba3ea9d6a.txt) |
| parse-statements | 1.0.11 | MIT | [LICENSE](apps/app/notices/186cbe83d485dc94.txt) |
| parse5 | 7.3.0 | MIT | [LICENSE](apps/app/notices/8c535800331e1e44.txt) |
| parseley | 0.12.1 | MIT | [LICENSE](apps/app/notices/07e82387dc9c036f.txt) |
| parseurl | 1.3.3 | MIT | [LICENSE](apps/app/notices/11d017c3b9f1ee3f.txt) |
| pascal-case | 3.1.2 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| path-browserify | 1.0.1 | MIT | [LICENSE](apps/app/notices/a22b9d5763f574e5.txt) |
| path-exists | 4.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| path-key | 3.1.1 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| path-key | 4.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| path-parse | 1.0.7 | MIT | [LICENSE](apps/app/notices/3f4609137f650705.txt) |
| path-scurry | 1.11.1 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| path-scurry | 2.0.1 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| path-to-regexp | 6.3.0 | MIT | [LICENSE](apps/app/notices/4eeb3271453a891d.txt) |
| pathe | 1.1.2 | MIT | [LICENSE](apps/app/notices/cb00dc7c358014d3.txt) |
| pathe | 2.0.3 | MIT | [LICENSE](apps/app/notices/52e92576851154ba.txt) |
| pathval | 2.0.1 | MIT | [LICENSE](apps/app/notices/5d45910e7ed82fec.txt) |
| peberminta | 0.9.0 | MIT | [LICENSE](apps/app/notices/07e82387dc9c036f.txt) |
| perfect-debounce | 2.1.0 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| piccolore | 0.1.3 | ISC |  |
| picocolors | 1.1.1 | ISC | [LICENSE](apps/app/notices/6582629e29794668.txt) |
| picomatch | 2.3.1 | MIT | [LICENSE](apps/app/notices/d0cd141b0c322fde.txt) |
| picomatch | 4.0.4 | MIT | [LICENSE](apps/app/notices/d0cd141b0c322fde.txt) |
| picomatch | 4.0.7 | MIT | [LICENSE](apps/app/notices/d0cd141b0c322fde.txt) |
| pify | 2.3.0 | MIT | [license](apps/app/notices/6fb9754611c20f66.txt) |
| pirates | 4.0.7 | MIT | [LICENSE](apps/app/notices/b3e8623bbd73e4f9.txt) |
| pkg-types | 1.3.1 | MIT | [LICENSE](apps/app/notices/cb00dc7c358014d3.txt) |
| pkg-types | 2.3.0 | MIT | [LICENSE](apps/app/notices/cb00dc7c358014d3.txt) |
| pkg-types | 2.3.3 | MIT | [LICENSE](apps/app/notices/cb00dc7c358014d3.txt) |
| pluralize | 8.0.0 | MIT | [LICENSE](apps/app/notices/5822e0d816e53e35.txt) |
| postcss | 8.5.28 | MIT | [LICENSE](apps/app/notices/5be1f3465bba68a6.txt) |
| postcss | 8.5.6 | MIT | [LICENSE](apps/app/notices/c4630ac8b89cb317.txt) |
| postcss | 8.5.8 | MIT | [LICENSE](apps/app/notices/c4630ac8b89cb317.txt) |
| postcss-calc | 10.1.1 | MIT | [LICENSE](apps/app/notices/a3fb61c22ecb516a.txt) |
| postcss-colormin | 7.0.10 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-convert-values | 7.0.12 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-discard-comments | 7.0.8 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-discard-duplicates | 7.0.4 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-discard-empty | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-discard-overridden | 7.0.3 | MIT | [LICENSE](apps/app/notices/b2964fbeb03aa572.txt) |
| postcss-import | 15.1.0 | MIT | [LICENSE](apps/app/notices/e775239f3f181bf6.txt) |
| postcss-js | 4.1.0 | MIT | [LICENSE](apps/app/notices/d6998a4ba4e15bba.txt) |
| postcss-load-config | 6.0.1 | MIT | [LICENSE](apps/app/notices/21ffeb3616fb8bbc.txt) |
| postcss-merge-longhand | 7.0.7 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-merge-rules | 7.0.11 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-minify-font-values | 7.0.3 | MIT | [LICENSE](apps/app/notices/3687447039151857.txt) |
| postcss-minify-gradients | 7.0.5 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-minify-params | 7.0.9 | MIT | [LICENSE](apps/app/notices/c95b29e3c4209b6f.txt) |
| postcss-minify-selectors | 7.1.2 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-nested | 6.2.0 | MIT | [LICENSE](apps/app/notices/02a0c8b164b043f1.txt) |
| postcss-normalize-charset | 7.0.3 | MIT | [LICENSE](apps/app/notices/c95b29e3c4209b6f.txt) |
| postcss-normalize-display-values | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-positions | 7.0.4 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-repeat-style | 7.0.4 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-string | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-timing-functions | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-unicode | 7.0.9 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-url | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-normalize-whitespace | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-ordered-values | 7.0.4 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-reduce-initial | 7.0.9 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-reduce-transforms | 7.0.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-selector-parser | 6.1.2 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-selector-parser | 7.1.1 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-svgo | 7.1.3 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-unique-selectors | 7.0.7 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| postcss-value-parser | 4.2.0 | MIT | [LICENSE](apps/app/notices/3687447039151857.txt) |
| powershell-utils | 0.2.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| prebuild-install | 7.1.3 | MIT | [LICENSE](apps/app/notices/0aa9add6a9158efa.txt) |
| prelude-ls | 1.2.1 | MIT | [LICENSE](apps/app/notices/b9eb082c39fe245e.txt) |
| prettier | 3.8.1 | MIT | [LICENSE](apps/app/notices/b0f2417199889f1c.txt) |
| prettier-linter-helpers | 1.0.1 | MIT | [LICENSE.md](apps/app/notices/20e80c18f6f0a93b.txt) |
| prettier-plugin-sql-cst | 0.13.0 | GPL-3.0-or-later | [LICENSE](apps/app/notices/f817886ee6bb65ed.txt) |
| prettier-plugin-tailwindcss | 0.6.14 | MIT | [LICENSE](apps/app/notices/2c93b6bf68a7e680.txt) |
| prettier-plugin-toml | 2.0.6 | MIT | [LICENSE](apps/app/notices/db2d1ad10d0c84dd.txt) |
| pretty-bytes | 7.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| pretty-format | 27.5.1 | MIT | [LICENSE](apps/app/notices/52412d7bc7ce4157.txt) |
| prismjs | 1.30.0 | MIT | [LICENSE](apps/app/notices/2b947f0901a7ffcf.txt) |
| process | 0.11.10 | MIT | [LICENSE](apps/app/notices/59a400d04c507857.txt) |
| process-nextick-args | 2.0.1 | MIT | [license.md](apps/app/notices/ecdccbcf39024f62.txt) |
| promise | 7.3.1 | MIT | [LICENSE](apps/app/notices/5e733eb92ed0c571.txt) |
| prompts | 2.4.2 | MIT | [license](apps/app/notices/ade66f698fd417ad.txt) |
| property-information | 7.1.0 | MIT | [license](apps/app/notices/5d0698266086f217.txt) |
| proto-list | 1.2.4 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| proxy-from-env | 2.1.0 | MIT | [LICENSE](apps/app/notices/f55828df4b8752c4.txt) |
| pug | 3.0.3 | MIT | [LICENSE](apps/app/notices/2fe0235fa666d290.txt) |
| pug-attrs | 3.0.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pug-code-gen | 3.0.3 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pug-error | 2.1.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pug-filters | 4.0.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pug-lexer | 5.0.1 | MIT | [LICENSE](apps/app/notices/44191656d296391e.txt) |
| pug-linker | 4.0.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pug-load | 3.0.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pug-parser | 6.0.0 | MIT | [LICENSE](apps/app/notices/44191656d296391e.txt) |
| pug-runtime | 3.0.1 | MIT | [LICENSE](apps/app/notices/44191656d296391e.txt) |
| pug-strip-comments | 2.0.0 | MIT | [LICENSE.md](apps/app/notices/1ac0263302bfb8ee.txt) |
| pug-walk | 2.0.0 | MIT | [LICENSE](apps/app/notices/f1a3942b131d45df.txt) |
| pump | 3.0.3 | MIT | [LICENSE](apps/app/notices/3fe8d55a98dbf260.txt) |
| punycode | 2.3.1 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| punycode.js | 2.3.1 | MIT | [LICENSE-MIT.txt](apps/app/notices/483acb265f182907.txt) |
| qrcode.vue | 3.8.0 | MIT | [LICENSE](apps/app/notices/d4613b8a6c168495.txt) |
| qs | 6.14.1 | BSD-3-Clause | [LICENSE.md](apps/app/notices/e7dc37bf662d7f78.txt) |
| quansync | 0.2.11 | MIT | [LICENSE.md](apps/app/notices/fd8a6a9b107d6591.txt) |
| queue-microtask | 1.2.3 | MIT | [LICENSE](apps/app/notices/d4c2065e2b936e62.txt) |
| radix3 | 1.1.2 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| range-parser | 1.2.1 | MIT | [LICENSE](apps/app/notices/f655e6291356ec0d.txt) |
| rc | 1.2.8 | (BSD-2-Clause OR MIT OR Apache-2.0) | [LICENSE.APACHE2](apps/app/notices/e8734448285a2dd7.txt), [LICENSE.BSD](apps/app/notices/65e7e4d223688c60.txt), [LICENSE.MIT](apps/app/notices/d72dea1a8cdf3f4d.txt) |
| rc9 | 2.1.2 | MIT | [LICENSE](apps/app/notices/688222000d499a06.txt) |
| rc9 | 3.1.0 | MIT | [LICENSE](apps/app/notices/688222000d499a06.txt) |
| react | 19.2.8 | MIT | [LICENSE](apps/app/notices/da6d3703ed11cbe4.txt) |
| react-dom | 19.2.8 | MIT | [LICENSE](apps/app/notices/da6d3703ed11cbe4.txt) |
| react-is | 17.0.2 | MIT | [LICENSE](apps/app/notices/52412d7bc7ce4157.txt) |
| read-cache | 1.0.0 | MIT | [LICENSE](apps/app/notices/e6fba77459ca7919.txt) |
| read-pkg | 5.2.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| read-pkg-up | 7.0.1 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| readable-stream | 2.3.8 | MIT | [LICENSE](apps/app/notices/ec62dc96da0099b8.txt) |
| readable-stream | 3.6.2 | MIT | [LICENSE](apps/app/notices/ec62dc96da0099b8.txt) |
| readable-stream | 4.7.0 | MIT | [LICENSE](apps/app/notices/ec62dc96da0099b8.txt) |
| readdir-glob | 1.1.3 | Apache-2.0 | [LICENSE](apps/app/notices/8cd23e2d76d27917.txt) |
| readdirp | 3.6.0 | MIT | [LICENSE](apps/app/notices/dffec71d93f273d2.txt) |
| readdirp | 4.1.2 | MIT | [LICENSE](apps/app/notices/dffec71d93f273d2.txt) |
| readdirp | 5.0.0 | MIT | [LICENSE](apps/app/notices/dffec71d93f273d2.txt) |
| recast | 0.23.11 | MIT | [LICENSE](apps/app/notices/6ca87d1dce5b8287.txt) |
| recma-build-jsx | 1.0.0 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| recma-jsx | 1.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| recma-parse | 1.0.0 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| recma-stringify | 1.0.0 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| redent | 3.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| redis-errors | 1.2.0 | MIT | [LICENSE](apps/app/notices/43f5ac55d8171ff9.txt) |
| redis-parser | 3.0.0 | MIT | [LICENSE](apps/app/notices/32875e91f440344f.txt) |
| refa | 0.12.1 | MIT | [LICENSE](apps/app/notices/8f5e36562ec9a0c3.txt) |
| regex | 5.1.1 | MIT | [LICENSE](apps/app/notices/8ca7af4f6c753e5a.txt) |
| regex | 6.1.0 | MIT | [LICENSE](apps/app/notices/3d19c2b6246b3072.txt) |
| regex-recursion | 5.1.1 | MIT | [LICENSE](apps/app/notices/8ca7af4f6c753e5a.txt) |
| regex-recursion | 6.0.2 | MIT | [LICENSE](apps/app/notices/3d19c2b6246b3072.txt) |
| regex-utilities | 2.3.0 | MIT | [LICENSE](apps/app/notices/8ca7af4f6c753e5a.txt) |
| regexp-ast-analysis | 0.7.1 | MIT | [LICENSE](apps/app/notices/4d104654b1daaf7a.txt) |
| regexp-to-ast | 0.5.0 | MIT | [LICENSE](apps/app/notices/ffdfd706a54ae169.txt) |
| regexp-tree | 0.1.27 | MIT | [LICENSE](apps/app/notices/0adcee8b9734247b.txt) |
| regjsparser | 0.10.0 | BSD-2-Clause | [LICENSE.BSD](apps/app/notices/2d65cdba6e67bd7f.txt) |
| rehype | 13.0.2 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| rehype-expressive-code | 0.40.2 | MIT | [LICENSE](apps/app/notices/4c81807ac60ec031.txt) |
| rehype-format | 5.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| rehype-parse | 9.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| rehype-raw | 7.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| rehype-recma | 1.0.0 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| rehype-stringify | 10.0.1 | MIT | [license](apps/app/notices/e18cf5173e928f80.txt) |
| relateurl | 0.2.7 | MIT | [license](apps/app/notices/4c97d11c3d10dded.txt) |
| remark-directive | 3.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| remark-gfm | 4.0.1 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| remark-mdx | 3.1.1 | MIT | [license](apps/app/notices/a18bf7b2118ad99e.txt) |
| remark-parse | 11.0.0 | MIT | [license](apps/app/notices/413654b0a78b9866.txt) |
| remark-rehype | 11.1.2 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| remark-smartypants | 3.0.2 | MIT | [license](apps/app/notices/7b22c6c471b1696d.txt) |
| remark-stringify | 11.0.0 | MIT | [license](apps/app/notices/413654b0a78b9866.txt) |
| remove-accents | 0.5.0 | MIT | [LICENSE](apps/app/notices/d1a4d73a0c668a73.txt) |
| request-light | 0.5.8 | MIT | [LICENSE.md](apps/app/notices/c3a24c02d678e5f0.txt) |
| request-light | 0.7.0 | MIT | [LICENSE.md](apps/app/notices/c3a24c02d678e5f0.txt) |
| require-directory | 2.1.1 | MIT | [LICENSE](apps/app/notices/a92e52eb1fa7cd74.txt) |
| require-from-string | 2.0.2 | MIT | [license](apps/app/notices/6ee0feb1f6ef996f.txt) |
| resize-observer-polyfill | 1.5.1 | MIT | [LICENSE](apps/app/notices/49fad6f35ac45600.txt) |
| resolve | 1.22.11 | MIT | [LICENSE](apps/app/notices/60acd7711e6c138e.txt) |
| resolve-from | 4.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| resolve-from | 5.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| resolve-pkg-maps | 1.0.0 | MIT | [LICENSE](apps/app/notices/10c904a49af44409.txt) |
| retext | 9.0.0 | MIT |  |
| retext-latin | 4.0.0 | MIT |  |
| retext-smartypants | 6.2.0 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| retext-stringify | 4.0.0 | MIT |  |
| reusify | 1.1.0 | MIT | [LICENSE](apps/app/notices/93a1506953b08ad4.txt) |
| rolldown | 1.0.0-rc.12 | MIT | [LICENSE](apps/app/notices/23ecfff35a5a2e80.txt) |
| rollup | 4.57.1 | MIT | [LICENSE.md](apps/app/notices/fa1bd040c5bdeefe.txt) |
| rollup | 4.63.6 | MIT | [LICENSE.md](apps/app/notices/fa1bd040c5bdeefe.txt) |
| rollup-plugin-visualizer | 6.0.11 | MIT | [LICENSE](apps/app/notices/975abd563775a495.txt) |
| rollup-plugin-visualizer | 7.1.1 | MIT | [LICENSE](apps/app/notices/975abd563775a495.txt) |
| rrweb-cssom | 0.8.0 | MIT | [LICENSE.txt](apps/app/notices/e539937c489c4928.txt) |
| rss | 1.2.2 | MIT | [LICENSE](apps/app/notices/0bbb9711e7996b30.txt) |
| run-applescript | 7.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| run-parallel | 1.2.0 | MIT | [LICENSE](apps/app/notices/d4c2065e2b936e62.txt) |
| safe-buffer | 5.1.2 | MIT | [LICENSE](apps/app/notices/c7cc929b57080f4b.txt) |
| safe-buffer | 5.2.1 | MIT | [LICENSE](apps/app/notices/c7cc929b57080f4b.txt) |
| safer-buffer | 2.1.2 | MIT | [LICENSE](apps/app/notices/4bc935e71be198c6.txt) |
| sass | 1.97.3 | MIT | [LICENSE](apps/app/notices/02b41feb22cab720.txt) |
| sax | 1.4.4 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| sax | 1.6.1 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| saxes | 6.0.0 | ISC |  |
| scheduler | 0.27.0 | MIT | [LICENSE](apps/app/notices/da6d3703ed11cbe4.txt) |
| scslre | 0.3.0 | MIT | [LICENSE](apps/app/notices/8f5e36562ec9a0c3.txt) |
| scule | 1.3.0 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| section-matter | 1.0.0 | MIT | [LICENSE](apps/app/notices/6d99b653e1464192.txt) |
| selderee | 0.11.0 | MIT | [LICENSE](apps/app/notices/07e82387dc9c036f.txt) |
| semver | 5.7.2 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| semver | 6.3.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| semver | 7.7.4 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| semver | 7.8.5 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| send | 1.2.1 | MIT | [LICENSE](apps/app/notices/25a328069fe771f8.txt) |
| serialize-javascript | 7.1.2 | BSD-3-Clause | [LICENSE](apps/app/notices/d3dfa68a3c80e64e.txt) |
| seroval | 1.6.8 | MIT | [LICENSE](apps/app/notices/2bd8a2c61751fc47.txt) |
| serve-placeholder | 2.0.2 | MIT | [LICENSE](apps/app/notices/7bb1e9eaebba08a5.txt) |
| serve-static | 2.2.1 | MIT | [LICENSE](apps/app/notices/63b9a188d7d43e64.txt) |
| setimmediate | 1.0.5 | MIT | [LICENSE.txt](apps/app/notices/c4b4ad3a5746f1f5.txt) |
| setprototypeof | 1.2.0 | ISC | [LICENSE](apps/app/notices/76d6d1ea0c268da3.txt) |
| sharp | 0.33.5 | Apache-2.0 | [LICENSE](apps/app/notices/73ba74dfaa520b49.txt) |
| sharp | 0.34.5 | Apache-2.0 | [LICENSE](apps/app/notices/73ba74dfaa520b49.txt) |
| sharp | 0.35.2 | Apache-2.0 | [LICENSE](apps/app/notices/73ba74dfaa520b49.txt) |
| shebang-command | 2.0.0 | MIT | [license](apps/app/notices/69dee148a2cc4705.txt) |
| shebang-regex | 3.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| shell-quote | 1.11.0 | MIT | [LICENSE](apps/app/notices/8bb16db1b047019e.txt) |
| shiki | 1.29.2 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| shiki | 3.22.0 | MIT | [LICENSE](apps/app/notices/7a9d8d01038aeacf.txt) |
| side-channel | 1.1.0 | MIT | [LICENSE](apps/app/notices/cfc3f455254c0af0.txt) |
| side-channel-list | 1.0.0 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| side-channel-map | 1.0.1 | MIT | [LICENSE](apps/app/notices/5e325595b4ea8cfe.txt) |
| side-channel-weakmap | 1.0.2 | MIT | [LICENSE](apps/app/notices/cfc3f455254c0af0.txt) |
| signal-exit | 4.1.0 | ISC | [LICENSE.txt](apps/app/notices/b173e19b9a78df30.txt) |
| simple-concat | 1.0.1 | MIT | [LICENSE](apps/app/notices/d4c2065e2b936e62.txt) |
| simple-get | 4.0.1 | MIT | [LICENSE](apps/app/notices/d4c2065e2b936e62.txt) |
| simple-git | 3.36.0 | MIT |  |
| simple-swizzle | 0.2.4 | MIT | [LICENSE](apps/app/notices/8f67ef1afdbd7b8d.txt) |
| sirv | 3.0.2 | MIT |  |
| sisteransi | 1.0.5 | MIT | [license](apps/app/notices/ade66f698fd417ad.txt) |
| sitemap | 8.0.2 | MIT | [LICENSE](apps/app/notices/4839f2c7b8478d3f.txt) |
| slash | 5.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| smob | 1.5.0 | MIT | [LICENSE](apps/app/notices/c85886d9005151bb.txt) |
| smol-toml | 1.6.0 | BSD-3-Clause | [LICENSE](apps/app/notices/fa5659948374d4f5.txt) |
| sortablejs | 1.14.0 | MIT | [LICENSE](apps/app/notices/e94dfc31e800d169.txt) |
| source-map | 0.6.1 | BSD-3-Clause | [LICENSE](apps/app/notices/6cb0631f71c77497.txt) |
| source-map | 0.7.6 | BSD-3-Clause | [LICENSE](apps/app/notices/6cb0631f71c77497.txt) |
| source-map | 0.8.0 | BSD-3-Clause | [LICENSE](apps/app/notices/6cb0631f71c77497.txt) |
| source-map-js | 1.2.1 | BSD-3-Clause | [LICENSE](apps/app/notices/6cb0631f71c77497.txt) |
| source-map-support | 0.5.21 | MIT | [LICENSE.md](apps/app/notices/3a7d3bb198e909ed.txt) |
| space-separated-tokens | 2.0.2 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| spdx-correct | 3.2.0 | Apache-2.0 | [LICENSE](apps/app/notices/cfc7749b96f63bd3.txt) |
| spdx-exceptions | 2.5.0 | CC-BY-3.0 |  |
| spdx-expression-parse | 3.0.1 | MIT | [LICENSE](apps/app/notices/7edb57f706530902.txt) |
| spdx-expression-parse | 4.0.0 | MIT | [LICENSE](apps/app/notices/7edb57f706530902.txt) |
| spdx-license-ids | 3.0.22 | CC0-1.0 |  |
| sprintf-js | 1.0.3 | BSD-3-Clause | [LICENSE](apps/app/notices/a4cdda44b5adea47.txt) |
| sql-parser-cst | 0.33.1 | GPL-2.0-or-later | [LICENSE](apps/app/notices/4dd33c79028dd169.txt) |
| srvx | 0.11.22 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| stable-hash-x | 0.2.0 | MIT | [LICENSE](apps/app/notices/97ad7193b6ccab04.txt) |
| standard-as-callback | 2.1.0 | MIT | [LICENSE](apps/app/notices/a1de72eb7bdf08c1.txt) |
| starlight-openapi | 0.14.4 | MIT | [LICENSE](apps/app/notices/e18006ec386cd205.txt) |
| statuses | 2.0.2 | MIT | [LICENSE](apps/app/notices/512cfa4d5e7a7569.txt) |
| std-env | 3.10.0 | MIT | [LICENCE](apps/app/notices/a6f36438e46fb911.txt) |
| std-env | 4.3.0 | MIT | [LICENCE](apps/app/notices/a6f36438e46fb911.txt) |
| storybook | 10.2.4 | MIT |  |
| stream-replace-string | 2.0.0 | MIT | [LICENSE](apps/app/notices/adeec242d63c58d0.txt) |
| streamx | 2.23.0 | MIT | [LICENSE](apps/app/notices/41a2aa55a9ebad3d.txt) |
| string-argv | 0.3.2 | MIT | [LICENSE](apps/app/notices/2aca619a9845c352.txt) |
| string-width | 4.2.3 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| string-width | 5.1.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| string-width | 7.2.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| string-width | 8.3.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| string_decoder | 1.1.1 | MIT | [LICENSE](apps/app/notices/11f2aafb37d06b3e.txt) |
| string_decoder | 1.3.0 | MIT | [LICENSE](apps/app/notices/11f2aafb37d06b3e.txt) |
| stringify-entities | 4.0.4 | MIT | [license](apps/app/notices/9f084fac69d8cf1e.txt) |
| strip-ansi | 6.0.1 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| strip-ansi | 7.1.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| strip-bom-string | 1.0.0 | MIT | [LICENSE](apps/app/notices/aab63d733edfbb74.txt) |
| strip-final-newline | 3.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| strip-indent | 3.0.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| strip-json-comments | 2.0.1 | MIT | [license](apps/app/notices/6fb9754611c20f66.txt) |
| strip-json-comments | 3.1.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| strip-literal | 3.1.0 | MIT | [LICENSE](apps/app/notices/af32efdd008a371c.txt) |
| strip-literal | 4.0.0 | MIT | [LICENSE](apps/app/notices/af32efdd008a371c.txt) |
| stripe | 18.5.0 | MIT | [LICENSE](apps/app/notices/b36d54d51ac6f20b.txt) |
| structured-clone-es | 2.0.1 | ISC | [LICENSE.md](apps/app/notices/dc6d4961d8b6ee74.txt) |
| style-mod | 4.1.3 | MIT | [LICENSE](apps/app/notices/cb4474e265473971.txt) |
| style-to-js | 1.1.21 | MIT | [LICENSE](apps/app/notices/bbb380e5c1a71707.txt) |
| style-to-object | 1.0.14 | MIT | [LICENSE](apps/app/notices/896c9fd6b5fc48ac.txt) |
| stylehacks | 7.0.11 | MIT | [LICENSE-MIT](apps/app/notices/2998094b38f7ace2.txt) |
| sucrase | 3.35.1 | MIT | [LICENSE](apps/app/notices/c43b99fc682391ce.txt) |
| supports-color | 10.2.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| supports-color | 7.2.0 | MIT | [license](apps/app/notices/48da2f39e100d408.txt) |
| supports-color | 8.1.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| supports-preserve-symlinks-flag | 1.0.0 | MIT | [LICENSE](apps/app/notices/0f0ca96f50793990.txt) |
| svgo | 3.3.2 | MIT | [LICENSE](apps/app/notices/d2b5640808aeec9c.txt) |
| svgo | 4.0.0 | MIT | [LICENSE](apps/app/notices/d2b5640808aeec9c.txt) |
| svgo | 4.1.0 | MIT | [LICENSE](apps/app/notices/d2b5640808aeec9c.txt) |
| symbol-tree | 3.2.4 | MIT | [LICENSE](apps/app/notices/9ea1eccdabe46976.txt) |
| synckit | 0.11.12 | MIT | [LICENSE](apps/app/notices/c66a0b24c4422dde.txt) |
| tagged-tag | 1.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| tailwindcss | 3.4.19 | MIT | [LICENSE](apps/app/notices/60e0b68c0f35c078.txt) |
| tailwindcss | 4.1.18 | MIT | [LICENSE](apps/app/notices/60e0b68c0f35c078.txt) |
| tapable | 2.3.0 | MIT | [LICENSE](apps/app/notices/824ef6c33ae5ecbb.txt) |
| tar | 7.5.7 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/8a1af140fdfbf5af.txt) |
| tar-fs | 2.1.5 | MIT | [LICENSE](apps/app/notices/3fe8d55a98dbf260.txt) |
| tar-stream | 2.2.0 | MIT | [LICENSE](apps/app/notices/3fe8d55a98dbf260.txt) |
| tar-stream | 3.1.7 | MIT | [LICENSE](apps/app/notices/3fe8d55a98dbf260.txt) |
| terser | 5.46.0 | BSD-2-Clause | [LICENSE](apps/app/notices/901d0a7fcaccaae9.txt) |
| text-decoder | 1.2.3 | Apache-2.0 | [LICENSE](apps/app/notices/c71d239df91726fc.txt) |
| thenify | 3.3.1 | MIT | [LICENSE](apps/app/notices/ae538dfbba770702.txt) |
| thenify-all | 1.6.0 | MIT | [LICENSE](apps/app/notices/965ef284f7f4c176.txt) |
| three | 0.172.0 | MIT | [LICENSE](apps/app/notices/4c40a1ef62450b85.txt) |
| tiny-inflate | 1.0.3 | MIT | [LICENSE](apps/app/notices/c0df7f551401f8f8.txt) |
| tiny-invariant | 1.3.3 | MIT | [LICENSE](apps/app/notices/b1c501095de70182.txt) |
| tinyclip | 0.1.15 | MIT | [LICENSE](apps/app/notices/caad6c05def3af48.txt) |
| tinyexec | 1.0.2 | MIT | [LICENSE](apps/app/notices/f95f668fe64081dd.txt) |
| tinyexec | 1.3.1 | MIT | [LICENSE](apps/app/notices/f95f668fe64081dd.txt) |
| tinyglobby | 0.2.15 | MIT | [LICENSE](apps/app/notices/22c68811e174cbbf.txt) |
| tinyglobby | 0.2.17 | MIT | [LICENSE](apps/app/notices/22c68811e174cbbf.txt) |
| tinyrainbow | 2.0.0 | MIT | [LICENCE](apps/app/notices/cebc084d54e6dd99.txt) |
| tinyspy | 4.0.4 | MIT | [LICENCE](apps/app/notices/cebc084d54e6dd99.txt) |
| tldts | 6.1.86 | MIT | [LICENSE](apps/app/notices/c64182d48160db94.txt) |
| tldts-core | 6.1.86 | MIT | [LICENSE](apps/app/notices/c64182d48160db94.txt) |
| to-regex-range | 5.0.1 | MIT | [LICENSE](apps/app/notices/e7d1fee7347ffddc.txt) |
| toidentifier | 1.0.1 | MIT | [LICENSE](apps/app/notices/a832d679750e49ab.txt) |
| token-stream | 1.0.0 | MIT | [LICENSE](apps/app/notices/44191656d296391e.txt) |
| totalist | 3.0.1 | MIT | [license](apps/app/notices/306fa513e39b23a6.txt) |
| tough-cookie | 5.1.2 | BSD-3-Clause | [LICENSE](apps/app/notices/22ec6791c91ba42c.txt) |
| tr46 | 0.0.3 | MIT |  |
| tr46 | 5.1.1 | MIT | [LICENSE.md](apps/app/notices/499d6d466d064e04.txt) |
| trim-lines | 3.0.1 | MIT | [license](apps/app/notices/9f084fac69d8cf1e.txt) |
| trough | 2.2.0 | MIT | [license](apps/app/notices/6c03fd41cfd7c92d.txt) |
| ts-api-utils | 2.5.0 | MIT | [LICENSE.md](apps/app/notices/76c9d5f5ea942054.txt) |
| ts-dedent | 2.2.0 | MIT | [LICENSE](apps/app/notices/eff13095d9d762c3.txt) |
| ts-deepmerge | 8.0.0 | ISC |  |
| ts-interface-checker | 0.1.13 | Apache-2.0 | [LICENSE](apps/app/notices/b40930bbcf80744c.txt) |
| ts-map | 1.0.3 | MIT | [LICENCE](apps/app/notices/a05dc5a07d8b94ee.txt) |
| tsconfck | 3.1.6 | MIT | [LICENSE](apps/app/notices/483edf639466c35b.txt) |
| tslib | 2.8.1 | 0BSD | [LICENSE.txt](apps/app/notices/210b19e543130388.txt) |
| tunnel-agent | 0.6.0 | Apache-2.0 | [LICENSE](apps/app/notices/d446a8c73d7bbe48.txt) |
| turbo | 2.11.5 | MIT | [LICENSE](apps/app/notices/f7ac4712aa30551d.txt) |
| type-check | 0.4.0 | MIT | [LICENSE](apps/app/notices/b9eb082c39fe245e.txt) |
| type-fest | 0.20.2 | (MIT OR CC0-1.0) | [license](apps/app/notices/64a93ffc0a06a226.txt) |
| type-fest | 0.6.0 | (MIT OR CC0-1.0) | [license](apps/app/notices/48da2f39e100d408.txt) |
| type-fest | 0.8.1 | (MIT OR CC0-1.0) | [license](apps/app/notices/48da2f39e100d408.txt) |
| type-fest | 2.19.0 | (MIT OR CC0-1.0) |  |
| type-fest | 4.41.0 | (MIT OR CC0-1.0) | [license-cc0](apps/app/notices/a2010f343487d3f7.txt), [license-mit](apps/app/notices/5c932d88256b4ab9.txt) |
| type-fest | 5.4.3 | (MIT OR CC0-1.0) | [license-cc0](apps/app/notices/a2010f343487d3f7.txt), [license-mit](apps/app/notices/5c932d88256b4ab9.txt) |
| type-level-regexp | 0.1.17 | MIT | [LICENCE](apps/app/notices/082f9c64e918856f.txt) |
| typesafe-path | 0.2.2 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| typescript | 5.9.3 | Apache-2.0 | [LICENSE.txt](apps/app/notices/a7d00bfd54525bc6.txt) |
| typescript-auto-import-cache | 0.3.6 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| typescript-eslint | 8.54.0 | MIT | [LICENSE](apps/app/notices/2eb5c7a0bba9deb7.txt) |
| uc.micro | 1.0.6 | MIT | [LICENSE.txt](apps/app/notices/483acb265f182907.txt) |
| uc.micro | 2.1.0 | MIT | [LICENSE.txt](apps/app/notices/483acb265f182907.txt) |
| ufo | 1.6.3 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| ufo | 1.6.4 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| ultrahtml | 1.6.0 | MIT | [LICENSE](apps/app/notices/5141aab157171b51.txt) |
| ultrahtml | 1.7.0 | MIT | [LICENSE](apps/app/notices/5141aab157171b51.txt) |
| uncrypto | 0.1.3 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| unctx | 2.5.0 | MIT | [LICENSE](apps/app/notices/4c59d25489cc9a9b.txt) |
| unctx | 3.0.1 | MIT | [LICENSE](apps/app/notices/4c59d25489cc9a9b.txt) |
| undici | 7.28.0 | MIT | [LICENSE](apps/app/notices/a6db8096b2707bc0.txt) |
| undici-types | 7.16.0 | MIT | [LICENSE](apps/app/notices/a6db8096b2707bc0.txt) |
| unenv | 2.0.0-rc.24 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| unhead | 2.1.17 | MIT | [LICENSE](apps/app/notices/d06451530138de11.txt) |
| unicorn-magic | 0.3.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| unicorn-magic | 0.4.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| unified | 11.0.5 | MIT | [license](apps/app/notices/05811400116ed61f.txt) |
| unifont | 0.7.3 | MIT | [LICENCE](apps/app/notices/a174fd5d58dfec7a.txt) |
| unimport | 5.7.0 | MIT | [LICENSE](apps/app/notices/5af3c68995307360.txt) |
| unimport | 6.5.0 | MIT | [LICENSE](apps/app/notices/5af3c68995307360.txt) |
| unist-util-find-after | 5.0.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| unist-util-is | 6.0.1 | MIT | [license](apps/app/notices/82974dbf2639d13e.txt) |
| unist-util-modify-children | 4.0.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| unist-util-position | 5.0.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| unist-util-position-from-estree | 2.0.0 | MIT | [license](apps/app/notices/807a88522a850092.txt) |
| unist-util-remove-position | 5.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| unist-util-stringify-position | 4.0.0 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| unist-util-visit | 5.1.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| unist-util-visit-children | 3.0.0 | MIT | [license](apps/app/notices/63cb98b3f6abfb3c.txt) |
| unist-util-visit-parents | 6.0.2 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| universalify | 2.0.1 | MIT | [LICENSE](apps/app/notices/3fda5977c0904e22.txt) |
| unplugin | 2.3.11 | MIT | [LICENSE](apps/app/notices/2ef2cbeeb84d5e7a.txt) |
| unplugin | 3.4.0 | MIT | [LICENSE](apps/app/notices/2ef2cbeeb84d5e7a.txt) |
| unplugin-dts | 1.0.3 | MIT | [LICENSE](apps/app/notices/0a5603fbbf7856d7.txt) |
| unplugin-utils | 0.3.2 | MIT | [LICENSE](apps/app/notices/fdb4c7395791e3ba.txt) |
| unplugin-vue-router | 0.19.2 | MIT | [LICENSE](apps/app/notices/15ba0a5ddf021991.txt) |
| unrs-resolver | 1.11.1 | MIT |  |
| unstorage | 1.17.4 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| unstorage | 1.17.5 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| untun | 0.2.2 | MIT | [LICENSE](apps/app/notices/db708a3ff8b0bc30.txt) |
| untyped | 2.0.0 | MIT | [LICENSE](apps/app/notices/96a82993436d17ab.txt) |
| unwasm | 0.5.3 | MIT | [LICENSE](apps/app/notices/46231df5a7733c3f.txt) |
| update-browserslist-db | 1.2.3 | MIT | [LICENSE](apps/app/notices/c414dde36704bd9c.txt) |
| update-browserslist-db | 1.3.3 | MIT | [LICENSE](apps/app/notices/9877e90da14aa8c9.txt) |
| uqr | 0.1.3 | MIT | [LICENSE](apps/app/notices/b39d50e24727f341.txt) |
| uri-js | 4.4.1 | BSD-2-Clause | [LICENSE](apps/app/notices/0af366eff4c01ec1.txt) |
| url-template | 3.1.1 | BSD-3-Clause | [LICENSE](apps/app/notices/978cee2a4419649e.txt) |
| use-sync-external-store | 1.6.0 | MIT | [LICENSE](apps/app/notices/da6d3703ed11cbe4.txt) |
| util-deprecate | 1.0.2 | MIT | [LICENSE](apps/app/notices/0154425673db15cd.txt) |
| validate-npm-package-license | 3.0.4 | Apache-2.0 | [LICENSE](apps/app/notices/cfc7749b96f63bd3.txt) |
| verkit | 0.3.2 | MIT | [LICENSE](apps/app/notices/9bdd8f6bcee5d0e8.txt) |
| vfile | 6.0.3 | MIT | [license](apps/app/notices/05811400116ed61f.txt) |
| vfile-location | 5.0.3 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| vfile-message | 4.0.3 | MIT | [license](apps/app/notices/dd1081884a929528.txt) |
| vite | 5.4.21 | MIT | [LICENSE.md](apps/app/notices/04d9940b3b8b372b.txt) |
| vite | 6.4.1 | MIT | [LICENSE.md](apps/app/notices/c6bfec08b0e78a19.txt) |
| vite | 7.3.6 | MIT | [LICENSE.md](apps/app/notices/a77a1c089806b39a.txt) |
| vite | 8.0.3 | MIT | [LICENSE.md](apps/app/notices/68b6ed369f7d3ff3.txt) |
| vite-dev-rpc | 2.0.0 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| vite-hot-client | 2.2.0 | MIT | [LICENSE](apps/app/notices/67cd5e903c1f908e.txt) |
| vite-node | 5.3.0 | MIT | [LICENSE](apps/app/notices/b702fad0bff2bd12.txt) |
| vite-plugin-checker | 0.12.0 | MIT | [LICENSE](apps/app/notices/de5da47fa106c7cb.txt) |
| vite-plugin-inspect | 11.4.1 | MIT | [LICENSE](apps/app/notices/b702fad0bff2bd12.txt) |
| vite-plugin-vue-tracer | 1.5.0 | MIT | [LICENSE.md](apps/app/notices/2a596f697b619094.txt) |
| vite-svg-loader | 5.1.0 | MIT | [LICENSE](apps/app/notices/d09e3b5add583716.txt) |
| vitefu | 1.1.1 | MIT | [LICENSE](apps/app/notices/ba7924d52a19d141.txt) |
| void-elements | 3.1.0 | MIT | [LICENSE](apps/app/notices/405a272eaef55669.txt) |
| volar-service-css | 0.0.68 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| volar-service-emmet | 0.0.68 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| volar-service-html | 0.0.68 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| volar-service-prettier | 0.0.68 | MIT | [LICENSE](apps/app/notices/a5e146ee0acef6fd.txt) |
| volar-service-typescript | 0.0.68 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| volar-service-typescript-twoslash-queries | 0.0.68 | MIT | [LICENSE](apps/app/notices/df52411dcd3c8f58.txt) |
| volar-service-yaml | 0.0.68 | MIT | [LICENSE](apps/app/notices/ec27ba2b3f854665.txt) |
| vscode-css-languageservice | 6.3.9 | MIT | [LICENSE.md](apps/app/notices/c3a24c02d678e5f0.txt) |
| vscode-html-languageservice | 5.6.1 | MIT | [LICENSE.md](apps/app/notices/c3a24c02d678e5f0.txt) |
| vscode-json-languageservice | 4.1.8 | MIT | [LICENSE.md](apps/app/notices/4742836d395a83a4.txt) |
| vscode-jsonrpc | 8.2.0 | MIT | [License.txt](apps/app/notices/ec9ee83580841e8e.txt) |
| vscode-languageserver | 9.0.1 | MIT | [License.txt](apps/app/notices/ec9ee83580841e8e.txt) |
| vscode-languageserver-protocol | 3.17.5 | MIT | [License.txt](apps/app/notices/ec9ee83580841e8e.txt) |
| vscode-languageserver-textdocument | 1.0.12 | MIT | [License.txt](apps/app/notices/ec9ee83580841e8e.txt) |
| vscode-languageserver-types | 3.17.5 | MIT | [License.txt](apps/app/notices/ec9ee83580841e8e.txt) |
| vscode-nls | 5.2.0 | MIT | [License.txt](apps/app/notices/8e7a245bb6b03e11.txt) |
| vscode-uri | 3.1.0 | MIT | [LICENSE.md](apps/app/notices/c669138cb1eb01fb.txt) |
| vue | 3.5.43 | MIT | [LICENSE](apps/app/notices/1bb85cc9b13b81ef.txt) |
| vue-bundle-renderer | 2.4.0 | MIT | [LICENSE.md](apps/app/notices/4e1bbdebcc63a4f4.txt) |
| vue-component-meta | 2.2.12 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| vue-component-type-helpers | 2.2.12 | MIT | [LICENSE](apps/app/notices/ac07310d94980d98.txt) |
| vue-component-type-helpers | 3.3.11 | MIT | [LICENSE](apps/app/notices/ac07310d94980d98.txt) |
| vue-confetti-explosion | 1.0.2 | See package sources | [LICENSE](apps/app/notices/2213c1ed79d0626c.txt) |
| vue-demi | 0.14.10 | MIT | [LICENSE](apps/app/notices/25b0ff5a880f9304.txt) |
| vue-devtools-stub | 0.1.0 | MIT | [LICENSE](apps/app/notices/24646edbdfa00baa.txt) |
| vue-docgen-api | 4.79.2 | MIT | [LICENSE](apps/app/notices/18d781a1190c8244.txt) |
| vue-eslint-parser | 10.2.0 | MIT | [LICENSE](apps/app/notices/fb58f56a8dab39ce.txt) |
| vue-eslint-parser | 9.4.3 | MIT | [LICENSE](apps/app/notices/fb58f56a8dab39ce.txt) |
| vue-i18n | 10.0.8 | MIT | [LICENSE](apps/app/notices/403a4d6f9815ae33.txt) |
| vue-inbrowser-compiler-independent-utils | 4.71.1 | MIT | [LICENSE](apps/app/notices/18d781a1190c8244.txt) |
| vue-observe-visibility | 2.0.0-alpha.1 | MIT |  |
| vue-resize | 2.0.0-alpha.1 | MIT |  |
| vue-router | 4.6.4 | MIT | [LICENSE](apps/app/notices/91a2845c4db44e74.txt) |
| vue-select | 4.0.0-beta.6 | MIT | [LICENSE.md](apps/app/notices/f290a9ac3bd0d3ea.txt) |
| vue-tsc | 2.2.12 | MIT | [LICENSE](apps/app/notices/a56351045b454753.txt) |
| vue-typed-virtual-list | 1.0.10 | Apache-2.0 | [LICENSE](apps/app/notices/ae630092a326193c.txt) |
| vue-virtual-scroller | 2.0.0-beta.8 | MIT | [LICENSE](apps/app/notices/73b6acd999671b53.txt) |
| vue3-ace-editor | 2.2.4 | MIT | [LICENSE](apps/app/notices/60b340d723f81abd.txt) |
| vue3-apexcharts | 1.10.0 | see LICENSE in LICENSE | [LICENSE](apps/app/notices/534b059f0ff483b8.txt) |
| vuedraggable | 4.1.0 | MIT | [LICENSE](apps/app/notices/8345d896e4db9d27.txt) |
| w3c-keyname | 2.2.8 | MIT | [LICENSE](apps/app/notices/869c30f368eb0873.txt) |
| w3c-xmlserializer | 5.0.0 | MIT | [LICENSE.md](apps/app/notices/ab654de803cdaa9e.txt) |
| web-namespaces | 2.0.1 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
| webidl-conversions | 3.0.1 | BSD-2-Clause | [LICENSE.md](apps/app/notices/a889cc4dbee2ae17.txt) |
| webidl-conversions | 7.0.0 | BSD-2-Clause | [LICENSE.md](apps/app/notices/a889cc4dbee2ae17.txt) |
| webpack-virtual-modules | 0.6.2 | MIT | [LICENSE](apps/app/notices/aa523c5b0d9c0223.txt) |
| whatwg-encoding | 3.1.1 | MIT | [LICENSE.txt](apps/app/notices/528eec83cb836a0a.txt) |
| whatwg-mimetype | 4.0.0 | MIT | [LICENSE.txt](apps/app/notices/528eec83cb836a0a.txt) |
| whatwg-url | 14.2.0 | MIT | [LICENSE.txt](apps/app/notices/db480f236292a093.txt) |
| whatwg-url | 5.0.0 | MIT | [LICENSE.txt](apps/app/notices/6b7a1792144374d8.txt) |
| which | 2.0.2 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| which | 6.0.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| which-pm-runs | 1.1.0 | MIT | [LICENSE](apps/app/notices/4339649ad03e633a.txt) |
| widest-line | 5.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| with | 7.0.2 | MIT | [LICENSE](apps/app/notices/5519d0442a0d5e5e.txt) |
| word-wrap | 1.2.5 | MIT | [LICENSE](apps/app/notices/73b5283588baa142.txt) |
| workerd | 1.20260730.1 | Apache-2.0 |  |
| wrangler | 4.116.0 | MIT OR Apache-2.0 |  |
| wrap-ansi | 7.0.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| wrap-ansi | 8.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| wrap-ansi | 9.0.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| wrappy | 1.0.2 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| ws | 8.21.0 | MIT | [LICENSE](apps/app/notices/2b29dcfe0d6471f7.txt) |
| ws | 8.22.0 | MIT | [LICENSE](apps/app/notices/2b29dcfe0d6471f7.txt) |
| wsl-utils | 0.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| wsl-utils | 1.0.1 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| xml | 1.0.1 | MIT | [LICENSE](apps/app/notices/d2b3e2f62078f282.txt) |
| xml-name-validator | 4.0.0 | Apache-2.0 | [LICENSE.txt](apps/app/notices/a6cba85bc92e0cff.txt) |
| xml-name-validator | 5.0.0 | Apache-2.0 | [LICENSE.txt](apps/app/notices/a6cba85bc92e0cff.txt) |
| xml2js | 0.6.2 | MIT | [LICENSE](apps/app/notices/c51452ef1dfd5606.txt) |
| xmlbuilder | 11.0.1 | MIT | [LICENSE](apps/app/notices/e368bc4263b466cf.txt) |
| xmlchars | 2.2.0 | MIT | [LICENSE](apps/app/notices/45d196313c2647d3.txt) |
| xss | 1.0.15 | MIT | [LICENSE](apps/app/notices/93dbf94b85881287.txt) |
| xxhash-wasm | 1.1.0 | MIT | [LICENSE.md](apps/app/notices/6f6b3afa109ea0d0.txt) |
| y18n | 5.0.8 | ISC | [LICENSE](apps/app/notices/2034cce3b6fafcdd.txt) |
| yallist | 3.1.1 | ISC | [LICENSE](apps/app/notices/4ec3d4c66cd87f5c.txt) |
| yallist | 5.0.0 | BlueOak-1.0.0 | [LICENSE.md](apps/app/notices/a49c9ba464796f65.txt) |
| yaml | 2.7.1 | ISC | [LICENSE](apps/app/notices/5bba27375d93e911.txt) |
| yaml | 2.8.2 | ISC | [LICENSE](apps/app/notices/5bba27375d93e911.txt) |
| yaml-language-server | 1.19.2 | MIT | [LICENSE](apps/app/notices/2a6ebc3c5b441f0a.txt) |
| yargs | 17.7.2 | MIT | [LICENSE](apps/app/notices/2f1a503bfab84b3b.txt) |
| yargs | 18.2.0 | MIT | [LICENSE](apps/app/notices/2f1a503bfab84b3b.txt) |
| yargs-parser | 21.1.1 | ISC | [LICENSE.txt](apps/app/notices/365496ca1f56da40.txt) |
| yargs-parser | 22.0.0 | ISC | [LICENSE.txt](apps/app/notices/365496ca1f56da40.txt) |
| yocto-queue | 0.1.0 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| yocto-queue | 1.2.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| yocto-spinner | 0.2.3 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| yoctocolors | 2.1.2 | MIT | [license](apps/app/notices/5c932d88256b4ab9.txt) |
| youch | 4.1.0-beta.10 | MIT | [LICENSE.md](apps/app/notices/bba2399e2c617b05.txt) |
| youch | 4.1.1 | MIT | [LICENSE.md](apps/app/notices/bba2399e2c617b05.txt) |
| youch-core | 0.3.3 | MIT | [LICENSE.md](apps/app/notices/26e09f87efc06dfb.txt) |
| zip-stream | 6.0.1 | MIT | [LICENSE](apps/app/notices/79bad9f51738814f.txt) |
| zod | 3.25.76 | MIT | [LICENSE](apps/app/notices/3f1189b28e3866e0.txt) |
| zod-to-json-schema | 3.25.1 | ISC | [LICENSE](apps/app/notices/80d3168ad2f70f6f.txt) |
| zod-to-ts | 1.2.0 | See package sources | [LICENSE](apps/app/notices/901eb546213d3447.txt) |
| zwitch | 2.0.4 | MIT | [license](apps/app/notices/ca4662cb5d1b738f.txt) |
