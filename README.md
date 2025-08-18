# NekoSune's Modules 🦦

A growing collection of handy and fun
[VRCOSC](https://github.com/VolcanicArts/VRCOSC) modules!

-   [🛠 Installation](#-installation)\
-   [📦 Modules](#-modules)
    -   [🔊 Nekos Audiolink](#-nekos-audiolink)

------------------------------------------------------------------------

## 🛠 Installation

These modules are designed for the
[VolcanicArts/VRCOSC](https://github.com/VolcanicArts/VRCOSC)
application.

1.  Install and launch **VRCOSC**.\
2.  Go to the **Package Download** tab.\
3.  Find **"NekoSune's Modules"** in the list.\
4.  Download the latest version, enable the modules you want, and you're
    ready to go! 🎉

> 💡 Have an idea for a feature or module? Open an issue or suggestion!\
> 🐞 Found a bug? Please report it so I can fix it quickly.

![VRCOSC package
installation](https://github.com/user-attachments/assets/fd67f861-84ff-4727-b3fb-94a4b5942cd8)

------------------------------------------------------------------------

## 📦 Modules

### 🔊 Nekos Audiolink

**Nekos Audiolink** listens to your chosen audio output device and
analyzes the signal in real time.\
It provides OSC parameters for **volume**, **stereo direction**, and
**frequency bands (Low, Bass, Mid, Treble)** that you can use inside
VRChat or other OSC-compatible apps.

#### ✨ Features

-   🎧 **Real-time audio analysis** directly from your selected output
    device\
-   ⚡ **Low-latency FFT frequency breakdown**\
-   📊 **Configurable sliders** for:
    -   **Gain** -- Adjust overall signal strength\
    -   **Smoothing** -- Control how responsive vs. stable the values
        are\
    -   **Low Boost** -- Emphasize `20–120 Hz` (sub-bass)\
    -   **Bass Boost** -- Emphasize `120–250 Hz`\
    -   **Mid Boost** -- Emphasize `250–4000 Hz`\
    -   **Treble Boost** -- Emphasize `4000–20000 Hz`\
-   📡 **OSC Parameters provided**:
    -   `Volume` -- Overall loudness (`0.0 – 1.0`)\
    -   `Direction` -- Stereo balance (`0.0 = left`, `0.5 = center`,
        `1.0 = right`)\
    -   `Low` -- Sub-bass amplitude (`20–120 Hz`)\
    -   `Bass` -- Bass amplitude (`120–250 Hz`)\
    -   `Mid` -- Midrange amplitude (`250–4000 Hz`)\
    -   `Treble` -- Treble amplitude (`4000–20000 Hz`)

#### ❓ How to Use

1.  Open the **Run** tab in VRCOSC.\
2.  In the **Runtime view**, select your preferred **audio device**
    under **Nekos Audiolink**.
    -   Devices that cannot be captured will be grayed out and added to
        the **Disabled Device List** (you can remove them if needed).\
3.  (Optional) Adjust the **sliders** to customize analysis to your
    taste.

![Module settings and
parameters](https://github.com/user-attachments/assets/43d919ba-de6f-4aa5-a3c0-5a3d09e92561)\
![Run tab with device
selection](https://github.com/user-attachments/assets/0f749660-2c17-4639-a49f-ac987283750c)
