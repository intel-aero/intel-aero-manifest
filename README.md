# intel-aero-manifest

Manifests for Intel Aero releases and development

`default.xml` - manifest for Intel Aero development branch

`$ repo init -u https://github.com/intel-aero/intel-aero-manifest.git`

`v<X>.<Y>.xml` - manifest for Intel Aero releases

As example, checking out v1.3 release:

`$ repo init -u https://github.com/intel-aero/intel-aero-manifest.git -m v1.3.xml -b refs/tags/v1.3`

The versioned manifests are kept on master branch but they are only valid when
there's a tag for that version already, so it's advised to pass the `-b` option
to make sure you are building a valid version.
