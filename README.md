# flatpak-kadas
<BR>Flatpak builds of KADAS Albireo from git https://github.com/kadas-albireo/kadas-albireo2
<BR>
<BR>Build:
<BR>clear && flatpak-builder --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir com.sourcepole.kadas.yml
<BR>
<BR>Build & Install:
<BR>clear && flatpak-builder --user --install --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir com.sourcepole.kadas.yml
<BR>
<BR>Or download an artifact from https://github.com/mattiasegly/flatpak-kadas/actions/workflows/flatpak-builder.yml
<BR>Extract .zip archive and install with:
<BR>flatpak --user install kadas.flatpak
