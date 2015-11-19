#FlexHelpers

**FlexHelpers** allows to you use flexbox on our site without know flex properties.

###Benefits
>* You can easily add flexbox display to contenets on your site.
* Easier positioning elements relative to each other.
* Faster adjusting the elements.
* No problems with setting margins. 


## Table of contents
>* [Requirements](#Requirements)
* [Installation](#Instalation)
* [Features](#Features)
* [Documentation](#Documentation)

## Requirements

1. Need to use SASS in your Project.

##Installation

Installation is very basic. One thing you need to do is add file flex-helpers to your sass files and compile project.


##Using helpers

When You want use helpers, You should extend to your element style, one of helper features.

```
@extend 'feature';
```

>#####EXAMPLE:

```
.content {	@extend %helper--flex-center-top;
}
```

## Feature Set
* [%helper--flex--center--top](#%helper--flex--center--top)
* [%helper--flex--center--center](#helper--flex--center--center)
* [%helper--flex--center--bottom](#%helper--flex--center--bottom)
* [%helper--flex--center--space-between](#%helper--flex--center--space-between)
* [%helper--flex--space-between--top](#%helper--flex--space-between--top)
* [%helper--flex--space-between--center](#%helper--flex--space-between--center)
* [%helper--flex--space-between--bottom](#%helper--flex--space-between--bottom)
* [%helper--flex--left--top](#%helper--flex--left--top)
* [%helper--flex--left--center](#%helper--flex--left--center)
* [%helper--flex--left--bottom](#%helper--flex--left--bottom)
* [%helper--flex--right--center](#%helper--flex--right--center)
* [%helper--flex--right--bottom](#%helper--flex--right--bottom)
* [%helper--flex--stretch](#%helper--flex--stretch)
* [%helper--flex--vertical-space-between](#%helper--flex--vertical-space-between)
* [%helper--list](#%helper--list)
* [%helper--list--flex](#%helper--list--flex)
* [%helper—-sec](#%helper—-sec)


## Documentation


### %helper--flex--center--top
> Sets up the elements vertically top and horizontally center.

### %helper--flex--center--center
> Sets up the elements vertically and horizontally center.

### %helper--flex--center--bottom
> Sets up the elements vertically bottom and horizontally center.

### %helper--flex--center--space-between
> Sets up the elements horizontally center with equal space between elements without space at content side.

### %helper--flex--space-between--top
> Sets up the elements vertically top with equal space between elements without space at content side.

### %helper--flex--space-between--center
> Sets up the elements vertically center with equal space between elements without space at content side.

### %helper--flex--space-between--bottom
> Sets up the elements vertically bottom with equal space between elements without space at content side.

### %helper--flex--left--top
> Sets up the elements vertically top and horizontally left.

### %helper--flex--left--center
> Sets up the elements vertically center and horizontally left.

### %helper--flex--left--bottom
> Sets up the elements vertically bottom and horizontally left.

### %helper--flex--right--top
> Sets up the elements vertically bottom and horizontally right.

### %helper--flex--right--center
> Sets up the elements vertically center and horizontally right.

### %helper--flex--right--bottom
> Sets up the elements vertically bottom and horizontally right.

### %helper--flex--stretch
> Sets up the elements which streatching to content box.

### %helper--flex--vertical-space-between
> Sets up the elements with horizontally space between elements without space at content side.

### %helper--list--flex
> Reset margins and paddings, delete list-style type and sets up the list elements display flexy with auto margins.

### %helper—-sec
> Sets up the flexy display for the sections.