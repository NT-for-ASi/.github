## AppleWOA Project Home Page

Hello! This organization is host to all the repositories that deal with the AppleWOA project, such as drivers, ancillary applications, and the UEFI and bootloader implementations along with the patchers needed for Apple hardware to boot Windows.

Current project maintainers:
- Arminder Singh ([amarioguy](https://github.com/amarioguy)) - project lead, co-developer
- [graphine27](https://github.com/graphine27) - co-developer
- [zx](https://github.com/48cf) - co-developer

## Disclaimer

This project is not affiliated or associated with Apple, Microsoft, or the Asahi Linux project, and is an independent venture born out of a love for the Apple silicon platform and the potential it can bring to Windows's ARM64 port.

### Project Links

Discord: https://discord.gg/djXD4hXyYB (where most *active* discussion takes place)

Telegram: https://t.me/AppleWOA (an alternate place to discuss AppleWOA (the project itself mainly))

## Highlighted repos

Below are the main repositories for the project. Note that some efforts (patchers are among these) may be an ancillary part of a repository rather than being it's own repository.

[Apple Silicon Project Mu repository](https://github.com/AppleWOA/apple_silicon_platforms_mu) - this is the main repository for the UEFI implementation and is where most (current) work takes place.

[m1n1, forked for better compatibility with non-Linux or UNIX-like guests](https://github.com/AppleWOA/m1n1_windows) - this is the repository for the fork of m1n1 that will be used to boot Windows for now. Currently being tweaked to remove dependence on a computer to boot under the hypervisor.

[NT Drivers repository](https://github.com/AppleWOA/apple_silicon_nt_drivers) - hosts the source for the Windows drivers for Apple platforms (as of 10/10/2025, HAL Extension for AIC mainly)
