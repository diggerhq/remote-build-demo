# A demo app to showcase Digger Remote Build

Simple Laravel app forked from [travellist-laravel-demo](https://github.com/do-community/travellist-laravel-demo)

## Problem

Docker builds take long on unstable connections due to large image size

## Solution
Digger supports remote Docker build and push! Only your code is transmitted over the network, everything else happens in ultra-fast Amazon data centers.

```
dg env build <myenv> --remote
```

```
dg env push <myenv> --remote
```

## Learn more

Get scalable infrastructure in one click – with Digger your team can fully focus on the product, and you still get all the benefits of AWS / GCP such as free credits.

[learn.digger.dev](https://learn.digger.dev) 
