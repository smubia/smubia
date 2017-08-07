# smubia.org / smubia.github.io
The Home of SMU Business Intelligence and Analytics. We're large on reproducibility and open source code. Learn yourself some git and get started with helping us on content ;)

## Requirements

**TBD.** Setup Jekyll, bower, npm, bundle.
npm install, bower install, bundle install,

## Getting Started

If you're on a **fresh installation**:

run `npm i` first to install all the npm modules we need. Important for running gulp!

Then run the following:

`npm start`

This tells npm to run gulp which will convert all our scss styles into css. Without this step, you won't see your styles updated.

`jekyll serve --config _config.yml,_config_dev.yml`

This will run jekyll using the config files relevant to your environment
_config.yml is used on the server and _config_dev.yml is used on your local machine (the site.url differs for both)

###

If you're daring, simply run `gulp`. This will allow you to edit your pages and preview the changes in real-time on your browser across your computer and mobile devices (if you access the link gulp tells you to)

Use the **local Access URLs**

## Adding Information

- [Adding New Events and Workshops](#new-events-and-workshops)
- [Adding New Posts](#new-posts)
- [Adding New Pages](#new-pages)

### New Events and Workshops

1. Go to [/events/_posts](https://github.com/smubia/smubia/tree/master/events/_posts) and copy any of the existing event posts.
2. Anything enclosed in `-----` at the top, follow the format **very closely**
3. Always preview your post by clicking on the preview button
4. Commit with a relevant message on what you changed (don't be lazy!) **only after** you have previewed it, and ensured that it produces the expected output!

### New Posts

1. Go to [/blog/_posts](https://github.com/smubia/smubia/tree/master/blog/_posts) and copy any of the existing event posts.
2. Anything enclosed in `-----` at the top, follow the format **very closely**
3. Always preview your post by clicking on the preview button
4. Commit with a relevant message on what you changed (don't be lazy!) **only after** you have previewed it, and ensured that it produces the expected output!

### New Pages

1. Go to [/_pages](https://github.com/smubia/smubia/tree/master/_pages)
2. Create a folder that matches the name of the page you wish to create
3. Create an index.md file in that directory
4. Follow the structure of other index.md files in the direct, neighboring directory. Make sure the permalink is enclosed in 2 back slashes: `/some-permalink/` The permalink will be equivalent to `smubia.org/some-permalink` in the url bar.
5. Make sure you're using the pages layout: `layout: pages`
6. Always preview your md file to make sure the output matches.

## Contributing

If you're interested in contributing, either contact any one of the contributors or fork this repo. Make your changes and do a pull request (PR) :)
