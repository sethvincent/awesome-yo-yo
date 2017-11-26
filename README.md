# awesome-yo-yo
Modules &amp; resources related to the [yo-yo](https://github.com/maxogden/yo-yo) module.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Contents

- [About](#about)
- [Projects using yo-yo](#projects-using-yo-yo)
- [Dependencies](#dependencies)
- [Frameworks](#frameworks)
- [Components](#components)
- [Resources](#resources)
- [Related awesome lists](#related-awesome-lists)

## About

A tiny library for building modular UI components using [DOM diffing](#morphdom) and [ES6 tagged template literals](#tagged-template-literals), powered by [bel](https://www.npmjs.com/package/bel) and [morphdom](https://www.npmjs.com/package/morphdom) and based on the "yo-yo" data binding pattern: data down, actions up. 

## Projects using yo-yo

- [adventuretron](https://github.com/adventuretron/adventuretron) - Create self-guided workshops using electron
- [dat.land](https://github.com/datproject/dat.land) - The hosted web application for [dat](https://github.com/datproject/dat)
- [enviar](https://github.com/timwis/enviar) - Chat interface for SMS / text messages.
- [minidocs](https://github.com/freeman-lab/minidocs) - Build a minimalist site for your documentation
- [uppy](https://github.com/transloadit/uppy) - The next open source file uploader for web browsers.

## Dependencies

- [bel](https://github.com/shama/bel) - Create composable DOM elements using template strings.
- [hyperx](https://github.com/substack/hyperx) - Convert template strings to library backends.
- [morphdom](https://github.com/patrick-steele-idem/morphdom) - Fast and lightweight DOM diffing/patching (without the virtual part).

## Frameworks

Frameworks / libraries that use yo-yo.

- [choo](https://github.com/yoshuawuyts/choo)
- [inu](https://github.com/ahdinosaur/inu)

## Components

UI components & related modules that are compatible with yo-yo. Many modules that are built with bel and choo as dependencies that create DOM nodes should be compatible with yo-yo (they all ultimately have bel as a dependency).

- [base-elements](https://github.com/yoshuawuyts/base-elements) – A selection of configurable native DOM UI elements.
- [beldown](https://github.com/sethvincent/beldown) - Turn markdown into DOM nodes using tagged template strings.
- [bel-video-element](https://github.com/fraserxu/bel-video-element) - A simple video element with bel.
- [choo-chartist](https://www.npmjs.com/package/choo-chartist) - A wrapper for using [Chartist](https://github.com/gionkunz/chartist-js).
- [dom-notifications](https://github.com/finnp/dom-notifications) - Atom-inspired notifications component.
- [element-wrapper](https://github.com/fraserxu/element-wrapper) - A simple and safe way to set innerHTML for yo-yo or bel component.
- [interactive-sandbox](https://github.com/sethvincent/interactive-sandbox) - Create editable, interactive code examples for the browser that bundle dependencies from npm.
- [modal-element](https://github.com/shama/modal-element) - A basic modal DOM element.
- [yo-fs](https://github.com/karissa/yo-fs) - A client-side modular stream-friendly ui browser widget for navigating directories.
- [yo-yo-autogrow](https://github.com/tgfjt/yo-yo-autogrow) - textarea component via yo-yo, automatically adjust height.

## Build tools
- [yo-yoify](https://github.com/shama/yo-yoify) - Transform yo-yo or bel template strings into pure and fast document calls.
- [babel-plugin-yo-yoify](https://github.com/goto-bus-stop/babel-plugin-yo-yoify) - The same, but as a Babel plugin.

## Resources
- :movie_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
- :book: [Introduction to yo-yo.js](https://writingjavascript.org/posts/introduction-to-yo-yo-js)

## Related awesome lists

- [awesome-choo](https://github.com/YerkoPalma/awesome-choo)

## License

[CC0 v1](LICENSE)
