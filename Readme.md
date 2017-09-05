# Forked FixedHeader version adds the following features:

* Callback method when the header becomes fixed.
* Ability to size the header to the data table wrapper instead of the table itself.
* Disable any horizontal positioning.

For example:

```js
  fixedHeader: {
    positionVia: 'wrapper', // Position via the wrapper instead of the table
    horizontalPos: false, // Do not adjust the horizontal positioning
    fixedCallback: function(wrapper, fixedheader) {
        // Will receive wrapper and fixedheader jQuery objects.
        // Called when the header becomes fixed.
    }
  }
```

# FixedHeader

The FixedHeader plug-in will freeze in place the header and/or footer in a DataTable, ensuring that title information will remain always visible.


# Installation

To use FixedHeader the primary way to obtain the software is to use the [DataTables downloader](//datatables.net/download). You can also include the individual files from the [DataTables CDN](//cdn.datatables.net). See the [documentation](http://datatables.net/extensions/fixedheader/) for full details.

## NPM and Bower

If you prefer to use a package manager such as NPM or Bower, distribution repositories are available with software built from this repository under the name `datatables.net-fixedheader`. Styling packages for Bootstrap, Foundation and other styling libraries are also available by adding a suffix to the package name.

Please see the DataTables [NPM](//datatables.net/download/npm) and [Bower](//datatables.net/download/bower) installation pages for further information. The [DataTables installation manual](//datatables.net/manual/installation) also has details on how to use package managers with DataTables.


# Basic usage

FixedHeader is initialised using the `fixedHeader` option in the DataTables constructor - a simple boolean `true` will enable the feature. Further options can be specified using this option as an object - see the documentation for details.

Example:

```js
$(document).ready( function () {
    $('#myTable').DataTable( {
    	fixedHeader: true
    } );
} );
```


# Documentation / support

* [Documentation](https://datatables.net/extensions/fixedheader/)
* [DataTables support forums](http://datatables.net/forums)


# GitHub

If you fancy getting involved with the development of FixedHeader and help make it better, please refer to its [GitHub repo](https://github.com/DataTables/FixedHeader).

