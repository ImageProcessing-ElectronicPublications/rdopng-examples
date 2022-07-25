`ORG.IPEP:`
![GitHub repo size](https://img.shields.io/github/repo-size/ImageProcessing-ElectronicPublications/rdopng-examples)
![GitHub](https://img.shields.io/github/license/ImageProcessing-ElectronicPublications/rdopng-examples)  

# rdopng-examples

Rate-Distortion Optimized Lossy PNG and QOI Encoding Tool ([rdopng](https://github.com/ImageProcessing-ElectronicPublications/rdopng))

[rdopng](https://github.com/ImageProcessing-ElectronicPublications/rdopng) is a command line tool which uses LZ match optimization, Lagrangian multiplier [rate distortion optimization (RDO)](https://en.wikipedia.org/wiki/Rate%E2%80%93distortion_optimization), a simple perceptual error tolerance model, and [Oklab](https://bottosson.github.io/posts/oklab/)-based colorspace error metrics to encode 24/32bpp PNG files which are 30-80% smaller relative to lodepng/libpng. The tool defaults to reasonably fast near-lossless settings which writes PNG's around 30-40% smaller than lossless PNG encoders.

Unlike [pngquant](https://pngquant.org/), rdopng does not use 256-color palettes or dithering. PNG files encoded by rdopng typically range between roughly 2.5-7bpp, depending on the options used (and how much time and patience you have).

Some example encodes and command lines are [here](https://github.com/richgel999/rdopng/wiki/Examples).

You can download a pre-built Windows binary [here](https://github.com/richgel999/rdopng/releases). You may need to install the [VS 2022 runtime redistributable from Microsoft](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).

### Examples


| aliens.png [499788] |
| --- |
| ![](images/aliens.png) |
| aliens_rdo.png [261332] |
| ![](images/aliens_rdo.png) |
| aliens_2_rdo.png [206448] |
| ![](images/aliens_2_rdo.png) |

| crossyf.png [897010] |
| --- |
| ![](images/crossyf.png) |
| crossyf_rdo.png [323624] |
| ![](images/crossyf_rdo.png) |
| crossyf_2_rdo.png [265207] |
|![](images/crossyf_2_rdo.png) |

| doom.png [464665] |
| --- |
| ![](images/doom.png) |
| doom_rdo.png [279841] |
| ![](images/doom_rdo.png) |
| doom_delta.png [320663] |
| ![](images/doom_delta.png) |

| gotham.png [591247] |
| --- |
| ![](images/gotham.png) |
| gotham_rdo.png [192478] |
| ![](images/gotham_rdo.png) |
| gotham_delta.png [554380] |
| ![](images/gotham_delta.png) |
| gotham_2_rdo.png [171885] |
| ![](images/gotham_2_rdo.png) |
| gotham_2_delta.png [595632] |
| ![](images/gotham_2_delta.png) |

| high_fidelity.png [514995] |
| --- |
| ![](images/high_fidelity.png) |
| high_fidelity_1.png [363467] |
| ![](images/high_fidelity_1.png) |
| high_fidelity_2.png [188568] |
| ![](images/high_fidelity_2.png) |

| joker_768.png [339338] |
| --- |
| ![](images/joker_768.png) |
| joker_768_rdo.png [137253] |
| ![](images/joker_768_rdo.png) |
| joker_768_delta.png [362749] |
| ![](images/joker_768_delta.png) |
| joker_768_2_rdo.png [165524] |
| ![](images/joker_768_2_rdo.png) |
| joker_768_2_delta.png [339650] |
| ![](images/joker_768_2_delta.png) |
| joker_768_3_rdo.png [225803] |
| ![](images/joker_768_3_rdo.png) |
| joker_768_3_delta.png [280948] |
| ![](images/joker_768_3_delta.png) |
| joker_768_4_rdo.png [99386] |
| ![](images/joker_768_4_rdo.png) |
| joker_768_4_delta.png [374280] |
| ![](images/joker_768_4_delta.png) |

| kodim18.png [777096] |
| --- |
| ![](images/kodim18.png) |
| kodim18_rdo.png [235597] |
| ![](images/kodim18_rdo.png) |
| kodim18_delta.png [624582] |
| ![](images/kodim18_delta.png) |

| lara_1024.png [1500821] |
| --- |
| ![](images/lara_1024.png) |
| lara_1024_rdo.png [1201499] |
| ![](images/lara_1024_rdo.png) |
| lara_1024_delta.png [666483] |
| ![](images/lara_1024_delta.png) |

| magneto.png [153318] |
| --- |
| ![](images/magneto.png) |
| magneto_rdo.png [84790] |
| ![](images/magneto_rdo.png) |
| magneto_delta.png [117630] |
| ![](images/magneto_delta.png) |
| magneto_2_rdo.png [72941] |
| ![](images/magneto_2_rdo.png) |
| magneto_2_delta.png [105569] |
| ![](images/magneto_2_delta.png) |
| magneto_2_alpha_delta.png [4000] |
| ![](images/magneto_2_alpha_delta.png) |

| masterchief.png [448582] |
| --- |
| ![](images/masterchief.png) |
| masterchief_rdo.png [214551] |
| ![](images/masterchief_rdo.png) |
| masterchief_2_rdo.png [172080] |
| ![](images/masterchief_2_rdo.png) |

| minerology.png [888458] |
| --- |
| ![](images/minerology.png) |
| minerology_rdo.png [622869] |
| ![](images/minerology_rdo.png) |
| minerology_delta.png [487981] |
| ![](images/minerology_delta.png) |

| puppy.png [1567850] |
| --- |
| ![](images/puppy.png) |
| puppy_rdo.png [593962] |
| ![](images/puppy_rdo.png) |
| puppy_delta.png [1278004] |
| ![](images/puppy_delta.png) |

| stp.png [785006] |
| --- |
| ![](images/stp.png) |
| stp_rdo.png [412128] |
| ![](images/stp_rdo.png) |
| stp_delta.png [709160] |
| ![](images/stp_delta.png) |
| stp_2_rdo.png [321873] |
| ![](images/stp_2_rdo.png) |
| stp_2_delta.png [778349] |
| ![](images/stp_2_delta.png) |
| stp_3_rdo.png [289303] |
| ![](images/stp_3_rdo.png) |
| stp_3_delta.png [788024] |
| ![](images/stp_3_delta.png) |

| waterfall.png [2074607] |
| --- |
| ![](images/waterfall.png) |
| waterfall_rdo.png [1202930] |
| ![](images/waterfall_rdo.png) |
| waterfall_delta.png [1430319] |
| ![](images/waterfall_delta.png) |

| xfiles_768.png [500148] |
| --- |
| ![](images/xfiles_768.png) |
| xfiles_768_rdo.png [301910] |
| ![](images/xfiles_768_rdo.png) |
| xfiles_768_delta.png [355589] |
| ![](images/xfiles_768_delta.png) |
| xfiles_768_2_rdo.png [169558] |
| ![](images/xfiles_768_2_rdo.png) |
| xfiles_768_2_delta.png [458052] |
| ![](images/xfiles_768_2_delta.png) |
