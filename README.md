# MDN shared assets

This repository contains shared media assets for MDN Web Docs, including source files where available.

The assets are hosted at <https://mdn.github.io/shared-assets/>, so use the `mdn.github.io` URLs in MDN content.

## Getting started

If you are creating a live sample on MDN that requires assets (images, fonts) to demonstrate a feature, you can use these resources instead of adding new ones to the content repositories.

### Using shared assets in documentation

If you are working on MDN documentation, you can refer to images in markdown like so (suitable for diagrams):

```markdown:
![Diagram of a preflight request](https://mdn.github.io/shared-assets/images/diagrams/http/cors/preflight-correct.svg)
```

If you want to use images in code samples, you can refer to them like this for fonts, for example:

```css
@font-face {
  src: url("https://mdn.github.io/shared-assets/fonts/LeagueMono-VF.ttf");
  font-family: "LeagueMonoVariable";
  /* etc. */
}
```

Images are also similar in CSS:

```css
body {
  background: url("https://mdn.github.io/shared-assets/images/examples/leopard.jpg")
    #00d no-repeat fixed;
}
```

And in HTML, for example:

```html
<img
  alt="colorful balloon against a blue sky"
  src="https://mdn.github.io/shared-assets/images/examples/balloon.jpg"
/>
```

### Adding new assets

First, check if the shared assets repository (this repo) already contains a suitable existing resource.
If there is nothing appropriate, you may open a pull request that adds new resources.
Make sure you've checked the following things:

- compress resources such as images to conserve bandwidth on live pages
- the resources are [CC0](https://creativecommons.org/public-domain/cc0/) or are under a permissive license
- there is a need to add the resource instead of using existing ones

Your pull request must include:

- rationale for adding a resource, and
- links to licensing terms of the asset(s).

Once assets are added to the `main` branch, they will be available at `https://mdn.github.io/shared-assets/path/to/new/asset`.

## Contributing

Our project welcomes contributions from any member of our community.
If you want to find out more, you can see helpful links in our [Contributor Guide](CONTRIBUTING.md).

By participating in and contributing to our projects and discussions, you acknowledge that you have read and agree to our [Code of Conduct](CODE_OF_CONDUCT.md).

## Communications

If you have any questions, please reach out to us on our [communication channels](https://developer.mozilla.org/en-US/docs/MDN/Community/Communication_channels).

## License

This project is licensed under the [LICENSE](LICENSE.md).

### Attributions

- The font `fonts/font_with_slant_axis.woff2` was created by <https://github.com/arrowtype> and is used under the OFL license.
