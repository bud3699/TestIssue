<span style="color: red;">Warning: Your warning message here</span>
```diff
! Warning: download the correct version
```
$${\color{red}Red}$$

> [!WARNING]  
> Please make sure you download the correct one! 

> [!IMPORTANT]
> Please make sure you download the correct version!

**[zjoasan](https://github.com/zjoasan)** and **[Bud](https://github.com/bud3699)**


## Installation

1. Download the latest version from the above or the website, and extract the contents to a folder.
2. Copy the `\IddSampleDriver\` folder and its contents to `C:\IddSampleDriver\` before installing the driver **(important!)**.
3. Right click and run the *.bat file **as an Administrator** to add the driver certificate as a trusted root certificate.
4. Don't install the inf. Open device manager, click on any device, then click on the "Action" menu and click "Add Legacy Hardware".
5. Select "Add hardware from a list (Advanced)" and then select Display adapters.
6. Click "Have Disk..." and click the "Browse..." button. Navigate to the extracted files and select the inf file.
7. You are done! Go to display settings to customize the resolution of the additional displays. These displays show up in Sunshine, your Oculus or VR settings, and should be able to be streamed from.
8. You can enable/disable the display adapter to toggle the monitors.

**Ps.** Make sure that `options.txt` is accessible for the system at `C:\IddSampleDriver\options.txt` or the installation will fail.

---

### Beta Release Update Instructions

1. Download the beta version and extract the contents to a folder.
2. Copy the `\VirtualDisplayDriver\` folder and its contents to `C:\VirtualDisplayDriver\` before installing the driver **(important!)**.
3. Right click and run the *.bat file **as an Administrator** to add the driver certificate as a trusted root certificate.
4. Don't install the inf. Open device manager, click on any device, then click on the "Action" menu and click "Add Legacy Hardware".
5. Select "Add hardware from a list (Advanced)" and then select Display adapters.
6. Click "Have Disk..." and click the "Browse..." button. Navigate to the extracted files and select the inf file.
7. You are done! Go to display settings to customize the resolution of the additional displays. These displays show up in Sunshine, your Oculus or VR settings, and should be able to be streamed from.
8. You can enable/disable the display adapter to toggle the monitors.


| Project | Iddcx Ver | Signed | SDR          | HDR          | H-Cursor | Tweakable | ARM64 | Custom EDID | Float Refresh |
|---------|-----------|--------|--------------|--------------|----------|-----------|-------|-------------|---------------|
| [Virtual Display Driver](https://github.com/VirtualDisplay/Virtual-Display-Driver) | 1.10 (latest) | ✅    | ✅ (8/10bit) | ✅ (8/10/12bit) | ✅      | ✅         | ✅    | ✅           | ✅             |
| usbmmidd_v2 | -         | ✅    | ✅ (8bit)    | -            | -        | -         | -     | -           | -             |
| [virtual-display-rs](https://github.com/MolotovCherry/virtual-display-rs/issues/81) | 1.5       | -      | ✅ (8bit)    | -            | [#81](https://github.com/MolotovCherry/virtual-display-rs/issues/81) | ✅         | -     | -           | -             |
| parsec-vdd | 1.5       | ✅    | ✅ (8bit)    | -            | ✅        | 🆗         | -     | -           | -             |
| IddSampleDriver | 1.2       | -      | ✅ (8bit)    | -            | -        | -         | -     | -           | -             |
| RustDeskIddDriver | 1.2       | -      | ✅ (8bit)    | -            | -        | -         | -     | -           | -             |

