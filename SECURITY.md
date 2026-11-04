# Segurança

## O que reportar

- Um instalador que copia ficheiros para fora da pasta do jogo.
- Um `.zip` publicado que não corresponde ao `sha256` da release.
- Qualquer execução de código inesperada a partir do `install.cmd` / `install.sh`.

## Como reportar

**Não abras uma issue pública.** Usa o separador
[Security advisories](https://github.com/frederico-kluser/cyberpunk2077-mods-public/security/advisories/new)
(privado) com: versão do zip, `sha256` do ficheiro, sistema e o que observaste.

Resposta em até 7 dias. Os instaladores são scripts simples e auditáveis: `install.ps1` e `install.sh`
estão dentro do zip e podem ser lidos antes de correr.

## Âmbito

Este repositório **não distribui ficheiros do jogo** nem binários de terceiros: os instaladores contêm
scripts e o conteúdo do próprio mod (Lua/redscript/JSON).
