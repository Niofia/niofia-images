# Niofia Images

Product image CDN for Alibaba International listings.

## Folder structure

One folder per product style (kebab-case):

```
niofia-images/
├── car-seatbelt/                  # product: car safety belt
│   ├── raw/                       # original 1688 photos (unedited)
│   └── generated/                 # edited images for listing
├── lifejacket-lucky-yellow/       # product: dog life jacket - lucky yellow
│   ├── raw/
│   └── generated/
└── README.md
```

## Naming

- `01-main-white.jpg` main image 1 (white background)
- `02-scene.jpg` main image 2 (use scene)
- `03-features.jpg` main image 3 (feature callouts)
- `04-lifestyle.jpg` main image 4 (lifestyle)
- `05-details.jpg` main image 5 (detail close-ups)
- `06-size-chart.jpg` main image 6 (size chart)
- `07-how-to-use.jpg` detail image (instructions)
- `08-colors.jpg` detail image (SKU colors)
- `09-multi-angle.jpg` detail image (multi angle)
- `10-comparison.jpg` detail image (comparison)
- `11-brand.jpg` detail image (guarantee)

## Rules

- No brand logo / NIOFIA text on any image
- Same filename overwrites old version (no versioning)
- Use real product photos from 1688, do not alter product design
