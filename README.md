# Stellaris StellarView Compatibility
Disables Stellaris custom sky and configures StellarView for the planets.

## Dependencies
[StellarView Mixin Renderer](https://github.com/lukaskabc/StellarViewMixinRenderer)  
[Stellaris](https://github.com/st0x0ef/stellaris)  
[StellarView](https://github.com/Povstalec/StellarView)

## Notes
Dev notes, problems, TODOs, etc.

### Orbits
[Earth Celestials](src/main/resources/assets/stellaris/stellarview/celestials/planet/milky_way/sol/earth_orbit.json)  
[Earth View center](src/main/resources/assets/stellaris/stellarview/view_centers/earth_orbit.json)  
[Earth mixin setting](src/main/resources/assets/stellaris/stellarview_mixin_renderer/dimension_special_effects/earth_orbit.json)

No idea if and/or how to configure orbit info and related stuff.
requirements:
1. Earth must be always at the bottom of the orbit dimension (if you jump, you land there)
2. Dont know how to do it in a way that will respect the day/night cycle with respect to Sun and Luna position in the sky

**The same applies to other orbits mars_orbit, venus_orbit and mercury_orbit**