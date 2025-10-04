# Pixica Storage

Image storage repository for Pixica app.

## About

This repository stores images uploaded from the Pixica mobile application using GitHub as unlimited free cloud storage.

## Structure

```
pixica-storage/
└── images/
    └── 2024/
        ├── 01/
        ├── 02/
        ├── ...
        └── 12/
```

Images are organized by year and month for easy management.

## Features

- Unlimited storage (public repository)
- Global CDN delivery via jsDelivr
- Automatic organization by date
- Version control for all images

## CDN Access

Images are accessible via jsDelivr CDN:
```
https://cdn.jsdelivr.net/gh/saturnbrothers17/pixica-storage@main/images/YEAR/MONTH/filename.jpg
```

## API

Images are managed through the Pixica backend API deployed on Vercel.

## License

This repository is for Pixica app image storage only.
