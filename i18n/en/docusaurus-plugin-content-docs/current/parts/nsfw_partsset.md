# Lugharian-exclusive NSFW Parts Set Guide

This document is for purchasers of the [Lugharian-exclusive NSFW Parts Set](https://kurotori.booth.pm/items/6448425).

## How to use

Import the following required packages:

- [Modular Avatar](https://modular-avatar.nadena.dev/)
- [VRCFury](https://vrcfury.com/)

Then import this Unity package into a project where Lugharian is already installed.

Open the `NSFW_○○Base_Setup` scene under `Assets/Lugharian/Parts_R18`, and start the avatar creation system in Play Mode.

R18-related parameters are added at the end of the adjustment parameters.

After that, you can set it up in the same way as a regular Lugharian avatar.

## MA_Prefabs reference

You can add the following prefabs to the base body or the root of a created avatar via drag and drop to enable additional functionality.

### MA_AnalWiding

Adds a radial menu control for opening and closing the anus.

### MA_PenisControl

Adds controls and adjustments for the penis.

### SPS/SPS AnalHole

Adds an SPS-compatible anal gimmick. It conflicts with `MA_AnalWiding`, so they cannot be used together.

### SPS/Penis Plug

Adds an SPS-compatible penis gimmick. It conflicts with `MA_PenisControl`, so they cannot be used together.

### SPS/SPS Socket Mouth

Adds an SPS-compatible hole socket to the mouth.

## Notes when creating an MA-compatible base (v1.7 and later)

In general, follow [Advanced Outfit and Accessory Setup with Modular Avatar](../ma_presets.md#create-a-modular-avatar-compatible-base), but export with only the following option turned **on**:

- Active Alpha Mask

If you leave it **off**, the original model will appear at the anus and it will look closed.