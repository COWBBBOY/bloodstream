<p align="center">
<img width="75%" src="https://i.imgur.com/INSERT URL.png" alt="Banner">
</p>

<p align="center">
<b>Image laser speckle fluctuation to measure blood velocity</b>
</p>

<p align="center">
<a href="https://github.com/mattrohr/INSERT PROJECT URL/actions?query=workflow%3Abuild">
<img src="https://github.com/mattrohr/INSERT PROJECT URL/workflows/build/badge.svg?branch=main" alt="Build Status Badge">
</a>
</p>

## About
<img align="right" width="40%" src="https://i.imgur.com/KBu69Ng.png" alt="Animation">

Lasers emit light. This light is released at the same time, and is typically one color. After it hits a surface, it reflects. If it's a perfect mirror, it will fully reflect. But if it hits a rough surface, waves will travel in random directions. The rougher the surface, the more this "scattering". When two lightwaves cross paths, they interfere. This causes a speckle pattern. If the light hits a surface that's changing, like a drying wall of paint, the speckle pattern will change over time. The faster the evaporation, the faster the speckle change.

When we now shine laser light on a brain, we can measure blood flow. If we also stimulate the brain, we can determine how blood flow responds to neural activity. Therefore if we measure blood flow, we can estimate neurological state. This may result in a non-invasive test for neurodegeneration, like Alzheimers.

If this is helpful in your, please cite:

## Installation
Developed with Python 3.9.5

1. (recommended) python3 -m venv venv && source venv/bin/activate

2. pip install -r requirements.txt

3.

## Demo
1.

2.

3.

## Notes
wouldn't speckle change as a result of water evaporation on surface of brain

- Design decisions
    - Why Python? No license, unlike MATLAB
    - Why TIFF / TIF images?
- Why expensive laser?
    - if produced light is not consistently coherent, the interference pattern will change in time even if the surface and observer are not moving (image of hand-held laser). Thermal stability. good optics so uninform spread. Power regulation.
- Why expensive camera?
    - quantum efficiency.
- Tips
    - laser light -> heats surface = don't shine directly onto camera sensor

## Acknowledgements
- xxx for data collection
- xxx for LSCI algorithm.