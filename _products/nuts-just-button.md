---
name: Nuts with just the button
price: 150
slug: just-button-nuts
sku: RP1802210133
layout: product
---

Insert whatever we want here.

Here is the embed:



<div id='product-component-28521a963d4'></div>
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
      domain: 'linkitchen.myshopify.com',
      apiKey: '26a343d31f3b31b44a5f0f4f2d3920e5',
      appId: '6',
    });

    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: [508413542460],
        node: document.getElementById('product-component-28521a963d4'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "variantId": "all",
    "width": "240px",
    "contents": {
      "img": false,
      "imgWithCarousel": false,
      "title": false,
      "variantTitle": false,
      "price": false,
      "description": false,
      "buttonWithQuantity": false,
      "quantity": false
    },
    "text": {
      "button": "AGREGA AL CARRITO"
    },
    "styles": {
      "product": {
        "text-align": "left",
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0",
          "margin-bottom": "50px"
        }
      },
      "button": {
        "background-color": "#86c0f5",
        "color": "#fcb3e1",
        "font-family": "Arvo, serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        "padding-left": "50px",
        "padding-right": "50px",
        ":hover": {
          "background-color": "#79addd",
          "color": "#fcb3e1"
        },
        "border-radius": "0px",
        "font-weight": "bold",
        ":focus": {
          "background-color": "#79addd"
        }
      },
      "variantTitle": {
        "font-family": "Josefin Slab, sans-serif",
        "font-size": "17px",
        "font-weight": "normal"
      },
      "title": {
        "font-family": "Source Sans Pro, sans-serif",
        "font-size": "34px"
      },
      "description": {
        "font-size": "17px",
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      },
      "price": {
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      },
      "quantityInput": {
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px"
      },
      "compareAt": {
        "font-size": "11.9px",
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      }
    },
    "googleFonts": [
      "Arvo",
      "Josefin Slab",
      "Source Sans Pro",
      "Josefin Slab",
      "Josefin Slab",
      "Josefin Slab"
    ]
  },
  "cart": {
    "contents": {
      "button": true
    },
    "text": {
      "title": "Carrito",
      "empty": "El carrito esta vacio."
    },
    "styles": {
      "cart": {
        "background-color": "#929292"
      },
      "button": {
        "background-color": "#86c0f5",
        "color": "#fcb3e1",
        "font-family": "Arvo, serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        ":hover": {
          "background-color": "#79addd",
          "color": "#fcb3e1"
        },
        "border-radius": "0px",
        "font-weight": "bold",
        ":focus": {
          "background-color": "#79addd"
        }
      },
      "title": {
        "color": "#ffb1c6"
      },
      "footer": {
        "background-color": "#929292"
      },
      "header": {
        "color": "#ffb1c6"
      },
      "lineItems": {
        "color": "#ffb1c6"
      },
      "subtotalText": {
        "color": "#ffb1c6"
      },
      "subtotal": {
        "color": "#ffb1c6"
      },
      "notice": {
        "color": "#ffb1c6"
      },
      "currency": {
        "color": "#ffb1c6"
      },
      "close": {
        ":hover": {
          "color": "#ffb1c6"
        },
        "color": "#ffb1c6"
      },
      "emptyCart": {
        "color": "#ffb1c6"
      }
    },
    "googleFonts": [
      "Arvo"
    ]
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "variantTitle": false,
      "buttonWithQuantity": true,
      "button": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        "background-color": "#86c0f5",
        "color": "#fcb3e1",
        "font-family": "Arvo, serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        "padding-left": "50px",
        "padding-right": "50px",
        ":hover": {
          "background-color": "#79addd",
          "color": "#fcb3e1"
        },
        "border-radius": "0px",
        "font-weight": "bold",
        ":focus": {
          "background-color": "#79addd"
        }
      },
      "variantTitle": {
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      },
      "title": {
        "font-family": "Source Sans Pro, sans-serif"
      },
      "description": {
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      },
      "price": {
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      },
      "quantityInput": {
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px"
      },
      "compareAt": {
        "font-family": "Josefin Slab, sans-serif",
        "font-weight": "normal"
      }
    },
    "googleFonts": [
      "Arvo",
      "Josefin Slab",
      "Source Sans Pro",
      "Josefin Slab",
      "Josefin Slab",
      "Josefin Slab"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Arvo, serif",
        "background-color": "#86c0f5",
        ":hover": {
          "background-color": "#79addd"
        },
        "font-weight": "bold",
        ":focus": {
          "background-color": "#79addd"
        }
      },
      "count": {
        "color": "#fcb3e1",
        ":hover": {
          "color": "#fcb3e1"
        },
        "font-size": "18px"
      },
      "iconPath": {
        "fill": "#fcb3e1"
      }
    },
    "googleFonts": [
      "Arvo"
    ]
  },
  "option": {
    "styles": {
      "label": {
        "font-family": "Josefin Slab, sans-serif"
      },
      "select": {
        "font-family": "Josefin Slab, sans-serif"
      }
    },
    "googleFonts": [
      "Josefin Slab",
      "Josefin Slab"
    ]
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "lineItem": {
    "styles": {
      "variantTitle": {
        "color": "#ffb1c6"
      },
      "title": {
        "color": "#ffb1c6"
      },
      "price": {
        "color": "#ffb1c6"
      },
      "quantity": {
        "color": "#ffb1c6"
      },
      "quantityIncrement": {
        "color": "#ffb1c6",
        "border-color": "#ffb1c6"
      },
      "quantityDecrement": {
        "color": "#ffb1c6",
        "border-color": "#ffb1c6"
      },
      "quantityInput": {
        "color": "#ffb1c6",
        "border-color": "#ffb1c6"
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

here ends the buttom embed
