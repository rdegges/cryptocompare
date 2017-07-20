# cryptocompare

CryptoCompare is a static website that compares cryptocurrency prices for
popular currencies.

It uses plain old HTML, Javascript, and CSS to render a very simple, one page
application that shows you:

- The top 10 cryptocurrencies by market cap
- All cryptocurrency prices over the last hour, day, and week

This is useful for people interested in speculating on the cryptocurrency
marketplaces, as you can take a look at short term performance to get a feel for
how you'd like to speculate.


![website image][]


## Technical Details

This application is built with plain old HTML and [Bootstrap][] for CSS.  I'm
also using a Bootstrap theme called [Simplex][] which makes things look a tiny
bit better.

The Javascript part of the site is powered by [Vue.js][], a very simple
Javascript framework.

I'm also using:

- [vue2-filters][], a simple Vue.js library that provides some useful template
  filters for displaying text. In this app, I only the filter for helping to
  display currency values nicely.
- [axios][], a simple Javascript library for making HTTP requests

Finally, the data on this website is powered by two separate, free, API
services:

- [coinmarketcap][], which provides a list of the top 10 cryptocurrencies, and
  their price details, and
- [cryptocompare][], which provides metadata about all cryptocurrencies,
  including their respective logo images (which is what I use this for)


  [Bootstrap]: http://getbootstrap.com/ "Twitter Bootstra"
  [Simplex]: https://bootswatch.com/simplex/ "Simplex Bootstrap Theme"
  [Vue.js]: https://vuejs.org/ "Vue.js"
  [vue2-filters]: https://www.npmjs.com/package/vue2-filters "vue2-filters"
  [axios]: https://github.com/mzabriskie/axios "axios"
  [coinmarketcap]: https://coinmarketcap.com/api/ "coinmarketcap API"
  [cryptocompare]: https://www.cryptocompare.com/api "cryptocompare API"
  [website image]: /static/images/screenshot.png "Screenshot"
