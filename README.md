# Accurate Biot-Savart routines with Correct Asymptotic Behaviour
<img src="abscab_logo.png" alt="ABSCAB logo" width="200" align="right"/>

This library can be used to compute the magnetic field and the magnetic vector potential
of filamentary current carriers in the form of a circular loop and straight segments.
Arbitrary geometries of conductors can be approximated by a polygon along its contour
and the connecting segments between the polygon vertices are modeled by straight segments.
Finite-width conductors can be approximated by arranging multiple filaments
throughout the cross section of the current carrier.

Please consider leaving a GitHub star if you like this software.

If you use this software for scientific work,
we kindly ask you to cite [the corresponding article](https://doi.org/10.1016/j.cpc.2023.108692):
```bibtex
@article{abscab_2023,
  title  = {{Biot-Savart routines with minimal floating point error}},
  author = {Jonathan Schilling and Jakob Svensson and Udo Höfel and Joachim Geiger and Henning Thomsen},
  journal = {Computer Physics Communications},
  pages = {108692},
  year = {2023},
  issn = {0010-4655},
  doi = {10.1016/j.cpc.2023.108692}
}
```

This is the C implementation of [ABSCAB](https://github.com/jonathanschilling/abscab).

![Build & Test](https://github.com/jonathanschilling/abscab-c/actions/workflows/build.yml/badge.svg)

| description         | link to file |
| ------------------- | ---------------------------------------------------------------------- |
| main implementation | [`abscab.h`](abscab/abscab.h)         |
| unit tests          | [`test_abscab.c`](test/test_abscab.c) |
| demo code           | [`demo_abscab.c`](test/demo_abscab.c) |
| parallelized        | :heavy_check_mark: (OpenMP)                                           |

