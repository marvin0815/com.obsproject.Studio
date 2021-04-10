Forked from https://github.com/flathub/com.obsproject.Studio

# Changes from upstream
1. added gstreamer-vaapi plugin
1. added gstreamer-msdk and vdpau plugin
1. added iHD libva driver
1. added obs-gstreamer plugin
1. added obs-gstreamer patch to support MSDK (no vdpau atm)
1. added libcef and enable browser plugin

# ToDo
* Update GST to 1.18.x
* track and merge upstream updates

# Prebuild Package

```
curl -o - https://raw.githubusercontent.com/marvin0815/com.obsproject.Studio/gstreamer-vaapi/marvin0815@users.noreply.github.com.pub && \
flatpak remote-add --gpg-import - obs-gst https://s3.undreaming.org/flatpak/
flatpak install obs-gst com.obsproject.Studio
```
