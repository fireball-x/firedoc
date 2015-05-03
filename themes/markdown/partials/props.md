
`{{name}}`: `{{#crossLink type}}{{/crossLink}}`

{{#if overwritten_from}}
> Inherited from {{overwritten_from/class}} {{#if foundAt}}but overwritten in{{/if}} `{{{file}}}:{{{line}}}`
{{else}}
{{#if extended_from}}
> Inherited from `{{extended_from}}`
{{/if}}
Defined in `{{{file}}}:{{{line}}}`
{{/if}}

{{#if deprecationMessage}}
**Deprecated**: {{deprecationMessage}}
{{/if}}

{{#if since}}
Available since {{since}}
{{/if}}

---------------------

{{{propertyDescription}}}

{{#if default}}
**Default**: {{default}}
{{/if}}

{{#example}}
##### Examples

{{{.}}}
{{/example}}

{{#if subprops}}

##### Sub Properties

{{#subprops}}
- {{name}} `{{#crossLink type}}{{/crossLink}}` {{description}}
{{/subprops}}

{{/if}}