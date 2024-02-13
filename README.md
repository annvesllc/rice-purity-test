# Rice Purity Quiz Embed Plugin for WordPress
The [Rice Purity Test](https://ricepurityytest.com) Quiz Embed Plugin offers a straightforward and efficient method to incorporate the Rice Purity Quiz into your WordPress site. This lightweight plugin uses a shortcode to embed the quiz via an iframe, enhancing your website's content with an interactive element that encourages user engagement and participation.

## Features
Easy Embedding: Embed the Rice Purity Quiz into your posts or pages using a simple shortcode.
Responsive Design: Ensures a great viewing experience across devices, from desktops to mobile phones.
Seamless Integration: The quiz integrates directly into your site, keeping your visitors engaged without navigating away.
Customizable Dimensions: While the default size works well for most sites, you can easily adjust the width and height to fit your layout.
## Installation
Download the Plugin:

Navigate to the Releases section and download the latest version of the plugin.
Upload to Your WordPress Site:

Go to your WordPress dashboard, navigate to Plugins > Add New > Upload Plugin, and choose the downloaded ZIP file.
Activate the Plugin:

After uploading, activate the plugin through the 'Plugins' menu in WordPress.
Usage
Once the plugin is activated, you can embed the Rice Purity Quiz anywhere on your site using the shortcode [rice_purity_quiz].

## Basic Shortcode:
[rice_purity_quiz]
##Advanced Customization:
Currently, customization options such as adjusting the iframe's dimensions are to be directly edited within the plugin's PHP file. Future updates aim to include these options within the shortcode for easier access.

## Customization
To adjust the iframe dimensions, edit the plugin's PHP file where the iframe is defined. Replace the width="100%" and height="600px" attributes with your desired dimensions.

## Example:

$quiz_iframe = '<iframe src="https://ricepurityytest.com/start-test/" width="800px" height="500px" frameborder="0" allowfullscreen></iframe>';

## Support
For support, feature requests, or bug reporting, please open an issue in the GitHub repository issue tracker.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your proposed changes or enhancements.

## License
This plugin is licensed under the GPL-2.0+ license. Feel free to use, modify, and distribute it according to the license terms.

## Acknowledgments
Thanks to all contributors and users of the Rice Purity Quiz Embed Plugin. Your support and feedback help make this plugin better for everyone.
