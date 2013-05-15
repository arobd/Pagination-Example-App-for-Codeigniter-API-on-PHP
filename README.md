Pagination
==========

This code example shows how to use the Pagination helper bundled in CodeIgniter to distribute a list of data across multiple pages.
Changes were made with the following:

- **pagination.php** - the Controller file used to load/initialize and use the Pagination helper and to retrieve a segment of an array of names. It's located under /application/controllers.

- **page-view.php** - the View file containing the HTML/CSS used to present the names that are specified by the controller, as well as list the page links. It's located under /applications/views.

- **routes.php** - a config file used to specify which Controller to use when the user navigates to a specific route. The change was made to use "pagination" controller. It's located under /application/config.
