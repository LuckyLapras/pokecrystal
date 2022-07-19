it's currently 34 degrees celsius outside (and probably higher inside) at the time of writing which for some reason spurred me to start making a crystal rom hack. for now i'll probably just implement a bunch of the tutorials and bugfixes that the good people who originally worked on this disassembly put together

things for future me to consider:
- replacing psychic tm in celadon game corner with some tm u find on the floor (move names are in constants/item\_constants.asm)
- evolution moves
- weather shenanigans
  - automatic weather in more places (i've only got the ones included in the tutorial for now)
  - weather icons
  - hail in movesets and also as a tm. in fact all of the movesets and tms need to be reworked.
- fossils in rocks
- change pocket pc name i cannot trust ~~me~~ ~~daz~~ emile with it
- other miscellaneous graphical edits

original readme:

This is a disassembly of Pokémon Crystal.

It builds the following ROMs:

- Pokemon - Crystal Version (UE) (V1.0) [C][!].gbc `sha1: f4cd194bdee0d04ca4eac29e09b8e4e9d818c133`
- Pokemon - Crystal Version (UE) (V1.1) [C][!].gbc `sha1: f2f52230b536214ef7c9924f483392993e226cfb`
- Pokemon - Crystal Version (A) [C][!].gbc `sha1: a0fc810f1d4e124434f7be2c989ab5b5892ddf36`
- CRYSTAL_ps3_010328d.bin `sha1: c60d57a24bbe8ecf7cba54ab3f90669f97bd330d`
- CRYSTAL_ps3_us_revise_010710d.bin `sha1: 391ae86b1d5a26db712ffe6c28bbf2a1f804c3c4`
- CGBBYTE1.784.patch `sha1: a25517f60ca0e887d39ec698aa56a0040532a4b3`

To set up the repository, see [INSTALL.md](INSTALL.md).


(i've removed all of the original repo's links bc they won't really matter for this project but i will [drop a link to the original repo here](https://github.com/pret/pokecrystal). my apologies if i've fucked this up again. i don't think i have.)
