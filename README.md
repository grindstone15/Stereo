# Vintage Stereo Bluetooth Project

A simple static website documenting a first electronics project: restoring a vintage stereo and adding a Bluetooth audio input.

## Files

- `index.html` contains the full website.
- `styles.css` contains all styling.
- `assets/` is where project photographs should be placed.

## Adding photos

The current site contains visual placeholders. Replace each placeholder `<figure>` in `index.html` with an image using the suggested filename. Example:

```html
<figure>
  <img src="assets/final-stereo.jpg" alt="Finished vintage stereo after restoration">
  <figcaption>The finished stereo after reassembly.</figcaption>
</figure>
```

Suggested filenames are printed below each placeholder in the website.

## Publishing with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, and the `assets` folder.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/root` folder.
7. Save. GitHub will provide the public website address after deployment.

## Safety note

Vintage electronics may contain exposed mains voltage and charged capacitors. Unplug the stereo before opening it and verify voltages before making connections.
