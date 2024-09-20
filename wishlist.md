This is a list of all sorts of various issues in software that intrigues me! Will be filled with more as time goes on.

## Wayland / Nvidia (NVK, etc) / XDG Portals / etc. Protocols

- [x] linux-drm-syncobj-v1 https://gitlab.freedesktop.org/wayland/wayland-protocols/-/merge_requests/90
- [x] xdg-toplevel-icon-v1 https://gitlab.freedesktop.org/wayland/wayland-protocols/-/merge_requests/269
- [x] ext-screencopy-v1 https://gitlab.freedesktop.org/wayland/wayland-protocols/-/merge_requests/124

#### chromium/electron wayland by default
[chromium wayland issue tracking](https://issues.chromium.org/issues?q=componentid:1456988%20status:(open%20%7C%20new%20%7C%20assigned%20%7C%20accepted))

#### winewayland.drv
[winewayland.drv MRs](https://gitlab.winehq.org/wine/wine/-/merge_requests?scope=all&state=opened&search=winewayland)

#### nvk

[General nvk issues](https://gitlab.freedesktop.org/mesa/mesa/-/issues/?label_name%5B%5D=NVK) [General nvk MRs](https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests?label_name%5B%5D=NVK) [gfxstrand's activity](https://gitlab.freedesktop.org/gfxstrand)

- [x] full zink support https://gitlab.freedesktop.org/mesa/mesa/-/issues/9477
- [x] full dxvk support https://gitlab.freedesktop.org/mesa/mesa/-/issues/9478
- [ ] full vkd3d-proton support https://gitlab.freedesktop.org/mesa/mesa/-/issues/9479

#### flatpaks

- [ ] steam: https://github.com/ValveSoftware/steam-for-linux/issues/4473
- [ ] vscode (issues keep being closed)

## [Cosmic Desktop Environment](https://github.com/pop-os/cosmic-epoch)

#### Xwayland/Electron/Server-side decorations

- [x] https://github.com/pop-os/cosmic-comp/issues/355
- [x] https://github.com/pop-os/cosmic-comp/issues/352
- [x] Blurry xwayland apps https://github.com/Smithay/smithay/pull/1223)
- [x] https://github.com/pop-os/cosmic-comp/issues/329
- [x] https://github.com/pop-os/cosmic-comp/issues/359

#### Other compositor issues/features

- [ ] https://github.com/pop-os/cosmic-comp/issues/351 https://github.com/Smithay/smithay/pull/1341
- [ ] linux-drm-syncobj-v1 https://github.com/Smithay/smithay/pull/1356

#### COSMIC Workspaces
- [ ] workspace overview touchpad gesture
- [ ] workspace scrolling in overview
- [x] fix lag when opening workspace overview for the first time
- [ ] fix too long names causing weird skinny windows
- [x] workspaces icon applet
- [ ] workspaces applet shortened mode (only show number to the left and right)

#### Quality of life changes needed

##### workspace gestures
- [x] to/from workspace gestures https://github.com/pop-os/cosmic-comp/pull/342
- [ ] open/close workspace overlay gestures

##### various Workspace fixes

##### other QOL changes

- [x] Icon handling for apps without a desktop entry [Solution 1: XDG Portal](https://github.com/flatpak/xdg-desktop-portal/discussions/1305) [Solution 2: Wayland Protocol](https://gitlab.freedesktop.org/wayland/wayland-protocols/-/merge_requests/269)
- [x] Cosmic apps are slow to open https://github.com/pop-os/cosmic-comp/issues/348
- [x] Drag windows to side or top to maximize or tile right/left https://github.com/pop-os/cosmic-comp/issues/340
- [x] libcosmic double-click to maximize window (requires double click in iced) https://github.com/pop-os/libcosmic/issues/323
- [ ] Click notification to go to source https://github.com/pop-os/cosmic-applets/issues/223

#### misc bugs
- [ ] Can't connect to enterprise network https://github.com/pop-os/cosmic-applets/issues/225
- [x] Can't unmute mic from audio applet https://github.com/pop-os/cosmic-applets/issues/234
- [x] No osds https://github.com/pop-os/cosmic-osd/pull/19
