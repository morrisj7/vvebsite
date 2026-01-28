# Website Assets Repository

This repository serves as a centralized storage location for all website assets used with Squarespace. It provides an organized structure for managing images, 3D models, videos, fonts, and other digital content.

## Repository Structure

```
vvebsite/
├── images/          # Image files (PNG, JPG, SVG, GIF, etc.)
├── 3d-models/       # 3D model files (GLB, GLTF, OBJ, FBX, etc.)
├── videos/          # Video files (MP4, MOV, WEBM, etc.)
├── fonts/           # Custom font files (TTF, OTF, WOFF, etc.)
└── documents/       # PDF and other document files
```

## Directory Descriptions

### `/images`
Store all image assets including:
- Logos and branding
- Photography and graphics
- Icons and illustrations
- Background images
- Product photos

### `/3d-models`
Store 3D model files including:
- Interactive 3D content
- Model textures and materials
- Animation files

### `/videos`
Store video content including:
- Background videos
- Product demonstrations
- Promotional content

### `/fonts`
Store custom web fonts:
- Brand-specific typography
- Custom font families

### `/documents`
Store downloadable documents:
- PDFs
- Whitepapers
- Brochures

## Using Assets with Squarespace

### Accessing Files
Once files are uploaded to this repository, they can be accessed via GitHub's raw content URL:

```
https://raw.githubusercontent.com/morrisj7/vvebsite/main/<directory>/<filename>
```

**Example:**
```
https://raw.githubusercontent.com/morrisj7/vvebsite/main/images/logo.png
```

### Integration Methods

1. **Code Blocks**: Use Custom CSS or Code Injection in Squarespace to reference asset URLs
2. **Image Blocks**: Link directly to raw GitHub URLs in image blocks
3. **Custom Code**: Embed assets in custom HTML/CSS/JavaScript sections

### Best Practices

1. **File Naming**: Use lowercase, hyphenated names (e.g., `my-image.jpg`)
2. **Organization**: Keep related assets in subdirectories within each main folder
3. **Optimization**: Compress images and videos before uploading to reduce load times
4. **Version Control**: Commit meaningful changes with descriptive messages
5. **File Size**: Keep individual files under 100MB (GitHub limit)

## Adding New Assets

1. Clone this repository
2. Add your files to the appropriate directory
3. Commit and push changes:
```bash
git add .
git commit -m "Add [description of assets]"
git push
```

## Getting Asset URLs

To get the direct URL for any asset in this repository:
1. Navigate to the file on GitHub
2. Click the "Raw" button
3. Copy the URL from your browser's address bar

Or construct the URL manually:
```
https://raw.githubusercontent.com/morrisj7/vvebsite/main/[directory]/[filename]
```

## Notes

- All assets in this repository are served over HTTPS
- GitHub provides unlimited bandwidth for public repositories
- Assets are cached by GitHub's CDN for fast delivery
- Consider using a branch strategy (e.g., `main` for production, `dev` for testing)
