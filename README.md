# awesome-rust-safety-critical
Entry points on discovering the safety critical rust ecosystem.

# Tools
## Toolchain
- [Ferrocene](https://ferrocene.dev/) Qualified Compiler Toolchain for Rust
- [AdaCore GNAT PRO](https://www.adacore.com/gnatpro-rust) Qualified Compiler Toolchain for Rust

## Analysis
- [Clippy](https://github.com/rust-lang/rust-clippy) Official Rust linting tool
- [Geiger](https://github.com/geiger-rs/cargo-geiger) A tool that lists statistics related to the usage of unsafe Rust code in a Rust crate and all its dependencies.
- [Kani](https://github.com/model-checking/kani) Formal verification framework built on CMBC.
- [Pristi](https://github.com/viperproject/prusti-dev) Formal verification framework based on Viper.
- [Creusot](https://github.com/creusot-rs/creusot) Deductive verifier for Rust code.
- [MIRI](https://github.com/rust-lang/miri) MIR analysis tool.
- [Seahorn](https://seahorn.github.io/) Analysis framework for LLVM languages like Rust.

## Memory Safety
- [rlsf](https://github.com/yvt/rlsf) Constant time memory allocator for embedded & safety systems.

## OS & Runtimes
- [Hubris](https://github.com/oxidecomputer/hubris) A Rust microkernel for embedded systems with safety requirements

# Ressources
## Communities
- [Safety Critical Rust Consortium](https://github.com/rustfoundation/safety-critical-rust-consortium) Consortium on safety-critical Rust by the Rust Foundation and industry partners.
- [safety-dance](https://github.com/rust-secure-code/safety-dance?tab=readme-ov-file) Community around the use of `unsafe` in Rust
## Papers
- [Bringing Rust to Safety-Critical Systems in Space](https://indico.esa.int/event/528/attachments/5988/10197/Bringing_Rust_to_Safety_Critical_Systems_in_Space.pdf) 
## Articels
- [Rust is DO-178C Certifiable](https://blog.pictor.us/rust-is-do-178-certifiable/#:~:text=With%20developments%20such%20as%20the,remain%20are%20awareness%20and%20education.)
## Sites
- [Ferrous Sytems Blog](https://ferrous-systems.com/blog/)
- [arewesafetycriticalyet.org](https://arewesafetycriticalyet.org/) Website of the Safety Critical Rust Consortium
## Other
- [misra-rust](https://github.com/adfernandes/misra-rust) Experimentation of what MISRA-C rules are covered by the Rust compiler