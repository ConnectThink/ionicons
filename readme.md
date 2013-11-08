# Ionicons For Wordpress

Wordpress plugin that adds [ionicons](http://ionicons.com) support to your theme and wp-admin. Quickly add icons to your wordpress site via html, css or shortcode. 

## Usage

### HTML
Use icons in your posts and templates using the `<i>` element. First [find the icon](http://ionicons.com/) class name you wish to display and add the classes `icon` and the name of your icon of choice. Like so: 

    <i class="icon ion-chatbox"></i>

### CSS
Use icons in your css with `:before` and `:after` tags. Define the `content` property with with the [appropriate css content code](http://ionicons.com/) and define `font-family` as `Iconicons`. Like so:

    .element:before {
      content: '\f109';
      font-family: Ionicons;
      font-weight: normal;
      font-style: normal;
    }

### Shortcode
Use shortcodes in your post editor. Paste the icon class name in the name attribute.

    [icon name=ion-checkmark]  

## Installation
You know the drill. 

1. Upload ionicons plugin via the Plugins page in Wordpress
2. Activate the plugin
3. Use one of the aformentioned methods to display your icons. 

###Editing Icons
Like regular fonts, these icons are vectors, so they are fully scalable to any size. Consider using css to make icons the precise size you need. You can also change the icon's color, orientation, or whatever you can think of. 

    .ion-checkmark {
      font-size: 30px;
      color: orange;
    }

### Finding Icons
The icons come with a `Cheet Sheet` which can be accesses via the Plugins page in Wordpress. It will list all the plugins, their class name, css content value, and provide an example of different sizes. 

You can also visit [ionicons.com](http://ionicons.com/) for a searchable list of all the icons. Yay! No scrolling line by line!

## Credits

Designed by [@helloimben](https://twitter.com/helloimben).

All brand icons are trademarks of their respective owners. The use of these trademarks does not indicate endorsement of the trademark holder by Drify, Connect Think, nor vice versa.

Plugin built and maintained by [Connect Think]('http://connectthink.com').

## License

Ionicons and this plugin are licensed under the [MIT license](http://opensource.org/licenses/MIT).
