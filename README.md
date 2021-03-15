DirectToxy
====

DirectTox client for Windows.

Feel free to contribute.

Compiling Toxy
===

#### Submodules
```
git submodule update --init --recursive
```
#### NuGet dependencies
* AForge.Video
* NAudio
* Squirrel

These should be downloaded by Visual Studio automatically. This requires [NuGet](http://docs.nuget.org/docs/start-here/installing-nuget) to be installed.

An up-to-date list of NuGet dependencies can be found in Toxy/packages.config
#### Separate dependencies

* [Tox library](https://github.com/irungentoo/toxcore), more info on how to compile/obtain this can be found [here](https://github.com/alexbakker/SharpTox#things-youll-need).

Once you have obtained Tox, place libtox.dll in the libs folder.
