# Changelog

## WIP

### Added

- Add sub groups center left/right to navbar component
- Add box-shadow-hover to utility component
- Add height option to Height Viewport component

### Changed
- Less no longer uses component attribute selectors

### Removed
- Removed uk-cover CSS only solution

### Fixed

- Fix icon 'play-circle'
- Fix spinner when 'stroke-width' cannot be read
- Fix memory leak in SVG component
- Prevent transition-toggle from setting a transition
- Fix width-expand not wrapping into next row in rare cases
- Allow a fixed width on on nested grids with grid-match

## 3.0.0 beta 6 (January 24, 2017)

### Added

- Toggable triggers 'shown'/'hidden' events, when animations complete

### Fixed

- Fix component initialization
- Fix card component extending inverse
- Fix background-fixed for Firefox and IE

## 3.0.0 beta 5 (January 18, 2017)

### Changed

- UIkit observes body tag too now
- Performance improvements

### Fixed

- Fix regression with initialization (IE + Edge)
- Fix beta 2 regression for Svg’s (Safari)
- Fix Sticky width after resize
- Fix page width on resizing Offcanvas
- Fix props initialization for data-uk- components
- Fix sortable children loosing event bindings after sort

## 3.0.0 beta 4 (January 18, 2017)

### Fixed

- Fix Scrollspy Nav within Sticky (Safari)
- Fix beta 3 regression for Accordion
- Fix lazy initialized components

## 3.0.0 beta 3 (January 17, 2017)

### Added

- Add support for 'data-uk-' prefixed component attributes
- Add support for Primary Arguments in components
- Add support for Functional Components
- Components reinitialize on added/removed children

### Fixed

- Fix sortable behaviour
- Fix link muted and link reset

## 3.0.0 beta 2 (January 11, 2017)

### Added

- Enable deferred loading of UIkit

### Changed

- Improve relative path to icons.svg

### Fixed

- Fix Icon component on canvas elements (Safari)

## 3.0.0 beta 1 (January 09, 2017)

### Added

- Initial release
