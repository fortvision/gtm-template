# FORTVISION for Google Tag Manager

**Status: draft — this template has not yet been published in the Community Template Gallery.**

The FORTVISION tag loads the FORTVISION site tag for the Site ID you specify. It supports on-site campaigns and page-view reporting. What additional visitor and ecommerce events are available depends on the site's implementation and FORTVISION integrations.

## Before you begin

- A FORTVISION workspace and a website registered under **On-site → Sites & embed code**.
- The Site ID issued for that site. Each customer uses their own ID; the template does not create one.
- A Google Tag Manager web container installed on the website.

## Installation

1. Obtain your Site ID in FORTVISION under **On-site → Sites & embed code**. Create a site there if needed.
2. In your GTM workspace, import the FORTVISION tag template. After publication, search the Community Template Gallery for **FORTVISION**. Until then, an administrator can import `template.tpl` in **Templates → Tag Templates → New → Import**.
3. Create a new tag using **FORTVISION** and enter your Site ID.
4. Choose a suitable page-view trigger and configure consent checks so the tag fires only when permitted by your site's consent settings and applicable requirements.
5. Use **Preview** to check that the tag fires successfully and that page views appear for the expected site in FORTVISION. Publish the GTM container only after verification.

Avoid installing the FORTVISION site tag more than once through a plugin, an embed snippet, or another GTM tag.

## Ecommerce data

This template loads the website tag; it does not by itself synchronize the product catalog, order records, or customer records. Ecommerce events may require a compatible data layer or additional platform/server-side integration. Confirm the events and sync required for your store before relying on them.

## Privacy and consent

The loaded site tag may use browser storage and, depending on the site's configuration, load other integrations. Review the site's privacy and cookie disclosures and configure GTM consent checks and triggers appropriate to that site.

## Support

For installation help, contact [FORTVISION](https://fortvision.com/he/contact.html) or open an issue in this repository.

## License

Apache License 2.0. See [LICENSE](LICENSE).
