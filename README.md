# Harpokration On Line (HOL)

This repository contains the code that runs [Harpokration On Line](https://dcthree.github.io/harpokration/), a collaborative translation project for [Harpokration's](https://en.wikipedia.org/wiki/Harpocration) *Lexicon of the Ten Orators*.

Data is available at: <https://github.com/dcthree/harpokration-data>

See also:

 * [Announcement blog post for Harpokration On Line](https://blogs.library.duke.edu/dcthree/2015/05/26/harpokration-on-line/)
 * [Photios On Line](https://dcthree.github.io/photios/)
 * [The Index of Ancient Greek Lexica](https://dcthree.github.io/ancient-greek-lexica/)

## Technical Details

This is a fork of <https://github.com/ryanfb/cts-cite-driver> to draw both CTS text and CITE translations from Google Fusion Tables, with additional modifications for linking to the Suda On Line and Perseus for text entries.

The editing links currently point at an instance of the [CITE Collection Editor](https://github.com/ryanfb/cite-collection-editor) proxied by a [CITE Collection Manager](https://github.com/ryanfb/cite-collection-manager) instance running on Google App Engine at <http://cite-harpokration.appspot.com/>.
