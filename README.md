
# hassio-api-mod
This is a hassio api integration package for working in the [Moddable SDK](https://www.moddable.com/). This attempts to maintain the same interface we know from [Home Assistant](https://www.home-assistant.io/).

## Installation
`git clone https://github.com/juniper-garden/hassio-api-mod.git` or `git clone git@github.com:juniper-garden/hassio-api-mod.git`
`cd hassio-wifi-mod && yarn install`
`yarn build`

Copy the `/hassio-api-mod` folder into your moddable sdk project,
then add the improv-wifi-mod package to your projects manifest.json includes:

`"./hassio-api-mod/manifest.json"`

A full example is included as `example-manifest.json`

## Usage
Import the file and instantiate an instance of Hassio

i.e.

```
import Hassio from "hassio-api-mod";

let hassioController = new Hassio();

```

