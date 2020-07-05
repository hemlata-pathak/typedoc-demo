[tsdoc-demo](../globals.md) › ["lib/average"](_lib_average_.md)

# Module: "lib/average"

## Index

### Functions

* [getAverage](_lib_average_.md#const-getaverage)

## Functions

### `Const` getAverage

▸ **getAverage**(`x`: number, `y`: number): *number*

*Defined in [lib/average.ts:49](https://github.com/hemlata-pathak/typedoc-demo/blob/fdf07e1/src/lib/average.ts#L49)*

The summary section should be brief. On a documentation web site,
it will be shown on a page that lists summaries for many different
API items.  On a detail page for a single item, the summary will be
shown followed by the remarks section (if any).

**`remarks`** 

The main documentation for an API item is separated into a brief
"summary" section optionally followed by an `@remarks` block containing
additional details.

Unlike the summary, the remarks block may contain lengthy documentation
content.  The remarks should not restate information from the summary,
since the summary section will always be displayed wherever the remarks
section appears.  Other sections (e.g. an `@example` block) if shown
will usually appear after the remarks section.

Code samples can be enclosed in a Markdown code fence:
```ts
function getAverage(x, y) {
  return (x + y) / 2.0;
}
```

If you use special symbols and don't want to use a code span, you can
escape them using backslashes:  \{\@inheritDoc Button.render\}

**`samplecustomblocktag`** 

You can define your own custom block tags and tell the parser about them.
The playground doesn't render this block, but your own tooling could do that.

**`privateremarks`** 

The `@privateRemarks` tag starts a block of additional commentary that is not meant
for an external audience.  A documentation tool must omit this content from an
API reference web site.  It should also be omitted when generating a normalized
*.d.ts file.

Modifiers look like block tags, but they do not start a documentation block.
For example this `@sealed` tag tells us that nobody should inherit from the
class.  But if text appeared after it, that text would get attached to the
previous block.

**`sealed`** 

**Parameters:**

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

**Returns:** *number*
