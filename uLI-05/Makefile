all: fab

clean:
	rm -r fab

fab: uLI-05.kicad_pcb uLI-05.kicad_sch
	kikit fab jlcpcb --no-drc --assembly --schematic uLI-05.kicad_sch uLI-05.kicad_pcb fab

.PHONY: all clean
