## About

Welcome to the personal website of **Jesús Sanz**! This site is built using the **Zaggonaut theme**, a minimalist and versatile design that emphasizes simplicity and clean aesthetics. The core of the site is powered by **Astro**, a modern static site generator that optimizes performance and ensures a smooth browsing experience. 

What sets this website apart, however, is the personal touch behind it. Built with a little bit of imagination and a lot of passion, this site reflects my journey as a developer, sharing insights, projects, and experiences along the way. Whether you're here to explore my work, dive into my blog posts, or simply learn more about what I do, I hope you find something inspiring.

Feel free to browse through, and don't hesitate to get in touch if you have any questions or ideas to share!

# DNS Configurations

Create a file named CNAME in the root of your repository and add your primary domain:

At your domain provider, set up the following A records for the root domain (@):

185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

For the www subdomain, you can add a CNAME record pointing to your GitHub Pages domain.

GitHub Pages does not support automatic redirects between custom domains. If you want www.jesussanz.dev to redirect to jesussanz.dev, you need to set up a redirect via your DNS provider or use an external service like Cloudflare to handle a 301 redirect. (GitHub Docs on Custom Domains Troubleshooting)

## Enable HTTPS:

After your DNS changes have propagated, enable HTTPS in your repository’s GitHub Pages settings. This can take up to 24 hours to become active. (GitHub Docs on Securing Pages with HTTPS)