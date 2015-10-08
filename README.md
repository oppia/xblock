## Embedding Oppia explorations in the OpenEdX platform

Oppia is a tool for creating short interactive tutorials (called 'explorations') that try to simulate a conversation with a human tutor. This XBlock allows Oppia explorations to be embedded in OpenEdX courses.

For installation instructions, please consult the latest OpenEdX documentation. You may also find [this tutorial](http://opencraft.com/doc/edx/xblock/tutorial.html#deploying-to-edx-platform) useful.

Notes:

1. You will need to add the value "oppia" to the `advanced_modules` field in Studio's 'Advanced Settings' menu.
2. On devstack, the XBlock does not show up in Studio as a live preview in the editor. However, it does show up in the LMS.
3. This XBlock also comes with default logging capabilities that make use of edX's `event-tracking` library (documented [here](http://edx.readthedocs.org/projects/edx-developer-guide/en/latest/analytics.html#event-tracking)).
