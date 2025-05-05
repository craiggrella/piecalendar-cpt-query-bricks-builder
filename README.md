# piecalendar-cpt-query-bricks-builder
This is a custom post type query for bricks builder query loop query editor to query pie calendar events from a custom post type.

## Plugins Required
There are several required plugins to make this work, including:
- [Bricks Builder](https://bricksbuilder.io)
- [Pie calendar](https://piecalendar.com)

You'll also need code or a plugin to create the custom post types. In this example, I've used [Advanced Custom Fields Pro](https://www.advancedcustomfields.com) to create the custom post type and custom taxonomy which are used in the query filter.

## Instructions
- In the query area of the query loop in Bricks Builder, toggle the selection for Query Editor (PHP).
- [Add Code](https://github.com/craiggrella/piecalendar-cpt-query-bricks-builder/blob/main/query-editor-php)
- Sign Code
- Save

Note: This code restricts event dates to the past and a custom event taxonomy. This can be changed by removing the meta query on start date or editing the values. You can also remove the tax query or edit values to suit your needs.


## Additional Resources
- [WordPress Query Parameters](https://developer.wordpress.org/reference/classes/wp_query/#parameters)
