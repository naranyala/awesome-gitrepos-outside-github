# Awesome Git Repos Outside GitHub

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome git repositories hosted outside GitHub — including self-hosted platforms, alternative forges, and notable projects whose **primary source of truth and development** is not on GitHub.

## Contents

- [Git Hosting Platforms](#git-hosting-platforms)
- [Operating Systems & Kernels](#operating-systems--kernels)
- [Core System & Toolchains](#core-system--toolchains)
- [Core Frameworks & Libraries](#core-frameworks--libraries)
- [Programming Languages](#programming-languages)
- [Desktop Environments & Display Servers](#desktop-environments--display-servers)
- [Web & Networking](#web--networking)
- [Applications & Multimedia](#applications--multimedia)
- [Databases](#databases)
- [Games](#games)
- [Emulation & Virtualization](#emulation--virtualization)
- [Ecosystems & Companion Tools](#ecosystems--companion-tools)
- [Niche Linux Dotfiles Stacks](#niche-linux-dotfiles-stacks)

---

## Git Hosting Platforms

### Self-Hosted
*Platforms you can run yourself.*

| Platform | Repo | Description |
|----------|------|-------------|
| **Gitea** | [go-gitea/gitea](https://gitea.com/gitea/gitea) | Lightweight self-hosted Git service written in Go |
| **Forgejo** | [forgejo/forgejo](https://codeberg.org/forgejo/forgejo) | Community-driven fork of Gitea |
| **GitLab CE** | [gitlabhq/gitlabhq](https://gitlab.com/gitlabhq/gitlabhq) | Open-source GitLab Community Edition |
| **Gogs** | [gogs/gogs](https://gogs.io) | Painless self-hosted Git service in Go |

### Public Instances
*Publicly accessible git hosting services.*

| Platform | URL | Focus |
|----------|-----|-------|
| **GitLab** | [gitlab.com](https://gitlab.com) | DevOps platform, big open-source community |
| **Codeberg** | [codeberg.org](https://codeberg.org) | Non-profit, community-driven, runs Forgejo |
| **Gitee** | [gitee.com](https://gitee.com) | China-based, popular in Chinese dev community |
| **Bitbucket** | [bitbucket.org](https://bitbucket.org) | Atlassian's offering, free private repos |
| **sr.ht** | [sr.ht](https://sr.ht) | Minimalist hosting, pays contributors |

---

## Operating Systems & Kernels

*   [**Linux Kernel**](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/) — The Linux kernel source tree. Uses its own cgit infrastructure.
*   [**Android (AOSP)**](https://android.googlesource.com/) — Android Open Source Project. Hosted on Google's Gitiles.
*   [**FreeBSD**](https://cgit.freebsd.org/src/) — FreeBSD operating system source tree.
*   [**OpenBSD**](https://cgit.openbsd.org/src/) — OpenBSD operating system source tree.
*   [**NetBSD**](https://anonhg.netbsd.org/) — NetBSD source tree.
*   [**Fuchsia**](https://fuchsia.googlesource.com/fuchsia) — Google's capability-based operating system.
*   [**Haiku**](https://cgit.haiku-os.org/haiku/) — Open-source OS targeting personal computing, inspired by BeOS.
*   [**Alpine Linux**](https://gitlab.alpinelinux.org/alpine/aports) — Security-oriented, lightweight Linux distribution based on musl libc and busybox.
*   [**Gentoo**](https://gitweb.gentoo.org/repo/gentoo.git/) — The official Gentoo package repository.
*   [**Yocto Project (Poky)**](https://git.yoctoproject.org/poky) — A reference embedded distribution for the Yocto Project.
*   [**Buildroot**](https://git.buildroot.net/buildroot) — A simple, efficient and easy-to-use tool to generate embedded Linux systems.
*   [**OpenWrt**](https://git.openwrt.org/openwrt/openwrt.git) — A Linux operating system targeting embedded devices.
*   [**9front**](https://git.9front.org/plan9front/plan9front) — A fork of the Plan 9 operating system.
*   [**Trisquel**](https://gitlab.trisquel.org/trisquel/package-helpers) — A fully free operating system endorsed by the Free Software Foundation.
*   [**GNU Hurd**](https://git.savannah.gnu.org/cgit/hurd/hurd.git) — The GNU project's replacement for the Unix kernel.
*   [**MINIX 3**](https://git.minix3.org/minix.git) — A free, highly reliable microkernel OS created by Andrew S. Tanenbaum.
*   [**postmarketOS**](https://gitlab.com/postmarketOS/pmaports) — A Linux distribution for phones and other mobile devices.
*   [**Ubuntu Touch**](https://gitlab.com/ubports/development/core/ubuntu-touch) — A mobile version of the Ubuntu operating system.

## Core System & Toolchains

*   [**Git**](https://git.kernel.org/pub/scm/git/git.git/) — The source code of the Git version control system itself.
*   [**GCC (GNU Compiler Collection)**](https://gcc.gnu.org/git/gcc.git) — The GNU Compiler Collection.
*   [**Glibc (GNU C Library)**](https://sourceware.org/git/glibc.git) — The GNU C Library, used in most Linux systems.
*   [**Musl libc**](https://git.musl-libc.org/cgit/musl/) — Lightweight, fast, simple C library.
*   [**GNU Coreutils**](https://git.savannah.gnu.org/cgit/coreutils.git) — The basic file, shell and text manipulation utilities of the GNU operating system.
*   [**GNU Bash**](https://git.savannah.gnu.org/cgit/bash.git) — The GNU Bourne-Again SHell.
*   [**GnuPG**](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gnupg.git) — The GNU Privacy Guard, a free implementation of the OpenPGP standard.
*   [**Samba**](https://git.samba.org/samba.git) — Standard Windows interoperability suite of programs for Linux and Unix.
*   [**BusyBox**](https://git.busybox.net/busybox/) — The Swiss Army Knife of Embedded Linux.
*   [**GNU Binutils & GDB**](https://sourceware.org/git/binutils-gdb.git) — The GNU Binary Utilities and the GNU Project Debugger.
*   [**GNU Guix**](https://git.savannah.gnu.org/cgit/guix.git) — Transactional package manager and advanced distribution of the GNU system.
*   [**pacman**](https://gitlab.archlinux.org/pacman/pacman) — A library-based package manager with dependency support used by Arch Linux.
*   [**Libreboot**](https://cgit.libreboot.org/libreboot.git) — Free system boot replacement (coreboot distribution).
*   [**s6**](https://git.skarnet.org/cgits/s6) — A small suite of programs for UNIX, designed to allow process supervision.
*   [**Zsh**](https://git.code.sf.net/p/zsh/code) — A shell designed for interactive use, although it is also a powerful scripting language.
*   [**GRUB**](https://git.savannah.gnu.org/cgit/grub.git) — The GRand Unified Bootloader, default for most Linux distributions.
*   [**Coreboot**](https://review.coreboot.org/coreboot.git) — An extended firmware platform aiming to replace proprietary BIOS/UEFI.
*   [**Woodpecker CI**](https://codeberg.org/woodpecker-ci/woodpecker) — A simple, extensible continuous integration engine.
*   [**Cygwin & Newlib**](https://sourceware.org/git/newlib-cygwin.git) — A large collection of GNU and Open Source tools providing functionality similar to a Linux distribution on Windows.
*   [**Valgrind**](https://sourceware.org/git/valgrind.git) — An instrumentation framework for building dynamic analysis tools (memory debugging, profiling).

## Core Frameworks & Libraries

*   [**Qt**](https://code.qt.io/cgit/qt/qtbase.git) — The legendary cross-platform application framework and widget toolkit.
*   [**Cairo**](https://gitlab.freedesktop.org/cairo/cairo) — A 2D graphics library with support for multiple output devices.
*   [**FreeType**](https://gitlab.freedesktop.org/freetype/freetype) — A freely available software library to render fonts.
*   [**EFL (Enlightenment Foundation Libraries)**](https://git.enlightenment.org/enlightenment/efl) — A collection of libraries handling drawing, event loops, and UI widgets.
*   [**CMake**](https://gitlab.kitware.com/cmake/cmake) — The de facto standard build system generator for C and C++.

## Programming Languages

*   [**Go**](https://go.googlesource.com/go) — The Go programming language. Hosted on Google's Gitiles.
*   [**Ruby**](https://git.ruby-lang.org/ruby.git) — Official Ruby language source tree.
*   [**GHC (Glasgow Haskell Compiler)**](https://gitlab.haskell.org/ghc/ghc) — The main compiler for the Haskell programming language.
*   [**V8**](https://chromium.googlesource.com/v8/v8) — Google's open source high-performance JavaScript and WebAssembly engine.
*   [**Free Pascal**](https://gitlab.com/freepascal.org/fpc/source) — A 32, 64, and 16-bit professional Pascal compiler.
*   [**Hare**](https://git.sr.ht/~sircmpwn/hare) — A systems programming language designed to be simple, stable, and robust.
*   [**Vala**](https://gitlab.gnome.org/GNOME/vala) — An object-oriented language that compiles to C and is deeply integrated with GObject.
*   [**GNU Guile**](https://git.savannah.gnu.org/cgit/guile.git) — The preferred extension language for the GNU system (Scheme implementation).
*   [**Tcl/Tk**](https://core.tcl-lang.org/tcl) — A powerful dynamic programming language and GUI toolkit (hosted via Fossil).

## Desktop Environments & Display Servers

*   [**Wayland**](https://gitlab.freedesktop.org/wayland/wayland) — The Wayland display server protocol.
*   [**XServer**](https://gitlab.freedesktop.org/xorg/xserver) — The X.Org X11 display server.
*   [**Mesa**](https://gitlab.freedesktop.org/mesa/mesa) — Open-source OpenGL, Vulkan, and other graphics API implementations.
*   [**GNOME (GTK)**](https://gitlab.gnome.org/GNOME/gtk) — The GTK toolkit and core GNOME libraries.
*   [**KDE Plasma**](https://invent.kde.org/plasma/plasma-workspace) — The KDE Plasma desktop environment.
*   [**Sway (wlroots)**](https://gitlab.freedesktop.org/wlroots/wlroots) — Modular Wayland compositor library used by Sway.
*   [**River**](https://codeberg.org/river/river) — A dynamic tiling Wayland compositor.
*   [**Xfce**](https://gitlab.xfce.org/xfce) — A lightweight desktop environment for UNIX-like operating systems.
*   [**dwm**](https://git.suckless.org/dwm/) — A dynamic window manager for X.
*   [**st**](https://git.suckless.org/st/) — A simple terminal implementation for X.
*   [**Enlightenment**](https://git.enlightenment.org/enlightenment/enlightenment) — A window manager and desktop environment known for its eye-candy and performance.

## Web & Networking

*   [**Chromium**](https://chromium.googlesource.com/chromium/src) — The open-source browser project behind Google Chrome, Edge, Brave, etc.
*   [**Tor Browser**](https://gitlab.torproject.org/tpo/applications/tor-browser) — The Tor Browser source code.
*   [**OpenSSH**](https://anongit.mindrot.org/openssh.git) — The premier connectivity tool for remote login with the SSH protocol.
*   [**WireGuard**](https://git.zx2c4.com/wireguard-linux) — Fast, modern, secure VPN tunnel.
*   [**Wireshark**](https://gitlab.com/wireshark/wireshark) — The world's most popular network protocol analyzer.
*   [**Tor**](https://gitlab.torproject.org/tpo/core/tor) — The core Tor network daemon.
*   [**HAProxy**](https://git.haproxy.org/?p=haproxy.git) — Reliable, high performance TCP/HTTP load balancer.
*   [**MediaWiki**](https://gerrit.wikimedia.org/r/mediawiki/core) — The free software wiki engine used by Wikipedia.
*   [**Drupal**](https://git.drupalcode.org/project/drupal) — Open source content management system.
*   [**PeerTube**](https://framagit.org/framasoft/peertube/PeerTube) — A free, decentralized and federated video platform.
*   [**Mobilizon**](https://framagit.org/framasoft/mobilizon) — A federated tool to find, create and organize events.
*   [**Pleroma**](https://git.pleroma.social/pleroma/pleroma) — A lightweight fediverse server.
*   [**cgit**](https://git.zx2c4.com/cgit/) — A hyperfast web frontend for git repositories written in C.
*   [**NetSurf**](https://git.netsurf-browser.org/netsurf.git) — A small, fast web browser.
*   [**Ikiwiki**](https://git.ikiwiki.info/) — A wiki compiler.
*   [**GNU IceCat**](https://git.savannah.gnu.org/cgit/gnuzilla.git) — The GNU version of the Firefox browser, with emphasis on privacy and free software.
*   [**Lighttpd**](https://git.lighttpd.net/lighttpd/lighttpd.git) — A secure, fast, compliant, and very flexible web-server.
*   [**BIND 9**](https://gitlab.isc.org/isc-projects/bind9) — The most widely used Domain Name System (DNS) software on the Internet.
*   [**Exim**](https://git.exim.org/exim.git) — A widely used message transfer agent (MTA) developed at the University of Cambridge.
*   [**Jami**](https://git.jami.net/savoirfairelinux/jami-client-qt) — A free and universal communication platform preserving user privacy (GNU project).
*   [**Gajim**](https://gitlab.com/gajim/gajim) — A fully-featured XMPP client written in Python and GTK.
*   [**GnuTLS**](https://gitlab.com/gnutls/gnutls) — A secure communications library implementing the SSL, TLS and DTLS protocols.
*   [**GNU Wget**](https://git.savannah.gnu.org/cgit/wget.git) — The classic, non-interactive network downloader.

## Applications & Multimedia

*   [**GNU Emacs**](https://git.savannah.gnu.org/cgit/emacs.git) — The extensible, customizable, self-documenting real-time display editor.
*   [**LibreOffice**](https://git.libreoffice.org/core) — The free office productivity suite.
*   [**Blender**](https://projects.blender.org/blender/blender) — 3D creation suite. Hosted on their own Gitea instance.
*   [**GIMP**](https://gitlab.gnome.org/GNOME/gimp) — GNU Image Manipulation Program.
*   [**Krita**](https://invent.kde.org/graphics/krita) — Professional free and open source painting program.
*   [**Inkscape**](https://gitlab.com/inkscape/inkscape) — Professional vector graphics editor.
*   [**KiCad**](https://gitlab.com/kicad/code/kicad) — Cross Platform and Open Source Electronics Design Automation Suite.
*   [**VLC Media Player**](https://code.videolan.org/videolan/vlc) — Highly portable multimedia player.
*   [**FFmpeg**](https://git.ffmpeg.org/ffmpeg.git) — Complete, cross-platform solution to record, convert and stream audio and video.
*   [**GStreamer**](https://gitlab.freedesktop.org/gstreamer/gstreamer) — A powerful, versatile, and extensible multimedia framework.
*   [**PipeWire**](https://gitlab.freedesktop.org/pipewire/pipewire) — Server and user space API to deal with multimedia pipelines.
*   [**PulseAudio**](https://gitlab.freedesktop.org/pulseaudio/pulseaudio) — A featureful, general-purpose sound server for POSIX OSes.
*   [**Ardour**](https://git.ardour.org/ardour/ardour.git) — The digital audio workstation.
*   [**Pass**](https://git.zx2c4.com/password-store/) — The standard unix password manager.
*   [**F-Droid**](https://gitlab.com/fdroid/fdroidclient) — The free and open source Android app repository client.
*   [**aerc**](https://git.sr.ht/~rjarry/aerc) — A highly efficient email client for your terminal.
*   [**catgirl**](https://git.causal.agency/catgirl) — A TLS-only terminal IRC client.
*   [**GNU Screen**](https://git.savannah.gnu.org/cgit/screen.git) — A full-screen window manager that multiplexes a physical terminal.
*   [**GNU Nano**](https://git.savannah.gnu.org/cgit/nano.git) — A small and friendly text editor.
*   [**Mutt**](https://gitlab.com/muttmua/mutt) — A small but very powerful text-based mail client.
*   [**Kdenlive**](https://invent.kde.org/multimedia/kdenlive) — An open source video editor based on the MLT Framework and KDE Frameworks.

## Databases

*   [**PostgreSQL**](https://git.postgresql.org/gitweb/) — The world's most advanced open source relational database.
*   [**SQLite**](https://sqlite.org/src/) — The most deployed database engine in the world. (Note: Primarily hosted using Fossil).

## Games

*   [**Veloren**](https://gitlab.com/veloren/veloren) — A multiplayer voxel RPG written in Rust.
*   [**Xonotic**](https://gitlab.com/xonotic/xonotic) — An addictive arena shooter with crisp movement and a wide array of weapons.
*   [**0 A.D.**](https://gitea.wildfiregames.com/0ad/0ad) — A free, open-source, historical Real Time Strategy (RTS) game and engine.
*   [**OpenMW**](https://gitlab.com/OpenMW/openmw) — An open-source game engine reimplementation of The Elder Scrolls III: Morrowind.

## Emulation & Virtualization

*   [**QEMU**](https://gitlab.com/qemu-project/qemu) — A generic and open source machine emulator and virtualizer.
*   [**Wine**](https://gitlab.winehq.org/wine/wine) — A compatibility layer capable of running Windows applications on Linux and other POSIX-compliant operating systems.
*   [**Xen Project**](https://xenbits.xen.org/git-http/xen.git) — The legendary baremetal hypervisor.

## Ecosystems & Companion Tools

*Tools, extensions, and core applications that complement the major projects listed above.*

### Wayland & Sway (SourceHut)
*   [**mako**](https://git.sr.ht/~emersion/mako) — A lightweight notification daemon for Wayland.
*   [**grim**](https://git.sr.ht/~emersion/grim) — A tool to grab images from a Wayland compositor.
*   [**slurp**](https://git.sr.ht/~emersion/slurp) — Select a region in a Wayland compositor (often used with grim).

### Suckless Tools (git.suckless.org)
*   [**dmenu**](https://git.suckless.org/dmenu/) — A fast and lightweight dynamic menu for X.
*   [**slstatus**](https://git.suckless.org/slstatus/) — A status monitor for window managers that use WM_NAME (like dwm).
*   [**surf**](https://git.suckless.org/surf/) — A simple web browser based on WebKit2/GTK+.

### GNU Ecosystem (Savannah)
*   [**Org-mode**](https://git.savannah.gnu.org/cgit/emacs/org-mode.git) — For keeping notes, maintaining TODO lists, planning projects, and authoring documents within Emacs.
*   [**GNU Make**](https://git.savannah.gnu.org/cgit/make.git) — A tool which controls the generation of executables and other non-source files of a program.
*   [**GNU Awk (gawk)**](https://git.savannah.gnu.org/cgit/gawk.git) — The GNU implementation of the AWK programming language.

### Linux Userland & Networking Core (kernel.org / freedesktop)
*   [**util-linux**](https://git.kernel.org/pub/scm/utils/util-linux/util-linux.git) — Essential system utilities like `mount`, `fdisk`, and `dmesg`.
*   [**iproute2**](https://git.kernel.org/pub/scm/network/iproute2/iproute2.git) — The standard networking utilities for Linux (like `ip`).
*   [**D-Bus**](https://gitlab.freedesktop.org/dbus/dbus) — The standard message bus system for inter-process communication on Linux.
*   [**NetworkManager**](https://gitlab.freedesktop.org/NetworkManager/NetworkManager) — The standard daemon for managing internet connections on Linux.

### Terminal Email Syncing (SourceForge / cgit)
*   [**isync (mbsync)**](https://git.code.sf.net/p/isync/isync) — A fast command line application which synchronizes mailboxes (IMAP/Maildir).
*   [**msmtp**](https://git.marlam.de/msmtp.git) — A very simple and easy to use SMTP client with excellent sendmail compatibility.

### Desktop Core Apps (GitLab instances)
*   [**WirePlumber**](https://gitlab.freedesktop.org/pipewire/wireplumber) — A powerful session and policy manager for PipeWire.
*   [**Dolphin**](https://invent.kde.org/system/dolphin) — KDE's lightweight and powerful file manager.
*   [**Nautilus**](https://gitlab.gnome.org/GNOME/nautilus) — The core file manager for the GNOME desktop.
*   [**Thunar**](https://gitlab.xfce.org/xfce/thunar) — A modern file manager for the Xfce Desktop Environment.
*   [**Okular**](https://invent.kde.org/graphics/okular) — The universal document viewer developed by KDE.
*   [**Evince**](https://gitlab.gnome.org/GNOME/evince) — A document viewer for multiple document formats for the GNOME desktop.
*   [**Epiphany (GNOME Web)**](https://gitlab.gnome.org/GNOME/epiphany) — The web browser for the GNOME desktop.

### Operating System Tooling
*   [**apk-tools**](https://gitlab.alpinelinux.org/alpine/apk-tools) — The Alpine Package Keeper, Alpine Linux's package manager.
*   [**FreeBSD Ports**](https://cgit.freebsd.org/ports/) — The FreeBSD ports and packages collection.

---

## Niche Linux Dotfiles Stacks

If you want to build a highly customized, niche Linux dotfiles setup using *only* software whose primary development happens outside of GitHub, here are a few theoretical stacks you can build from this list:

### 1. The "Suckless" X11 Minimalist
A setup focusing on absolute minimalism, compiling from source, and using C-based configuration.
*   **OS Base**: [Alpine Linux](https://gitlab.alpinelinux.org/alpine/aports)
*   **Window Manager**: [dwm](https://git.suckless.org/dwm/)
*   **App Launcher**: [dmenu](https://git.suckless.org/dmenu/)
*   **Status Bar**: [slstatus](https://git.suckless.org/slstatus/)
*   **Terminal**: [st](https://git.suckless.org/st/)
*   **Shell**: [GNU Bash](https://git.savannah.gnu.org/cgit/bash.git)
*   **Web Browser**: [surf](https://git.suckless.org/surf/)
*   **Editor**: [GNU Emacs](https://git.savannah.gnu.org/cgit/emacs.git) (or just `vi` from [BusyBox](https://git.busybox.net/busybox/))
*   **Passwords**: [Pass](https://git.zx2c4.com/password-store/)

### 2. The Modern Wayland Indie Hacker
A modern, keyboard-driven Wayland setup utilizing indie tools hosted primarily on SourceHut and self-hosted instances.
*   **OS Base**: [GNU Guix](https://git.savannah.gnu.org/cgit/guix.git)
*   **Compositor**: [Sway](https://gitlab.freedesktop.org/wlroots/wlroots)
*   **Notifications**: [mako](https://git.sr.ht/~emersion/mako)
*   **Screenshots**: [grim](https://git.sr.ht/~emersion/grim) + [slurp](https://git.sr.ht/~emersion/slurp)
*   **Terminal**: [st](https://git.suckless.org/st/)
*   **Shell**: [Zsh](https://git.code.sf.net/p/zsh/code)
*   **Web Browser**: [Chromium](https://chromium.googlesource.com/chromium/src)
*   **Email Stack**: [aerc](https://git.sr.ht/~rjarry/aerc) + [isync (mbsync)](https://git.code.sf.net/p/isync/isync) + [msmtp](https://git.marlam.de/msmtp.git)
*   **IRC Client**: [catgirl](https://git.causal.agency/catgirl)

### 3. The Lightweight Traditional Desktop
A more traditional, mouse-friendly setup that avoids heavy corporate telemetry and bloat.
*   **OS Base**: [Alpine Linux](https://gitlab.alpinelinux.org/alpine/aports)
*   **Desktop Environment**: [Xfce](https://gitlab.xfce.org/xfce)
*   **File Manager**: [Thunar](https://gitlab.xfce.org/xfce/thunar)
*   **Network Manager**: [NetworkManager](https://gitlab.freedesktop.org/NetworkManager/NetworkManager)
*   **Shell**: [GNU Bash](https://git.savannah.gnu.org/cgit/bash.git)
*   **Web Browser**: [Tor Browser](https://gitlab.torproject.org/tpo/applications/tor-browser)
*   **Text Editor**: [GNU Nano](https://git.savannah.gnu.org/cgit/nano.git)
*   **Office Suite**: [LibreOffice](https://git.libreoffice.org/core)
*   **Media**: [VLC](https://code.videolan.org/videolan/vlc)

### 4. The Free Software Absolutist
A Libre-only stack endorsed by the Free Software Foundation. No proprietary blobs, telemetry, or non-free JS allowed.
*   **Firmware**: [Libreboot](https://cgit.libreboot.org/libreboot.git)
*   **Operating System**: [Trisquel](https://gitlab.trisquel.org/trisquel/package-helpers)
*   **Desktop Environment**: [GNOME (GTK)](https://gitlab.gnome.org/GNOME/gtk)
*   **File Manager**: [Nautilus](https://gitlab.gnome.org/GNOME/nautilus)
*   **Shell**: [GNU Bash](https://git.savannah.gnu.org/cgit/bash.git)
*   **Web Browser**: [GNU IceCat](https://git.savannah.gnu.org/cgit/gnuzilla.git) or [Epiphany](https://gitlab.gnome.org/GNOME/epiphany)
*   **Document Viewer**: [Evince](https://gitlab.gnome.org/GNOME/evince)
*   **Text Editor**: [GNU Emacs](https://git.savannah.gnu.org/cgit/emacs.git) + [Org-mode](https://git.savannah.gnu.org/cgit/emacs/org-mode.git)
*   **Office Suite**: [LibreOffice](https://git.libreoffice.org/core)

### 5. The Hardened Server / Privacy Node
A completely self-hosted, supervised environment built for resilience and security without systemd.
*   **Base OS**: [OpenBSD](https://cgit.openbsd.org/src/)
*   **Process Supervision**: [s6](https://git.skarnet.org/cgits/s6)
*   **Core Utils**: [util-linux](https://git.kernel.org/pub/scm/utils/util-linux/util-linux.git)
*   **Shell**: [Zsh](https://git.code.sf.net/p/zsh/code)
*   **Terminal Multiplexer**: [GNU Screen](https://git.savannah.gnu.org/cgit/screen.git)
*   **Web Server**: [Lighttpd](https://git.lighttpd.net/lighttpd/lighttpd.git)
*   **VPN**: [WireGuard](https://git.zx2c4.com/wireguard-linux)
*   **Anonymity**: [Tor](https://gitlab.torproject.org/tpo/core/tor)

### 6. The Open-Source Creative Studio
A dotfiles setup tailored to digital artists, musicians, and video editors who rely on independent community infrastructure.
*   **OS Base**: [FreeBSD](https://cgit.freebsd.org/src/)
*   **Desktop Environment**: [Enlightenment](https://git.enlightenment.org/enlightenment/enlightenment)
*   **Web Browser**: [Chromium](https://chromium.googlesource.com/chromium/src)
*   **Audio Pipeline**: [PipeWire](https://gitlab.freedesktop.org/pipewire/pipewire) + [WirePlumber](https://gitlab.freedesktop.org/pipewire/wireplumber)
*   **Digital Audio Workstation**: [Ardour](https://git.ardour.org/ardour/ardour.git)
*   **Video Editing**: [Kdenlive](https://invent.kde.org/multimedia/kdenlive)
*   **Graphics & Painting**: [Krita](https://invent.kde.org/graphics/krita) and [GIMP](https://gitlab.gnome.org/GNOME/gimp)
*   **3D Modeling**: [Blender](https://projects.blender.org/blender/blender)

### 7. The Console Warrior (TUI Only)
A machine running without X11 or Wayland, entirely dependent on the framebuffer, GNU tools, and multiplexers.
*   **OS Base**: [Alpine Linux](https://gitlab.alpinelinux.org/alpine/aports) or [Buildroot](https://git.buildroot.net/buildroot)
*   **Shell**: [Zsh](https://git.code.sf.net/p/zsh/code)
*   **Multiplexer**: [GNU Screen](https://git.savannah.gnu.org/cgit/screen.git)
*   **Network Config**: [iproute2](https://git.kernel.org/pub/scm/network/iproute2/iproute2.git)
*   **Mail Stack**: [Mutt](https://gitlab.com/muttmua/mutt) + [isync (mbsync)](https://git.code.sf.net/p/isync/isync) + [msmtp](https://git.marlam.de/msmtp.git)
*   **Text Editor**: [GNU Nano](https://git.savannah.gnu.org/cgit/nano.git) or `vi`
*   **Text Processing**: [GNU Awk (gawk)](https://git.savannah.gnu.org/cgit/gawk.git)

### 8. The Complete KDE Plasma Workstation
A fully-featured KDE experience built mostly from KDE's own GitLab instance.
*   **OS Base**: [Gentoo](https://gitweb.gentoo.org/repo/gentoo.git/)
*   **Desktop Environment**: [KDE Plasma](https://invent.kde.org/plasma/plasma-workspace)
*   **File Manager**: [Dolphin](https://invent.kde.org/system/dolphin)
*   **Document Viewer**: [Okular](https://invent.kde.org/graphics/okular)
*   **Video Editor**: [Kdenlive](https://invent.kde.org/multimedia/kdenlive)
*   **Graphics**: [Krita](https://invent.kde.org/graphics/krita)
*   **Browser**: [Chromium](https://chromium.googlesource.com/chromium/src)

### 9. The Mobile / Post-Convergence User
A stack centered around running a true Linux stack on mobile hardware.
*   **OS Base**: [postmarketOS](https://gitlab.com/postmarketOS/pmaports) or [Ubuntu Touch](https://gitlab.com/ubports/development/core/ubuntu-touch)
*   **Compositor**: [Sway](https://gitlab.freedesktop.org/wlroots/wlroots) (highly adaptable to mobile)
*   **Browser**: [Epiphany (GNOME Web)](https://gitlab.gnome.org/GNOME/epiphany)
*   **Communications**: [Jami](https://git.jami.net/savoirfairelinux/jami-client-qt) + [Gajim](https://gitlab.com/gajim/gajim)
*   **Mail**: [aerc](https://git.sr.ht/~rjarry/aerc)
*   **Network**: [NetworkManager](https://gitlab.freedesktop.org/NetworkManager/NetworkManager) + [WireGuard](https://git.zx2c4.com/wireguard-linux)

### 10. The Legacy UNIX Purist
A purist approach prioritizing code correctness and portability over modern fluff.
*   **OS Base**: [NetBSD](https://anonhg.netbsd.org/)
*   **Window Manager**: [dwm](https://git.suckless.org/dwm/)
*   **Terminal**: [st](https://git.suckless.org/st/)
*   **Browser**: [NetSurf](https://git.netsurf-browser.org/netsurf.git)
*   **Mail Stack**: [Mutt](https://gitlab.com/muttmua/mutt)
*   **Text Editor**: [GNU Nano](https://git.savannah.gnu.org/cgit/nano.git) or `vi`
*   **Compiler**: [GCC](https://gcc.gnu.org/git/gcc.git)

### 11. The Hardware Engineer / Maker
A workstation designed for electronics design and embedded systems development.
*   **OS Base**: [Gentoo](https://gitweb.gentoo.org/repo/gentoo.git/)
*   **Desktop Environment**: [Xfce](https://gitlab.xfce.org/xfce)
*   **Hardware Design**: [KiCad](https://gitlab.com/kicad/code/kicad)
*   **Embedded Build System**: [Buildroot](https://git.buildroot.net/buildroot) or [Yocto (Poky)](https://git.yoctoproject.org/poky)
*   **System Tools**: [util-linux](https://git.kernel.org/pub/scm/utils/util-linux/util-linux.git) (fdisk, mount)
*   **Terminal**: [st](https://git.suckless.org/st/) + [GNU Screen](https://git.savannah.gnu.org/cgit/screen.git)

### 12. The Plan 9 / 9front Enthusiast
A complete departure from UNIX, using the Plan 9 fork ecosystem.
*   **OS Base**: [9front](https://git.9front.org/plan9front/plan9front)
*   **Window Manager**: `rio` (built into 9front)
*   **Editor**: `sam` / `acme` (built into 9front)
*   **Compiler**: Plan 9 C compiler (built into 9front)
*   **Mail**: `upas` (built into 9front)
*(Note: 9front provides a completely self-contained userland and graphical environment out-of-the-box).*

### 13. The Graphical Wayland Power User
For those who want dynamic tiling but with a bit more modernity and flexibility than Sway.
*   **OS Base**: Arch Linux (using [pacman](https://gitlab.archlinux.org/pacman/pacman))
*   **Compositor**: [River](https://codeberg.org/river/river)
*   **Launcher**: [dmenu](https://git.suckless.org/dmenu/) (via Xwayland or Wayland ports)
*   **Terminal**: [st](https://git.suckless.org/st/)
*   **Browser**: [Chromium](https://chromium.googlesource.com/chromium/src)
*   **Audio Pipeline**: [PipeWire](https://gitlab.freedesktop.org/pipewire/pipewire) + [WirePlumber](https://gitlab.freedesktop.org/pipewire/wireplumber)

### 14. The Secure OSINT Node
Focused completely on anonymity, secure communications, and privacy.
*   **OS Base**: [Alpine Linux](https://gitlab.alpinelinux.org/alpine/aports)
*   **Window Manager**: [Sway](https://gitlab.freedesktop.org/wlroots/wlroots)
*   **Networking**: [Tor](https://gitlab.torproject.org/tpo/core/tor) + [WireGuard](https://git.zx2c4.com/wireguard-linux)
*   **Communications**: [Jami](https://git.jami.net/savoirfairelinux/jami-client-qt) + [Gajim](https://gitlab.com/gajim/gajim) + [catgirl](https://git.causal.agency/catgirl)
*   **Browser**: [Tor Browser](https://gitlab.torproject.org/tpo/applications/tor-browser)

### 15. The Pure GNOME Evangelist
Using nothing but official GNOME stack projects hosted directly on GNOME's GitLab.
*   **OS Base**: [Trisquel](https://gitlab.trisquel.org/trisquel/package-helpers)
*   **Desktop Environment**: [GNOME (GTK)](https://gitlab.gnome.org/GNOME/gtk)
*   **File Manager**: [Nautilus](https://gitlab.gnome.org/GNOME/nautilus)
*   **Browser**: [Epiphany (GNOME Web)](https://gitlab.gnome.org/GNOME/epiphany)
*   **Document Viewer**: [Evince](https://gitlab.gnome.org/GNOME/evince)
*   **Multimedia**: [GStreamer](https://gitlab.freedesktop.org/gstreamer/gstreamer)

### 16. The Lightweight Haiku Desktop
A complete desktop experience that avoids Linux and BSD entirely, focused on personal computing.
*   **OS Base**: [Haiku](https://cgit.haiku-os.org/haiku/)
*   **File Manager**: Tracker (built-in)
*   **Web Browser**: WebPositive (built-in)
*   **Terminal**: Haiku Terminal (built-in)
*   **Media**: [VLC Media Player](https://code.videolan.org/videolan/vlc) (ported to Haiku)

---

## Contribution

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

A few notes:
- **Only non-GitHub primary repos** — Please only add repositories where the **primary** source of truth is not GitHub. If a project uses GitHub as its main issue tracker and PR platform, it belongs in other awesome lists.
- **Keep descriptions concise** — one line per repo.
- **Verify links** — make sure the URL works before submitting.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
