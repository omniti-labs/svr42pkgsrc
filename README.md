To use this tool:

 * Set the three variables at the top of the script.
 * VENDOR should have no spaces.
 * BASEURL should contain http accessible SVR4 datastream format
   packages.

Run the tool:

   ./svr42pkgsrc NAMEOFREMOTEFILE

This will produce a pkgsrc compatible tgz file.  You must have pkgtrans
installed to read the SVR4 packages and pkg_create install to create the
pkgsrc packages.
