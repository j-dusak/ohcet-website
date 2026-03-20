# Images Directory

This directory contains placeholder image files for the wedding photography website template.

## Required Images

Replace the following placeholder images with your own photos:

### Hero Image
- **hero.jpg** - Main hero image for the homepage (index.html)
  - Recommended size: 1920x1080px or larger
  - Format: JPG, optimized for web
  - This image will be displayed fullscreen on the homepage

### Team Photos
- **team-1.jpg** - Portrait photo of team member 1 (Photographer)
  - Recommended size: 800x800px (square)
  - Format: JPG, optimized for web
  
- **team-2.jpg** - Portrait photo of team member 2 (Videographer)
  - Recommended size: 800x800px (square)
  - Format: JPG, optimized for web

### Gallery Photos
- **photo-01.jpg** through **photo-08.jpg** - Gallery images
  - Recommended size: Minimum 800px width
  - Format: JPG, optimized for web
  - Aspect ratio: Square (1:1) or 4:3 works best for the grid layout
  - You can add more photos by following the pattern (photo-09.jpg, photo-10.jpg, etc.)

## Image Optimization Tips

1. **Compress images** before uploading to reduce file size and improve page load speed
   - Use tools like TinyPNG, ImageOptim, or Squoosh
   - Aim for file sizes under 500KB per image when possible

2. **Use appropriate formats**
   - JPG for photos
   - PNG only if transparency is needed
   - Consider WebP format for modern browsers (requires HTML updates)

3. **Responsive images** (optional enhancement)
   - For better performance, you can create multiple sizes of each image
   - Use the `srcset` attribute in HTML for responsive images
   - Example: `<img srcset="photo-01-small.jpg 400w, photo-01-medium.jpg 800w, photo-01-large.jpg 1200w" ...>`

## Adding More Gallery Images

To add more images to the gallery:

1. Add your image files to this directory (e.g., `photo-09.jpg`)
2. Open `gallery.html`
3. Copy one of the existing `<figure class="gallery-item">` blocks
4. Update the `src` path and `alt` text
5. Paste it into the `.gallery-grid` container

Example:
```html
<figure class="gallery-item">
    <img src="assets/images/photo-09.jpg" alt="Description of your photo" loading="lazy">
</figure>
```

## Placeholder Images

For testing purposes, you can use placeholder services like:
- https://placeholder.com
- https://via.placeholder.com/800x800
- https://picsum.photos/800/800

Or create simple colored placeholder images using image editing software.

