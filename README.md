## Structure for the JSON configuration file


Use the keyword **{target}** to mark where you want the given keyword to appear

```
[
    {
        "category": "My category of dorks",
        "dorks": [
            {
                "label": "My dork name",
                "value": "Put the dork for {target} here"
            },
            {
                "label": "Another {target} dork name",
                "value": "another dork here {target}"
            }
        ]
    },
    {
        "category": "Another category",
        "dorks": [
            {
                "label": "My dork name",
                "value": [
                    "Put a dork here against {target}",
                    "{target} a second dork here",
                    "Put {target} dork here"
                ]
            },
            {
                "label": "My dork name",
                "value": [
                    "Put a {target} here"
                ]
            }
        ]
    }
]
```



*To start somewhere "dorks-sample.json" is available in source code.*
