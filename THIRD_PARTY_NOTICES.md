# Third-party acknowledgements

GOOD CLEAN STEMS releases include or work with third-party software, model configurations, model weights, and fonts. The licenses and terms described here apply only to those third-party components; they do not license the GOOD CLEAN STEMS source code.

## MLX Audio Separator

[MLX Audio Separator](https://github.com/ssmall256/mlx-audio-separator) provides MLX-native audio separation on Apple silicon. It is distributed under the MIT License and is derived from Audio Separator.

Copyright (c) 2024-2026 ssmall256.

## Audio Separator

[Audio Separator](https://github.com/nomadkaraoke/python-audio-separator) provides the upstream separation architecture and model support used by MLX Audio Separator. It is distributed under the MIT License and credits Ultimate Vocal Remover and its contributors.

## Ultimate Vocal Remover

[Ultimate Vocal Remover](https://github.com/Anjok07/ultimatevocalremovergui) is the source of model discovery, model metadata, and substantial community work behind modern music source separation. Credit belongs to Anjok07, Aufr33, KimberleyJSN, Unwa, Viperx, and the wider UVR community.

## Models

The public model pack includes work by the following authors and communities:

- Kimberley Jensen for Kim Vocal 2.
- Unwa (pcunwa) for Kim FT2, Kim FT3, Kim Inst V1E, Leap, and Leap XE. The Leap models are available from [pcunwa/BS-Roformer-Leap](https://huggingface.co/pcunwa/BS-Roformer-Leap/tree/main/Xe).
- ZFTurbo for BS PolarFormer 62 and its official [v1.0.20 release](https://github.com/ZFTurbo/Music-Source-Separation-Training/releases/tag/v1.0.20). PolarFormer uses the MIT-licensed [PoPE implementation](https://github.com/lucidrains/PoPE-pytorch) by Phil Wang.
- The BS-RoFormer-SW contributors.

Model weights are not covered by a GOOD CLEAN STEMS license. Each model remains under the terms provided by its author or distribution source.

The MIT-licensed MLX conversion of Kim Vocal 2 credits Kimberley Jensen for the original weights and Xocialize for conversion and packaging: [mlx-community/mel-roformer-kim-vocal-2-mlx](https://huggingface.co/mlx-community/mel-roformer-kim-vocal-2-mlx).

## MLX

[MLX](https://github.com/ml-explore/mlx) is Apple's array framework for machine learning on Apple silicon. It is distributed under the MIT License.

## FFmpeg

[FFmpeg](https://ffmpeg.org/) handles audio decoding and encoding. The FFmpeg binary included in tester builds was compiled with GPL components and is distributed under GNU GPL version 3 or later. The complete license text is included in the packaged app. FFmpeg source is available from [ffmpeg.org](https://ffmpeg.org/download.html).

GOOD CLEAN STEMS communicates with FFmpeg as a separate command-line process.

## Fonts

BBH Hegarty and IBM Plex Mono are distributed under the SIL Open Font License 1.1. Their license texts are included with the corresponding font files in packaged builds.

## Serato

Serato is a trademark of Serato Limited. GOOD CLEAN STEMS is an independent project and is not endorsed by Serato Limited.
