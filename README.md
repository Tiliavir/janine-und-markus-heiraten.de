# Wedding Website

This is the website for our wedding in 2025.
It is built with Hugo and the hugo-story theme.

## Images

Images are supposed to be in the webp format.

```bash
 $ mogrify -strip -auto-orient -resize 3000x3000 -quality 85 image.webp 
```

## Linking from a QR Code

- `https://guest:EinLebenLang@www.janine-und-markus-heiraten.de/`

Trivial authentication. Sufficient to keep the side from being indexed by google and other crawlers.
User name and password is hidden after a quick redirect, URL forwarding between guests and non guests will not work
easily.
