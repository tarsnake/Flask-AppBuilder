Introduction
============

The main goal for this project is to provide a simple development framework
that handles the main problems any web application or site encounters.
It will help you adhere to the DRY (Don't repeat yourself) principle.

Keeping in mind that it must be possible to develop directly on Flask/Jinja2 for custom pages or flows,
that painlessly integrate the framework.
But the framework itself should go further then an admin scaffolding package.
It should have builtin presentation alternatives, and behaviour.
Should be highly configurable, and should have extra goodies.

It's intended to lower errors, bugs and project's time to deliver.

This package has some CSS and JS batteries included:

	- Google charts CSS and JS
	- BootStrap CSS and JS
	- BootsWatch Themes
	- Font-Awesome CSS and Fonts

Includes:
---------

  - Security
      - Automatic permissions lookup, based on exposed methods. It will grant all permissions to the Admin Role.
      - Inserts on the Database all the detailed permissions possible on your application.
      - Public (no authentication needed) and Private permissions.
      - Role based permissions.
      - Authentication support for OpenID, Database and LDAP.
  - Views and Widgets
      - Automatic menu generation.
      - Automatic CRUD generation.
      - Big variety of filters for your lists.
      - Various view widgets: lists, master-detail, list of thumbnails etc
      - Select2, Datepicker, DateTimePicker
      - Google charts with automatic group by or direct values and filters.
  - Forms
      - Automatic, Add, Edit and Show from Database Models
      - Labels and descriptions for each field.
      - Automatic base validators from model's definition.
      - Custom validators, extra fields, custom filters for related dropdown lists.
      - Image and File support for upload and database field association. It will handle everything for you.
      - Field sets for Form's (Django style).
  - i18n
      - Support for multi-language via Babel
  - Bootstrap 3.0.3 CSS and js, with Select2 and DatePicker
  - Font-Awesome icons, for menu icons and actions.




