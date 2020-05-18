---
title: Covid-19 Data Visualization Tracker
subtitle: Tracking data visualizations from around globe during the Covid-19 pandemic
layout: layouts/base.njk
---


## This site is a starting point


## Post pages

The pages found in in the posts

## <ul class="listing">
## {%- for page in collections.post -%}
## <li>
##    <a href="{{ page.url }}">{{ page.data.title }}</a> -
##   <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
##  </li>
##{%- endfor -%}
## </ul>

## Links from an external data source

TTracking Covid-19 Data Visualizations here:

All visualizations:

- John's Hopkins Global: (<a href="https://coronavirus.jhu.edu/map.html"</a>)
- John's Hopkins US: (<a href="https://coronavirus.jhu.edu/us-map"</a>)
- Facebook Data for Good Mobility Data: (<a href="https://visualization.covid19mobility.org/?date=2020-05-13&dates=2020-04-08_2020-05-13"</a>)
- RT.Live (<a href="https://rt.live/"</a>)
- Economist:(<a href="https://www.economist.com/graphic-detail/2020/04/17/coronavirus-infections-have-peaked-in-much-of-the-rich-world"</a>)
- Wordometer:(<a href="https://www.worldometers.info/coronavirus/)
- Independent Covid-19 Tracker: (<a href="https://trackthevirus.info/"</a>)
- Naccho: (<a href="https://covid19-naccho.hub.arcgis.com/"</a>)
- WHO: (<a href="https://covid19.who.int/"</a>)
- Nextstrain: (<a href="https://nextstrain.org/ncov/asia"</a>)
- Singapore Contact Tracing: (<a href="https://public.tableau.com/profile/aimpoint.digital#!/vizhome/AimpointSingaporeCOVID-19NetworkAnalysis/StaticNetworkGraph"</a>)


## <ul class="listing">
##{%- for item in hawksworx.entries.slice(0,5) -%}
##  <li>
##    <a href="{{ item.link }}">{{ item.title }}</a>
##  </li>
##{%- endfor -%}
##</ul>


## Prerequisite

- [Node and NPM](https://nodejs.org/)

## Running locally

```bash
# install the dependencies
npm install

# External data sources can be stashed locally
npm run seed

# It will then be available locally for building with
npm run start
```

## Add some Netlify helpers
Netlify Dev adds the ability to use Netlify redirects, proxies, and serverless functions.

```bash
# install the Netlify CLI in order to get Netlify Dev
npm install -g netlify-cli

# run a local server with some added Netlify sugar in front of Eleventy
netlify dev
```

##A serverless functions pipeline is included via Netlify Dev. By running `netlify dev` you'll be able to execute any of your serverless functions directly like this:

- [/.netlify/functions/hello](/.netlify/functions/hello)
- [/.netlify/functions/fetch-joke](/.netlify/functions/fetch-joke)

### Redirects and proxies

## Netlify's Redirects API can provide friendlier URLs as proxies to these URLs.

- [/api/hello](/api/hello)
- [/api/fetch-joke](/api/fetch-joke)




