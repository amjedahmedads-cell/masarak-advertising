# Masarak Advertising website

This is a static, bilingual Arabic/English version of the Masarak Advertising
website. It does not depend on Manus services, a server, a database, or API
secrets. The WhatsApp, phone, Instagram, and Facebook links are included.

## Preview locally

Serve this folder with a static HTTP server. The clean page URLs (such as
`/services/`) resolve to each route's `index.html` on static hosting; opening
the files directly with a `file://` URL may not support route navigation.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to its
   default branch.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions**
   as the build and deployment source.
3. The included workflow deploys the site after each push to `main`.

The site can first be published at the GitHub Pages URL. The custom domain
`masarak-advertising.space` has not been configured because it must be purchased
and its DNS records must point to GitHub Pages first. After that, add the domain
under **Settings → Pages**.

## Site pages

- Arabic: `/`, `/services/`, `/about/`, `/portfolio/`, `/contact/`
- English: `/en/`, `/en/services/`, `/en/about/`, `/en/portfolio/`,
  `/en/contact/`

The portfolio intentionally says there are no approved projects to show, as on
the current published site.
