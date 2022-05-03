# beerApp

React Native app about beer

## Overview

A mixture of different info & tools for those that enjoy a good beer. However the real purpose is to improve React Native and other tech stack skills.

- Brewing Recipes - List of brewing recipes via Punk API
- Print Brewing Recipies
- Edit and Add new recipes (localy)
- Save own Recipes locally
- Meetups - Find local microwbreweries via Meetup API
- Pints Earned - Movement converted to energy expressed as an average pint of beer
- Drinking games - eg. 2048 as beer brand labels, make your own beer brand, get back from the pub maze game
- Theme change : light/dark

> Apps that exist now
>
> Brewfather app: features Planning, brewing, fermenting cycle. Whats an MVP of this?
>
> Brewee app: breweries / craft beer locator: Make mine British focused
>
> Untappd app: Discover and share beers, breweries: beer ratings, reviews,likes etc : Very high number of downloads!: Make mine British focused

### Node Server / Firebase or other (future)

- Store Data in dB so can share
  - New and edited beer recipes (consider as a git structure, aka can fork, clone etc a recipe)
  - share game scores
- Have own Restful API for beer recipes
- Have own GraphQL API for beer recipes
- Have own API for local craft beer bars (that I construct)
- login (optional) : for more info ie emails, notifications
- Notifications served - eg new beer recipies
- Emails - bi-monthly very brief latest info

## Tech Stack

- API's : Restful, graphQL
- React : useState, useEffect, useRef, Context, useMemo, useCallback, Redux
- React Native
  - React Navigation, WebView, SafeAreaView, Text, Pushable, FlatList, SectionList
  - react-native-safe-area-context, react-native-webview
  - React Native- Paper - components following Material Design guidelines
  - react-native-sensors - to estimate movement aka energy used
- Node : date-fns
- TDD: Jest, React Native Testing library
- TypeScript

All in stages and multiple versions
