# Sass Starter Kit Based on ITCSS Methodology 

This is a sass file starter kit based on the ITCSS methodology.  The file breakdown is as follows.

```
+ scss/
|
| + settings/                        # global variables for use throughout project
|  | -- _settings.global                  # base sizes
|  | -- _settings.colors                  # color variables
|
| + tools/                           # tools (mixins and functions)
|  | -- _tools.mixins                     # mixins
|  | -- _tools.functions                  # functions
|  | -- _tools.lib                        # dependencies
|  | -- _tools.lib.settings               # settings for dependencies
|
| + generic/                         # generic styles - houses high-level far reaching styles
|  | -- _generic.reset                    # margin and padding reset
|  | -- _generic.normalize                # normalize files 
|  | -- _generic.boxsizing                # global box-sizing 
|  | -- _generic.shared                   # global values that multiple elements share 
|
| + elements/                        # element styles without classes
|  | -- _elements.page                    # html margin/padding/color
|  | -- _elements.headings                # type sizes
|  | -- _elements.links                   # links stylings - base and hover
|  | -- _elements.lists                   # list stylings
|  | -- _elements.images                  # image stylings
|  | -- _elements.quotes                  # quote stylings
| 
| + objects/                         #  First layer of class-based selectors (non-cosmetic such as layouts, patterns, or 'objects')
|  | -- _objects.wrappers                 # wrapper layout
|  | -- _objects.layout                   # general layout of elements
|  | -- _objects.media                    # object media layout
|
| + components/                      # explict styling of designed pieces of the DOM 
|  | -- _components.page-title            # title stylings
|  | -- _components.buttons               # buttons
|  | -- _components.testimonials          # testimonials
|  | -- _components.avatars               # avatars or other specific image styling
|
| + trumps/                          # Layer that beats all other layers and has power to override everything else that has gone before it. 
|  | -- _trumps.links
|  | -- _trumps.widths
```

