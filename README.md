# buckley


to run the site: 
$ npx eleventy --serve


EleventyHtmlBasePlugin - > changes the url for every path so in file '.eleventy.js', line 11, set ' baseHref: "", ' so that it clears out any appended urls


Using the ' | safe' filter will let json data files render html elements.
For json files, if there are extra repeated things, go into the json file an delete any white space return charaters.


Nunjucks Conditional Statement Examples for Eleventy: https://design2seo.com/blog/web-development/11ty/nunjucks-if-statement-for-eleventy/

Filters for 11ty: https://11ty.rocks/eleventyjs/content/
