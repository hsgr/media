# Hackerspace.gr media

A collection of videos and photos by Hackerspace.gr.

[media.hackerspace.gr](https://media.hackerspace.gr)


## Upload media

Get in touch with Hackerspace.gr members to get access.

## Contribute

For functionality improvements consider contributing to the [upstream project](https://github.com/saimn/sigal).

For full documentation check the [official upstream website](http://sigal.saimon.org/). Bellow is a quick guide that will help you setup a local development environment for [media.hackerspace.gr](https://media.hackerspace.gr).

1. Clone this repository locally.

2. Put some photos inside the `media/` subfolder.

3. Install dependencies.

    pip install sigal cssmin

4. Make changes to the design that lives under the `themes/` subdfolder.

5. If you made changes to css minify them.

    cat base.css style.css skeleton.css layout.css colorbox.css |cssmin > style.min.css

6. Build the gallery.

    sigal build

7. Test that everything looks good.

    sigal server

8. Profit.
