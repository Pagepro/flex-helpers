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
* [helper--flex--left--top](#helper--flex--left--top--helper--inline-flex--left--top)
* [helper--flex--left--center](#helper--flex--left--center--helper--inline-flex--left--center)
* [helper--flex--left--bottom](#helper--flex--left--bottom--helper--inline-flex--left--bottom)
* [helper--flex--left--stretch](#helper--flex--left--stretch--helper--inline-flex--left--stretch)
* [helper--flex--left--space-between](#helper--flex--left--space-between--helper--inline-flex--left--space-between)
* [helper--flex--left--space-around](#helper--flex--left--space-around--helper--inline-flex--left--space-between)

#### - flex row with children horizontally centered:
* [helper--flex--center--top](#helper--flex--center--top--helper--inline-flex--center--top)
* [helper--flex--center--center](#helper--flex--center--center--helper--inline-flex--center--center)
* [helper--flex--center--bottom](#helper--flex--center--bottom--helper--inline-flex--center--bottom)
* [helper--flex--center--stretch](#helper--flex--center--stretch--helper--inline-flex--center--stretch)
* [helper--flex--center--space-between](#helper--flex--center--space-between--helper--inline-flex--center--space-between)
* [helper--flex--center--space-around](#helper--flex--center--space-around--helper--inline-flex--center--space-around)

#### - flex row with children positionned horizontally to right:
* [helper--flex--right--top](#helper--flex--right--top--helper--inline-flex--right--top)
* [helper--flex--right--center](#helper--flex--right--center--helper--inline-flex--right--center)
* [helper--flex--right--bottom](#helper--flex--right--bottom--helper--inline-flex--right--bottom)
* [helper--flex--right--stretch](#helper--flex--right--stretch--helper--inline-flex--right--stretch)
* [helper--flex--right--space-between](#helper--flex--right--space-between--helper--inline-flex--right--space-between)
* [helper--flex--right--space-around](#helper--flex--right--space-around--helper--inline-flex--right--space-around)

#### - flex row with children positionned horizontally space-between:
* [helper--flex--space-between--top](#helper--flex--space-between--top--helper--inline-flex--space-between--top)
* [helper--flex--space-between--center](#helper--flex--space-between--center--helper--inline-flex--space-between--center)
* [helper--flex--space-between--bottom](#helper--flex--space-between--bottom--helper--inline-flex--space-between--bottom)
* [helper--flex--space-between--stretch](#helper--flex--space-between--stretch--helper--inline-flex--space-between--stretch)
* [helper--flex--space-between--space-between](#helper--flex--space-between--space-between--helper--inline-flex--space-between--space-between)
* [helper--flex--space-between--space-around](#helper--flex--space-between--space-around--helper--inline-flex--space-between--space-around)

#### - flex row with children positionned horizontally space-around:
* [helper--flex--space-around--top](#helper--flex--space-around--top--helper--inline-flex--space-around--top)
* [helper--flex--space-around--center](#helper--flex--space-around--center--helper--inline-flex--space-around--center)
* [helper--flex--space-around--bottom](#helper--flex--space-around--bottom--helper--inline-flex--space-around--bottom)
* [helper--flex--space-around--stretch](#helper--flex--space-around--stretch--helper--inline-flex--space-around--stretch)
* [helper--flex--space-around--space-between](#helper--flex--space-around--space-between--helper--inline-flex--space-around--space-between)
* [helper--flex--space-around--space-around](#helper--flex--space-around--space-around--helper--inline-flex--space-around--space-around)

## Flex column
**Flex column helpers** allows to you position component's children in column

#### - flex column with children positionned vertically to top:
* [helper--flex--top--left](#helper--flex--top--left--helper--inline-flex--top--left)
* [helper--flex--top--center](#helper--flex--top--center--helper--inline-flex--top--center)
* [helper--flex--top--right](#helper--flex--top--right--helper--inline-flex--top--right)

#### - flex column with children vertically centered:
* [helper--flex--center--left](#helper--flex--center--left--helper--inline-flex--center--left)
* [helper--flex--center--center--column](#helper--flex--center--center--column--helper--inline-flex--center--center)
* [helper--flex--center--right](#helper--flex--center--right--helper--inline-flex--center--right)

#### - flex column with children positionned vertically to bottom:
* [helper--flex--bottom--left](#helper--flex--bottom--left--helper--inline-flex--bottom--left)
* [helper--flex--bottom--center](#helper--flex--bottom--center--helper--inline-flex--bottom--center)
* [helper--flex--bottom--right](#helper--flex--bottom--right--helper--inline-flex--bottom--right)

#### - flex column with children positionned vertically space-between:
* [helper--flex--space-between--left](#helper--flex--space-between--left--helper--inline-flex--space-between--left)
* [helper--flex--space-between--center--column](#helper--flex--space-between--center--column--helper--inline-flex--space-between--center)
* [helper--flex--space-between--right](#helper--flex--space-between--right--helper--inline-flex--space-between--right)

#### - flex column with children positionned vertically space-around:
* [helper--flex--space-around--left](#helper--flex--space-around--left--helper--inline-flex--space-around--left)
* [helper--flex--space-around--center--column](#helper--flex--space-around--center--column--helper--inline-flex--space-around--center--column)
* [helper--flex--space-around--right](#helper--flex--space-around--right--helper--inline-flex--space-around--right)

**Inline-flex row helpers** allows to you position component's children in row

#### - inline-flex row with children positionned horizontally to left:
* [helper--inline-flex--left--top](#helper--flex--left--top--helper--inline-flex--left--top)
* [helper--inline-flex--left--center](#helper--flex--left--center--helper--inline-flex--left--center)
* [helper--inline-flex--left--bottom](#helper--flex--left--bottom--helper--inline-flex--left--bottom)
* [helper--inline-flex--left--stretch](#helper--flex--left--stretch--helper--inline-flex--left--stretch)
* [helper--inline-flex--left--space-between](#helper--flex--left--space-between--helper--inline-flex--left--space-between)
* [helper--inline-flex--left--space-around](#helper--flex--left--space-around--helper--inline-flex--left--space-between)

#### - inline-flex row with children horizontally centered:
* [helper--inline-flex--center--top](#helper--flex--center--top--helper--inline-flex--center--top)
* [helper--inline-flex--center--center](#helper--flex--center--center--helper--inline-flex--center--center)
* [helper--inline-flex--center--bottom](#helper--flex--center--bottom--helper--inline-flex--center--bottom)
* [helper--inline-flex--center--stretch](#helper--flex--center--stretch--helper--inline-flex--center--stretch)
* [helper--inline-flex--center--space-between](#helper--flex--center--space-between--helper--inline-flex--center--space-between)
* [helper--inline-flex--center--space-around](#helper--flex--center--space-around--helper--inline-flex--center--space-around)

#### - inline-flex row with children positionned horizontally to right:
* [helper--inline-flex--right--top](#helper--flex--right--top--helper--inline-flex--right--top)
* [helper--inline-flex--right--center](#helper--flex--right--center--helper--inline-flex--right--center)
* [helper--inline-flex--right--bottom](#helper--flex--right--bottom--helper--inline-flex--right--bottom)
* [helper--inline-flex--right--stretch](#helper--flex--right--stretch--helper--inline-flex--right--stretch)
* [helper--inline-flex--right--space-between](#helper--flex--right--space-between--helper--inline-flex--right--space-between)
* [helper--inline-flex--right--space-around](#helper--flex--right--space-around--helper--inline-flex--right--space-around)

#### - inline-flex row with children positionned horizontally space-between:
* [helper--inline-flex--space-between--top](#helper--flex--space-between--top--helper--inline-flex--space-between--top)
* [helper--inline-flex--space-between--center](#helper--flex--space-between--center--helper--inline-flex--space-between--center)
* [helper--inline-flex--space-between--bottom](#helper--flex--space-between--bottom--helper--inline-flex--space-between--bottom)
* [helper--inline-flex--space-between--stretch](#helper--flex--space-between--stretch--helper--inline-flex--space-between--stretch)
* [helper--inline-flex--space-between--space-between](#helper--flex--space-between--space-between--helper--inline-flex--space-between--space-between)
* [helper--inline-flex--space-between--space-around](#helper--flex--space-between--space-around--helper--inline-flex--space-between--space-around)

#### - inline-flex row with children positionned horizontally space-around:
* [helper--inline-flex--space-around--top](#helper--flex--space-around--top--helper--inline-flex--space-around--top)
* [helper--inline-flex--space-around--center](#helper--flex--space-around--center--helper--inline-flex--space-around--center)
* [helper--inline-flex--space-around--bottom](#helper--flex--space-around--bottom--helper--inline-flex--space-around--bottom)
* [helper--inline-flex--space-around--stretch](#helper--flex--space-around--stretch--helper--inline-flex--space-around--stretch)
* [helper--inline-flex--space-around--space-between](#helper--flex--space-around--space-between--helper--inline-flex--space-around--space-between)
* [helper--inline-flex--space-around--space-around](#helper--flex--space-around--space-around--helper--inline-flex--space-around--space-around)

## Inline-flex column
**Inline-flex column helpers** allows to you position component's children in column

#### - inline-flex column with children positionned vertically to top:
* [helper--inline-flex--top--left](#helper--flex--top--left--helper--inline-flex--top--left)
* [helper--inline-flex--top--center](#helper--flex--top--center--helper--inline-flex--top--center)
* [helper--inline-flex--top--right](#helper--flex--top--right--helper--inline-flex--top--right)

#### - inline-flex column with children vertically centered:
* [helper--inline-flex--center--left](#helper--flex--center--left--helper--inline-flex--center--left)
* [helper--inline-flex--center--center--column](#helper--flex--center--center--column--helper--inline-flex--center--center)
* [helper--inline-flex--center--right](#helper--flex--center--right--helper--inline-flex--center--right)

#### - inline-flex column with children positionned vertically to bottom:
* [helper--inline-flex--bottom--left](#helper--flex--bottom--left--helper--inline-flex--bottom--left)
* [helper--inline-flex--bottom--center](#helper--flex--bottom--center--helper--inline-flex--bottom--center)
* [helper--inline-flex--bottom--right](#helper--flex--bottom--right--helper--inline-flex--bottom--right)

#### - inline-flex column with children positionned vertically space-between:
* [helper--inline-flex--space-between--left](#helper--flex--space-between--left--helper--inline-flex--space-between--left)
* [helper--inline-flex--space-between--center--column](#helper--flex--space-between--center--column--helper--inline-flex--space-between--center)
* [helper--inline-flex--space-between--right](#helper--flex--space-between--right--helper--inline-flex--space-between--right)

#### - inline-flex column with children positionned vertically space-around:
* [helper--inline-flex--space-around--left](#helper--flex--space-around--left--helper--inline-flex--space-around--left)
* [helper--inline-flex--space-around--center--column](#helper--flex--space-around--center--column--helper--inline-flex--space-around--center--column)
* [helper--inline-flex--space-around--right](#helper--flex--space-around--right--helper--inline-flex--space-around--right)


## Documentation


### helper--flex--left--top // helper--inline-flex--left--top
> Sets up component's children.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex--left--top.png "flex--left--top")

### helper--flex--left--center // helper--inline-flex--left--center
> Sets up component's children.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex--left--center.png "flex--left--center")

### helper--flex--left--bottom // helper--inline-flex--left--bottom
> Sets up component's children.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex--left--bottom.png "flex--left--bottom")

### helper--flex--left--stretch // helper--inline-flex--left--stretch
> Sets up component's children.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex--left--stretch.png "flex--left--stretch")

### helper--flex--left--space-between // helper--inline-flex--left--space-between
> Sets up component's children.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex--left--space-between.png "flex--left--space-between")

### helper--flex--left--space-around // helper--inline-flex--left--space-around
> Sets up component's children.

![alt text](https://raw.githubusercontent.com/Pagepro/flex-helpers/master/docs/flex--left--space-around.png "flex--left--space-around")
