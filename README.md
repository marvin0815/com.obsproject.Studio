Forked from https://github.com/flathub/com.obsproject.Studio

# Changes from upstream
1. added gstreamer-vaapi plugin
1. added obs-gstreamer plugin

# ToDo
* Update GST to 1.18.x
* publish build to some repo
* track and merge upstream updates

# Prebuild Package

```
curl -o - https://raw.githubusercontent.com/marvin0815/com.obsproject.Studio/gstreamer-vaapi/marvin0815@users.noreply.github.com.pub \
flatpak remote-add --gpg-import - obs-gst https://s3.undreaming.org/flatpak/
flatpak install obs-gst com.obsproject.Studio
```
