FOOTPRINTS = mini-din-3.kicad_mod mini-din-4.kicad_mod input_label.kicad_mod output_label.kicad_mod unbal2bal.kicad_mod

all: $(FOOTPRINTS)

%.kicad_mod: %.svg
	svg2mod -i $< -o $@ -p 0.1 --center

clean:
	rm $(FOOTPRINTS)

.PHONY: clean
