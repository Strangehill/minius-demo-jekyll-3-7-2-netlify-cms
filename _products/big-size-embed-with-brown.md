---
name: Nuts on a big size embed
price: 150
slug: big-size-embed
sku: RP1802210132
layout: product
---

Here is the embed:


<div id='product-component-11670170d8f'></div>
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
        node: document.getElementById('product-component-11670170d8f'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "layout": "horizontal",
    "variantId": "all",
    "width": "100%",
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "variantTitle": false,
      "description": true,
      "buttonWithQuantity": true,
      "button": false,
      "quantity": false
    },
    "text": {
      "button": "AGREGA AL CARRITO"
    },
    "styles": {
      "product": {
        "text-align": "right",
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0",
          "margin-bottom": "50px"
        }
      },
      "button": {
        "background-color": "#7d57b6",
        "color": "#dffdf6",
        "font-family": "Playfair Display, serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        "padding-left": "50px",
        "padding-right": "50px",
        ":hover": {
          "background-color": "#714ea4",
          "color": "#dffdf6"
        },
        "border-radius": "30px",
        "font-weight": "bold",
        ":focus": {
          "background-color": "#714ea4"
        }
      },
      "variantTitle": {
        "font-family": "Strait, sans-serif",
        "font-size": "17px",
        "font-weight": "bold"
      },
      "title": {
        "font-family": "Source Sans Pro, sans-serif",
        "font-size": "34px"
      },
      "description": {
        "font-size": "17px",
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      },
      "price": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      },
      "quantityInput": {
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px"
      },
      "compareAt": {
        "font-size": "11.9px",
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      }
    },
    "googleFonts": [
      "Playfair Display",
      "Strait",
      "Source Sans Pro",
      "Strait",
      "Strait",
      "Strait"
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
        "background-color": "#2b1818"
      },
      "button": {
        "background-color": "#7d57b6",
        "color": "#dffdf6",
        "font-family": "Playfair Display, serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        ":hover": {
          "background-color": "#714ea4",
          "color": "#dffdf6"
        },
        "border-radius": "30px",
        "font-weight": "bold",
        ":focus": {
          "background-color": "#714ea4"
        }
      },
      "title": {
        "color": "#ffffff"
      },
      "footer": {
        "background-color": "#2b1818"
      },
      "header": {
        "color": "#ffffff"
      },
      "lineItems": {
        "color": "#ffffff"
      },
      "subtotalText": {
        "color": "#ffffff"
      },
      "subtotal": {
        "color": "#ffffff"
      },
      "notice": {
        "color": "#ffffff"
      },
      "currency": {
        "color": "#ffffff"
      },
      "close": {
        ":hover": {
          "color": "#ffffff"
        },
        "color": "#ffffff"
      },
      "emptyCart": {
        "color": "#ffffff"
      }
    },
    "googleFonts": [
      "Playfair Display"
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
        "background-color": "#7d57b6",
        "color": "#dffdf6",
        "font-family": "Playfair Display, serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        "padding-left": "50px",
        "padding-right": "50px",
        ":hover": {
          "background-color": "#714ea4",
          "color": "#dffdf6"
        },
        "border-radius": "30px",
        "font-weight": "bold",
        ":focus": {
          "background-color": "#714ea4"
        }
      },
      "variantTitle": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      },
      "title": {
        "font-family": "Source Sans Pro, sans-serif"
      },
      "description": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      },
      "price": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      },
      "quantityInput": {
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px"
      },
      "compareAt": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      }
    },
    "googleFonts": [
      "Playfair Display",
      "Strait",
      "Source Sans Pro",
      "Strait",
      "Strait",
      "Strait"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Playfair Display, serif",
        "background-color": "#7d57b6",
        ":hover": {
          "background-color": "#714ea4"
        },
        "font-weight": "bold",
        ":focus": {
          "background-color": "#714ea4"
        }
      },
      "count": {
        "color": "#dffdf6",
        ":hover": {
          "color": "#dffdf6"
        },
        "font-size": "18px"
      },
      "iconPath": {
        "fill": "#dffdf6"
      }
    },
    "googleFonts": [
      "Playfair Display"
    ]
  },
  "option": {
    "styles": {
      "label": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      },
      "select": {
        "font-family": "Strait, sans-serif",
        "font-weight": "bold"
      }
    },
    "googleFonts": [
      "Strait",
      "Strait"
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
        "color": "#ffffff"
      },
      "title": {
        "color": "#ffffff"
      },
      "price": {
        "color": "#ffffff"
      },
      "quantity": {
        "color": "#ffffff"
      },
      "quantityIncrement": {
        "color": "#ffffff",
        "border-color": "#ffffff"
      },
      "quantityDecrement": {
        "color": "#ffffff",
        "border-color": "#ffffff"
      },
      "quantityInput": {
        "color": "#ffffff",
        "border-color": "#ffffff"
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


Here ends the embed.
