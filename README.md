# Yahoo stocks Chrome plugin


## browserify

This plugins requires to write a wrapper around the [Yahoo finance node module](https://github.com/pilwon/node-yahoo-finance), and then produce a [browserify](https://browserify.org/articles.html) version of the script.

browserify <your yahoo finance module wrapper>.js --standalone stockwrapper > yahoostock.js