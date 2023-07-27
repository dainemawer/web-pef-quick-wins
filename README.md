# ⚡️ Byte-sized Web Performance Quick Wins
Welcome to the definitive guide on web performance optimization – a high-level checklist designed to empower users, site owners, and developers of all levels with the knowledge to enhance their website's performance. In today's fast-paced digital landscape, the speed and efficiency of a website play a crucial role in attracting and retaining visitors. 

Whether you're a seasoned web developer or just starting your online journey, this informative resource will equip you with a range of practical strategies and best practices to supercharge your website's loading times, responsiveness, and overall user experience. This checklist covers everything from quick and easy wins to more advanced techniques, ensuring you can unlock your website's true potential and leave your competitors in the dust.

All the best, Daine.

## Production Checklist

### Images - (Resources)

- [ ] Add the `loading="lazy"` attribute to all images below-the-fold.
- [ ] Add the `decoding="async"` attribute to all images below-the-fold.
- [ ] Set `fetchpriority="high"` and `loading="eager"` on the largest, initially visible image above the fold.
- [ ] Serve images in the `.webp` format for better compression, quality, and delivery.
- [ ] Ensure all images have a `width` and `height` attribute.
- [ ] Ensure images are rendered in their original `aspect-ratio` and are optimized for the web.

### Infrastructure - (Resources)

- [ ] Use a CDN to deliver static assets at the edge.
- [ ] Use Cloudflare to cache, serve, and optimize complex metrics like TTFB.

### CSS - (Resources)

- [ ] Do not overly specify CSS rules.
- [ ] Do not use the `@import` statement in CSS files.
- [ ] Minify CSS in production environments.
- [ ] Embed or Inline Critical CSS styles for content above the fold.
- [ ] Ensure only the CSS required for page rendering is loaded.
- [ ] Break large CSS files into smaller, easier-to-parse files for better performance.
- [ ] Defer the loading of non-critical CSS.

### Fonts - (Resources)

- [ ] Compress fonts
- [ ] Subset fonts where only one language is needed
- [ ] Load fonts locally, if possible, or from a CDN




