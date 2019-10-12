foliate-pkgsrc
==============

NetBSD [pkgsrc][4] script for Foliate.

You can find Foliate [here][1]

NOTE: This package is not yet available in the pkgsrc tree.

Installation
------------

Copy `print/foliate` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/print/foliate`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* Foliate is developed and maintained by [John Factotum][3].
* Thanks to `@coypoop` and `nia@` for reviewing and suggesting fixes to the
  package.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://johnfactotum.github.io/foliate/
[2]: https://github.com/johnfactotum/foliate#installation
[3]: https://github.com/johnfactotum
[4]: http://pkgsrc.se/print/foliate
