# Brew Packages

A list of recommendations for Homebrew packages on macOS I find useful.

## Essential

- [`vim`](https://formulae.brew.sh/formula/vim) (Text Editor)
- [`git`](https://formulae.brew.sh/formula/git) (Version Control)
- [`tmux`](https://formulae.brew.sh/formula/tmux) (Terminal Multiplexer)
- [`htop`](https://formulae.brew.sh/formula/htop) (Process Manager)
- [`python3`](https://formulae.brew.sh/formula/python@3.9) (Scripting Language)

## CLI Tools

- [`trash`](https://formulae.brew.sh/formula/trash) (Trash helper)
- [`tree`](https://formulae.brew.sh/formula/tree) (Directory listing)
- [`jq`](https://formulae.brew.sh/formula/jq) (JSON processor)
- [`rlwrap`](https://formulae.brew.sh/formula/rlwrap) (Readline wrapper)

## Development

- [`coreutils`](https://formulae.brew.sh/formula/coreutils) (GNU utils)
- [`visual-studio-code`](https://formulae.brew.sh/cask/visual-studio-code) (Editor/IDE)
- [`cmake` (Cask)](https://formulae.brew.sh/cask/cmake) (Build tool)
- [`ninja`](https://formulae.brew.sh/formula/ninja) (Lightweight build system)
- [`cocoapods`](https://formulae.brew.sh/formula/cocoapods) (Cocoa dependency manager)
- [`openjdk`](https://formulae.brew.sh/formula/openjdk) (Java)
- [`zulu8` (Cask)](https://github.com/Homebrew/homebrew-cask-versions/blob/master/Casks/zulu8.rb) (Java 8 with ARM64 support)
- [`node`](https://formulae.brew.sh/formula/node) (Node.js)
- [`gradle`](https://formulae.brew.sh/formula/gradle) (JVM build tool)
- [`haskell-stack`](https://formulae.brew.sh/formula/haskell-stack) (Haskell build tool)
- [`rustup-init`](https://formulae.brew.sh/formula/rustup-init) (Rust toolchain installer)
- [`swi-prolog`](https://formulae.brew.sh/formula/swi-prolog) (Prolog environment)
- [`flutter` (Cask)](https://formulae.brew.sh/cask/flutter) (UI toolkit)
- [`processing` (Cask)](https://formulae.brew.sh/cask/processing) (Software sketchbook)
- [`dotnet-sdk` (Cask)](https://formulae.brew.sh/cask/dotnet-sdk) (.NET SDK)
- [`llvm`](https://formulae.brew.sh/formula/llvm) (Compiler infrastructure, alternatively install via Xcode)
- [`ghidra`](https://formulae.brew.sh/cask/ghidra) (Reverse engineering tools)
- [`sf-symbols` (Cask)](https://formulae.brew.sh/cask/sf-symbols) (Symbols browser)

## Server

- [`postgresql`](https://formulae.brew.sh/formula/postgresql) (Database)
  - Note that you can use `brew services` [as described here](https://gist.github.com/ibraheem4/ce5ccd3e4d7a65589ce84f2a3b7c23a3?permalink_comment_id=3443897#gistcomment-3443897) to start and stop PostgreSQL as needed

## Emulation/Virtualization

- [`qemu`](https://formulae.brew.sh/formula/qemu) (Emulator)
- [`utm` (Cask)](https://formulae.brew.sh/cask/utm) (Virtual machines UI on top of QEMU)

## Containers

- [`docker` (Cask)](https://formulae.brew.sh/cask/docker) (Docker Desktop, container builder and runner)
- [`kubernetes-cli`](https://formulae.brew.sh/formula/kubernetes-cli) (Kubernetes API client)
- [`k9s`](https://formulae.brew.sh/formula/k9s) (Kubernetes TUI)
- [`helm`](https://formulae.brew.sh/formula/helm) (Kubernetes package manager)

## Utilities

- [`appcleaner` (Cask)](https://formulae.brew.sh/cask/appcleaner) (App removal utility)
- [`the-unarchiver` (Cask)](https://formulae.brew.sh/cask/the-unarchiver) (Unarchival tool)
- [`coconutbattery` (Cask)](https://formulae.brew.sh/cask/coconutbattery) (Battery info utility)
- [`barrier` (Cask)](https://formulae.brew.sh/cask/barrier) (KVM)
- [`raspberry-pi-imager` (Cask)](https://formulae.brew.sh/cask/raspberry-pi-imager) (Image flashing utility)

## Internet

- [`firefox` (Cask)](https://formulae.brew.sh/cask/firefox) (Web Browser)
- [`discord` (Cask)](https://formulae.brew.sh/cask/discord) (Voice and Text Chat)
- [`mattermost` (Cask)](https://formulae.brew.sh/cask/mattermost) (Text Chat)
- [`signal` (Cask)](https://formulae.brew.sh/cask/signal) (Messenger)
- [`zulip` (Cask)](https://formulae.brew.sh/cask/zulip) (Text Chat)
- [`slack` (Cask)](https://formulae.brew.sh/cask/slack) (Text Chat)
- [`zoom` (Cask)](https://formulae.brew.sh/cask/zoom) (Video Conferencing)

## Productivity

- [`mactex` (Cask)](https://formulae.brew.sh/cask/mactex) (LaTeX)
- [`libreoffice` (Cask)](https://formulae.brew.sh/cask/libreoffice) (Office suite)
- [`zotero` (Cask)](https://formulae.brew.sh/cask/zotero) (Bibliography manager)

## Fonts

- [`font-jetbrains-mono` (Cask)](https://github.com/Homebrew/homebrew-cask-fonts/blob/master/Casks/font-jetbrains-mono.rb) (Typeface for developers)

## Audio/Video

- [`ffmpeg`](https://formulae.brew.sh/formula/ffmpeg) (Audio/video converter)
- [`vlc` (Cask)](https://formulae.brew.sh/cask/vlc) (Multimedia player)
- [`spotify` (Cask)](https://formulae.brew.sh/cask/spotify) (Music streaming)
- [`mixxx` (Cask)](https://formulae.brew.sh/cask/mixxx) (DJing)
- [`blender` (Cask)](https://formulae.brew.sh/cask/blender) (3D modeling)
- [`obs` (Cask)](https://formulae.brew.sh/cask/obs) (Broadcasting and screencasting)
- [`blackhole-2ch` (Cask)](https://formulae.brew.sh/cask/blackhole-2ch) (Virtual Audio Driver, useful for routing desktop audio)

## Graphics

- [`gimp` (Cask)](https://formulae.brew.sh/cask/gimp) (Image editor)
- [`inkscape` (Cask)](https://formulae.brew.sh/cask/inkscape) (Vector graphics editor)

## Gaming

- [`epic-games` (Cask)](https://formulae.brew.sh/cask/epic-games) (Epic Games Launcher)
- [`steam` (Cask)](https://formulae.brew.sh/cask/steam) (Game Distribution Platform)
- [`multimc` (Cask)](https://formulae.brew.sh/cask/multimc) (Minecraft Launcher)
