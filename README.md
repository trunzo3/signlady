# The Sign Lady — Option 1: Bold Professional

A responsive, single-page, static site for Maria Trunzo. It follows the approved **Option 1** art direction and incorporates the bolder six-card **Our Services** section. No framework, server, build process, or external dependencies required.

## Preview

Open `index.html` in your browser, or serve the folder locally with `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new public GitHub repository.
2. Upload **the contents of this folder** (`index.html`, `assets/`, and this README) to its root.
3. Under **Settings → Pages**, choose **Deploy from a branch**, `main`, and `/ (root)`.
4. Open the GitHub Pages URL provided by GitHub once the deployment completes.

The contact buttons open an email message to `signsby@mariathesignlady.com`. Phone buttons initiate a call on compatible devices. No service-side form or third-party analytics are used.

## Image sourcing and accuracy

- The official logo was retrieved from Maria's November 5, 2026 Outlook email, named `New Look Logo.png`.
- The portrait is **the exact user-approved edited Maria photo**, cropped only to fit the design. Maria's face was not regenerated.
- Woodside van, Moreno leasing sign, billboard poster, Lincoln wall sign, custom branded artwork, and retractable banner originate from supplied or emailed assets.
- **The 8 "Explore the possibilities" gallery images and 5 moving-reel images are clearly disclosed as illustrative concepts.** These should be replaced with Maria's own photographs when available. They must not be represented as completed client jobs.
- Images from Featured Work and Our Work are distinct. The moving reel uses its own images. Its loop repeats its own 5 images solely to animate continuously, not across other page sections.
- The original Outlook email titled `Re: Auntie Ria` contains 43 individual OneDrive shared-file links. Their links were found but could not be downloaded from the present environment; the live website uses only locally packaged image files.

## Swapping in Maria's OneDrive photos

Maria's email lists images including `ADA Signs.jpg`, `Cafe Window Vinyl.jpg`, `Channel Letters.jpg`, `Embroidered Hat.jpg`, `Floor Directionals.jpg`, `Gooseport Van Window Perf.jpg`, `Kia Roseville.jpg`, `Large Format Wall Art.jpg`, `Town Square Windows.jpg`, and dozens more. Once those originals are locally available:

- Place them in `assets/` (WebP preferred for smaller sites).
- Replace the corresponding `assets/concept-*.webp` `src` and `data-lightbox` references in `index.html`.
- Update the card captions and remove their "Concept" labels and the general disclaimer.
- For the moving reel, replace the 5 `assets/reel-*.webp` references and update the alt text; each tile is duplicated once only for seamless looping.

**Important:** Do not place OneDrive private sharing tokens in the public GitHub repository. Put actual image files in `assets/` instead.

## Brand

Colors: black `#0d0f11`, red `#df0714`, turquoise `#00a5ad`; tagline: **Real Service, Real Quality, Real Fast.**
