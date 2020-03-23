# AW Business hours

Consists of two components
1. Timezone - Helps select the timezone
2. BusinesHours - Helps configure business hours

# Installation

`npm install --save aw-business-hours`

## Timezone Props

Prop  | Description | Type | Required / optional
----- |-------------| ---- |  -----------------
title | Title  | `String` | Required
description  | About Timezone | `String` | Required
timezone | List of timezones | `Object`  | Required
timezoneDefault | Default timezone value | `String` | Required
onChange | Updates selected timezone | `Function` | Required

## Business hours props

Prop  | Description | Type | Required / optional
----- |-------------| ---- |  -----------------
title | Title  | `String` | Required
description  | About Timezone | `String` | Required
selectedType | Type of working hours selected | `String`  | Required
updateSelectedType | Update selected working hours | `Function`  | Required
workingHours | Days and time configuration  | `Object` | Required
updateWorkingDays |  Update selected working days | `Function` | Required
showTimePicker | Initially Hide/show business hours configuration | `Boolean` | Required
toggleBusinessHrsView | Toggle business hours configuration view | `Function` | Required
onHoursChange | update selected time | `Function` | Required
validate | validate selected time | `Function` | Required
onApplyAll | Apply configuration of first day to all days | `Function` | Required
options - multipleTimerange| Add multiple shifts | `Object` | Optional
onAdd | Action on click of add | `Function` | Optional
onDelete | Action on click of delete | `Function` | Optional
onAppointment | Action on click of appointment | `Function` | Optional

# Set up instructions

```
git clone https://github.com/Adaptavant/frontoffice-commons.git
cd packages/aw-business-hours
npm install
npm start
```
Open http://localhost:8880/







