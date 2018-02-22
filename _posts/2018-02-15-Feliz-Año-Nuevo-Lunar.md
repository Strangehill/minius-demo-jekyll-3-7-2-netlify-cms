---
layout: post
title:  "Feliz Año Nuevo Lunar"
date:   2018-02-15 19:55:04
---

Happy Lunar New Year.

I wanted to put a quick website together to test a couple different technologies.

First, I'm writing these words from my command line. It's a powerful way to write but not everyone has learned such ways. Luckily, there are new tools that make it possible for non-coding types to blog on this system --- kinda like Wordpress but lighter and faster.

I've set up this alternative platform to compose your posts. It's called Netlify CMS.

Netlify is a website hosting provider. Netlify CMS is one of the main products they offer. It's an interface through which you can add, remove, and edit blog posts and pages. Any changes you make go live within a couple minutes. I would suggest you click on the following link and try it but if you do I'm pretty sure you won't get past the login screen.

[Netlify CMS for this early Mini Us mockup](https://keen-wiles-aa7309.netlify.com/admin).

I'll let y'all know soon about your accounts, but in the meantime I wanted to show something else.

Here's a shopify product.

Try adding it to a cart. Isn't it really simple from a visitor's standpoint?

<div id='product-component-2dd3c8704e6'></div>

<script type="text/javascript">
/*<![CDATA[*/

(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }

  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }

  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'haris-mahmood.myshopify.com',
      apiKey: 'a4e6808b1c4afa490c5b7459f7758347',
      appId: '15',
    });

    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: [9017131142],
        node: document.getElementById('product-component-2dd3c8704e6'),
        moneyFormat: '%24%24%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "variantId": "all",
    "contents": {
      "variantTitle": false,
      "description": false,
      "buttonWithQuantity": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      }
    }
  },
  "cart": {
    "contents": {
      "button": true
    },
    "styles": {
      "footer": {
        "background-color": "#ffffff"
      }
    }
  },
  "modalProduct": {
    "contents": {
      "variantTitle": false,
      "buttonWithQuantity": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      }
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  }
}
      });
    });
  }
})();
/*]]>*/
</script>

We can present our products just like that, or we can use more pictures, or use different sizes and we can change the color of the button, make the corners sharper or more rounded, and change the size of the button, as well as the text on the button so that it says something different than "ADD TO CART".

But what I didn't realize until I started looking more deeply into it, is that there's not much default styling to undo. The design Shopify gives to that button out of the box is pretty minimal.

I'll be looking more into Shopify so please share your questions.
