# Highcharts Bar Chart

This is an element for [weweb.io](https://www.weweb.io/).

## Installation

To run locally, first install all dependencies with `npm i`

## Start

To serve locally, run `npm run serve --port=[PORT]`, and then go to Weweb editor, open developper popup and add your custom element.

## Build

Before release, you can check build error by running `npm run build --name=highcharts-bar-chart`

## Changelog

### 0.1.7

- Add X and Y Axis max options
- Add Responsive Rules option

### 0.1.6

- Add title align and floating options

### 0.1.5

- Invert x and y axis

### 0.1.4

- Editable x-axis title
- Editable y-axis categories
- Allow using object UI to pick series' label and value keys

### 0.1.3

- Editable series label key and value key
- Editable x-axis categories
- Grouping in editor panel for better organization
- Editable y-axis title

### 0.1.2

- Editable series (chart data)

### 0.1.1

- Editable subtitle

### 0.1.0

- First version
- Support for basic editing of title

## Requirements

- Title
  - text ✔️
  - align ✔️
  - floating ✔️
  - margin
  - style
- xAxis
  - title ✔️
  - categories ✔️
  - max ✔️
  - allowDecimals
  - min
  - reversed
- yAxis
  - title ✔️
  - categories ✔️
  - max ✔️
  - allowDecimals
  - min
  - reversed
- Responsive
  - Bind code directly ✔️
- Series
  - Color
  - Border color / radius / width
  - Center in category
  - dataLabels
  - dataSorting
  - data as separate thing?
  - events?...
  - label?
  - opacity
- noData
- Loading
  - Weird. We have to call `chart.showLoading()` and `chart.hideLoading()` manually. Does weweb offer a way to do this from other events or something?
- Legend
  - align
  - backgroundColor
  - borderColor
  - borderRadius
  - borderWidth
  - floating
  - labelFormat
  - layout
  - title
  - verticalAlign
- Credits
  - enabled
- Colors array
- Chart
  - backgroundColor
  - borderColor
  - borderRadius
  - borderWidth
  - events?...
  - margin
  - plot?...
    - backgroundColor
    - borderColor
    - borderWidth
    - shadow
- Caption
- Tooltip
  - backgroundColor
  - borderColor
  - borderRadius
  - borderWidth
  - distance
  - enabled
- Drilldown
  - Should probably be flat code for now, as it is a complex feature (it basically adds another chart)
