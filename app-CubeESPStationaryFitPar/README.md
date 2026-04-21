Purpose:
  Find stationary points of ESP in a radial shell around a selected atom.
  Seed points are taken from sorted ESP values, then a local 3D quadratic fit
  is applied and grad(V)=0 is solved.

Usage:
  java CubeESPStationaryFit esp.cube [key=value ...] [-N=1] [verbose]
