# AW Business hours

Consists of two components
1.Timezone - Helps select the timezone
2.BusinesHours - Helps configure business hours

# Installation

npm install --save aw-business-hours

## Timezone Props

Prop  | Description | Type | Required/optional
----- |-------------| ---- |  -----------------
title | Title  | String | null | Required
description  | About Timezone | String | Required
timezone | List of timezones | Object  | Required
timezoneDefault | Timezone default value | String | Required
onChange | Updates selected timezone | Function | Required
timeZoneOptions(search) | Other customization options | Object | Optional



