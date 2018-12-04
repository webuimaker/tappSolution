This is the HUGO code for the www.tappsolutions.com

This README file will contain instructions for each anticipated maintenance that we will do to the site.

### Google Analytics

You can optionally enable Google Analytics. Type your tracking code in the ``.

```toml
googleAnalytics = "UA-XXXXX-X"
```

### Contact form
To enable the form in the contact page, just type your Formspree email in the `config.toml` file.

```yaml
[params]
email = "your@email.com"
```

### Menu

You can also define the menu items that will appear in the top bar. Edit the `[[params.menu]]` entries to create your menu.

```toml
[[params.menu]]
     name = "About us"
    url = "/about/"
    weight = 2
    identifier = "about"
```
The `weight` parameter will determine the order of the menu entries.

### Footer Menu

You can also define the menu items that will appear in the top bar. Edit the `[[params.footernav]]` entries to create your menu.

```toml
[[params.footernav]]
    name = "Privacy Policy"
    url = "/#/"
    weight = 7
```
The `weight` parameter will determine the order of the menu entries.

### Socaial Media  

You can also define the menu items that will appear in the top bar. Edit the `[[params.footersocial]]` entries to create your menu.

```toml
[[params.footersocial]]
    identifier = "twitter"
    pre = "<i class='fa fa-twitter'></i>"
    url = "#"
    weight = 1
```
The `weight` parameter will determine the order of the menu entries.


### Landing page

The landing page consists in many sections that can be activated and configured individually. Let's go through all sections from top to bottom.

#### about

The about content is configured in the config.

```
[params.about]
    enable = true
    title = "<span>About</span> Tapp Solutions"
    subtitle = "<p>Tapp Solutions helps Life and P&C companies automate Sales, Claims and Inspections using Mobile Apps. Using our custom mobile applications, Insurance companies can sell higher quality policies faster,  collect payments anywhere, and complete more inspections with less work.</p>"
    buttonText = "learn more"
    buttonUrl = "#"
```

#### schedule

The schedule content is configured in the config.

```
[params.schedule]
    enable = true
    title = "Want to increase your sales with E-app?"
    subtitle = "On Mobile And Desktop"
    buttonText = "Schedule a phone call or demo"
    buttonUrl = "#"
```


#### freeTrial

The freeTrial content is configured in the config.

```
[params.freeTrial]
    enable = true
    buttonText = "Free Trial of Apps"
    buttonUrl = "#"
```

#### Banner

The banner content is configured in the data directory.

```
data
└── banner
    ├── 1.yaml
    ├── 2.yaml
```

#### services

The services content is configured in the data directory.

```
data
└── services
    ├── 1.yaml
    ├── 2.yaml
```


#### clients

The clients content is configured in the data directory.

```
data
└── clients.json
```

#### reviews

The clients content is configured in the data directory.

```
data
└── reviews.json
```


#### team

The team content is configured in the data directory.

```
data
└── team.json
```