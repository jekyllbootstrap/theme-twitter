This is blog theme compatible with Jekyll-Bootstrap

<http://jekyllbootstrap.com> for usage.

website : <http://lincolnge.github.io>

### Install Themes

    $ rake theme:install git="git@github.com:lincolnge/theme-twitter-lin.git"
    
    
The installer uses git to download the Theme Package and then installs it. If you have obtained a Theme Package in another way, such as zip download, you can manually place it into your ./_theme_packages folder and then run the installer with the name of the theme.

    $ rake theme:install name="twitter-lin"
  
  
### Switch Themes

    $ rake theme:switch name="twitter-lin"