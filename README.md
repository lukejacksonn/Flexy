# Flexy

A CSS reset with some custom generic elements that can be used when prototyping and developing web sites or apps. A mostly structural library that takes advantage of `flexbox` and viewport units such as `vw`, `vh`, `vmin` and `vmax` to ease the pain of designing responsive layouts for various screen sizes and resolutions.

Here is a demo: http://codepen.io/lukejacksonn/pen/zvbPGb

### Disclaimer

Some of the practices and patterns used in this project are quite progressive. There are a few hard dependencies on certain css properties that not all browsers support (namely <IE10). Although fundamentally simple.. some of the techniques employed here require the developer to think a little differently about page layout than perhaps they might have traditionally. 

Flexbox is at the core of this library, it has been said not to depend on flexbox to layout a document but to use it as progressive enhancement. I agree with this statement but am a firm believer in the flexbox layout model as I think it offers much greater control over the arrangement and sizing of content in a document. Therefore I am willing to invest some time into figuring out how to get the most out of it and hopefully by the time something genuinely useful has been curated, then browsers will support the specification with enough consistency that we as developer/designers can rely on it with confidence.

- Browser Support (~95%): http://caniuse.com/#feat=flexbox

Viewport units are also taken advantage of quite heavily. The support for this property is a lot lower than flexbox but the negative implications if it is not supported is going to be mostly superficial and there are many workarounds/fallbacks.

- Browser Support (~80%): http://caniuse.com/#search=vw

## Introduction

As developers we tend to like putting things in boxes. We like to be explicit and have full control over _all_ the things. Unfortunately for us some things are out of our control, one of these things that makes life very difficult for developer/designers is the size of the users viewport. Gone are the days of `800x600` resolutions and static `960px` grids. It is time to let go.

To guarantee a good user experience on every viewport variation now takes a lot of working out!

- Using flexy as a basis of your project will help you lay out content whist sidestepping some of the common pitfalls of responsive design. Encouraging content to lay itself out allows you to concentrate on other aspects of development.

- To make sense of things in the flexbox world we break things down into containers and items, encourage the abstraction of structure from content and try to keep things generic as possible. Try make a little go a long way and stay dry.


#TODO

- Document Components `c-`, `i-`, `x-`, `xx-`, `y-`
- Create Demo Layouts `Mostly Fluid`, `Column Drop`, `Layout Shifter`, `Tiny Tweaks`



