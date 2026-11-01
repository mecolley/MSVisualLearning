# Mass spectrometry signal processing, one idea at a time

Interactive, browser-based lessons on what happens between a mass spectrometer's detector and a peak list: what a peak is, what noise is, and how software decides where a peak is and how much is there.

**Live site:** https://YOUR-USERNAME.github.io/REPO-NAME/

Every lesson uses simulated data, so the true answer is always known, and everything runs in the browser. There is nothing to install and no data leaves the page.

## Lessons

| # | Lesson | File |
|---|--------|------|
| 1 | [Anatomy of a spectrum](anatomy_of_a_spectrum.html) | `anatomy_of_a_spectrum.html` |
| 2 | [What noise looks like](what_noise_looks_like.html) | `what_noise_looks_like.html` |
| 3 | [Smoothing and baseline removal](smoothing_and_baseline.html) | `smoothing_and_baseline.html` |
| 4 | [Detecting peaks](detecting_peaks.html) | `detecting_peaks.html` |
| 5 | [Finding a peak’s center](peak_centroid_demo.html) | `peak_centroid_demo.html` |
| 6 | [Overlapping peaks and resolution](overlapping_peaks.html) | `overlapping_peaks.html` |
| 7 | [Mass calibration](mass_calibration.html) | `mass_calibration.html` |
| 8 | [Combining many scans](combining_scans.html) | `combining_scans.html` |

## Using the lessons offline

Download the repository and open `index.html` in any browser. Each lesson is a single self-contained HTML file, so it can also be emailed or shared on its own.

## Adding a lesson

1. Put the lesson's `.html` file in the repository's top folder. Use lowercase names with no spaces, because GitHub Pages links are case-sensitive.
2. In `index.html`, find the comment that starts `HOW TO ADD A LESSON` and copy the template into the list.
3. Add a row to the table above.

## Files

- `index.html`: the home page listing all lessons
- `anatomy_of_a_spectrum.html`: Anatomy of a spectrum
- `what_noise_looks_like.html`: What noise looks like
- `smoothing_and_baseline.html`: Smoothing and baseline removal
- `detecting_peaks.html`: Detecting peaks
- `peak_centroid_demo.html`: Finding a peak’s center
- `overlapping_peaks.html`: Overlapping peaks and resolution
- `mass_calibration.html`: Mass calibration
- `combining_scans.html`: Combining many scans
- `404.html`: shown by GitHub Pages for broken links
- `.nojekyll`: tells GitHub Pages to serve the files as they are, without processing them
