# I Cake Bakery website

A single-page bakery site: home with a 3D scroll story (cake is baked, frosted, decorated and boxed as you scroll), menu, gallery, reviews, notice board, about and an order form that opens WhatsApp with the order filled in.

Everything lives in `index.html`. There is no build step.

## Edit your details

Open `index.html` and find the block that starts with `EDIT YOUR BAKERY DETAILS HERE`.

- `whatsapp`: country code + number, digits only, e.g. `919876543210`
- `phone`, `email`, `address`, `hours`, `instagram`, `googleReviews`
- `MENU`, `GALLERY`, `REVIEWS` and `NOTICES` are lists right below it. Edit names, prices and text there.

## Photos

Menu and gallery photos are loaded from Unsplash (free to use, credited in the footer under "Photo credits").
To use your own photo for an item, add `img: 'images/your-photo.jpg'` to that item and put the file in an `images/` folder in this repo. Your photo replaces the Unsplash one.

## Deploy

This repo is connected to Vercel. Every push to `main` deploys automatically. No framework, build command or output directory is needed.

## Built with

Three.js (3D scroll story), Motion (Framer Motion's animation engine), Lenis (smooth scrolling), Google Fonts (Bagel Fat One, Figtree).
