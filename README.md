
### Run the following to setup Jekyll.rb

`jekyll new PROJECT-NAME`
`cd PROJECT-NAME`

### Keep a backup of default jekyll's index.html for reference
`mv index.jekyll.html`

### Setup compass
create a config.rb to setup compass
    require 'zurb-foundation'
....# Require any additional compass plugins here.
    # Set this to the root of your project when deployed:
    http_path = "/"
    css_dir = "stylesheets"
    sass_dir = "sass"
    images_dir = "images"
    javascripts_dir = "javascripts"
    sass_options = {:debug_info => true}
    # You can select your preferred output style here (can be overridden via the command line):
    # output_style = :expanded or :nested or :compact or :compressed
    output_style = :compact

# To enable relative paths to assets via compass helper functions. Uncomment:
# relative_assets = true

# To disable debugging comments that display the original location of your selectors. Uncomment:
# line_comments = false

### Install zurb Foundation 
`compass install foundation`

### Once setup run the following commands to watch for updates
`jekyll serve --watch`
compass --watch

## More info
[jekyll.rb](http://jekyllrb.com/)
[zurb foundation 4](http://foundation.zurb.com/)
