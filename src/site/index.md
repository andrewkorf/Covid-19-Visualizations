---
title: Covid-19 Data Vix Tracker
subtitle: Tracking data visualizations from around globe during the Covid-19 pandemic
layout: layouts/base.njk
---



## Links from an external data source

Tracking Covid-19 Data Visualizations here:

<p>
All visualizations:
<ul>
<li>- John's Hopkins Global: (<a href="https://coronavirus.jhu.edu/map.html">https://coronavirus.jhu.edu/map.html</a>)
<li>- John's Hopkins US: (<a href="https://coronavirus.jhu.edu/us-map">https://coronavirus.jhu.edu/us-map</a>)
<li>- Facebook Data for Good Mobility Data: (<a href="https://coronavirus.jhu.edu/us-map">https://coronavirus.jhu.edu/us-map</a>)
<li>- RT.Live (<a href="https://rt.live/">https://rt.live/</a>)
<li>- Economist:(<a href="https://www.economist.com/graphic-detail/2020/04/17/coronavirus-infections-have-peaked-in-much-of-the-rich-world">https://www.economist.com/graphic-detail/2020/04/17/coronavirus-infections-have-peaked-in-much-of-the-rich-world</a>)
<li>- Wordometer:(<a href="https://www.worldometers.info/coronavirus/">https://www.worldometers.info/coronavirus/</a>)
<li>- Independent Covid-19 Tracker: (<a href="https://trackthevirus.info/">ttps://trackthevirus.info/</a>)
<li>- Naccho: (<a href="https://covid19-naccho.hub.arcgis.com/">ttps://covid19-naccho.hub.arcgis.com/</a>)
<li>- WHO: (<a href="https://covid19.who.int/">Https://covid19.who.int/</a>)
<li>- Nextstrain: (<a href="https://nextstrain.org/ncov/asia">https://nextstrain.org/ncov/asia</a>)
<li>- Singapore Contact Tracing: (<a href="https://public.tableau.com/profile/aimpoint.digital#!/vizhome/AimpointSingaporeCOVID-19NetworkAnalysis/StaticNetworkGraph">https://public.tableau.com/profile/aimpoint.digital#!/vizhome/AimpointSingaporeCOVID-19NetworkAnalysis/StaticNetworkGraph</a>)
</ul>
</p>


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




