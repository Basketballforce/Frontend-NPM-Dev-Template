# What & Why
- Wanted to create a starting place in NPM with a minimal & common set of frontend tooling for development purposes. 

# Includes setup for:
- Eslint
- Sass/scss
- Autoprefixer
- Babel
- Postcss
- Webpack
- StyleLint
- Pug

# To be added
- Combine css watch & js watch into one npm command
- Combine css & tailwind watch scripts into one npm command

# You can build and compile the required components with npm
- Watch & Build css on changes: npm run watch:css
- Watch & Build js on changes: npm run watch:js
- Watch & Build tailwind on changes: npm run watch:tailwind

# No automatic browser refreshing is enforced.
- There are several free tools that support this. For example the live server extension in vscode

# Lessons Learned
- A lot of js focused frontend dev tools and build tools should really be saved until the end of development
    - *with the exception of style and code linting
    - Minimzation and compressed builds, images, etc. can really wait until the end and only complicate dev setup and workflow

- Pug is a cool html templating engine/library but, looses points due to lack of adoption and develper efficiency to a point where using it doesn't make sense (at least in my case)
    - Learning pug isn't too hard but takes a little bit of time. As someone who knows most of the html I am going to need & with the benefits of a modern text editor (such as snippets and autocomplete), using pug doesn't really speed up develpment and only slows me down/complicates the workflow.
    - Due to lack of adoption, I want to use html boilerplate with pug but, that requires converion each time which can be tedious & error prone 

    - I was really only looking to use pug to extend html pages but, this can easily be done with copy and paste.

- Simplicity is key, and the heart of popular html,css & js frontend tooling seems to conflict this. 
    - Each tool has its place and purpose but, as a dev building a website, I don't really want these tools till the end of the development process.
    - I spent 3-5 hours learning and setting up these tools. I'd much rather have spent that time working on a site's html,css & js

- SCSS is awesome if your are extending another existing css library or building your own
    - Otherwise, its probably overkill

- Tailwind & many other tooling's install/setup process can & should be explained more verbosely for those less familiar to the tooling & npm (In my opinon)


# Other
- Best Pug tutorial I could find: https://www.sitepoint.com/a-beginners-guide-to-pug/
- Inspiration for this repo: https://wweb.dev/blog/how-to-create-static-website-npm-scripts/