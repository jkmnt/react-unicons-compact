# unicons-react-compact
Repacked [react-unicons](https://github.com/Iconscout/react-unicons) for minimum size and fast load

The original unicons-react have React components for each icon.
So you have >1000 distinct components with the same code and just the different art.

Your bundle size is huge. Even gzipped and minified, browser must interpret all this code at load, slowing down the initial page render.

My repacked edition exposes just the single component with icon name being the parameter.
The icon art lives in a dictionary keyed by icon name. So no code repeats anymore.

```ts

<Unicons name="pen"/>

```
## How to use it ?
Just drop `unicons.ts` in you project

## I need just a few icons, not the whole icon pack. Should I use your compacted edition ?
No. Use the original unicons-react
