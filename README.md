# Block-TPE: supplement to the WSC 2026 poster

Supplementary material for the poster *Bayesian Optimization in High-Dimensional, Mixed Search Spaces
Using Block-Partitioned Tree-Structured Parzen Estimators* by Vipul Chalotra, Sasan Amini and Inneke
Van Nieuwenhuyse (Hasselt University), Winter Simulation Conference 2026, Glasgow.

The website is the single file `index.html`. It opens with the abstract and citation, then follows the
poster panel by panel and shows each figure next to the full table behind it. The figures are embedded
in the file; only the equations load KaTeX from a CDN.

## Publishing with GitHub Pages

1. Create a **public** repository and upload `index.html`, `.nojekyll` and this `README.md` to its root.
2. In the repository, open **Settings → Pages**. Under *Build and deployment* choose
   *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
3. After a minute or two the page is live at `https://<user>.github.io/<repository>/`.
   That is the address for the poster's QR code.

`.nojekyll` is an empty file that tells GitHub Pages to serve `index.html` as it is.

## Updating

`index.html` is generated from the stored results. To update the page, upload a newly built
`index.html` over the old one. The link to the published proceedings version will be added once it
exists.

Contact: vipul.chalotra@uhasselt.be
