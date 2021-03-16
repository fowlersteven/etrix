# etrix

This python script is a helper for bending concentric offsets of electrical conduit, and normalizing their spacing width. This app guarantees the spacing width of the conduits at the first bend, not just at the final bend. etrix is run entirely from the command line using arguments. This currently only supports the usecase where the largest offset is known. I call this the "converge" usecase. 

### Usage:

run `./etrix --help` for help

eg: `./etrix -d 0 2 5.5 7 9 -o 22 -a 30 --first_mark 12.0`

### Installation:

from a terminal run `git clone https://github.com/fowlersteven/etrix/` 

`cd etrix`

`chmod +x etrix`

### TODO: 

- [x] Add flag for quiet output (ie. less descriptive text, condense the numeric values).
- [x] Add a diverge option for offsets where the smallest offset is the only known value. 
- [ ] write a more thorough readme. 
- [ ] Concentric rolled offsets
- [ ] Concentric 90s generator
- [ ] Concentric kick 90s
- [ ] change plane of offsets (rack to wall)
- [ ] change plane with kick 90s (rack to wall)
- [ ] concentric segmented 90s generator
