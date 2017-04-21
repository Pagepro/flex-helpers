# FlexHelpers

**FlexHelpers** allows to you use flexbox on your site without know flex properties.

### Benefits
>* You can easily add flexbox display to contenets on your site.
* Easier positioning elements relative to each other.
* Faster adjusting the elements.
* No problems with setting margins. 


## Table of contents
>* [Requirements](#requirements)
* [Installation](#installation)
* [Features](#feature-set)
* [Documentation](#documentation)

## Requirements

1. Need to use SASS in your Project.

## Installation

1. Download flex-helpers from Github or using npm:

```shell
npm install flex-helpers
```
2. Add flex-helpers file to your sass files and compile project.

```css
@import "node_modules/flex-helpers/flex-helpers";
```

## Using helpers

When You want use helpers, You should include to your element style, one of helper features.

```
@include 'feature';
```

##### EXAMPLE:

```css
.content {
    @include helper--flex--left--center;
 }
```

# Feature Set

## Flex row
**Flex row helpers** allows to you position component's children in row

#### - flex row with children positionned horizontally to left:
* [helper--flex--left--top](#helper--flex--left--top)
* [helper--flex--left--center](#helper--flex--left--center)
* [helper--flex--left--bottom](#helper--flex--left--bottom)
* [helper--flex--left--stretch](#helper--flex--left--stretch)
* [helper--flex--left--space-between](#helper--flex--left--space-between)
* [helper--flex--left--space-around](#helper--flex--left--space-around)

#### - flex row with children horizontally centered:
* [helper--flex--center--top](#helper--flex--center--top)
* [helper--flex--center--center](#helper--flex--center--center)
* [helper--flex--center--bottom](#helper--flex--center--bottom)
* [helper--flex--center--stretch](#helper--flex--center--stretch)
* [helper--flex--center--space-between](#helper--flex--center--space-between)
* [helper--flex--center--space-around](#helper--flex--center--space-around)

#### - flex row with children positionned horizontally to right:
* [helper--flex--right--top](#helper--flex--right--top)
* [helper--flex--right--center](#helper--flex--right--center)
* [helper--flex--right--bottom](#helper--flex--right--bottom)
* [helper--flex--right--stretch](#helper--flex--right--stretch)
* [helper--flex--right--space-between](#helper--flex--right--space-between)
* [helper--flex--right--space-around](#helper--flex--right--space-around)

#### - flex row with children positionned horizontally space-between:
* [helper--flex--space-between--top](#helper--flex--space-between--top)
* [helper--flex--space-between--center](#helper--flex--space-between--center)
* [helper--flex--space-between--bottom](#helper--flex--space-between--bottom)
* [helper--flex--space-between--stretch](#helper--flex--space-between--stretch)
* [helper--flex--space-between--space-between](#helper--flex--space-between--space-between)
* [helper--flex--space-between--space-around](#helper--flex--space-between--space-around)

#### - flex row with children positionned horizontally space-around:
* [helper--flex--space-around--top](#helper--flex--space-around--top)
* [helper--flex--space-around--center](#helper--flex--space-around--center)
* [helper--flex--space-around--bottom](#helper--flex--space-around--bottom)
* [helper--flex--space-around--stretch](#helper--flex--space-around--stretch)
* [helper--flex--space-around--space-between](#helper--flex--space-around--space-between)
* [helper--flex--space-around--space-around](#helper--flex--space-around--space-around)

## Flex column
**Flex row helpers** allows to you position component's children in column

## Inline-flex row
**Inline-flex row helpers** allows to you position component's children in row

## Inline-flex column
**Inline-flex row helpers** allows to you position component's children in column

* [%helper--flex--center--top](#helper--flex--center--top)
* [%helper--flex--center--center](#helper--flex--center--center)
* [%helper--flex--center--bottom](#helper--flex--center--bottom)
* [%helper--flex--center--space-between](#helper--flex--center--space-between)
* [%helper--flex--space-between--top](#helper--flex--space-between--top)
* [%helper--flex--space-between--center](#helper--flex--space-between--center)
* [%helper--flex--space-between--bottom](#helper--flex--space-between--bottom)
* [%helper--flex--left--top](#helper--flex--left--top)
* [%helper--flex--left--center](#helper--flex--left--center)
* [%helper--flex--left--bottom](#helper--flex--left--bottom)
* [%helper--flex--right--center](#helper--flex--right--center)
* [%helper--flex--right--bottom](#helper--flex--right--bottom)
* [%helper--flex--stretch](#helper--flex--stretch)
* [%helper--flex--vertical-space-between](#%helper--flex--vertical-space-between)
* [%helper--list](#helper--list)
* [%helper--list--flex](#helper--list--flex)
* [%helper—-sec](#helper—-sec)


## Documentation


### %helper--flex--center--top
> Sets up the elements vertically top and horizontally center.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-center-top.PNG "flex-center-top")

### %helper--flex--center--center
> Sets up the elements vertically and horizontally center.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-center-center.PNG "flex-center-center")

### %helper--flex--center--bottom
> Sets up the elements vertically bottom and horizontally center.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-center-bottom.PNG "flex-center-bottom")

### %helper--flex--center--space-between
> Sets up the elements horizontally center with equal space between elements without space at content side.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-center-space-between.PNG "flex-center-space-between")

### %helper--flex--space-between--top
> Sets up the elements vertically top with equal space between elements without space at content side.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-space-between-top.PNG "flex-space-between-top")

### %helper--flex--space-between--center
> Sets up the elements vertically center with equal space between elements without space at content side.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-space-between-center.PNG "flex-space-between-center")

### %helper--flex--space-between--bottom
> Sets up the elements vertically bottom with equal space between elements without space at content side.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-space-between-bottom.PNG "flex-space-between-bottom")

### %helper--flex--left--top
> Sets up the elements vertically top and horizontally left.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-left-top.PNG "flex-left-top")

### %helper--flex--left--center
> Sets up the elements vertically center and horizontally left.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-left-center.PNG "flex-left-center")

### %helper--flex--left--bottom
> Sets up the elements vertically bottom and horizontally left.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-left-bottom.PNG "flex-left-bottom")

### %helper--flex--right--top
> Sets up the elements vertically bottom and horizontally right.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-right-top.PNG "flex-right-top")

### %helper--flex--right--center
> Sets up the elements vertically center and horizontally right.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-right-center.PNG "flex-right-center")

### %helper--flex--right--bottom
> Sets up the elements vertically bottom and horizontally right.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-right-bottom.PNG "flex-right-bottom")

### %helper--flex--stretch
> Sets up the elements which streatching to content box.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-stretch.PNG "flex-stretch")

### %helper--flex--vertical-space-between
> Sets up the elements with horizontally space between elements without space at content side.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex-vertical-space-between.PNG "flex-vertical-space-between")

### %helper--list--flex
> Reset margins and paddings, delete list-style type and sets up the list elements display flexy with auto margins.

### %helper—-sec
> Sets up the flexy display for the sections.
