# Hide Revision Field

## ABOUT
Hide Revision Field provides a configurable field formatter for the revision log
field for revisionable entities. This allows you to create revisions but reduces
noise for your content editors/site owners. All revisionable entity types are
supported including module added.

The widget has 4 settings for each instance:

  - `Default`: Provide a default log message.
  - `Show` (TRUE): Whether to show the field. If enabled the two other options
  will override this.
  - `Permission Based` (FALSE): Show if the user has the
  `access revision field` permission.
  - `Allow user specific configuration` (TRUE): Enables users to customize this
  field's visibility via their profile page if they have the
  `administer revision field personalization` permission.

## REQUIREMENTS
Drupal 8 is required, Drupal 8.6.x or higher is suggested - automatic tests only
on Drupal 8.6+, manually tested on 8.5.x.

## INSTALLATION
Install as you would normally install a contributed Drupal module. See the
[Drupal 8 instructions](http://drupal.org/documentation/install/modules-themes/modules-8)
if required in the Drupal documentation for further information.

## CONFIGURATION
Configuration can be accessed for each supported entity bundle on the form
display edit page for that entity type. For example for the Node type Article
that would be at `/admin/structure/types/manage/article/form-display`.

## FAQ
Any questions? Ask away on the issue queue or contact the maintainer
[Nick Wilde](https://drupal.org/u/nickwilde).
