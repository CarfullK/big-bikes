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
- **Rob** (teal #4dbbc4): MT-10 (2018), 1190 Adventure (2013)
- **Joolz** (gold #c4a34d): CBR1100XX Super Blackbird, CX 650 Eurosport, Tiger 900 (1995), CZ 175
- **Keith + Joolz shared** (salmon #d4777c): CB100N

### Usage:
Tell Claude: "Run OPT1 for Rob" or "Run OPT1 for Joolz"
