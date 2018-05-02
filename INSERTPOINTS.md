## INSERTPOINTS

### Include: Page

``` hbs
{{! @INSERT :: START @id: skip-nav, @tag: component-partial }}
{{#with skip-nav.variations.default}}
	{{> skip-nav}}
{{/with}}
{{! @INSERT :: END }}
```