# Pink Pumpkin moving guides

Public static site of practical UK moving guides from [Pink Pumpkin Logistics](https://pinkpumpkinlogistics.co.uk).

Intended live site: https://dalw387.github.io/pink-pumpkin-guides/

This is plain HTML and CSS. There is no build step. GitHub Pages should be set to deploy from the `main` branch, folder `/` (root).

To turn Pages on (one time): open [Settings → Pages](https://github.com/Dalw387/pink-pumpkin-guides/settings/pages), choose **Deploy from a branch**, branch **main**, folder **/** (root), then Save. The site usually appears within a minute or two.

## Adding a future article

1. Add the cleaned article as `guides/your-slug/index.html` (use an existing guide as the template).
2. Link it from `index.html`.
3. Add the URL to `sitemap.xml`.
4. Commit to `main`. Pages will update on its own.

Do not invent figures, prices, testimonials or stats. Do not include a home address or phone number. Keep the tone calm, warm and in plain UK English. Every page should say that Pink Pumpkin Logistics is our site and include a “Post your job free” link to https://pinkpumpkinlogistics.co.uk.
