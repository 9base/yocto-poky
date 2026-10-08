> [!NOTE]
> **9base status: Preserved** · **Lifecycle: archived reference copy.**
>
> This is a historical fork of [TinkerBoard2/yocto-poky](https://github.com/TinkerBoard2/yocto-poky).
> 9base retains it for provenance and reference and does not actively maintain it.
> Upstream source and inherited authorship remain attributed to their original contributors.

# yocto-poky — 9base preservation notes

## Role and inherited divergence

This is the Poky/OpenEmbedded/BitBake source component named by the Tinker
Board 2 Linux BSP manifest. The retained default branch is
`linux4.19-rk3399-debian10`.

The 8 October 2026 comparison against the same-named `TinkerBoard2/yocto-poky`
branch found **26 ahead / 4,044 behind**. It is a divergent preserved snapshot,
not an identical mirror. Every returned ahead commit is generic Yocto/Poky
documentation or package metadata work by other upstream contributors dated
October-November 2020, with messages tracing Yocto documentation or OE-Core
revisions. The local tip is also from 2020. These counts do not demonstrate
9base-authored development. No account-linked Zaryob-authored commits were
returned; this does not exhaustively resolve unlinked historical identities.

The 9base repository object was created on 18 September 2022; that timestamp
does not prove when it entered the organization. Its recorded push timestamp
predates that object-creation date, reinforcing why repository timestamps
alone cannot be treated as local contribution evidence.

The original upstream documentation remains unchanged:

- [README.poky](README.poky) — Poky overview;
- [README.OE-Core](README.OE-Core) — OpenEmbedded-Core overview;
- [README.qemu](README.qemu) — QEMU notes;
- [README.hardware](README.hardware) — generic Yocto reference BSP notes.

The reference hardware README is not evidence of a complete Tinker Board 2
configuration in this repository. The manifest references additional vendor
layers and components outside this retained family. Existing license files
and inherited commit attribution are preserved; no current BSP build or
synchronization policy is asserted.

## Tinker Board 2 platform family

| Layer | Preserved 9base repository |
| --- | --- |
| Linux checkout manifests | [Tinkerboard2-manifest](https://github.com/9base/Tinkerboard2-manifest) |
| Linux kernel | [Tinkerboard2-kernel](https://github.com/9base/Tinkerboard2-kernel) |
| U-Boot bootloader | [Tinkerboard2-uboot](https://github.com/9base/Tinkerboard2-uboot) |
| Buildroot build system | [Tinkerboard2-buildroot](https://github.com/9base/Tinkerboard2-buildroot) |
| Debian/rootfs scripts | [Tinkerboard2-debian](https://github.com/9base/Tinkerboard2-debian) |
| Rockchip firmware and loaders | [Tinkerboard2-rkbin](https://github.com/9base/Tinkerboard2-rkbin) |
| Poky/OpenEmbedded/BitBake | [yocto-poky](https://github.com/9base/yocto-poky) |
| Android checkout manifests | [Tinkerboard2Android-manifest](https://github.com/9base/Tinkerboard2Android-manifest) |

The [Linux release manifest](https://github.com/9base/Tinkerboard2-manifest/blob/linux4.19-rk3399-debian10/default.xml) explicitly names the kernel, U-Boot,
Buildroot, Debian, rkbin and yocto-poky components. Its remote still points to
`TinkerBoard2`, not these 9base forks; it does not automatically select 9base's
historical Debian fix. This family is only a retained subset of the vendor's
larger source graph, not a self-contained complete BSP checkout.

The Android manifests concern the same board family but target a separate
`TinkerBoard2-Android` source graph; they do not establish use of these 9base
Linux components.

## Historical note

These preservation notes were reconstructed on **8 October 2026** from the
repository tree, exposed branches, commit history and upstream comparisons.
They are new archival documentation, not evidence that this explanation existed
at the historical fork date. The original reason for retention or any deployment
is not established by the inspected record. No contemporary build, support or
upstream synchronization commitment is implied.

The original upstream [README.hardware](README.hardware) is retained as a separate,
unchanged file. Its historical content and other README variants are preserved.
