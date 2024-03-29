📝 _If you want to see how these themes are made, look in the `public/styles/themes` directory! If you don't have a valid theme entered, the site will default to the styles outlined in `style.css`._

### ...or create your own!

Customize your site by updating `custom-theme.css` inside the `public/styles/themes` folder with CSS to update colors, fonts, or any other style rules. Update your `theme` in `settings.json` to `custom-theme` to have the app use those new rules.

📝 _You can rename `custom-theme.css`, just make sure you use the new file name as your theme value in `settings.json`._

🖼️ Check out examples of other themes the community has created in [this Playlist](https://glitch.com/@glitch/featured-glitch-in-bio-remixes) and [submit your own](https://forms.gle/9WFWjSmhdiEoRgVs5) to share!

## Other Tips & tricks

- Check out the [Glitch-in-bio section of our Help Center](https://help.glitch.com/kb/section/13/) for more documentation on how to customize or troubleshoot your new app!
- If you notice your preview is a little out of sync with your `settings.json`, hit the reload button in the preview window and it should update!
- Looking for ways to extend your app, or for inspiration? Check out the official [Glitch-in-bio page](https://glitch.com/glitch-in-bio).

## What's in this project?

← `README.md`: That’s this file. You can delete it, or keep it handy so you don't lose the instructions.

← `index.html`: This is the main page template vite uses to build your site. You'll see the handlebars syntax for importing the data you specify in `settings.json` (built into the structures in `layout/`). You'll also find some tips on configuring the page in the HTML comments.

← `settings.json`: Settings for your name, links, images, and social media. The `index.html` page includes the data using the structures defined in `layout/`.

← `layout/`: Markup templates — you can edit every line of HTML or never even look at any of it. The data you specify in `settings.json` will be built into the page using the HTML in here using handlebars syntax (e.g. `{{settings.name}}`).

← `public/styles/`: Stylesheets for Glitch in Bio, including alternate themes. Change your theme in `settings.json`. You can create a new theme by adding a CSS file to this folder and specifying it using its name in the settings (e.g. `glitch`, `gallery`, `menu`, or whatever yours is called!)

← `public/manifest.json` and `public/sw.js`: These set your site up to function as a Progressive Web App (PWA)–if you add new assets (e.g. stylesheets) you can include them in the list in `sw.js` to cache your site for offline viewing.

← `assets`: Add images here and copy the links into `settings.json` to show them in your site.

![Glitch](https://cdn.glitch.com/a9975ea6-8949-4bab-addb-8a95021dc2da%2FLogo_Color.svg?v=1602781328576)

## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.
