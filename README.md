# DKOPA

**Engineering studio. We build the systems that run underneath the surface.**

GPU-bound applications, CAD tooling, and clean infrastructure — with interfaces that get out of the way.

[dkopa.com](https://dkopa.com) · [devlog](https://dkopa.com/log) · [contact@dkopa.com](mailto:contact@dkopa.com)

## Products

- **[DKOPA Viewer](https://dkopa.com/viewer)** — browser-native CAD viewer for STEP, IGES, BREP, STL, and OBJ. OpenCascade compiled to WebAssembly, WebGPU rendering, section planes with caps, B-rep face picking, and measurement. Files are parsed locally in a Web Worker — nothing is uploaded.

## Open source

- **[mesh-section-caps](./mesh-section-caps)** — closed section-contour extraction and cap triangulation for arbitrary triangle meshes. The same code that fills the cross-section view in the viewer, published as a standalone module.
