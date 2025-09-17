# flatpak-kadas
<BR>Flatpak builds of KADAS Albireo from git https://github.com/kadas-albireo/kadas-albireo2
<BR>
<BR>Build:
<BR>clear && flatpak-builder --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir com.sourcepole.kadas.yml
<BR>
<BR>Install:
<BR>clear && flatpak-builder --user --install --jobs=3 --ccache --disable-rofiles-fuse --force-clean --delete-build-dirs --disable-download build-dir com.sourcepole.kadas.yml
<BR>
<BR>
<BR>Download:
<BR>Get the occasional artifact from https://github.com/mattiasegly/flatpak-kadas/actions/workflows/flatpak-builder.yml
<BR>Extract .zip archive and install with:
<BR>flatpak --user install kadas.flatpak
