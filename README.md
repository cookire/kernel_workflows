# Kernel recommendations:


### Mi 8 Pro (equuleus)


# Kernel Labels:

The kernel label uses the following format:
- `buildDate-deviceName-buildType-kernelVariant-runNumber`
As an example you can see:
- `2025.06.18-MiA3-KSU-SM6125-22.2-148`

### buildDate
The date the kernel was built following the format: `YYYY.MM.DD`.
### deviceName
The name of the device the kernel is built for, like `MiA3`.
### buildType
The type of the build, it can be the following:
- Normal (empty)
- KSU (-KSU)
- RKSU (-RKSU)
- KSUN (-KSUN)

For SUSFS variants, the buildType receives a `.SUSFS` suffix.

### runNumber
Simply the number of the github run, don't use this as a definitive versioning metric, always base yourself on the build date.

# Kernels used when building:
 - [Lineage](https://github.com/cookire/android_kernel_xiaomi_sdm845) • NON-RDP

# Credits:

**Kernel Sources**:
- [@TheSillyOk](https://github.com/TheSillyOk) -> Created this github action
- [@CZB666-wdnmd](https://github.com/CZB666-wdnmd/android_kernel_xiaomi_sdm845) -> Kernel

**Workflow/Patches**:
- [@TheWildJames](https://github.com/TheWildJames) -> workflow reference, patches
- [@simonpunk](https://gitlab.com/simonpunk) -> susfs patches
- [@sidex15](https://github.com/sidex15) -> susfs patches
