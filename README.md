#XML pattern for class members rearrangement for Rider
___
>###Class member ordering
>+ Group class members in the following order:
>  + Nested classes, enums, delegates and events.
>  + Static, const and readonly fields.
>  + Fields and properties.
>  + Constructors and finalizers.
>  + Methods.
>+ Within each group, elements should be in the following order:
>  + Public.
>  + Internal.
>  + Protected internal.
>  + Protected.
>  + Private.
>> https://google.github.io/styleguide/csharp-style.html
___
##Configure
You can configure this using ```Preferences | Editor | Code Style | C# -> File Layout```