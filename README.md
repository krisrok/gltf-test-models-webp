# Test files for EXT_texture_webp

1. CesiumBoxWebp-WithFallbackPNG.gltf
    - Does not require the extension, has a PNG texture as fallback
    - Renamed copy of https://github.com/CesiumGS/cesium/blob/bd8be76b7707ddb9c858ae39538c18064c218f98/Specs/Data/Models/Box-Textured-Webp/CesiumBoxWebp.gltf, found via https://github.com/Zek-enterprises/glTF/blob/master/extensions/2.0/Vendor/EXT_texture_webp/README.md#known-implementations
1. CesiumBoxWebp-Required.gltf
    - Modified to require support for the extension, no fallback.
