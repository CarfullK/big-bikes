# Big Bikes App

A single-file mobile-friendly web app for browsing legendary motorcycles.

## Features

- Manufacturer and model dropdown selection
- Random Ride button for discovery
- **Image gallery with multiple photos per bike**
  - Wikimedia Commons images (freely licensed)
  - Manufacturer website images (where available)
  - Swipeable on mobile, clickable navigation on desktop
  - Source labels showing image origin
- Bike specs display (engine, power, torque, weight)
- Fun facts for each motorcycle
- Dark theme with motorcycle-inspired styling
- Responsive design (mobile-first, works on laptops too)

## File Structure

```
big-bikes.html    - The entire app (single file, no dependencies)
README.md         - This file
```

## How to Use

1. Open `big-bikes.html` in any web browser
2. Select a manufacturer from the first dropdown
3. Select a model from the second dropdown
4. View the bike's photo, specs, and fun fact

Or just hit **Random Ride** to discover a bike.

## Included Manufacturers

- BMW
- Ducati
- Harley-Davidson
- Honda
- Indian
- Kawasaki
- Suzuki
- Triumph

## Future Development Ideas

- [ ] Add more manufacturers (Yamaha, KTM, Aprilia, Moto Guzzi)
- [ ] Add more models per manufacturer
- [x] ~~Replace placeholder images with actual bike photos~~ (Done - using Wikimedia + manufacturer images)
- [ ] Add bike comparison feature (side-by-side specs)
- [ ] Add favorites system (localStorage)
- [ ] Add sound effects (engine start, rev)
- [ ] Add quiz mode (guess the bike from specs)
- [ ] Add filtering by category (Cruiser, Sport, Adventure, etc.)
- [ ] Add year/generation information
- [ ] Add price estimates
- [ ] Add "bikes I've ridden" tracker

## Technical Notes

- Pure HTML/CSS/JavaScript - no frameworks or build tools
- All data embedded in the file (no API calls)
- Images loaded from two sources (requires internet):
  - **Wikimedia Commons** - freely licensed motorcycle photos
  - **Manufacturer websites** - official product images
- Uses CSS Grid and Flexbox for layout
- CSS animations for transitions
- Touch swipe support for mobile gallery navigation
- Mobile viewport meta tag for proper scaling

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge) on:
- iOS / Android phones
- Tablets
- Laptops / Desktops
