# skip-nav

## Description

Various content areas such as navigation, search, or page content can be skipped by users of assistive technologies.

The skip-nav component should be included at the beginning of the page and contains the first focusable elements of the tab order.

-----------

## Requirements
- `Veams#5.0.0` 

-----------

## Installation

### Installation with Veams from local machine

`veams install bp absolute/filepath/to/skip-nav`

### Installation with Bower or Veams

When published on bower you can install the  by executing:

1. `veams install veams-component skip-nav`

-----------

## Fields

### `c-skip-nav`

#### Settings
- settings.skipNavClasses {`String`} - _Modifier classes for ._ 

#### Content
- content.title {`String`} - _Title, for semantics_
- content.main {`String`} - _only displayed if there is a main content block to skip to_
- content.skipLink {`Object[]`} - _Object contains every link_

- content.skipLink.href {`String`} - _href value of a link_
- content.skipLink.text {`String`} - _text of a link_

