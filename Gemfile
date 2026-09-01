source 'https://rubygems.org'

gem "jekyll", "~> 4.4.1" # installed by `gem jekyll`
# gem "webrick"        # required when using Ruby >= 3 and Jekyll <= 4.2.2

gem "just-the-docs", "0.12.0" # pinned to the current release
# gem "just-the-docs"        # always download the latest release

gem "dark-dungeons-theme", github: "sunflowermans/designing-dungeons-theme"


group :jekyll_plugins do
        gem "jekyll-hover-popup" # Link hovering preview windows
        gem "jekyll-jtd-toc-nav" # Table of Contents in the navigation bar
        gem "jekyll-dice-tray" # Dice tray with clickable dice notation recognition
        gem "jekyll-image-links" # Custom image-map features
        gem "jekyll-scry-content" 
        gem "scry-rpg-callouts"
end

# Adventure / ruleset content gems (discovered by jekyll-scry-content).
# Pin gemspec versions. Path gems are for local development; use git+tag for private full-art.
gem "scry-seers-sanctum", "~> 3.2", github: "sunflowermans/scry-seers-sanctum"
gem "scry-a-familiar-tower", "~> 1.1", github: "sunflowermans/scry-a-familiar-tower"
gem "scry-ose-rules", "~> 1.0", github: "sunflowermans/scry-ose-rules"
#gem "scry-seers-sanctum", github: "sunflowermans/scry-seers-sanctum", tag: "v3.2.1"
