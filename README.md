# MapLibre Android builds for Mapzi

A Maven repository, served from this branch through
`https://raw.githubusercontent.com/umitmutluu/maplibre-native/mapzi-maven/`.

`org.maplibre.gl:android-sdk-opengl:13.5.2-mapzi.1` is MapLibre Android 13.5.2
with one change, built from branch `mapzi/android-13.5.2`: with
`symbol-sort-key`, overlapping symbols in different tiles keep the key order
after a pan or a zoom.
