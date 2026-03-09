# Stellaris StellarView Compatibility
[![Modrinth](https://img.shields.io/modrinth/dt/stellaris-stellarview-compatibility?style=for-the-badge&logo=modrinth&color=626e7b&label=Modrinth)](https://modrinth.com/mod/stellaris-stellarview-compatibility)
<a href="https://curseforge.com/minecraft/mc-mods/stellaris-stellarview-compatibility" target="_blank"><img src="https://img.shields.io/curseforge/dt/1482048?style=for-the-badge&logo=curseforge&color=626e7b&label=CurseForge" alt="Curseforge"></a>
<a href="https://curseforge.com/minecraft/texture-packs/stellaris-stellarview-compatibility-resourcepack" target="_blank"><img src="https://img.shields.io/curseforge/dt/1482062?style=for-the-badge&logo=curseforge&color=626e7b&label=Curseforge%20Resourcepack%20version" alt="Curseforge"></a>

Disables Stellaris custom sky and configures StellarView sky for every planet.

## Dependencies

<table>
  <tbody>
    <tr>
      <td>StellarView Mixin Renderer</td>
      <td>&nbsp;&nbsp;&nbsp;&nbsp;</td>
      <td>
        <a href="https://github.com/lukaskabc/StellarViewMixinRenderer/">
          <img src="https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="https://modrinth.com/mod/stellar-view-mixin-renderer">
          <img src="https://img.shields.io/badge/Modrinth-grey?style=for-the-badge&logo=modrinth" alt="Modrinth">
        </a>
      </td>
      <td>
        <a href="https://curseforge.com/minecraft/mc-mods/stellar-view-mixin-renderer">
          <img src="https://img.shields.io/badge/CurseForge-grey?style=for-the-badge&logo=curseforge" alt="CurseForge">
        </a>
      </td>
    </tr>
    <tr>
      <td>Stellaris</td>
      <td></td>
      <td>
        <a href="https://github.com/st0x0ef/stellaris/">
          <img src="https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="https://modrinth.com/mod/stellaris">
          <img src="https://img.shields.io/badge/Modrinth-grey?style=for-the-badge&logo=modrinth" alt="Modrinth">
        </a>
      </td>
      <td>
        <a href="https://curseforge.com/minecraft/mc-mods/stellaris">
          <img src="https://img.shields.io/badge/CurseForge-grey?style=for-the-badge&logo=curseforge" alt="CurseForge">
        </a>
      </td>
    </tr>
    <tr>
      <td>StellarView</td>
      <td></td>
      <td>
        <a href="https://github.com/Povstalec/stellarview/">
          <img src="https://img.shields.io/badge/GitHub-grey?style=for-the-badge&logo=GitHub" alt="GitHub">
        </a>
      </td>
      <td>
        <a href="https://modrinth.com/mod/stellarview">
          <img src="https://img.shields.io/badge/Modrinth-grey?style=for-the-badge&logo=modrinth" alt="Modrinth">
        </a>
      </td>
      <td>
        <a href="https://curseforge.com/minecraft/mc-mods/stellarview">
          <img src="https://img.shields.io/badge/CurseForge-grey?style=for-the-badge&logo=curseforge" alt="CurseForge">
        </a>
      </td>
    </tr>
  </tbody>
</table>

## Implemented planets/dimensions

- Earth (overworld)
- Earth Orbit
- Jupiter
- Mars
- Mars Orbit
- Mercury
- Mercury Orbit
- Moon
- Venus
- Venus Orbit

## Notes

Dev notes, problems, TODOs, etc.

- Some celestials/star fields are visible through planets

### Orbits
[Earth Celestials](src/main/resources/assets/stellaris/stellarview/celestials/planet/milky_way/sol/earth_orbit.json)  
[Earth View center](src/main/resources/assets/stellaris/stellarview/view_centers/earth_orbit.json)  
[Earth mixin setting](src/main/resources/assets/stellaris/stellarview_mixin_renderer/dimension_special_effects/earth_orbit.json)

No idea if and/or how to configure orbit info and related stuff.
requirements:
1. Earth must be always at the bottom of the orbit dimension (if you jump, you land there)
2. Dont know how to do it in a way that will respect the day/night cycle with respect to Sun and Luna position in the sky

**The same applies to other orbits mars_orbit, venus_orbit and mercury_orbit**

### Planets
Daylight cycle on planets does not reflect the sun position

