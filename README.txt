=== APS Content Moderator Plugin ===
Contributors: DevNiko
Website link: https://github.com/DevNiko/aps-content-moderator-plugin
Tags: text analysis, ai, comment, blog post, filtering, unwanted content
Requires at least: 4.5.0
Tested up to: 5.8.2
Stable tag: 1.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The plugin allows you to filter blog comments for obscene, revealing, ambiguous or offensive content using the APS Content Moderator API.
If the User Comment contains any of the above unwanted data, the comment will automatically be set to "not approved". If none of the content is found, the comment will be released. You can save a lot of time because you don't have to check every comment manually.
The sensitivity of the filtering can be adjusted.

== Description ==

The plugin allows you to filter blog comments for obscene, revealing, ambiguous or offensive content using the APS Content Moderator API.
If the User Comment contains any of the above unwanted data, the comment will automatically be set to "not approved". If none of the content is found, the comment will be released. You can save a lot of time because you don't have to check every comment manually.
The sensitivity of the filtering can be adjusted.

== Installation ==

Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Where i can find the Plugin Settings =

The settings can be found under the menu item Settings -> Aps Content Moderator.

= Where can I get the APS Content Moderator API Key? =

To get the API Key, visit the site https://rapidapi.com/dev.nico/api/ai-powered-content-moderator

You need a RapidAPI account to use the API. All further information can be found on the RapidAPI page.

= which languages are supported by the APS Content moderator API? =

Currently supported languages are: Afrikaans, Albanian, Amharic, Arabic, Armenian, Assamese, Azerbaijani, Bangla - Bangladesh, Bangla - India, Basque, Belarusian, Bosnian - Cyrillic, Bosnian - Latin, (Creole), Bulgarian, Catalan, Central Kurdish, Cherokee, Chinese (Simplified), Chinese (Traditional) - Hong Kong SAR, Chinese (Traditional) - Taiwan, Croatian, Czech, Danish, Dari, Dutch, English, Estonian, Filipino, Finnish, French, Galician, Georgian, German, Greek, Gujarati, Hausa, Hebrew, Hindi, Hungarian, Icelandic, Igbo, Indonesian, Inuktitut, Irish, isiXhosa, isiZulu, Italian, Japanese, Kannada, Kazakh, Khmer, K'iche, Kinyarwanda, Kiswahili, Konkani, Korean, Kyrgyz, Lao, Latvian, Lithuanian, Luxembourgish, Macedonian, Malay, Malayalam, Maltese, Maori, Marathi, Mongolian, Nepali, Norwegian (Bokmål), Norwegian (Nynorsk), Odia, Pashto, Persian, Polish, Portuguese - Brazil, Portuguese - Portugal, Pulaar, Punjabi, Punjabi (Pakistan), Quechua (Peru), Romanian, Russian, Scottish Gaelic, Serbian (Cyrillic), Serbian (Cyrillic, Bosnia, and Herzegovina), Serbian (Latin), Sesotho, Sesotho sa Leboa, Setswana, Sindhi, Sinhala, Slovak, Slovenian, Spanish, Swedish, Tajik, Tamil, Tatar, Telugu, Thai, Tigrinya, Turkish, Turkmen, Ukrainian, Urdu, Uyghur, Uzbek, Valencian, Vietnamese, Welsh, Wolof, Yoruba

For more information please visit the Documentation: https://rapidapi.com/dev.nico/api/ai-powered-content-moderator/details

== Screenshots ==

1. The Content Moderator Plugin Settings Section.
2. In the comment Edit Section you can review the result.
3. In the result table you can see what the API has found in the text.

== Changelog ==
1.0.0 Release
1.0.1 Bugfix: Refined Post comment field selection to avoid problems with other plugins.
1.1.1 Some JS bug fixes and improvements. Added new settings options (enable / disable "Comment Max Length Notification". Possibility to define a alternate HTML element id or class name for the comment textarea. )
1.1.2 Function check with Wordpress 5.8.x. Added new "Good to know" hints. Some spelling correction.

== Upgrade Notice ==
1.0.0 Release
1.1.1 New Settings: "Comment Max Length Notification"

== Good to know ==

You can try to deactivate the options "Comment must be manually approved" and "Comment author must have a previously approved comment" in "Discussion Settings" and let the Plugin do the job for you.

By default, the plugin limits the comment text length to 1024 characters. Since the Content Moderator API can handle a maximum of 1024 characters per request. The limitation can be switched off in the plugin settings. Then, only the first 1024 chars of the comment will be checked.

Furthermore, all HTML tags are filtered out of the comment.

== Support ==

Please visit the GitHub repository page and open an issue: https://github.com/DevNiko/aps-content-moderator-plugin/issues