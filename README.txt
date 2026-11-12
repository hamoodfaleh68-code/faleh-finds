FALEH FINDS - static website
============================
Files
  index.html     the whole site (HTML, CSS and JavaScript are inside this file)
  products.json  your product list (starts empty)
  img/           logo and images (see img/README.txt)
  .nojekyll      tells GitHub Pages to serve files as they are

No dependencies, no build step, no external libraries. All paths are relative.

IMPORTANT: products.json is loaded with fetch(), so open the site through a web
address (GitHub Pages or any host). Opening index.html directly from your phone's
Files app will show the site but no products.

Put it online with GitHub Pages (from a phone)
  1. Unzip this file in your phone's Files app.
  2. github.com -> New repository -> name it faleh-finds -> Public.
  3. Add file -> Upload files -> upload index.html, products.json, .nojekyll
     and the img folder contents (type img/ before each image file name).
  4. Settings -> Pages -> Deploy from a branch -> main -> / (root) -> Save.
  5. Your link: https://YOURUSERNAME.github.io/faleh-finds/

Before publishing
  - In index.html, replace your-email@example.com with your real email.

Adding a product (edit products.json on GitHub, pencil icon)
  [
    {
      "id": "my-first-product",
      "name": "Product name",
      "category": "sneakers",
      "description": "Your own short description.",
      "image": "img/my-first-product.jpg",
      "link": "https://www.amazon.in/... your affiliate link",
      "tags": ["tag one", "tag two"],
      "featured": true,
      "collections": ["everyday-essentials"]
    }
  ]
  Separate several products with commas. "id" must be unique, lowercase, no spaces.

Category names (use in "category")
  mens-fashion, womens-fashion, sneakers, watches, electronics, smartphones, audio,
  gaming, home-kitchen, fitness-accessories, student-essentials, travel-accessories,
  bags-backpacks, office-desk, beauty-personal-care

Collection names (use in "collections")
  everyday-essentials, study-desk-setup, minimalist-lifestyle, gaming-setup,
  travel-essentials, fashion-accessories

Pages included (all work from the menu and footer)
  Home, Shop (search, filter, sort), Categories, 15 category pages, 6 collection pages,
  product pages, About, Contact, FAQ, Privacy Policy, Terms, Affiliate Disclosure,
  Editorial Policy.
