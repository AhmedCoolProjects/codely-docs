---
sidebar_position: 1
---

:::info Introduction
Clear script for locking player vehicles, optimized on server & client side + many more features
:::

## Get it now!

```mdx-code-block
<div
style={{
    display: "flex",
    alignItems: "center",
    justifyContent: "center",
    flexDirection: "row"
}}
>

<a style={{
    display: "flex",
    alignItems: "center",
    justifyContent: "center",
    flexDirection: "column",
    margin: "0 12px"
}} href="https://forum.cfx.re/t/free-sqz-carkeys/4781174" target="_blank"> <img src="/img/fivem.png" alt="FIVEM ICON" style={{
    width: 60,
    height: 60,
    borderRadius: 30,
}} />FiveM Post</a>

<a style={{
    display: "flex",
    alignItems: "center",
    justifyContent: "center",
    flexDirection: "column",
    margin: "0 12px"
}} href="https://github.com/csquizer/sqz\_carkeys" target="_blank"> <img src="/img/github.png" alt="GITHUB ICON" style={{
    width: 60,
    height: 60,
    borderRadius: 30,
}} />GitHub</a>



</div>


```

## Features

* Lock personaly/society owned vehicles
* Give vehicle keys to other players
* Reset vehicle keys at Locksmith (place on the map)
* Give temporarily keys of vehicle
* Optimized client & server side

## Instalation

* Drop the script into your resources folder and start it in your `server.cfg`
* Run the sql.sql file
* For optional export ussage, take a look bellow

## Controls

* /givekeys - Give keys to a player
* /lockvehicle or J - Lock closest vehicle

### Exports

* Server side
  * `exports['sqz_carkeys']:resetPlate(plate)` - Resets a vehicle plate's cache
  * `exports['sqz_carkeys']:giveTempKeys(plate, identifier, timeout)` - Adds temporarily keys to a player (until the server), timeout is an optional param, time in ms until the key is reset