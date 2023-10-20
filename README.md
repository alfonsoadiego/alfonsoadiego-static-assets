# Static assets repository

This repository is designed to hold and serve static assets for our projects, hosted via Netlify.

## Quick Start

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/static-assets-repo.git
   ```

2. **Add your static asset**

   Place your static assets (images, stylesheets, scripts, etc.) into the appropriate directories.

3. **Push to GitHub**

   ```bash
   git add .
   git commit -m "Add [Your Asset Name]"
   git push origin main
   ```

4. **Deploy to Netlify**

   Netlify will now automatically deploy changes pushed to this repository.

   If you haven't already set up continuous deployment:

   - Log in to your Netlify account.
   - Click the "New site from Git" button.
   - Connect to GitHub and select this repository.
   - Configure build settings if needed (not required for simple static assets).
   - Click "Deploy site".

## Directory Structure

- `/images`: For image assets.
- `/styles`: For stylesheets (CSS).
- `/scripts`: For JavaScript files.

## Accessing Assets

Once deployed, your assets can be accessed via the Netlify subdomain:

```
https://your-netlify-subdomain.netlify.app/images/your-image.png
```

Replace `your-netlify-subdomain` with your actual Netlify subdomain and `your-image.png` with your actual file path.

## Contributing

Feel free to contribute to this repository by opening pull requests. Make sure to place assets in the correct directories and follow naming conventions.

## License

This repository is open-source. See [LICENSE](./LICENSE) for details.

## Contact

For questions or concerns, reach out to [alfonso.adiego@gmail.com](mailto:alfonso.adiego@gmail.com).
