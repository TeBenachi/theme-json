### WordPress theme.json

`"version": 1`

#### Presets 
Setting: color palettes, font sizes, or gradients 


#### Palette
    "color": {
          "palette": [
            {
              "name": "Magenta",
              "slug": "magenta",
              "color": "#ff00ff"
            },
            {
              "name": "Orange",
              "slug": "orange",
              "color": "#f5af19"
            }
          ]
        }

Inline style output

    --wp--preset--color--magenta
    --wp--preset--color--orange
    

#### theme.json

    {
        "version": 1,

        "settings": {

            "custom": true,
            "customDuotone": true,
            "customGradient": true,
            "link": true,

            "color": {
                "palette": [
                {
                    "name": "Magenta",
                    "slug": "magenta",
                    "color": "#ff00ff"
                },
                {
                    "name": "Orange",
                    "slug": "orange",
                    "color": "#f5af19"
                }
                ],
                "gradients": [
                    {
                        "name": "Magenta to orange",
                        "slug": "magenta-to-orange",
                        "gradient": "linear-gradient(135deg, var(--wp--preset--color--magenta), var(--wp--preset--color--orange))"
                    }
                ],
                "duotone": []
            },

            "layout": {
                "contentSize": "800px",
                "wideSize": "1000px"
            },

            "spacing": {
                "customMargin": false,
                "customPadding": false,
                "units": [ "px", "em", "rem", "vh", "vw" ]
            },

            "typography": {
          "customFontSize": true,
          "customLineHeight": false,
          "dropCap": true,
          "fontSizes": [
                    {
              "name": "Small",
              "size": "14px",
              "slug": "small"
            },
            {
              "name": "Normal",
              "size": "16px",
              "slug": "normal"
            },
            {
              "name": "Large",
              "size": "24px",
              "slug": "large"
            },
            {
              "name": "Huge",
              "size": "34px",
              "slug": "huge"
            }
                ]
        },

            "blocks": {
          "core/paragraph": {
            "color": {},
            "custom": {},
            "layout": {},
            "spacing": {},
            "typography": {}
          },
          "core/heading": {},
          "etc": {}
        }
        }
    }




    
#### Border
    "border": {
          "customColor": true,
          "customRadius": true,
          "customStyle": true,
          "customWidth": true
     }
     
#### Custom
    "custom": {
          "line-height": {
            "body": 1.7,
            "heading": 1.3
          }
        }
