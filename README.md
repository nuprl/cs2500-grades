cs2500-grades
==========

Grades handin client package for CS2500 grading server for Fall 2014.

# Install instructions
First, ensure any older semesters are removed:

```raco pkg remove cs2500-grades```

Then, install the new semester:

```raco pkg install
github://github.com/bluephoenix47/cs2500-grades/f14```

Make sure not to use the master branch, as it doesn't contain the
server's certificate. Instead, use the semester specific branch, such as
`f14` for fall 2014, or `sp15` for spring 2015.

You can also use DrRacket's File -> Install Package menu to install this
package.

If patches are released during the semester:

```raco pkg update cs2500-grades```

Alternatively, use `build-plt` to build a PLT file that can be installed
via DrRacket's File -> Install PLT File. New versions must be manually
distributed and manually updated via this menu.

If a PLT file is needed, use `git checkout master build-plt`.
