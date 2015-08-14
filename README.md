# oppia-xblock

## Embedding Oppia explorations in the OpenEdX platform

This XBlock is packaged in the standard way as other third-party XBlock
contributions to the OpenEdX platform. The following notes are only
suggestions, but please note that the way XBlocks are installed may change over
time. If in doubt, consult the latest OpenEdX documentation.

Download the contents of this repository to a folder on your local machine, and deploy it following the
instructions in [this tutorial](http://opencraft.com/doc/edx/xblock/tutorial.html#deploying-to-edx-platform).

Note that you will need to add the value "oppia" to the `advanced_modules`
field in Studio's 'Advanced Settings' menu.

Notes:

(1) On devstack, the XBlock does not show up in Studio as a live preview in the
    editor. However, it does show up in the LMS.
(2) If you wish to record events, you can do so by modifying the _log() method
    in the oppia.py file.
