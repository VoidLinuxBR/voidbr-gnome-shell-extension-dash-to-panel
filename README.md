# voidbr-gnome-shell-extension-dash-to-panel

Empacotamento do [Dash to Panel](https://github.com/home-sweet-gnome/dash-to-panel) para o VoidBR Linux.

Instala a extensão **no sistema** (não no `~/.local`), para que os padrões do
`voidbr-gnome-config` (`90_voidbr-gnome.gschema.override`) sejam aplicados:
barra única embaixo, flutuante, transparente e desenhada em "ilhas" pelo tema
`VoidBR-Tokyonight`.

| Arquivo | Destino |
|---|---|
| extensão | `/usr/share/gnome-shell/extensions/dash-to-panel@jderose9.github.com` |
| schema | `/usr/share/glib-2.0/schemas/org.gnome.shell.extensions.dash-to-panel.gschema.xml` |
| traduções | `/usr/share/locale/*/LC_MESSAGES/dash-to-panel.mo` |

Para atualizar, troque o `pkgver` no `pkgfile/PKGFILE` pela nova tag do upstream (`v<pkgver>`).

Licença: GPL-2.0-or-later (a mesma do Dash to Panel).
