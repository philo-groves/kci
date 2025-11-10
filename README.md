## Kernel Continuous Integration (kci)

A reusable source for automatically running tests for kernels built with `kboot` and `ktest`. Test results are assessed and reported back to the cloud-based runner (e.g. Github Actions).

This project is in early development.

### Kernel Compatibility

#### Bootloaders
- ✅ Bootloader (rust crate)
- ❌ Limine

#### Image Type
- ✅ BIOS
- ✅ UEFI

### Architectures
- ✅ x86-64
- ❌ aarch64
- ❌ risc-v