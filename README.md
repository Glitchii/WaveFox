# *WaveFox*

##### Minimum Requirements
- Firefox 102 / ESR 102
- Windows
- MacOS
- Linux

##### Installation

- Download the `chrome` folder and put it in your user profile folder. For convenience, use `about:profiles`
- Go to `about:config` and activate the keys below

  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `svg.context-properties.content.enabled`
  - `layout.css.color-mix.enabled`

- Specify the desired shape of the tabs

  ##### Proton
  ![Proton](https://user-images.githubusercontent.com/85301851/180247798-3685fad6-cc4e-49ad-9b0e-7664354233ff.PNG)
  - `userChrome.ProtonTabs-Enabled`
  
  ##### Photon
  ![Photon](https://user-images.githubusercontent.com/85301851/180248812-8aecba52-77bd-4ee5-9e04-e6f07276dfa4.PNG)
  - `userChrome.PhotonTabs-Enabled`

  ##### WaveFox
  ![WaveFox](https://user-images.githubusercontent.com/85301851/180248857-fee4dd92-6d6c-4c34-8615-bf69e740f2bd.PNG)
  - `userChrome.WaveFoxTabs-Enabled`

  ##### Chrome
  ![Modern Chrome](https://user-images.githubusercontent.com/85301851/180248907-bdcf4ffc-fd4a-4923-b97d-a0b0b0cf5ee2.PNG)
  - `userChrome.ChromeTabs-Enabled`

  ##### Edge
  ![Edge](https://user-images.githubusercontent.com/85301851/180248952-faa55898-0243-4cdf-ba6a-33513184398f.PNG)
  - `userChrome.EdgeTabs-Enabled`

  ##### Australis
  ![Australis](https://user-images.githubusercontent.com/85301851/180248996-2f21d3b0-e33b-4feb-bbfc-2859df714344.PNG)
  - `userChrome.AustralisTabs-Enabled`

  ##### Chrome (Legacy)
  ![Legacy Chrome](https://user-images.githubusercontent.com/85301851/180249039-350dd21d-51ee-432b-a79d-0c82861e7d43.PNG)
  - `userChrome.LegacyChromeTabs-Enabled`

### How to create keys?
##### You need to restart your browser for the changes to take effect
![изображение](https://user-images.githubusercontent.com/85301851/180253017-22325fad-2f53-47f5-b409-618ca7fe6084.png)
![изображение](https://user-images.githubusercontent.com/85301851/180253209-3e6965a9-641a-4ac2-bf3d-242ac8b3451c.png)

## Optional

### Windows System Effects
Works with modern versions of Windows 11 / Windows 10. System effects must be supported on the operating system side. Otherwise, you need third-party software, such as MikaForEveryone. Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/160720915-a055134a-357c-44cc-a638-8dd56e869111.png)

Download and install MicaForEveryone from the link below.

https://github.com/minusium/MicaForEveryone/releases

- `userChrome.WindowsSystemEffects-Enabled`

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

- `userChrome.SemiTransparentToolbar-Enabled`
- `userChrome.TransparentToolbar-Enabled` (Proton Tabs Only)

### Linux Transparency
Requires Linux with transparency support. Tested on Linux Manjaro KDE + ForceBlur. Transparency is active for all modes, but does not work everywhere. This may change with future browser updates. Works only with the system theme.

![изображение](https://user-images.githubusercontent.com/85301851/173119832-e82bc2f7-eda7-4167-9dcd-ccca50383816.png)

- `userChrome.LinuxSemiTransparency-Enabled`
- `userChrome.LinuxTransparency-Enabled`
- `gfx.webrender.all` (Required key)

### Colorways
https://www.reddit.com/r/firefox/comments/uq26ao/bringing_back_your_preferred_colorways/?utm_source=share&utm_medium=web2x&context=3

### Additional Container Indicator
![изображение](https://user-images.githubusercontent.com/85301851/161597087-fc818bc5-c60e-48a9-8eb9-1bcafc030607.png)

- `userChrome.AdditionalContainerIndicator-Enabled`

### Tab Bar Highlight
It is also possible to turn on the border and the shadow at the same time.
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

##### Border
- `userChrome.LowBorderSaturation-Enabled`
- `userChrome.MediumBorderSaturation-Enabled`
- `userChrome.HighBorderSaturation-Enabled`
- `userChrome.VeryHighBorderSaturation-Enabled`

##### Shadow
- `userChrome.LowShadowSaturation-Enabled`
- `userChrome.MediumShadowSaturation-Enabled`
- `userChrome.HighShadowSaturation-Enabled`
- `userChrome.VeryHighShadowSaturation-Enabled`

### Tab Separators
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

- `userChrome.TabSeparators-Enabled`

### Menu Density
By default context menus follow the selected interface density, but it is possible to set a fixed size.

| Compact | Normal | Touch |
|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/152645825-7d351e3e-b938-4fa1-a460-1f699ed1c3c6.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645878-d917e841-837a-4a11-8fc1-ce0fc2262aef.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645915-833c1b22-e320-445f-817e-408ea26f7605.png) |

- `userChrome.CompactContextMenu-Enabled`
- `userChrome.NormalContextMenu-Enabled`
- `userChrome.TouchContextMenu-Enabled`

### Icons

| Regular | Filled |
|---------|--------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151192708-5ae7691c-ce07-49d8-b4fb-fc58692b63fe.png) |

- `userChrome.RegularMenuIcons-Enabled`
- `userChrome.FilledMenuIcons-Enabled`

### Drag Space
![изображение](https://user-images.githubusercontent.com/85301851/152680229-43547df0-1d2c-4384-b024-950e7aa56ca6.png)

- `userChrome.LeftSideDragSpace-Disabled`
- `userChrome.RightSideDragSpace-Disabled`
- `userChrome.DragSpaceAboveTabsWindowedMode-Disabled`
- `userChrome.DragSpaceAboveTabsMaximizedMode-Enabled`
- `userChrome.DragSpaceAboveTabsFullscreenMode-Enabled`

### Selected Tab Highlight
![изображение](https://user-images.githubusercontent.com/85301851/170877154-44db11c2-02ce-4aab-821e-c3cc68f26a2d.png)

- `userChrome.SelectedTabHighlight-Enabled`
