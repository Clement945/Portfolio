# &#128512; Portfolio

Application web : Portfolio Clément Arki
## Html (bout de code) :
``` html

<!DOCTYPE html>
<html lang="fr" dir="ltr">
    <head>
    <meta charset="UTF-8">
    <meta name="description" content="Portfolio Clément Arki">
    <meta name="viewport" content="width-device-width, initial-scale=1.0">
    <title>Portfolio Clément Arki</title>
    <!--<link rel="icon" type="image/png" href=""/>-->
    <link rel="apple-touch-icon" sizes="180x180" href="./favicon/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon/favicon-16x16.png">
    <link rel="icon" type="image/ico"  href="favicon/favicon.ico">
    <link rel="manifest" href="./favicon/site.webmanifest">
    <link rel="stylesheet" type="text/css" href="./css/style.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet"/>
</head>

<body>

</body>

</html>
```
## Css (bout de code) :

``` css

@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400&family=Open+Sans:wght@300;400;500&display=swap');

html{
    font-size: 62.5%;
}

body{
    font: 1.6rem 'Nunito', sans-serif;
    margin: 0;
}



*{
    box-sizing: border-box;
}

h1,h2,h3,p,figure,ol,ul{
    margin: 0;
    padding: 0;
    list-style-type: none;
}

h1,h2,h3{
    font-weight: normal;
}

a{
    text-decoration: none;
    color: #000;
}

/*thème*/

:root{
    --color-primary: #1d1d1d;
    --color-secondary: #2b5797;
    --color-trois: #FFFFFF;
    --color-quatre: #DC143C;
    --color-cinq: #A9A9A9;
    --color-six: rgb(240, 232, 232);
}

header h1{
    line-height: 8.5rem;
    text-align: center;
    color: var(--color-trois);
    
}
main, footer{
    max-width: 80rem;
    margin: 0 auto 3rem;
    line-height: 3rem;
}

```

## Compostion du répertoire
* index.html
* css/style.css
* asset/
* js/
* favicon/