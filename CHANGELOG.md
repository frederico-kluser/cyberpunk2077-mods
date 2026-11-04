# Changelog

Todas as mudanças notáveis deste repositório (e dos instaladores que ele publica) ficam aqui.
Formato: [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/) · versionamento em
[SemVer](https://semver.org/lang/pt-BR/).

## [0.2.1] — 2026-11-04

Primeira release pública: o **Mission Reset** para o Cyberpunk 2077 2.5.

### Adicionado
- Instalador em `.zip` para Windows (`install.cmd` / `install.ps1`) e Linux/Steam Deck (`install.sh`),
  com desinstalador (`uninstall.*`) que repõe os ficheiros substituídos.
- O zip traz o **NetSites 0.4.2** (dependência) e a ponte **LogSentry 0.4.1** — não é preciso mais nada.
- O instalador encontra a pasta do jogo sozinho (Steam, GOG, Epic; Linux nativo, Flatpak, Heroic,
  Lutris, cartões) e **avisa** o que falta (CET, redscript, Codeware) com o link de cada um.
- Instruções em português e inglês, imagens do fluxo de instalação e do resultado.
