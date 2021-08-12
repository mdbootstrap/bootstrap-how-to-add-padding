# How to add padding in Bootstrap?

Bootstrap includes a wide range of shorthand responsive padding utility classes to modify an element’s appearance.

**Example**: Usage `pe-*` class.

`p` - for classes that set padding

`e` - for classes that set `padding-end` (right side)

If you want to set a padding on the left side use `.ps-*` classes (`s` stands for "start")

## Detailed explanation

Spacing utilities that apply to all breakpoints, from `xs` to `xxl`, have no breakpoint abbreviation in them. This is because those classes are applied from `min-width: 0` and up, and thus are not bound by a media query. The remaining breakpoints, however, do include a breakpoint abbreviation.

The classes are named using the format `{property}{sides}-{size}` for `xs` and `{property}{sides}-{breakpoint}-{size}` for `sm, md, lg, xl, and xxl`.

Where property is one of:

* `m` - for classes that set `margin`
* `p` - for classes that set `padding`

#### Much more examples and a detailed description can be found at [📄 Documentation page](https://mdbootstrap.com/how-to/bootstrap/padding-add/)
