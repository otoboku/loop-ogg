# Third-Party Notices and Licenses

This project (`loop-ogg`) includes and links against third-party software under various open-source licenses.

---

## 1. C/C++ Native System Dependencies

The binary release may statically or dynamically link against the following native libraries:

### libsoxr
* **License:** LGPL-2.1-or-later / BSD-3-Clause
* **Copyright:** Copyright (c) 2013 Rob Sykes
* **Website:** https://sourceforge.net/projects/soxr/
* **Notice:** `loop-ogg` is open-source under MIT/Apache-2.0. In compliance with LGPL-2.1 section 6, users are free to re-link or re-compile this application with modified versions of `libsoxr` using the source code provided at our repository.

### PortAudio
* **License:** MIT-style (SCAE License)
* **Copyright:** Copyright (c) 1999-2006 Ross Bencina and Phil Burk
* **Website:** http://www.portaudio.com/

---

## 2. Rust Crates Dependencies

This project uses the following Rust crates (for full automated license details, see `THIRD_PARTY_LICENSES.html` included in the distribution):

* **Apache-2.0 / MIT Dual License:**
  `anyhow`, `atty`, `bitflags`, `byteorder`, `cc`, `cfg-if`, `clap`, `clap_derive`, `ctrlc`, `env_logger`, `hashbrown`, `heck`, `hermit-abi`, `humantime`, `indexmap`, `lazy_static`, `libc`, `libsoxr` (Rust crate), `libsoxr-sys`, `log`, `memchr`, `memoffset`, `nix`, `num`, `num-integer`, `num-iter`, `num-traits`, `os_str_bytes`, `pkg-config`, `portaudio` (Rust crate), `proc-macro-error`, `proc-macro2`, `quote`, `regex`, `regex-syntax`, `strsim`, `syn`, `termcolor`, `terminal_size`, `textwrap`, `tinyvec`, `unicode-xid`, `winapi`, `winapi-util`

* **BSD-3-Clause / BSD-2-Clause / CC0 / Unlicense:**
  `aho-corasick`, `autocfg`, `lewton`, `ogg`, `tinyvec_macros`, `version_check`
