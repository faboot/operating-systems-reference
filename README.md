# Operating Systems Reference

*A curated, chronologically ordered reference of notable operating
systems and platforms.*

This document groups related systems into themed sections and lists
them from oldest to newest within each category, alongside their
official project resources.

**88 systems across 8 families** — BSD, Linux, GNU, illumos, Xen-based,
experimental/research, Apple, and Windows-based custom builds. Every
entry carries its first public release date, official website, source
repositories, and a short overview quoting the project's own words.

> **Scope and sourcing.** Descriptions quote each project's own official
> site or repository wherever a usable statement exists; the rest is
> written from those same sources. Entries are ordered by first public
> availability, not by rename or stable-release date — so, for example,
> Raspberry Pi OS is dated from Raspbian (2012) and Solus from
> Evolve OS (2014).

## Downloads

| Format | Description |
| --- | --- |
| [PDF](Operating-Systems-Reference.pdf) | 31 pages, printable, with clickable links |
| [JSON](operating-systems.json) | Structured data — build something on top of it |
| [CSV](operating-systems.csv) | Opens directly in Excel or LibreOffice |

The PDF, JSON, and CSV are all generated from this file, so they stay in
step with it.

## Contributing

Corrections, missing systems, and dead links are all fair game — open an
issue or a pull request. A few conventions keep the file consistent:

- **Dates** are the first *public* release, not a rename or a founding
  announcement. Cite the source.
- **Quotes** come from the project's own site or repository, kept short.
- **Repositories**: if a project's GitHub is a mirror, label it as one
  and link the canonical tree.
- One system per pull request keeps review easy.

## License

Licensed under [CC BY-SA 4.0](LICENSE). Quotations remain the property
of their respective projects and are used for identification and
commentary.

## Table of Contents

**I. BSD Family**

- [1. NetBSD](#1-netbsd)
- [2. FreeBSD](#2-freebsd)
- [3. OpenBSD](#3-openbsd)
- [4. DragonFly BSD](#4-dragonfly-bsd)
- [5. MidnightBSD](#5-midnightbsd)
- [6. GhostBSD](#6-ghostbsd)
- [7. HardenedBSD](#7-hardenedbsd)

**II. Linux Distributions**
- [1. Linux From Scratch](#1-linux-from-scratch)
- [2. Gentoo](#2-gentoo)
- [3. Arch Linux](#3-arch-linux)
- [4. Puppy Linux](#4-puppy-linux)
- [5. Fedora](#5-fedora)
- [6. Ubuntu](#6-ubuntu)
- [7. Kubuntu](#7-kubuntu)
- [8. Alpine Linux](#8-alpine-linux)
- [9. Xubuntu](#9-xubuntu)
- [10. Linux Mint](#10-linux-mint)
- [11. Trisquel](#11-trisquel)
- [12. Calculate Linux](#12-calculate-linux)
- [13. Void Linux](#13-void-linux)
- [14. Tails](#14-tails)
- [15. Mageia](#15-mageia)
- [16. Manjaro](#16-manjaro)
- [17. Whonix](#17-whonix)
- [18. Kali Linux](#18-kali-linux)
- [19. Parrot OS](#19-parrot-os)
- [20. OpenMandriva](#20-openmandriva)
- [21. Solus](#21-solus)
- [22. Ubuntu MATE](#22-ubuntu-mate)
- [23. KDE neon](#23-kde-neon)
- [24. Devuan](#24-devuan)
- [25. Artix Linux](#25-artix-linux)
- [26. Pop!_OS](#26-pop_os)
- [27. EndeavourOS (Antergos’ successor)](#27-endeavouros-antergos-successor)
- [28. Ubuntu Cinnamon](#28-ubuntu-cinnamon)
- [29. GNOME OS](#29-gnome-os)
- [30. CachyOS](#30-cachyos)
- [31. Nobara Linux](#31-nobara-linux)
- [32. TUXEDO OS](#32-tuxedo-os)
- [33. PikaOS Linux](#33-pikaos-linux)
- [34. Vanilla OS](#34-vanilla-os)
- [35. blendOS](#35-blendos)
- [36. Chimera Linux](#36-chimera-linux)
- [37. Vendefoul Wolf Linux](#37-vendefoul-wolf-linux)
- [38. secureblue](#38-secureblue)
- [39. aerynOS](#39-aerynos)
- [40. KDE Linux](#40-kde-linux)
- [41. Ageless Linux](#41-ageless-linux)

**Additional Linux Distributions (Specialized & Niche Use Cases)**

- [42. Slackware](#42-slackware)
- [43. antiX Linux](#43-antix-linux)
- [44. Tiny Core Linux](#44-tiny-core-linux)
- [45. Zorin OS](#45-zorin-os)
- [46. Parabola GNU/Linux-libre](#46-parabola-gnulinux-libre)
- [47. Peppermint OS](#47-peppermint-os)
- [48. SparkyLinux](#48-sparkylinux)
- [49. Raspberry Pi OS](#49-raspberry-pi-os)
- [50. Bedrock Linux](#50-bedrock-linux)
- [51. BlackArch](#51-blackarch)
- [52. MX Linux](#52-mx-linux)
- [53. Archman Linux](#53-archman-linux)
- [54. RebornOS](#54-rebornos)
- [55. Archcraft](#55-archcraft)
- [56. Asahi Linux](#56-asahi-linux)

**III. Systems Independent (GNU)**

- [1. GNU Project (gnu.org)](#1-gnu-project-gnuorg)
- [2. GNU Guix](#2-gnu-guix)

**IV. illumos Family**

- [1. illumos](#1-illumos)
- [2. OpenIndiana](#2-openindiana)
- [3. SmartOS](#3-smartos)
- [4. OmniOS](#4-omnios)
- [5. Tribblix](#5-tribblix)

**V. Xen-Based Systems**

- [1. Xen](#1-xen)
- [2. Qubes OS](#2-qubes-os)

**VI. Experimental & Research Systems**

- [1. FreeDOS](#1-freedos)
- [2. ReactOS](#2-reactos)
- [3. Haiku](#3-haiku)
- [4. Redox OS](#4-redox-os)
- [5. SerenityOS](#5-serenityos)

**VII. Apple Platforms (Operating Systems & Services)**

  *Operating Systems*
- [1. macOS](#1-macos)
- [2. iOS](#2-ios)
  *Services*
- [3. Apple](#3-apple)
- [4. Apple Account](#4-apple-account)
- [5. iCloud](#5-icloud)

**VIII. Windows-Based Custom Systems (Debloated & Community Builds)**

- [1. Windows](#1-windows)
- [2. Revision (ReviOS)](#2-revision-revios)
- [3. AtlasOS](#3-atlasos)
- [4. Windows X-Lite](#4-windows-x-lite)
- [5. Tiny11](#5-tiny11)
- [6. Nano11](#6-nano11)

------------------------------------------------------------------------
------------------------------------------------------------------------

# I. BSD Family

*A set of Unix-like operating systems descended from the Berkeley Software
Distribution, covering portable, performance-oriented, desktop, and
security-hardened BSD variants.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. NetBSD

-   **Initial Release:** Apr 1993
-   **Official Website:** <https://www.netbsd.org>
-   **Source Repository (CVS):** <https://cvsweb.netbsd.org>
-   **GitHub Mirror:** <https://github.com/NetBSD>
-   **Overview:** NetBSD — *"Of course it runs NetBSD"* — is a
    highly portable Unix-like operating system built around clean design
    and broad hardware support; for example, the same codebase runs on
    everything from VAX minicomputers and vintage home computers to
    modern ARM boards and Raspberry Pis, which is where its long-running
    slogan comes from in the first place.

------------------------------------------------------------------------

## 2. FreeBSD

-   **Initial Release:** Nov 1993
-   **Official Website:** <https://www.freebsd.org>
-   **Source Repository:** <https://cgit.freebsd.org>
-   **GitHub Mirror:** <https://github.com/freebsd>
-   **Overview:** FreeBSD — known for decades by its motto *"The Power
    to Serve"* — is a performance-oriented Unix-like system widely
    deployed in servers and infrastructure; for example, its networking
    stack and ZFS support have made it the base underneath large
    platforms like Netflix's content-delivery network and Sony's
    PlayStation operating system.

------------------------------------------------------------------------

## 3. OpenBSD

-   **Initial Release:** Jul 1996
-   **Official Website:** <https://www.openbsd.org>
-   **GitHub:** <https://github.com/openbsd>
-   **Game of Trees (Got) Mirror:** <https://openbsd.gothub.org/index.html>
-   **Overview:** OpenBSD's own homepage sums up its efforts as
    *"portability, standardization, correctness, proactive security and
    integrated cryptography"*; for example, the project performs a
    continuous, ongoing source-code security audit of its own codebase,
    and its OpenSSH tool — now the standard way most of the internet
    logs into remote servers — was itself born out of OpenBSD.

------------------------------------------------------------------------

## 4. DragonFly BSD

-   **Initial Release:** Jul 2003
-   **Official Website:** <https://www.dragonflybsd.org>
-   **Source Repository:** <https://gitweb.dragonflybsd.org/?p=dragonfly.git;a=summary>
-   **GitHub:** <https://github.com/DragonFlyBSD>
-   **Overview:** DragonFly BSD is a FreeBSD fork that, in the project's
    own words, *"provides an opportunity for the BSD base to grow in an
    entirely different direction"*; for example, its HAMMER2 filesystem
    and LWKT threading model were built from scratch by creator Matthew
    Dillon specifically to solve scalability problems he foresaw in
    FreeBSD's own approach to multiprocessing.

------------------------------------------------------------------------

## 5. MidnightBSD

-   **Initial Release:** Aug 2007
-   **Official Website:** <https://www.midnightbsd.org>
-   **GitHub:** <https://github.com/MidnightBSD>
-   **Overview:** MidnightBSD — *"a desktop operating system for x86 and
    x86-64 based PCs"* — is a FreeBSD derivative built specifically for
    everyday desktop use rather than servers; for example, it ships
    Xfce as its default desktop and bundles email, web browsing, and
    office software out of the box, filling a gap its founder felt
    FreeBSD itself had long overlooked.

------------------------------------------------------------------------

## 6. GhostBSD

-   **Initial Release:** Mar 2010
-   **Official Website:** <https://www.ghostbsd.org>
-   **GitHub:** <https://github.com/ghostbsd>
-   **Overview:** GhostBSD is *"a user-friendly, open-source operating
    system based on FreeBSD"*, designed to provide a secure and
    efficient desktop experience for everyone; for example, it ships a
    ready-to-use MATE desktop out of the box and follows a slow,
    conservative release cycle rather than chasing bleeding-edge
    packages, making FreeBSD approachable for people coming from a
    regular Linux desktop.

------------------------------------------------------------------------

## 7. HardenedBSD

-   **Initial Release:** 2014
-   **Official Website:** <https://hardenedbsd.org>
-   **GitHub:** <https://github.com/HardenedBSD>
-   **Overview:** HardenedBSD — *"implements strong exploit mitigations
    and security hardening technologies on top of FreeBSD"* — began in
    2013 as an Address Space Layout Randomization (ASLR) patch for
    FreeBSD before growing into a full security-focused fork; for
    example, the firewall project OPNsense adopted HardenedBSD's ASLR
    implementation in 2016, and by 2019 had migrated to HardenedBSD
    entirely.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# II. Linux Distributions

*A broad catalog of general‑purpose, security‑focused, gaming, and
immutable Linux distributions, organized chronologically and linked to
their official project resources.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. Linux From Scratch

-   **Initial Release:** 1998
-   **Official Website:** <https://www.linuxfromscratch.org>
-   **Source Repository:** <https://git.linuxfromscratch.org>
-   **GitHub Mirror:** <https://github.com/lfs-book>
-   **Overview:** Linux From Scratch (LFS) — *"Your Distro, Your
    Rules"* — is a project that provides step-by-step instructions for
    building a custom Linux system entirely from source code, letting
    users understand and control every component of their operating
    system; for example, choosing their own init system, C library, or
    kernel configuration instead of inheriting someone else's defaults.

------------------------------------------------------------------------

## 2. Gentoo

-   **Initial Release:** 1999, 2000, 2001, Mar 2002
-   **Official Website:** <https://www.gentoo.org>
-   **Source Repository:** <https://gitweb.gentoo.org>
-   **GitHub Mirror:** <https://github.com/gentoo>
-   **Codeberg:** <https://codeberg.org/gentoo/gentoo>
-   **Overview:** Gentoo — *"can be automatically optimized and
    customized for just about any application or need"* — is a
    source-based Linux distribution built around the Portage package
    manager, which compiles software locally rather than installing
    pre-built binaries; for example, a user can toggle specific USE
    flags to build the very same package differently for a lightweight
    server versus a full gaming desktop.

------------------------------------------------------------------------

## 3. Arch Linux

-   **Initial Release:** 2001, Mar 2002
-   **Official Website:** <https://archlinux.org>
-   **GitLab:** <https://gitlab.archlinux.org/archlinux>
-   **Overview:** Arch Linux — *"a lightweight and flexible Linux
    distribution that tries to Keep It Simple"* — ships mostly
    unmodified upstream software and lets users build up their system
    package by package with `pacman`; for example, the community-run
    Arch User Repository (AUR) adds thousands of user-submitted
    packages on top of the official repositories.

------------------------------------------------------------------------

## 4. Puppy Linux

-   **Initial Release:** Jun 2003
-   **Official Website:** <https://puppylinux-woof-ce.github.io>
-   **GitHub:** <https://github.com/puppylinux-woof-ce>
-   **Overview:** Puppy Linux — *"a collection of multiple Linux
    distributions"* built on the same shared tools and principles — is
    designed to be ready to use, typically 1.5 GB or less in size, and
    customizable within minutes; for example, several official variants
    are built on top of Ubuntu, Debian, or Slackware packages while
    keeping the same lightweight Puppy-specific desktop and utilities.

------------------------------------------------------------------------

## 5. Fedora

-   **Initial Release:** Nov 2003
-   **Official Website:** <https://fedoraproject.org>
-   **Source Repository:** <https://forge.fedoraproject.org>
-   **Overview:** Fedora — sponsored by Red Hat and shaped by
    *"an innovative, free, and open source platform for hardware,
    clouds, and containers"* — ships several official editions built
    from the same upstream packages; for example, Fedora Workstation
    targets everyday desktop use while Fedora CoreOS and Fedora IoT
    package that same base for container hosts and embedded devices,
    and its immutable Fedora Atomic base — Silverblue with GNOME,
    Kinoite with KDE Plasma, among others — has, in turn, become a
    foundation other projects build on top of. Beyond the main
    editions, Fedora also offers official Spins that swap in a
    different desktop from the same repositories — KDE Plasma, Xfce,
    MATE, and others — and Labs, curated software bundles built for a
    specific field, such as the Astronomy Lab or the Security Lab, so
    someone in a particular niche gets a ready-to-go Fedora tailored to
    it from day one.

------------------------------------------------------------------------

## 6. Ubuntu

-   **Initial Release:** Oct 2004

-   **Official Website:** <https://ubuntu.com>
-   **Launchpad:** <https://code.launchpad.net/ubuntu>
-   **GitHub:** <https://github.com/ubuntu>
-   **Project Reference GitHub:** <https://github.com/canonical>

-   **Overview:** Ubuntu — *"the modern, open source operating system
    on Linux for the enterprise"* — is a Debian-based distribution
    developed by Canonical, released in Desktop, Server, and Core
    editions; for example, the same underlying system that runs on a
    developer's laptop also powers unmodified instances on AWS, Azure,
    and Google Cloud, and embedded devices through Ubuntu Core. Its
    official Flavours program lets Canonical-recognized teams swap in a
    different desktop on that same base — Kubuntu, Xubuntu, and Ubuntu
    MATE among them.

-   **Releases Portal:** <https://releases.ubuntu.com> Official archive of
    stable Ubuntu Desktop and Server ISO releases.

-   **CD Image Server:** <https://cdimage.ubuntu.com> Source for official
    ISO images including development and alternative builds.

-   **Checksum Reference:** <https://help.ubuntu.com/community/UbuntuHashes>
    Documentation for verifying SHA256 checksums and signatures.

-   **Verification Guide:** <https://ubuntu.com/tutorials/how-to-verify-ubuntu>
    or
    <https://discourse.ubuntu.com/t/how-to-verify-your-ubuntu-download/14010>
    Official tutorial explaining how to verify downloaded Ubuntu images.

------------------------------------------------------------------------

## 7. Kubuntu

-   **Initial Release:** Apr 2005
-   **Official Website:** <https://kubuntu.org>
-   **GitHub:** <https://github.com/kubuntu-team>
-   **Overview:** Kubuntu — *"The Elegant Linux Distribution"* — is an
    official Ubuntu flavor that swaps the default GNOME desktop for KDE
    Plasma; for example, its built-in KRunner launcher can open files,
    convert currencies, or control music playback from one keyboard
    shortcut, all on top of the same package base and release schedule
    as standard Ubuntu.

------------------------------------------------------------------------

## 8. Alpine Linux

-   **Initial Release:** Aug 2005
-   **Official Website:** <https://alpinelinux.org>
-   **GitLab:** <https://gitlab.alpinelinux.org/alpine>
-   **GitHub:** <https://github.com/alpinelinux>
-   **Overview:** Alpine Linux — *"Small. Simple. Secure."* — is built
    around musl libc and BusyBox instead of glibc and GNU coreutils,
    keeping a minimal container image under 8 MB; for example, its
    compiled binaries use position-independent execution with
    stack-smashing protection by default, part of why it's a common
    base image for Docker containers.

------------------------------------------------------------------------

## 9. Xubuntu

-   **Initial Release:** Jun 2006
-   **Official Website:** <https://xubuntu.org>
-   **GitHub:** <https://github.com/Xubuntu>
-   **Overview:** Xubuntu — *"a light, stable and configurable desktop
    environment with conservative workflows"* — is an Ubuntu flavor
    built around Xfce; for example, it keeps a traditional panel-and-menu
    layout and modest default resource use, making it a common pick for
    older or lower-specification hardware that still needs a full
    desktop experience.

------------------------------------------------------------------------

## 10. Linux Mint

-   **Initial Release:** Aug 2006
-   **Official Website:** <https://linuxmint.com>
-   **GitHub:** <https://github.com/linuxmint>
-   **Overview:** Linux Mint — built to be *"a modern, elegant and
    comfortable operating system"* that's both powerful and easy to
    use — is developed on top of Ubuntu and Debian; for example, its
    own Cinnamon desktop, Update Manager, and Software Manager are all
    built in-house specifically to keep updates conservative and avoid
    the regressions that can come with more aggressive rolling
    releases.

------------------------------------------------------------------------

## 11. Trisquel

-   **Initial Release:** Jan 2007 (first public release); project
    development began in 2004
-   **Official Website:** <https://trisquel.info>
-   **GitLab:** <https://gitlab.trisquel.org/trisquel>
-   **Overview:** Trisquel — *"a 100% free operating system"* — is an
    Ubuntu-based, FSF-endorsed GNU/Linux distribution with every piece
    of proprietary software, firmware, and driver blob stripped out or
    replaced; for example, the project was born at the University of
    Vigo in Spain to serve as an educational operating system with
    Galician-language support, was officially presented in April 2005
    with Richard Stallman's own backing, and ships MATE as its default
    desktop for a lighter, more traditional feel than stock Ubuntu.

------------------------------------------------------------------------

## 12. Calculate Linux

-   **Initial Release:** Jun 2007
-   **Official Website:** <https://www.calculate-linux.org>
-   **GitHub:** <https://github.com/calculatelinux>
-   **Source Repository:** <https://git.calculate-linux.org/calculate>
-   **Overview:** Calculate Linux is a Gentoo-based Linux distribution
    developed by Calculate Ltd., optimized for fast, ready-to-use deployment
    in organization environments. It layers the Calculate and Distros Portage
    overlays on top of Gentoo, offering Desktop, Directory Server, and Scratch
    editions with prebuilt binary packages while remaining fully
    Portage-compatible — *"a fast and functional user-friendly Linux
    distribution, based on Gentoo"*, with a rolling-release model and a
    consistent, familiar desktop experience across KDE, Cinnamon, MATE,
    Xfce, or LXQt.

------------------------------------------------------------------------

## 13. Void Linux

-   **Initial Release:** 2008
-   **Official Website:** <https://voidlinux.org>
-   **GitHub:** <https://github.com/void-linux>
-   **Overview:** Void Linux — *"a general purpose operating system,
    based on the monolithic Linux kernel"* — is not a fork of any
    existing distribution; its `XBPS` package manager and runit-based init
    system were both written from scratch, and software is available as
    prebuilt binaries or built directly from source via the `xbps-src`
    collection.

------------------------------------------------------------------------

## 14. Tails

-   **Initial Release:** Jun 2009
-   **Official Website:** <https://tails.net>
-   **GitLab:** <https://gitlab.tails.boum.org/tails/tails>
-   **Overview:** Tails — *"a portable operating system that protects
    against surveillance and censorship"* — boots from a USB stick and
    routes all its Internet traffic through the Tor network; for
    example, it leaves no trace on the computer once shut down, and
    journalists, activists, and domestic-violence survivors have used it
    specifically to keep sensitive work off a shared or monitored
    machine.

------------------------------------------------------------------------

## 15. Mageia

-   **Initial Release:** Jun 2011
-   **Official Website:** <https://www.mageia.org>
-   **Source Repository:** <https://gitweb.mageia.org/>
-   **Overview:** Mageia — *"Stable, secure operating system for
    desktop & server"* — is a non-profit, community-run continuation
    of Mandriva Linux, formed in 2010 by former Mandriva employees and
    contributors; for example, its own Mageia Control Center lets a
    user configure hardware, networking, and system settings from one
    graphical tool, across a choice of KDE Plasma, GNOME, Xfce,
    Cinnamon, MATE, LXQt, or Enlightenment desktops.

------------------------------------------------------------------------

## 16. Manjaro

-   **Initial Release:** Jul 2011
-   **Official Website:** <https://manjaro.org>
-   **GitLab:** <https://gitlab.manjaro.org>
-   **GitHub:** <https://github.com/manjaro>
-   **Overview:** Manjaro is *"a user-friendly Linux distribution based
    on the independently developed Arch operating system"*; for
    example, it holds packages back in its own testing and stable
    branches before they reach users, and ships a graphical Manjaro
    Hardware Detection tool, both meant to smooth over the rough edges
    that come with using Arch directly.

------------------------------------------------------------------------

## 17. Whonix

-   **Initial Release:** Feb 2012
-   **Official Website:** <https://www.whonix.org>
-   **GitLab:** <https://gitlab.com/whonix>
-   **GitHub:** <https://github.com/Whonix>
-   **Overview:** Whonix is *"an operating system focused on anonymity,
    privacy and security"*, built from two isolated virtual machines — a
    Gateway that solely runs Tor, and a Workstation that can only reach
    the network through it — so that even malware running as root on
    the Workstation cannot discover the machine's real IP address.

------------------------------------------------------------------------

## 18. Kali Linux

-   **Initial Release:** Mar 2013
-   **Official Website:** <https://www.kali.org>
-   **GitLab:** <https://gitlab.com/kalilinux>
-   **Overview:** Kali Linux, billed as *"The Most Advanced Penetration
    Testing Distribution, Ever"*, is a Debian-based distribution built
    for security auditing; it ships with over 600 preinstalled tools
    covering tasks like vulnerability scanning, wireless attacks, and
    digital forensics, and is maintained by Offensive Security.

------------------------------------------------------------------------

## 19. Parrot OS

-   **Initial Release:** Apr 2013
-   **Official Website:** <https://www.parrotsec.org>
-   **GitHub:** <https://github.com/parrotsec>
-   **GitLab:** <https://gitlab.com/parrotsec>
-   **Overview:** Parrot OS is a Debian-based distribution *"designed
    with Security, Development, and Privacy in mind"*; for example, its
    Security Edition ships a full penetration-testing toolkit, while the
    lighter Home Edition targets everyday desktop use with privacy tools
    like an anonymous browsing mode built in.

------------------------------------------------------------------------

## 20. OpenMandriva

-   **Initial Release:** Nov 2013
-   **Official Website:** <https://www.openmandriva.org>
-   **Build System (ABF):** <https://abf.openmandriva.org>
-   **GitHub:** <https://github.com/OpenMandrivaAssociation>
-   **Overview:** OpenMandriva — built around *"the best balance
    between the most modern features and stability"*, from newbies to
    developers — is a community-run continuation of the Mandriva Linux
    lineage, sponsored by the
    OpenMandriva Association; for example, it builds most of its
    packages with the Clang/LLVM toolchain rather than GCC, and offers
    its own `urpmi`- and `dnf`-based package management alongside a
    Plasma-focused desktop.

------------------------------------------------------------------------

## 21. Solus

-   **Initial Release:** May 2014 (as Evolve OS); renamed Solus in Apr
    2015, with Solus 1.0 following in Dec 2015
-   **Official Website:** <https://getsol.us>
-   **GitHub:** <https://github.com/getsolus>
-   **Overview:** Solus is *"an operating system that is designed for
    home computing"*, built entirely from scratch rather than forked
    from Debian, Arch, or anything else; for example, its own `eopkg`
    package manager follows what the project calls a *"stable-rolling"*
    model — delivering the newest software weekly, only after testing,
    rather than the bleeding-edge approach it says can sacrifice
    reliability for novelty — across a choice of Budgie, GNOME, Plasma,
    or Xfce desktops.

------------------------------------------------------------------------

## 22. Ubuntu MATE

-   **Initial Release:** Oct 2014
-   **Official Website:** <https://ubuntu-mate.org>
-   **GitHub:** <https://github.com/ubuntu-mate>
-   **Overview:** Ubuntu MATE is *"a stable, easy-to-use operating
    system with a configurable desktop environment"*, aimed at people
    who prefer a traditional desktop layout; for example, its own
    MATE Tweak tool can switch the entire desktop between several
    preset layouts — Traditional, Redmond, Cupertino, or Netbook — in
    a couple of clicks, without reinstalling anything.

------------------------------------------------------------------------

## 23. KDE neon

-   **Initial Release:** Jan, Jun 2016
-   **Official Website:** <https://neon.kde.org>
-   **GitLab:** <https://invent.kde.org/neon>
-   **Overview:** KDE neon — built to *"showcase KDE software exactly
    as the KDE developers intended it"*, with no patches — is an
    Ubuntu-based platform built by the KDE project itself to deliver
    the newest Plasma desktop and KDE application releases on top of a
    stable Ubuntu LTS base; for example, a bug fixed upstream in KDE
    software can reach neon users
    within days, rather than waiting for the next Kubuntu release
    cycle.

------------------------------------------------------------------------

## 24. Devuan

-   **Initial Release:** May 2017 (first stable release, Devuan 1.0
    "Jessie"); founding announcement in Nov 2014
-   **Official Website:** <https://www.devuan.org>
-   **Source Repository:** <https://git.devuan.org/explore/repos>
-   **Overview:** Devuan was founded in November 2014 by a
    self-described Veteran Unix Admins collective, announced on its
    own site as *"a fork of Debian without systemd"* built to preserve
    what the project calls Init Freedom, with early administrative
    support from the Dyne.org non-profit foundation; that founding
    announcement predates any installable release by nearly three
    years. For example, a user can pick sysvinit, runit, or OpenRC as
    the init system, and can still choose Xfce, Cinnamon, KDE Plasma,
    LXQt, or MATE as the desktop on top.

------------------------------------------------------------------------

## 25. Artix Linux

-   **Initial Release:** Jul 2017
-   **Official Website:** <https://artixlinux.org>
-   **Source Repository:** <https://gitea.artixlinux.org/explore/repos>
-   **GitHub (former home):** <https://github.com/artix-linux>
-   **Overview:** Artix Linux — *"Simple. Fast. Systemd-free."* — is a
    rolling-release, Arch-based distribution that swaps systemd for a
    real init system; for example, a user can pick OpenRC, runit, s6, or
    dinit as PID 1, on the reasoning that the first process a system
    starts should stay simple, secure, and stable rather than take on
    extra responsibilities.

------------------------------------------------------------------------

## 26. Pop!_OS

-   **Initial Release:** Oct 2017
-   **Official Website:** <https://system76.com/pop>
-   **GitHub:** <https://github.com/pop-os>
-   **Project Reference GitHub:** <https://github.com/system76>
-   **Overview:** Pop!_OS is billed by its maker, System76, as an
    operating system *"for STEM and creative professionals who use
    their computer as a tool to discover and create"*; for example, it
    ships with automatic Nvidia and AMD GPU driver handling built in and
    a tiling window manager that can be toggled on or off, both aimed
    at people doing graphics, engineering, or development work rather
    than general browsing.

------------------------------------------------------------------------

## 27. EndeavourOS (Antergos’ successor)

-   **Initial Release:** May, Jun 2019
-   **Official Website:** <https://endeavouros.com>
-   **GitHub:** <https://github.com/endeavouros-team>
-   **Overview:** EndeavourOS picks up where Antergos left off, offering
    *"a lightweight Arch-based, terminal-centric system ready to
    personalise"*; for example, its online installer lets a user add a
    desktop of their choice — Xfce, KDE Plasma, GNOME, and others — on
    top of an otherwise close-to-vanilla Arch base, without the manual
    setup Arch itself requires.

------------------------------------------------------------------------

## 28. Ubuntu Cinnamon

-   **Initial Release:** Dec 2019
-   **Official Website:** <https://ubuntucinnamon.org>
-   **GitHub:** <https://github.com/ubuntucinnamon>
-   **Overview:** Ubuntu Cinnamon — *"the most traditionally modern
    desktop you will ever love"* — is a community-developed,
    officially recognized Ubuntu flavor that pairs the Cinnamon
    desktop — originally built for Linux Mint — with Ubuntu's package
    base and release cycle; for example, someone who prefers Cinnamon's
    traditional panel-and-menu layout can get it with Ubuntu's hardware
    enablement and PPA ecosystem instead of switching distributions
    entirely.

------------------------------------------------------------------------

## 29. GNOME OS

-   **Initial Release:** Sep 2020 (introduced alongside GNOME 3.38.0)
-   **Official Website:** <https://os.gnome.org>
-   **GitLab:** <https://gitlab.gnome.org/GNOME/gnome-build-meta>
-   **Overview:** GNOME OS — *"producing and distributing bootable VM
    images for debugging and testing features"* — is a nightly,
    image-based reference platform built by the GNOME project itself
    rather than a general daily-driver distribution; for example, it
    rebuilds and boots a fresh system image from every commit made
    across GNOME's many modules, using OSTree and Flatpak, so
    developers, designers, and testers can try tomorrow's GNOME before
    it ever reaches an actual distribution's repositories.

------------------------------------------------------------------------

## 30. CachyOS

-   **Initial Release:** Jul 2021
-   **Official Website:** <https://cachyos.org>
-   **GitHub:** <https://github.com/cachyos>
-   **Overview:** CachyOS is *"an Arch Linux based distribution, which
    improves the performance, throughput and interactivity"* — an
    Arch-based distribution built around
    performance, using a BORE scheduler and CPU-architecture-optimized
    packages (x86-64-v3/v4) rather than the generic builds most
    distributions ship; for example, its own installer can detect a
    system's CPU and automatically offer the fastest matching package
    repository, and it ships a dedicated handheld edition for devices
    like the Steam Deck.

------------------------------------------------------------------------

## 31. Nobara Linux

-   **Initial Release:** Jul 2022
-   **Official Website:** <https://nobaraproject.org>
-   **GitHub:** <https://github.com/Nobara-Project>
-   **Overview:** Nobara is a Fedora-based distribution — *"A
    Fedora-based desktop, tuned for gaming, streaming, and content
    creation"* — built by Linux kernel and GNOME contributor Thomas
    "GloriousEggroll" Crider
    specifically for gaming and content creation; for example, it
    patches in codecs, Wine/Proton tweaks, and GPU driver fixes that
    stock Fedora leaves out, so games and streaming software work
    without the user hunting down third-party repositories first.

------------------------------------------------------------------------

## 32. TUXEDO OS

-   **Initial Release:** Sep 2022
-   **Official Website:** <https://www.tuxedocomputers.com/en/TUXEDO-OS_1.tuxedo>
-   **GitLab:** <https://gitlab.com/tuxedocomputers/development/tuxedo_os>
-   **GitHub (former home):** <https://github.com/tuxedocomputers>
-   **Overview:** TUXEDO OS — *"simple by default, powerful when
    needed"* — is an Ubuntu-based distribution built by the hardware
    maker TUXEDO Computers, whose stated mission with it is making
    Linux accessible to the general public; it ships preinstalled on
    the company's own laptops and desktops, and its TUXEDO Control
    Center app lets a user manage fan curves, keyboard backlighting,
    and power
    profiles for their exact TUXEDO hardware from one graphical tool,
    something a generic Ubuntu install can't do out of the box.

------------------------------------------------------------------------

## 33. PikaOS Linux

-   **Initial Release:** Dec 2022, Jan 2023
-   **Official Website:** <https://wiki.pika-os.com/en/home>
-   **Source Repository:** <https://git.pika-os.com>
-   **GitHub (former home):** <https://github.com/PikaOS-Linux>
-   **Overview:** PikaOS is a Debian/Ubuntu-based Linux distribution —
    *"a gaming focused Linux distribution focussing on ease of use and
    high compatability"* — built by taking the gaming know-how behind
    Nobara — patched kernels, Wine/Proton tuning, and
    driver fixes aimed at running Windows games well — and pairing it
    with Ubuntu's broad hardware support and package base, so it works
    well for gaming out of the box without much manual tinkering.

------------------------------------------------------------------------

## 34. Vanilla OS

-   **Initial Release:** Oct, Nov, Dec 2022
-   **Official Website:** <https://vanillaos.org>
-   **GitHub:** <https://github.com/vanilla-os>
-   **Overview:** Vanilla OS is an immutable Ubuntu-based operating
    system — *"built with simplicity in mind"* — keeping the base
    system on an A/B root layout called ABRoot so every update is
    applied atomically and can be rolled back if something breaks. For
    example, its `apx` package manager uses OCI containers to install
    software from Ubuntu, Fedora, or Arch repositories side by side,
    without ever touching or destabilizing the immutable base.

------------------------------------------------------------------------

## 35. blendOS

-   **Initial Release:** Jan 2023
-   **Official Website:** <https://blendos.co>
-   **GitHub:** <https://github.com/blend-os>
-   **GitLab:** <https://git.blendos.co/blendOS>
-   **Overview:** blendOS is an Arch-based immutable Linux distribution
    — *"a seamless blend of all Linux distributions"* — letting
    users install and run software from Debian, Ubuntu, Fedora, Arch,
    and other ecosystems side by side, with GNOME as the primary desktop
    alongside optional KDE Plasma or Xfce sessions. For example, a user
    could pull one package with `apt`, another with `dnf`, and a third
    with `pacman` or `yay`, all from the same shell, or boot into a full
    standalone desktop session from a different distro entirely — while
    the base system itself stays read-only and is rebuilt atomically
    with each update.

------------------------------------------------------------------------

## 36. Chimera Linux

-   **Initial Release:** Jun 2023 (first Alpha); project development
    began mid-2021
-   **Official Website:** <https://chimera-linux.org>
-   **GitHub:** <https://github.com/chimera-linux>
-   **Overview:** Chimera Linux — *"born from unhappiness with the
    status quo"* — is an independent, general-purpose distribution
    built entirely from scratch since 2021 by former Void Linux
    developer Nina Kolesová (q66); for example, it swaps GNU coreutils
    for FreeBSD's userland, uses the LLVM toolchain and musl libc
    instead of GCC and glibc, and runs the Dinit init system rather
    than systemd, while still packaging modern software like GNOME,
    KDE Plasma, and Flatpak on top.

------------------------------------------------------------------------

## 37. Vendefoul Wolf Linux

-   **Initial Release:** Aug, Sep 2023
-   **Official Website:** <https://vendefoul-wolf-linux.sourceforge.io>
-   **Source Repository:** <https://sourceforge.net/projects/vendefoul-wolf-linux>
-   **Overview:** Vendefoul Wolf Linux — *"a complete and free
    distribution available in all its versions and desktop
    environments"* — is a Devuan-based distribution built to work out
    of the box with low resource usage; for example, it ships several
    desktop editions and keeps telemetry out entirely, inheriting
    Devuan's systemd-free base rather than Debian's default one.

------------------------------------------------------------------------

## 38. secureblue

-   **Initial Release:** Dec 2023, Q1 2024
-   **Official Website:** <https://secureblue.dev>
-   **GitHub:** <https://github.com/secureblue/secureblue>
-   **Project Reference GitHub:** <https://github.com/secureblue>
-   **Overview:** secureblue — *"increase defenses against the
    exploitation of both known and unknown vulnerabilities"* — is a
    hardened, Fedora Atomic-based image built around security best
    practices rather than convenience; for example, it enables
    hardened memory allocators and stricter kernel settings by
    default, and ships separate images built on top of Fedora
    Silverblue (GNOME) and Kinoite (KDE) for users who want that
    hardening without assembling it themselves.

------------------------------------------------------------------------

## 39. aerynOS

-   **Initial Release:** Feb-Mar 2025
-   **Official Website:** <https://aerynos.com>
-   **GitHub:** <https://github.com/aerynOS>
-   **GitHub Forums:** <https://github.com/orgs/aerynOS/discussions>
-   **Overview:** aerynOS (formerly Serpent OS) is *"an independent
    performance-oriented Linux-based operating system"* that diverges
    significantly from traditional distributions while still aiming for
    a familiar, comfortable environment. Built by industry veterans and
    produced entirely by tooling the project developed in-house, it
    uses atomic updates and cutting-edge packaging in what the team
    describes as the next evolution in Linux distributions — an
    engineering-led effort built from the ground up rather than a fork
    of an existing base.

------------------------------------------------------------------------

## 40. KDE Linux

-   **Initial Release:** 2025 (currently Alpha)
-   **Official Website:** <https://linux.kde.org>
-   **GitLab:** <https://invent.kde.org/kde-linux/kde-linux>
-   **Overview:** KDE Linux — *"A free Linux-based operating system
    built by KDE"* — is an image-based distribution built from Arch
    Linux packages that KDE itself calls a "reference implementation"
    of Plasma and KDE apps, currently in Alpha; for example, it
    deliberately ships without the `pacman` package manager, installing
    software instead through Flatpak via Discover, with atomic image
    updates, Btrfs snapshots, and one-click rollback if something
    breaks.

------------------------------------------------------------------------

## 41. Ageless Linux

-   **Initial Release:** Mar 2026
-   **Official Website:** <https://agelesslinux.org>
-   **GitHub:** <https://github.com/agelesslinux/agelesslinux>
-   **Overview:** Ageless Linux is a Debian-based distribution created as
    an act of political protest against age verification, alongside a
    related hardware project building computing devices resistant to
    age checks; as the project puts it, *"We don't know how old you
    are. We don't want to know."* It is a registered operating system
    under California's Digital Age Assurance Act (AB 1043, Chapter
    675, Statutes of 2025, signed by Governor Newsom on October 13,
    2025), and states it is in full, knowing, and intentional
    noncompliance with the age-verification requirements of Cal. Civ.
    Code § 1798.501(a). The project is run by John McCardle / FFwF
    Robotics LLC / Goblincorps as political commentary and civil
    disobedience, and is not affiliated with the Debian Project,
    Canonical, the Free Software Foundation, or the California State
    Legislature; it adds that no children were age-verified or harmed,
    no data was collected, and no privacy was violated in the making of
    the distribution — while noting that the California legislature
    disagrees that these things are compatible.

------------------------------------------------------------------------
------------------------------------------------------------------------

### Additional Linux Distributions (Specialized & Niche Use Cases)


------------------------------------------------------------------------

## 42. Slackware

-   **Initial Release:** Jul 1993
-   **Official Website:** <https://www.slackware.com>
-   **Source Repository:** <https://git.slackbuilds.org/slackbuilds>
-   **Overview:** Slackware, the oldest still-maintained Linux
    distribution, is *"designed with the twin goals of ease of use and
    stability as top priorities"*; for example, it ships with no
    graphical installer and no automatic dependency resolution by
    default, a deliberately conservative approach that leaves package
    management and system configuration almost entirely in the user's
    hands through plain text files.

------------------------------------------------------------------------

## 43. antiX Linux

-   **Initial Release:** Jul 2007
-   **Official Website:** <https://antixlinux.com>
-   **GitHub:** <https://github.com/antiX-Linux>
-   **Overview:** antiX is *"a fast, lightweight and easy to install
    systemd-free Linux live CD distribution"* based on Debian Stable;
    for example, it can boot and run entirely from a live USB on a
    machine with as little as 128 MB of RAM, without ever touching the
    hard drive, which is part of why it's a common pick for reviving
    very old PCs.

------------------------------------------------------------------------

## 44. Tiny Core Linux


-   **Initial Release:** Jan 2009
-   **Official Website:** <http://www.tinycorelinux.net>
-   **Overview:** Tiny Core Linux is a minimal system built on BusyBox
    and FLTK that, in the project's own words, *"represents only the
    core needed to boot into a very minimal X desktop"* — everything
    beyond that arrives as user-selected extensions from an online
    repository; for example, it ships in three sizes: a text-only Core
    at roughly 17 MB, the FLWM-based TinyCore desktop at about 24 MB,
    and CorePlus bundling optional extras, and by default it
    decompresses entirely into RAM at boot rather than installing to
    disk, which is much of the reason it runs so quickly on hardware
    other distributions have long abandoned.

------------------------------------------------------------------------

## 45. Zorin OS

-   **Initial Release:** 2009
-   **Official Website:** <https://zorin.com/os/>
-   **GitHub:** <https://github.com/zorinos>
-   **Overview:** Zorin OS is *"designed to make your computer faster,
    more secure and easier to use"*, built on Ubuntu with a strong
    focus on easing the switch from Windows or macOS; for example, its
    built-in Zorin Appearance tool can switch the entire desktop layout
    to resemble Windows 11, Windows 7, or macOS with one click, easing
    the transition for new switchers.

------------------------------------------------------------------------

## 46. Parabola GNU/Linux-libre

-   **Initial Release:** Oct 2009
-   **Official Website:** <https://www.parabola.nu>
-   **Source Repository:** <https://git.parabola.nu>
-   **GitLab:** <https://gitlab.com/parabola>
-   **Overview:** Parabola calls itself *"a fully free, simple, and
    lightweight operating system"*, an Arch- and Debian-based
    distribution built entirely from source under the GNU Free System
    Distribution Guidelines (FSDG); for example, its own build servers
    compile every package from clean chroots with networking disabled,
    specifically to strip out and replace any software or artwork that
    falls outside those guidelines, and the project earned Free
    Software Foundation recognition as a fully free distribution on
    May 20, 2011.

------------------------------------------------------------------------

## 47. Peppermint OS

-   **Initial Release:** May 2010
-   **Official Website:** <https://peppermintos.com>
-   **GitHub:** <https://github.com/peppermintos>
-   **Overview:** Peppermint OS — which, by its own account, has
    *"always been a minimalistic distro with signature custom
    tools"* — started out blending a lightweight desktop with
    cloud-app integration on an Ubuntu base, and is now built on
    Debian/Devuan Stable instead; for example, its signature Ice tool
    turns any website into what looks and behaves like a
    standalone desktop app, a feature it kept even after moving away
    from its original Ubuntu foundation.

------------------------------------------------------------------------

## 48. SparkyLinux

-   **Initial Release:** Oct 2011
-   **Official Website:** <https://sparkylinux.org>
-   **GitHub:** <https://github.com/sparkylinux>
-   **Overview:** SparkyLinux — *"a fast, lightweight and fully
    customizable operating system"* — is a Debian-based distribution
    offered in several editions built around different needs; for
    example, its GameOver edition ships preinstalled with gaming
    platforms and
    emulators, while its MinimalGUI and MinimalCLI editions strip things
    down to a bare Openbox desktop or command line for building a
    system up from scratch.

------------------------------------------------------------------------

## 49. Raspberry Pi OS

-   **Initial Release:** Jul 2012 (as Raspbian); renamed Raspberry Pi OS
    in May 2020
-   **Official Website:** <https://www.raspberrypi.com/software/>
-   **GitHub:** <https://github.com/raspberrypi>
-   **Overview:** Raspberry Pi OS is *"a free operating system based on
    Debian, optimised for the Raspberry Pi hardware"*, maintained
    directly by Raspberry Pi itself; for example, it ships with over
    35,000 precompiled packages and, unlike most desktop distributions,
    still supports the original 2012 Raspberry Pi Model B alongside the
    newest boards.

------------------------------------------------------------------------

## 50. Bedrock Linux

-   **Initial Release:** Aug 2012
-   **Official Website:** <https://bedrocklinux.org>
-   **GitHub:** <https://github.com/bedrocklinux>
-   **Overview:** Bedrock Linux is *"a meta Linux distribution which allows
    users to mix-and-match components"* from otherwise incompatible
    distributions into one broadly unified system — for example, running
    Debian's stable coreutils alongside Arch's cutting-edge kernel,
    Void's runit init system, a PDF reader kept patched through Gentoo's
    Portage, a font pulled from Arch's AUR, games built against Ubuntu's
    libraries, and business software built against CentOS's libraries,
    all side by side as though packaged for one single distribution. It
    is aimed at advanced users seeking maximum flexibility through
    cross-distro compatibility layers.

------------------------------------------------------------------------

## 51. BlackArch

-   **Initial Release:** Aug 2012
-   **Official Website:** <https://blackarch.org>
-   **GitHub:** <https://github.com/BlackArch>
-   **Overview:** BlackArch is *"an Arch Linux-based penetration testing
    distribution for penetration testers and security researchers"*,
    with a dedicated repository holding well over 2,800 security tools
    at last count; for example, it can be installed as a full live
    system or layered on top of an existing Arch installation, adding
    just the BlackArch tool groups a user actually needs.

------------------------------------------------------------------------

## 52. MX Linux

-   **Initial Release:** Dec 2013
-   **Official Website:** <https://mxlinux.org>
-   **GitHub:** <https://github.com/MX-Linux>
-   **Overview:** MX Linux is *"a cooperative venture between the antiX
    and former MEPIS communities"*, built on a Debian Stable base with
    Xfce as its main desktop; for example, its own MX Tools panel
    bundles system snapshot, USB-installer, and driver-management
    utilities into one place, drawing on ideas from both antiX and the
    older MEPIS project.

------------------------------------------------------------------------

## 53. Archman Linux

-   **Initial Release:** Mar 2017
-   **Official Website:** <https://archman.org>
-   **GitLab:** <https://gitlab.com/Archman-OS>
-   **GitHub:** <https://github.com/archman-os>
-   **Overview:** Archman Linux — *"a fast, elegant, and user-friendly
    desktop experience"* — is an independent, Arch Linux-based
    distribution built by a community project; for example, its
    primary edition ships a carefully configured Xfce desktop
    installed through the Calamares installer,
    with KDE Plasma and MATE offered as alternative editions and
    `pamac` providing a graphical front end for package management.

------------------------------------------------------------------------

## 54. RebornOS

-   **Initial Release:** 2018
-   **Official Website:** <https://rebornos.org>
-   **GitHub:** <https://github.com/rebornos-team>
-   **Overview:** RebornOS — *"whose goal is to make Arch Linux more
    approachable to beginners"* — is an Arch Linux-based distribution
    built around a graphical installer called Reborn Creator; for
    example, a user can pick from a long list of desktop environments
    — GNOME, KDE Plasma, Xfce, Cinnamon, and others — directly during
    setup, arriving at a ready-to-use Arch system without touching the
    command line.

------------------------------------------------------------------------

## 55. Archcraft

-   **Initial Release:** Q4 2020
-   **Official Website:** <https://archcraft.io>
-   **GitHub:** <https://github.com/archcraft-os>
-   **Overview:** Archcraft — *"a fast, friendly, open-source operating
    system, for newbies, geeks & DIY enthusiasts"* — is an Arch-based
    distribution built around minimalist window managers rather than a
    full desktop environment; for example, it ships with several
    pre-configured Openbox themes
    and layouts that a user can switch between instantly from a menu,
    getting a polished, uncluttered look without hand-tuning
    dotfiles.

------------------------------------------------------------------------

## 56. Asahi Linux

-   **Initial Release:** Q4 2020, Q1 2021
-   **Official Website:** <https://asahilinux.org>
-   **GitHub:** <https://github.com/asahilinux>
-   **Overview:** Asahi Linux *"aims to bring you a polished Linux
    experience on Apple Silicon Macs"*, reverse-engineering largely
    undocumented Apple hardware to write the needed drivers from
    scratch; for example, the project's own Fedora Asahi Remix now
    supports OpenGL and Vulkan graphics on M1 and M2 Macs, hardware
    Apple itself never offered official Linux drivers for.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# III. Systems Independent (GNU)

*A reference to the GNU operating system and its ecosystem of tools and
distributions that deliver a free, Unix-like platform independent of
any specific vendor or hardware line.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. GNU Project (gnu.org)

-   **Project Announcement:** Sep 1983
-   **Development Start:** Jan 1984
-   **(FSF) Project Start:** Oct 1985
-   **GCC (GNU Compiler Collection):** 1987
-   **GNU Hurd:** 1990
-   **Official Website:** <https://www.gnu.org>
-   **GCC (GNU Compiler Collection) Project Page:** <https://gcc.gnu.org>
-   **GNU Hurd Project Page:** <https://www.gnu.org/software/hurd/>
-   **Official Source Hosting (Savannah, GNU):** <https://savannah.gnu.org>
-   **Source Hosting (Savannah, NonGNU):** <https://savannah.nongnu.org>
-   **Source Repository (GCC):** <https://gcc.gnu.org/git/gcc.git>
-   **Source Repository (Hurd):** <https://git.savannah.gnu.org/cgit/hurd>
-   **Overview:** The GNU Project has been *"developing the free Unix
    style operating system GNU"* since 1983, so that computer users can
    have the freedom to share and improve the software they use; it was
    announced by Richard Stallman on September 27, 1983, with
    development starting that following January, and its four core
    freedoms — to run, study, redistribute, and improve software — have
    since become the founding template that most free-software licenses
    are built around. Savannah hosts official GNU packages at
    <https://savannah.gnu.org>, while <https://savannah.nongnu.org>
    provides the same infrastructure for free software projects outside
    the GNU Project itself.

------------------------------------------------------------------------

## 2. GNU Guix

-   **Project Start:** Jun 2012
-   **First Release:** Jan 2013
-   **First Stable System Release:** May 2019
-   **Official Website:** <https://guix.gnu.org>
-   **Source Repository:** <https://git.guix.gnu.org>
-   **Codeberg:** <https://codeberg.org/guix/guix>
-   **Savannah (former home):** <https://cgit.git.savannah.gnu.org/cgit/guix.git>
-   **Overview:** GNU Guix — *"designed to give users more control over
    their general-purpose and specialized computing environments"* — is
    a transactional package manager and, as Guix System, a full
    distribution of the GNU operating system built on the Linux-libre
    kernel; for example, its declarative, Scheme-based package
    definitions let a user roll an entire system configuration back to
    an exact prior state with one command, the same transactional
    upgrade-and-rollback model it borrows from and builds upon Nix.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# IV. illumos Family

*A set of modern, open-source descendants of OpenSolaris that carry
forward the illumos kernel into server, enterprise, and
virtualization-focused operating systems.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. illumos

-   **Initial Release:** Aug 2010
-   **Official Website:** <https://illumos.org>
-   **Source Repository:** <https://code.illumos.org>
-   **GitHub Mirror:** <https://github.com/illumos>
-   **Overview:** illumos describes itself on its own homepage as *"a
    Unix operating system which provides next-generation features for
    downstream distributions"*, forked from OpenSolaris in August 2010
    after Oracle discontinued that project; for example, it carries
    forward Solaris-era technologies like ZFS, DTrace, and Zones, and
    serves as the shared core — much like the Linux kernel does for
    Linux distributions — for every other entry in this section.

------------------------------------------------------------------------

## 2. OpenIndiana

-   **Initial Release:** Sep 2010
-   **Official Website:** <https://www.openindiana.org>
-   **GitHub:** <https://github.com/OpenIndiana>
-   **Overview:** OpenIndiana, billed on its own site as a *"Community-driven
    illumos Distribution"*, is the most direct continuation of the old
    Project Indiana codename that OpenSolaris itself was born from; for
    example, it aims to be the de facto OpenSolaris successor installed
    on production servers where free security and bug fixes still
    matter, maintained by volunteers under the stewardship of the
    illumos Foundation.

------------------------------------------------------------------------

## 3. SmartOS

-   **Initial Release:** Aug 2011
-   **Official Website:** <https://tritondatacenter.com/smartos>
-   **GitHub:** <https://github.com/TritonDataCenter/smartos-live>
-   **Project Reference GitHub:** <https://github.com/TritonDataCenter>
-   **Overview:** SmartOS is billed by its maintainers as *"a lightweight
    container hypervisor that delivers industrial grade security"*,
    combining OpenSolaris-derived Zones with bhyve and KVM
    virtualization; for example, it boots entirely into RAM rather than
    from disk, which makes an operating system upgrade as simple as
    rebooting into a newer image, and it serves as the engine behind
    Triton DataCenter's cloud infrastructure.

------------------------------------------------------------------------

## 4. OmniOS

-   **Initial Release:** Apr 2012
-   **Official Website:** <https://omnios.org>
-   **GitHub:** <https://github.com/omniosorg>
-   **Overview:** OmniOS describes itself on its own homepage as an
    *"illumos based server OS with ZFS, Bhyve, DTrace, Crossbow, SMF and
    Linux zone support"*, deliberately built for server class hardware
    rather than laptops or workstations; for example, every fourth
    stable release is designated a Long-Term Support (LTS) build
    supported for three years, letting operators schedule upgrades on
    their own timeline instead of chasing every release.

------------------------------------------------------------------------

## 5. Tribblix

-   **Initial Release:** Oct 2012
-   **Official Website:** <https://www.tribblix.org>
-   **GitHub:** <https://github.com/tribblix>
-   **Overview:** Tribblix — *"the retro illumos distribution"* — is an
    independent illumos-based operating system created and still
    single-handedly maintained by Peter Tribble; for example, its
    software is installed in themed bundles called "overlays" rather
    than individual packages, and it deliberately keeps an old-school
    feel — including classic root logins and lightweight apps like
    AbiWord — while running modern illumos technologies such as ZFS,
    Zones, and DTrace underneath, on both x86 and legacy SPARC
    hardware.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# V. Xen-Based Systems

*A focused look at the Xen hypervisor and security-oriented systems
built on top of it that use hardware virtualization for isolation and
compartmentalization.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. Xen

-   **Initial Release:** Oct 2003
-   **Official Website:** <https://xenproject.org/>
-   **Source Repository:** <https://xenbits.xen.org>
-   **GitHub Mirror:** <https://github.com/xen-project>
-   **Overview:** The Xen Project describes its own hypervisor as *"an
    open source hypervisor for infrastructure, embedded,
    security-sensitive, and virtualization platforms"*; for example, it
    is the only type-1, bare-metal hypervisor available as open source,
    and it powers some of the largest commercial clouds in production
    today alongside security-focused systems such as Qubes OS.

------------------------------------------------------------------------

## 2. Qubes OS

-   **Initial Release:** Apr 2011, Sep 2012
-   **Official Website:** <https://www.qubes-os.org>
-   **GitHub:** <https://github.com/QubesOS>
-   **Overview:** Qubes OS calls itself, with deliberate modesty, *"A
    reasonably secure operating system"*, built around a Security by
    Isolation approach on top of the Xen hypervisor; for example, it
    lets a user run their email, browser, and work documents each in
    their own separate, color-coded virtual machine, so that a
    compromise in one — say, a malicious email attachment — never
    reaches the others. Edward Snowden has publicly said he uses it.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# VI. Experimental & Research Systems

*A selection of hobbyist, retro-compatible, and research operating
systems that explore alternative kernels, architectures, and design
philosophies outside mainstream platforms.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. FreeDOS

-   **Project Start:** Jun 1994
-   **First Release:** Sep 2006 (version 1.0)
-   **Official Website:** <https://www.freedos.org>
-   **GitHub Kernel:** <https://github.com/FDOS/kernel>
-   **GitHub:** <https://github.com/FDOS>
-   **GitLab:** <https://gitlab.com/FreeDOS>
-   **Overview:** FreeDOS *"aims to be a complete, free, 100% MS-DOS
    compatible operating system"*, started by Jim Hall in June 1994 the
    day after Microsoft announced it would stop selling MS-DOS; for
    example, people still use it today to run classic DOS games like
    DOOM on modern hardware, keep old business software running on an
    embedded till or cash register, or develop new DOS software from
    scratch.

------------------------------------------------------------------------

## 2. ReactOS

-   **Project Inception:** 1996
-   **First Release:** Feb 1998
-   **Official Website:** <https://reactos.org>
-   **GitHub:** <https://github.com/reactos>
-   **Git Mirror:** <https://git.reactos.org>
-   **Overview:** ReactOS is *"a free open source operating system based
    on the design principals found"* in the Windows NT architecture,
    built entirely from scratch with no Microsoft code involved; for
    example, it aims for binary compatibility with real Windows
    applications and drivers, so programs written for Windows Server
    2003 and later can, in principle, run unmodified — though the
    project remains in alpha and is recommended only for testing and
    evaluation rather than daily use.

------------------------------------------------------------------------

## 3. Haiku

-   **Initial Release:** Aug 2001
-   **Official Website:** <https://www.haiku-os.org>
-   **Source Repository:** <https://git.haiku-os.org>
-   **GitHub Mirror:** <https://github.com/haiku>
-   **Overview:** Haiku describes itself on its own homepage as *"fast,
    simple to use, easy to learn and yet very powerful"*, a
    community-driven continuation of the discontinued BeOS; for
    example, it reused BeOS's own Tracker file manager and Deskbar
    taskbar as open-sourced starting points, then rebuilt the rest of
    the operating system from scratch while still aiming for binary
    compatibility with the original BeOS API.

------------------------------------------------------------------------

## 4. Redox OS

-   **Initial Release:** Apr 2015
-   **Official Website:** <https://www.redox-os.org>
-   **GitHub:** <https://github.com/redox-os>
-   **GitLab:** <https://gitlab.redox-os.org/redox-os/redox>
-   **Overview:** Redox OS is *"a complete Unix-like microkernel-based
    operating system written in Rust"*, created in 2015 by Jeremy
    Soller with safety and reliability as its central design goals; for
    example, its RedoxFS filesystem borrows ZFS-like features such as
    copy-on-write and data integrity checking, and its relibc C library
    lets many existing C and C++ programs be recompiled for Redox with
    little to no modification.

------------------------------------------------------------------------

## 5. SerenityOS

-   **First Public Release:** Oct 2018
-   **Official Website:** <https://serenityos.org>
-   **GitHub:** <https://github.com/SerenityOS>
-   **Overview:** SerenityOS calls itself *"a love letter to '90s user
    interfaces with a custom Unix-like core"*, a graphical hobby
    operating system built from scratch in C++ by former Apple WebKit
    engineer Andreas Kling; for example, the project builds its own
    browser engine, window server, and userland applications entirely
    in-house rather than reusing existing Unix tooling, and it grew
    largely in public through Kling's own YouTube development videos.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# VII. Apple Platforms (Operating Systems & Services)

*Apple's own operating systems, alongside the core web properties and
cloud services that provide identity, synchronization, and device
integration across the Apple ecosystem.*

------------------------------------------------------------------------
------------------------------------------------------------------------

### Operating Systems

## 1. macOS

-   **Initial Release:** Jan 1984 (as the original Macintosh System
    Software); modern Unix-based line since Mar 2001 (as Mac OS X)
-   **Official Website:** <https://www.apple.com/macos/>
-   **Overview:** The current release, macOS Tahoe, carries Apple's own
    tagline *"Fresh faced. Timelessly Mac"* — Apple's desktop and
    laptop operating system for the Mac, built on the Unix-based Darwin
    core with a hybrid XNU kernel; for example, that same Darwin
    foundation is open-sourced separately, while the polished desktop
    layer on top of it has run continuously on Mac hardware since Mac
    OS X's debut in 2001, through Intel and now Apple Silicon chips
    alike.

------------------------------------------------------------------------

## 2. iOS

-   **Initial Release:** Jun 2007 (as iPhone OS 1.0)
-   **Official Website:** <https://www.apple.com/ios/>
-   **Overview:** Announcing the current release, Apple's own newsroom
    described iOS 26 as bringing *"a beautiful new design, intelligent
    experiences, and improvements to the apps users rely on every
    day"* — Apple's mobile operating system for the iPhone, originally
    called iPhone OS before being renamed iOS in 2010 to reflect its
    spread to other Apple devices; for example, the same underlying
    platform was adapted into iPadOS for the iPad and shares its core
    with watchOS and tvOS, letting Apple ship one connected ecosystem
    across phones, tablets, watches, and TVs.

------------------------------------------------------------------------

### Services

## 3. Apple

-   **First Introduced:** Apr 1976
-   **Official Website:** <https://www.apple.com/>
-   **GitHub:** <https://github.com/apple>
-   **Overview:** Apple's official website — under the banner of its
    long-running *"Think Different"* philosophy — showcases the
    company's products, from iPhone and Mac to iPad, alongside its
    services, support resources, and official company information; for
    example, apple.com is also where the company still marks its own
    milestones, having run a "50 Years of Thinking Different" retrospective
    tying its 2026 anniversary back to that same 1997 campaign.

------------------------------------------------------------------------

## 4. Apple Account

-   **First Introduced:** 2000
-   **Official Website:** <https://account.apple.com/>
-   **GitHub:** <https://github.com/apple>
-   **Overview:** An Apple Account — described in Apple's own support
    documentation as *"the account you use to access Apple Services
    like the App Store"* — is the unified sign-in behind every Apple
    device and service; for example, signing in with the same Apple
    Account on an iPhone, iPad, and Mac keeps purchases, subscriptions,
    and settings synced across all three, and the identifier was
    renamed from "Apple ID" to "Apple Account" to make that central
    role clearer.

------------------------------------------------------------------------

## 5. iCloud

-   **Initial Release:** Oct 2011
-   **Official Website:** <https://www.icloud.com>
-   **GitHub:** <https://github.com/apple>
-   **Overview:** iCloud's own homepage puts it simply: *"Log in to
    iCloud to access your photos, mail, notes, documents and more"* —
    Apple's cloud-based synchronization and storage platform; for
    example, a photo taken on an iPhone can appear moments later in the
    Photos app on a Mac or on iCloud.com from any browser, with edits
    and deletions kept in sync across every signed-in device.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------

# VIII. Windows-Based Custom Systems (Debloated & Community Builds)

*A focused Windows section highlighting official editions, popular
community-tuned builds, and trusted privacy and debloat tooling for
modern desktop use.*

------------------------------------------------------------------------
------------------------------------------------------------------------

## 1. Windows

-   **Initial Release:** Nov 1985
-   **Official Website:** <https://www.microsoft.com/windows>
-   **Support Status:** Official Microsoft product with full commercial
    support.
-   **Overview:** Windows 11, per Microsoft's own announcement, *"is
    designed to bring you closer to what you love"* — the proprietary
    operating system family developed by Microsoft, with modern
    versions built on the Windows NT architecture; for example, the
    same NT-based core scales from a home laptop up to enterprise
    server fleets, and Windows remains the platform most PC games and
    business software are built against first.

-   **Optional Privacy & Debloat Tooling:**
    -   [Sophia Script for Windows](https://github.com/farag2/Sophia-Script-for-Windows)
        — an open-source PowerShell module for fine-tuning and
        automating Windows 10 and 11 configuration, including privacy,
        telemetry, and UX tweaks.
    -   [privacy.sexy](https://privacy.sexy) — an open-source
        system-hardening tool that applies transparent privacy and
        security scripts.
    -   [Chris Titus Tech WinUtil](https://github.com/ChrisTitusTech/winutil)
        — an open-source utility to debloat, tweak, and configure
        Windows via a GUI.
    -   [Win11Debloat](https://github.com/Raphire/Win11Debloat) — a
        small, open-source PowerShell script to remove preinstalled
        apps, reduce telemetry, and declutter Windows 10 and 11.

------------------------------------------------------------------------

## 2. Revision (ReviOS)

-   **Initial Release:** 2019
-   **Official Website:** <https://www.revi.cc>
-   **GitHub:** <https://github.com/meetrevision>
-   **Support Status:** Unofficial community Windows customization,
    not an official Microsoft product.
-   **Overview:** ReviOS *"aspires to re-create what Windows as an
    operating system should have been — easy and simple"*, a
    community-driven, debloated Windows configuration that strips
    unnecessary services and telemetry; for example, it disables
    Windows Defender and Windows Update by default (both re-enableable
    through its own built-in tool) to squeeze out extra performance and
    privacy, particularly for gaming and general desktop use.

------------------------------------------------------------------------

## 3. AtlasOS

-   **Initial Release:** 2021
-   **Official Website:** <https://atlasos.net>
-   **GitHub:** <https://github.com/Atlas-OS/Atlas>
-   **Support Status:** Community-maintained Windows optimization
    project, independent from Microsoft.
-   **Overview:** AtlasOS says of itself, *"Atlas brings life back to
    Windows, designed to maximize privacy, usability, and
    performance"*; it is an open-source project that applies
    performance, privacy, and usability optimizations to Windows using
    scripted "playbooks" rather than a modified installer image; for
    example, its AME Wizard walks a user through toggling each
    optimization individually, so someone can keep Windows Defender and
    Windows Update active while still trimming background bloat.

------------------------------------------------------------------------

## 4. Windows X-Lite

-   **Initial Release:** 2022, 2023
-   **Official Website:** <https://windowsxlite.com>
-   **Support Status:** Unofficial third-party Windows images with
    no Microsoft affiliation.
-   **Overview:** Windows X-Lite's own tagline describes its builds as
    *"designed to Enhance Performance, Privacy, Stability and
    Control"*; it provides unofficial lightweight Windows images with
    many non-essential components and preinstalled apps removed, aimed
    at low-spec hardware; for example, its images are built to run
    unmodified on everything from old, weak laptops to modern gaming
    desktops, old or new, weak or strong.

------------------------------------------------------------------------

## 5. Tiny11

-   **Initial Release:** Feb 2023
-   **Official Website:** <https://ntdotdev.wordpress.com>
-   **GitHub:** <https://github.com/ntdevlabs/tiny11builder>
-   **Project Reference GitHub:** <https://github.com/ntdevlabs>
-   **Support Status:** Unofficial experimental project by NTDEV,
    not an official Windows edition.
-   **Overview:** Tiny11 is a series of heavily trimmed-down Windows 11
    builds and tools created by developer NTDEV, removing many default
    apps and features to cut disk footprint and memory use; for
    example, a full Tiny11 install can fit in around 8 GB of storage
    against Windows 11's usual 20 GB or more, letting the same modern
    OS run on hardware Microsoft's official system requirements would
    otherwise rule out. NTDEV has since moved primary blogging to
    ntdev.blog, though ntdotdev.wordpress.com remains live with the
    project's archive.

------------------------------------------------------------------------

## 6. Nano11

-   **Initial Release:** Sep 2025
-   **Official Website:** <https://ntdotdev.wordpress.com>
-   **GitHub:** <https://github.com/ntdevlabs/nano11>
-   **Project Reference GitHub:** <https://github.com/ntdevlabs>
-   **Support Status:** Unofficial, highly experimental project
    intended for advanced users only.
-   **Overview:** Nano11 is NTDEV's even more extreme follow-up to
    Tiny11, an experimental, minimal Windows 11 build stripped down to
    little more than its essential components; for example, independent
    testing has shrunk a Nano11 install to as little as 2.8 GB — about
    3.5 times smaller than Tiny11 itself — making it intended strictly
    for constrained or test environments rather than everyday use.

------------------------------------------------------------------------

[⬆ Back to Table of Contents](#table-of-contents)

------------------------------------------------------------------------
------------------------------------------------------------------------
