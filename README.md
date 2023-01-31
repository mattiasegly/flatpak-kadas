# flatpak-kadas
Build:<BR>
clear && flatpak-builder --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir ch.sourcepole.kadas-albireo2.yml<BR>
Install:<BR>
clear && flatpak-builder --user --install --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir ch.sourcepole.kadas-albireo2.yml
