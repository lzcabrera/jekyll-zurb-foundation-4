
### Run the following to setup Jekyll.rb

`jekyll new PROJECT-NAME`

`cd PROJECT-NAME`

### Keep a backup of default jekyll's index.html for reference
`mv index.jekyll.html`

### Setup compass
create a `config.rb` to setup compass

    require 'zurb-foundation'
....http_path = "/"
    css_dir = "stylesheets"
    sass_dir = "sass"
    images_dir = "images"
    javascripts_dir = "javascripts"
    sass_options = {:debug_info => true}
    output_style = :compact


### Install zurb Foundation 
`compass install foundation`

### Once setup run the following commands to watch for updates
`jekyll serve --watch`

compass --watch

## More info
[jekyll.rb](http://jekyllrb.com/)
[zurb foundation 4](http://foundation.zurb.com/)
