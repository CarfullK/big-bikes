# Big Bikes App - Development Notes

## OPT1: Download and Localize Images

Process to download external images and store them locally in the repo to prevent broken links.

### Steps:
1. Find all bikes for the specified person (Keith, Rob, or Joolz) and their current image URLs
2. Download each image to the `images/` folder with a descriptive filename
3. Update the code in `big-bikes.html` to reference local paths (e.g., `images/bike-name.jpg`)
4. Update `images/index.html` gallery to include the new images
5. Commit and push to GitHub

### Bike Ownership:
- **Keith** (purple #c45baa): Z1000 J3, CX 500 Eurosport, GSX 400, VFR750, GS 550, Marauder 800, 150 Cadet, Bandit 1200, Kingswood Wagon
- **Rob** (teal #4dbbc4): MT-10 (2018), 1190 Adventure (2013), MT5, RXS100, DT125R, KR1, KH250, CB250 Superdream, CG125, RS250 Reggiani Replica
- **Joolz** (gold #c4a34d): CBR1100XX Super Blackbird, CX 650 Eurosport, Tiger 900 (1995), CZ 175, Maxi (Puch)
- **Keith + Joolz shared** (salmon #d4777c): CB100N

### Usage:
Tell Claude: "Run OPT1 for Rob" or "Run OPT1 for Joolz"

## Bike Colors (for finding correct images)

### Rob's Bikes:
- Honda MT5 - black and yellow
- Yamaha RXS100 - maroon
- Kawasaki KR1 - red and white
- Kawasaki KH250 - green and blue
- Honda CB250 Superdream - blue
- Honda CG125 - early version
- Suzuki TL1000S - silver
- Honda CB1000F - Benetton colours
- Kawasaki KLX650 - green
- Ducati 1098S - red
- BMW S1000RR (2011) - silver
- BMW S1000XR - grey with graphics
- BMW F800S - red
- KTM 350 EXC-F (2014) - orange
- Honda CB900F Hornet - blue
- Cagiva River 600 - blue
- Suzuki DR350S - (no color specified)

### Joolz's Bikes:
- Puch Maxi - (no color specified)
- Honda CX 650 Eurosport - (no color specified)
