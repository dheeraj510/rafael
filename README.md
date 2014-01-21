## Super simple repro example for rails/sass-rails#166 and spree/spree#3415

To reproduce:

* Bundle install
* Start the app
* Go to the homepage
* According to app/assets/spree/frontend/_variables.css.scss, background should be *BLACK* but is instead *WHITE*.

WIP terrible hack to fix: https://gist.github.com/radar/8532607