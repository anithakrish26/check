# AW Business hours

Consists of two components
1. Timezone - Helps select the timezone
2. BusinesHours - Helps configure business hours

# Installation

`npm install --save aw-business-hours`

## Timezone Props

Prop  | Description | Type | Required/optional
----- |-------------| ---- |  -----------------
title | Title  | `String` | `Required`
description  | About Timezone | `String` | Required
timezone | List of timezones | `Object`  | Required
timezoneDefault | Default timezone value | `String` | Required
onChange | Updates selected timezone | `Function` | Required

## Business hours props

Prop  | Description | Type | Required/optional
----- |-------------| ---- |  -----------------
title | Title  | `String` | `Required`
description  | About Timezone | `String` | Required
selectedType | Type of working hours selected | `String`  | Required
updateSelectedType | Update selected working hours | `Function`  | Required
workingHours | Days and time configuration  | `Object` | Required
updateWorkingDays |  Update selected working days | `Function` | Required
showTimePicker | Initially Hide/show business hours configuration | `Boolean` | required
toggleBusinessHrsView | Toggle business hours configuration view | `Function` | required
onHoursChange | update selected time | `Function` | required
validate | validate selected time | `Function` | required
onApplyAll | Apply configuration of first day to all days | `Function` | required
options - multipleTimerange| Add multiple shifts | `Object` | optional
onAdd | Action on click of add | `Function` | optional
onDelete | Action on click of delete | `Function` | optional
onAppointment | Action on click of appointment | `Function` | optional







