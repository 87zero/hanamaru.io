# hanamaru.io
Hanamaru site


To build:

git push hanamaru.io

## To deploy 
To deploy to inyokohama.com

```bash
jekyll build
rsync -arvhz _site/* stuartcw@inyokohama.com:/usr/home/stuartcw/public_html/hanamaru.io
```
## Github Pages

Note if you want to deploy to the non-domain Github pages you need to change the based url in _config.yml to /hanamaru.io

# TODO

* Move hanamauru.io on Github Pages. Test on hanamarukk.com first.
* Maybe get an official Line ID and use that as a telephone/chat contact.
* Refactor the company information out into a separate page not blog entry.
* Add Some blog posts.
* Change the business details.
