microG for Custom ROMs
======================

Download microG prebuilt APKs for inclusion in a custom ROM.
This also downloads the GPG armor files of the packages to verify them.

Getting the packages
--------------------

* Add this to your local manifest:

      <?xml version="1.0" encoding="UTF-8"?>
      <manifest>
          <!-- microG -->
          <project name="Professor-Berni/android_vendor_microG"
                   path="vendor/microG"
                   remote="github"
                   revision="master" />
      </manifest>
      
* Sync the sources.

* After downloading go to the vendor dir and get the packages:

      cd vendor/microG
      ./get_packages.sh
