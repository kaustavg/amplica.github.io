# Approved asset sources

The HTML/CSS currently reference the approved assets directly from their original public URLs so the two-file static page works without the Webflow runtime.

To make the site completely offline/local, download these four files and replace the URLs with the suggested local paths:

| Asset | Suggested local path | Original source |
| --- | --- | --- |
| Oboe wordmark | `assets/oboe-logo.svg` | `https://assets-global.website-files.com/648c24201c47788e803ed3e8/648c2c079599271f54ec43f5_Obeo%20brand%20logo.svg` |
| Favicon | `assets/favicon.svg` | `https://assets-global.website-files.com/648c24201c47788e803ed3e8/649af415800b708073e897e5_Favicon%20.svg` |
| Animated hero background | `assets/homepage-bg.gif` | `https://dl.dropboxusercontent.com/scl/fi/j52ffpnrpx8pc5ivdr50x/Homepage-01.gif?rlkey=rhvwzcmrtz2ioek3dvpl0oq8l&dl=0` |
| Static fallback poster | `assets/home-bg-poster.jpg` | `https://assets-global.website-files.com/648c24201c47788e803ed3e8/64b61b90cf2b8b7a17a0a969_Home%20BG%20Video-poster-00001.jpg` |

No external CSS, JavaScript, analytics, Webflow runtime, jQuery, Lottie, GSAP, or SplitType dependencies remain.
