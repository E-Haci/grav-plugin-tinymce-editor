# v1.3.0
##  XX-09-2019

1. [](#new)
    * **Deprecated the semi-absolute media path handling in favor of fully relative paths** - previously inserted media **will keep working**
    * Added support for TinyMCE 5.x - now supporting the versions 4.9.6 and 5.0.15
    * Added a whitelist and a blacklist for customizing on which pages TinyMCE is used
    * Added the `evals` field for advanced TinyMCE parameters, only modifyable in `tinymce-editor.yaml`
2. [](#improved)
    * Made dragging and dropping media into the editor actually work
    * Reworked how TinyMCE is initialized for minor performance gains
3. [](#bugfix)
    * Suppressed the console warnings that appeared as the inserted media type was determined

# v1.2.7
##  16-09-2019

1. [](#improved)
    * Updated TinyMCE to 4.9.6
2. [](#bugfix)
    * Fixed the handling of fields with `validate.required` set to true

# v1.2.6
##  22-02-2019

1. [](#bugfix)
    * Fixed the handling of tinymce fields unrelated to pages

# v1.2.5
##  14-12-2018

1. [](#bugfix)
    * Fixed the handling of what libxml considers to be invalid tags

# v1.2.4
##  03-12-2018

1. [](#bugfix)
    * Fixed the handling of libxml versions older than 2.7.8

# v1.2.3
##  15-10-2018

1. [](#improved)
    * Removed a sillier overlooked debug check that magically appeared in v1.2.2

# v1.2.2
##  15-10-2018

1. [](#improved)
    * Improved the method used for TinyMCE path lookups
    * Removed a debug check from the code that was previously overlooked

# v1.2.1
##  01-10-2018

1. [](#bugfix)
    * Fixed the handling of Grav installs in subdirectories

# v1.2.0
##  27-09-2018

1. [](#new)
    * Added a persistable method of modifying the plugin's files
2. [](#improved)
    * Updated TinyMCE to 4.8.3
    * Improved modular page media handling
    * Improved default configuration
3. [](#bugfix)
    * Got bugged one time too many, `tinymce.html.twig` is unminified now

# v1.1.8
##  26-04-2018

1. [](#improved)
    * Improved parameter handling

# v1.1.7
##  05-02-2018

1. [](#bugfix)
    * Fixed label handling

# v1.1.6
##  12-01-2018

1. [](#bugfix)
    * Improved modular page handling again

# v1.1.5
##  11-01-2018

1. [](#bugfix)
    * Worked around GPM quirkyness, hopefully

# v1.1.4
##  10-01-2018

1. [](#bugfix)
    * Removed calls to a rarely available JavaScript function

# v1.1.3
##  10-01-2018

1. [](#improved)
    * Improved modular page handling

# v1.1.2
##  01-11-2017

1. [](#bugfix)
    * Fixed boolean values in parameters

# v1.1.1
##  28-10-2017

1. [](#improved)
    * Improved the file picker's URL handling

# v1.1.0
##  04-10-2017

1. [](#new)
    * Made the page editor's file picker output HTML and readded it to the interface
2. [](#bugfix)
    * Fixed Document Base URL

# v1.0.1
##  01-10-2017

1. [](#improved)
    * Fixed language shortcodes

# v1.0.0
##  27-09-2017

1. [](#new)
    * First release of the TinyMCE Editor Integration plugin
