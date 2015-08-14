## Embedding Oppia explorations in the OpenEdX platform

This XBlock is packaged in the standard way as other third-party XBlock contributions to the OpenEdX platform. Please consult the latest OpenEdX documentation for installation instructions. There is also a useful tutorial [here](http://opencraft.com/doc/edx/xblock/tutorial.html#deploying-to-edx-platform).

Notes:

1. You will need to add the value "oppia" to the `advanced_modules` field in Studio's 'Advanced Settings' menu.
2. On devstack, the XBlock does not show up in Studio as a live preview in the editor. However, it does show up in the LMS.
3. If you wish to record events, you can do so by modifying the `_log()` method in the `oppia.py` file.
