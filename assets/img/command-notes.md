gm convert -background white -gravity center -extent 1500x1500+0+0 r3.png r3b.png


inkscape --export-type png tgcc4.svg -o tgcc4.png

# convert svg to png and make it a square
inkscape --export-type png microtrials.svg -o microtrials.png
gm identify microtrials.png
gm convert -background white -gravity center -extent 636x636+0+0 microtrials.png microtrials.png

inkscape --export-type png odap.svg -o odap.png
gm identify odap.png
gm convert -background white -gravity center -extent 249x249+0+0 odap.png odap.png

inkscape --export-type png roboscope.svg -o roboscope.png
gm identify roboscope.png
gm convert -background white -gravity center -extent 900x900+0+0 roboscope.png roboscope.png

