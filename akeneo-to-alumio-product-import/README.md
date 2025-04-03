# Akeneo to Alumio – Product Import

Import Akeneo complete product data into Alumio storage.

Example of the data structure this will create is looking like

`{
  "code": "Acme Classic Mens Black PVC Work Boots",
  "categories": [
    {
      "categoryCode": "acme"
    },
    {
      "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
    }
  ],
  "customAttributes": {
    "gender": "mens",
    "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
    "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
    "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
    "sole_material": "rubber",
    "upper_material": "pvc",
    "brand": "acme",
    "color": "black",
    "packshot": [
      "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
      "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
      "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
    ]
  },
  "localizations": [
    {
      "customAttributes": {
        "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
      },
      "channelCode": "ecommerce",
      "localeCode": "de_DE"
    },
    {
      "customAttributes": {
        "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
      },
      "channelCode": "ecommerce",
      "localeCode": "en_GB"
    },
    {
      "customAttributes": {
        "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
      },
      "channelCode": "ecommerce",
      "localeCode": "en_US"
    },
    {
      "customAttributes": {
        "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
      },
      "channelCode": "ecommerce",
      "localeCode": "fr_FR"
    }
  ],
  "prices": [
    {
      "amount": "21.32",
      "currencyCode": "EUR"
    },
    {
      "amount": "18.11",
      "currencyCode": "GBP"
    },
    {
      "amount": "22.93",
      "currencyCode": "USD"
    }
  ],
  "attributeSetCode": "rubber_boots",
  "parentCode": null,
  "variants": [
    {
      "identifier": "1273192971",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "6",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 6. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Klassische Herren-Größe 6 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren-Größe 6 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren-Größe 6 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 6. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 6 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 6 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 6 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 6. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 6 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 6 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 6 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 6. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 6 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 6 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 6 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192971",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192972",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "6_5",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 6.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 6.5 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 6.5 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 6.5 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 6.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 6.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 6.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 6.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 6.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 6.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 6.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 6.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 6.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 6.5 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 6.5 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 6.5 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192972",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192973",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "7",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 7. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme klassischen Mens-Größe 7 Black PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens-Größe 7 Black PVC Arbeitsstiefel",
            "meta_title": "Acme klassischen Mens-Größe 7 Black PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 7. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 7 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 7 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 7 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 7. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 7 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 7 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 7 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 7. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme classique Hommes Taille 7 Noir PVC Bottes de travail",
            "erp_name": "Acme classique Hommes Taille 7 Noir PVC Bottes de travail",
            "meta_title": "Acme classique Hommes Taille 7 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192973",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192974",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "7_5",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 7.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme klassischen Mens Größe 7.5 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens Größe 7.5 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassische Mens Größe 7.5 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 7.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 7.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 7.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 7.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 7.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 7.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 7.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 7.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 7.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 7.5 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 7.5 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 7.5 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192974",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192975",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "9w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme klassischen Mens Größe 9W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens Größe 9W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassische Mens Größe 9W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 9W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 9W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 9W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192975",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192976",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "9_5",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme klassischen Mens Größe 9.5 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens Größe 9.5 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassische Mens Größe 9.5 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 9.5 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 9.5 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 9.5 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192976",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192977",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "9_5w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9.5W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 9.5W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 9.5W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 9.5W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9.5W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 9.5W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 9.5W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 9.5W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192977",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192978",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "10",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme klassischen Mens-Größe 10 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens-Größe 10 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassischen Mens-Größe 10 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme classique Hommes Taille 10 Noir PVC Bottes de travail",
            "erp_name": "Acme classique Hommes Taille 10 Noir PVC Bottes de travail",
            "meta_title": "Acme classique Hommes Taille 10 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192978",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192979",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "10w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 10W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 10W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 10W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 10W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 10W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 10W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192979",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192980",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "10_5",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren-Größe 10.5 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren-Größe 10.5 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren-Größe 10.5 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10.5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 10.5 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 10.5 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 10.5 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192980",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192981",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "10_5w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10.5W geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 10.5W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 10.5W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 10.5W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 10.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 10.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 10.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 10.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 10.5W geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 10.5W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 10.5W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 10.5W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192981",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192982",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "11",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 11 Black PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 11 Black PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 11 Black PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme classique Hommes Taille 11 Noir PVC Bottes de travail",
            "erp_name": "Acme classique Hommes Taille 11 Noir PVC Bottes de travail",
            "meta_title": "Acme classique Hommes Taille 11 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192982",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192983",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "11w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 11W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 11W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 11W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 11W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 11W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 11W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192983",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192984",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "11_5",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11,5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme klassischen Mens-Größe 11.5 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens-Größe 11.5 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassischen Mens-Größe 11.5 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11,5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 11.5 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 11.5 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 11.5 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192984",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192985",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "11_5w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11.5W geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 11.5W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 11.5W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 11.5W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 11.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 11.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 11.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 11.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 11.5W geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 11,5 W en PVC noir Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 11,5 W en PVC noir Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 11,5 W en PVC noir Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192985",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192986",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "12",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 12. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme klassischen Mens-Größe 12 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens-Größe 12 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassischen Mens-Größe 12 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 12. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 12 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 12 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 12 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 12. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 12 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 12 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 12 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 12. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 12 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 12 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 12 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192986",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192987",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "12w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 12W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 12W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 12W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 12W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 12W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 12W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 12W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 12W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 12W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 12W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 12W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 12W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 12W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 12W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 12W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 12W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192987",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192988",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "13",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 13. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 13 Black PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 13 Black PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 13 Black PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 13. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 13 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 13 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 13 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 13. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 13 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 13 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 13 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 13. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 13 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 13 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 13 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192988",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1273192989",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "13w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 13W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 13W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 13W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 13W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 13W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 13W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 13W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 13W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 13W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 13W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 13W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 13W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 13W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 13W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 13W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 13W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1273192989",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1583536546-984",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "8",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme klassischen Mens-Größe 8 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens-Größe 8 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassischen Mens-Größe 8 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme classique Hommes Taille 8 Noir PVC Bottes de travail",
            "erp_name": "Acme classique Hommes Taille 8 Noir PVC Bottes de travail",
            "meta_title": "Acme classique Hommes Taille 8 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1583536546-984",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1583536559-986",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "8w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 8W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 8W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 8W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 8W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 8W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 8W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1583536559-986",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1583536564-987",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "9",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 9 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 9 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 9 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 9. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 9 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 9 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 9 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 9. Holen Sie sich diese schwere Gummistiefel heute!",
            "name": "Acme classique Hommes Taille 9 Noir PVC Bottes de travail",
            "erp_name": "Acme classique Hommes Taille 9 Noir PVC Bottes de travail",
            "meta_title": "Acme classique Hommes Taille 9 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1583536564-987",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1583536579-989",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        },
        {
          "categoryCode": "print_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "8_5w",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8.5W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Klassische Herren Größe 8.5W Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme Klassische Herren Größe 8.5W Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme Klassische Herren Größe 8.5W Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8.5W. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8.5W Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8.5W Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8.5W Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und geschützt mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8.5W. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 8.5W Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 8.5W Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 8.5W Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1583536579-989",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    },
    {
      "identifier": "1583536585-990",
      "categories": [
        {
          "categoryCode": "acme"
        },
        {
          "categoryCode": "erp_rubber_boots"
        },
        {
          "categoryCode": "master_clothing_footwear_footwear_rubber_boots"
        }
      ],
      "groups": [],
      "customAttributes": {
        "gender": "mens",
        "image_1": "7/9/0/2/7902e8b49d6c6248c9f6252950ef5b90a1edb504_Acme_Classic_Mens_Black_PVC_Work_Boots__1.jpg",
        "image_2": "f/a/a/8/faa80d027de06b2ca31da17a620d7eb6dd27a04a_Acme_Classic_Mens_Black_PVC_Work_Boots__2.jpg",
        "shoe_size": "8_5",
        "banner_image": "f/6/2/e/f62e44f094878a200e7acb970734ec54983a0aa2_Acme_Classic_Mens_Black_PVC_Work_Boots__3.png",
        "sole_material": "rubber",
        "upper_material": "pvc",
        "brand": "acme",
        "color": "black",
        "packshot": [
          "images_image_1_acme_classic_mens_black_pvc_work_boots_1_jpg_products",
          "images_image_2_acme_classic_mens_black_pvc_work_boots_2_jpg_products",
          "images_banner_image_acme_classic_mens_black_pvc_work_boots_3_png_products"
        ]
      },
      "localizations": [
        {
          "customAttributes": {
            "description": "<p itemprop = \" Beschreibung \">\nDas Universal-PVC Black Boot ist für den Betonbau, Landwirtschaft, Lebensmittelverarbeitung Stätten und mehr entwickelt. Diese 100% wasserdichte Stiefel haben eine nahtlose Konstruktion. Sie sind aus hochwertigem gemacht, lange PVC nachhaltig.\n</ p>\n\n<ul class = \" Liste \">\n<li class = \" list__item \"> Hergestellt aus hochwertigem, langlebige PVC </ li>\n<li class = „“ list__item „“> Hergestellt aus Spritzformen mit nahtloser Konstruktion und rutschfeste Sohle </ li>\n<li class = \" list__item \"> Entworfen für den Betonbau und mehr </ li>\n<li class = \" list__item \"> Kick-off Ansätze für die einfache Entfernung </ li>\n<li class = \" list__item \"> 100% wasserdicht </ li>\n\n</ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"description\">\nThe all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n</p>\n\n<ul class=\"list\">\n<li class=\"list__item\">Made of high-grade, long-lasting PVC</li>\n<li class=\"list__item\">Made from injection-molds with seamless construction and non-slip soles</li>\n<li class=\"list__item\">Designed for concrete construction and more</li>\n<li class=\"list__item\">Kick-off lugs for easy removal</li>\n<li class=\"list__item\">100% waterproof</li>\n\n</ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "description": "<p itemprop=\"\"description\"\">\n                        The all-purpose PVC Black Boots are specifically designed for concrete construction, agricultural, food processing venues and more. These 100% waterproof boots have seamless construction. They are made of high-grade, long lasting PVC.\n                    </p>\n\n                    <ul class=\"\"list\"\">\n                                <li class=\"\"list__item\"\">Made of high-grade, long-lasting PVC</li>\n                                <li class=\"\"list__item\"\">Made from injection-molds with seamless construction and non-slip soles</li>\n                                <li class=\"\"list__item\"\">Designed for concrete construction and more</li>\n                                <li class=\"\"list__item\"\">Kick-off lugs for easy removal</li>\n                                <li class=\"\"list__item\"\">100% waterproof</li>\n\n                    </ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "description": "<p itemprop = \" description \">\n            PVC Bottes noires sont tous __gVirt_NP_NN_NNPS<__ usage spécialement conçu pour la construction de béton, de l'agriculture, des lieux de transformation des aliments et plus. Ces 100% des bottes imperméables ont une construction sans couture. Ils sont faits de haute qualité, de longue durée en PVC.\n          </ p>\n\n          <ul class = \" liste \">\n                <Li class = \" list__item \"> Fait de haute qualité, PVC durable </ li>\n                <Li class = \" list__item \"> Fabriqué à partir de moules par injection à semelles de construction sans soudure et antidérapantes </ li>\n                <Li class = \" list__item \"> Conçu pour la construction en béton et plus </ li>\n                <Li class = \" list__item \"> pattes de lancement pour un retrait facile </ li>\n                <Li class = \" list__item \"> 100% imperméable à l'eau </ li>\n\n          </ ul>"
          },
          "channelCode": "ecommerce",
          "localeCode": "fr_FR"
        },
        {
          "customAttributes": {
            "meta_keywords": "Gummistiefel, Fußbekleidung, Acme, PVC, wasserdicht",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8,5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme klassischen Mens Größe 8.5 Schwarz PVC Arbeitsstiefel",
            "erp_name": "Acme klassischen Mens Größe 8.5 Schwarz PVC Arbeitsstiefel",
            "meta_title": "Acme klassische Mens Größe 8.5 Schwarz PVC Arbeitsstiefel - AkeneoIndustrial.com"
          },
          "localeCode": "de_DE"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_GB"
        },
        {
          "customAttributes": {
            "meta_keywords": "rubber boots,footwear,acme,pvc,waterproof",
            "meta_description": "Keep your feet dry and protected with these Acme Classic Mens Black PVC Work Boots in size 8.5. Get these heavy-duty rubber boots today!",
            "name": "Acme Classic Mens Size 8.5 Black PVC Work Boots",
            "erp_name": "Acme Classic Mens Size 8.5 Black PVC Work Boots",
            "meta_title": "Acme Classic Mens Size 8.5 Black PVC Work Boots - AkeneoIndustrial.com"
          },
          "localeCode": "en_US"
        },
        {
          "customAttributes": {
            "meta_keywords": "bottes en caoutchouc, chaussures, Acme, PVC, imperméable à l'eau",
            "meta_description": "Halten Sie Ihre Füße trocken und mit diesen Acme klassischen Mens-Schwarz PVC Arbeitsstiefel in Größe 8,5 geschützt. Holen Sie sich diesen schweren Gummistiefel heute!",
            "name": "Acme Classique Hommes Taille 8.5 Noir PVC Bottes de travail",
            "erp_name": "Acme Classique Hommes Taille 8.5 Noir PVC Bottes de travail",
            "meta_title": "Acme Classique Hommes Taille 8.5 Noir PVC Bottes de travail - AkeneoIndustrial.com"
          },
          "localeCode": "fr_FR"
        }
      ],
      "prices": [
        {
          "amount": "21.32",
          "currencyCode": "EUR"
        },
        {
          "amount": "18.11",
          "currencyCode": "GBP"
        },
        {
          "amount": "22.93",
          "currencyCode": "USD"
        }
      ],
      "code": "1583536585-990",
      "statusCode": true,
      "attributeSetCode": "rubber_boots",
      "parentCode": "Acme Classic Mens Black PVC Work Boots"
    }
  ]
}`

For more information please refer to this wiki [page](https://github.com/alumio-int/akeneo-shopify-templates/wiki/Fetching-Product-Data-from-Akeneo-to-Alumio).
