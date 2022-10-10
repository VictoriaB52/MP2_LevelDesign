Models here are parts of Riki's armour bits and weapons, for pons who want mix-match themselfs.

Specific notings:
* Riki cheek fur make shading errors at place where clip with Riki cheek. No know how fix, sorry. (Tell Riki if know how fix!)
* Riki parts called "head, body, wings, holster" instead of Hom Hom "head, torso, arms, legs" (in same order). Also Riki no use Hom Hom "feet" part at all.
* Some of Riki's textures of different outfits are same name and same texture, but different quality resolution, like some of Riki's hair being sized half in some outfits but not others. For most cases, used higher-quality version. For some cases, other colours no have higher-quality, so must keep small version.

Model notings:
* Only put one model for all colours. Easy peasy swap out.
* Parts left unglued at same place where game glue them later after mix-matched. Riki pretty easy for this, only seam around neck and maybe holster. No think there any parts that get deleted for some combos, but could be.
* Blender anti-alias make artifacts at opaque-transparent material seams. Do Render > Anti-Aliasing > Full Sample for fix.
* Not-same alpha texture sizings and pixel interpolation can make blending artifacts. Poke settings around and maybe get okay.
* Hard stuff like weapons and armour could need textures to be mirrored outside edge instead of straight repeat. (Setting not appear to export/import.) Riki tried to say "all UVs inside bounds mean no mirror, UVs outside bounds mean yes mirror", but not be perfect and might sometimes not be true.

Armature notings:
* All bones are include, even if not really apply, or are actually points for special effects or weapon attachings.
* Much work had be done for Blender understand armatures (example: fingers not face right way on import). Ripped animations no work at all.

[EOF]