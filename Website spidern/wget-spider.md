# wget spider

Ruft alle über eine Sitemap erreichbaren Seiten einer Website auf.

    wget --quiet https://domain.de/sitemap --output-document - | egrep -o "http://domain\.de[^<]+" | wget --spider -i - --wait 1

## Installation wget

    $ brew install wget

## Quelle

Quelle: http://www.wezm.net/technical/2009/05/spider-a-site-with-wget-using-sitemap-xml/
