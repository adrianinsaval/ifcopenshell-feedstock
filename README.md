About ifcopenshell-feedstock
============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/ifcopenshell-feedstock/blob/main/LICENSE.txt)

Home: https://ifcopenshell.org

Package license: LGPL-3.0-or-later

Summary: IfcOpenShell is a library to support the IFC file format

Development: https://github.com/IfcOpenShell/IfcOpenShell

Documentation: https://ifcopenshell.org/

IfcOpenShell
============

IfcOpenShell is an open source ([LGPL]) software library for working with Industry Foundation Classes ([IFC]). Complete
parsing support is provided for [IFC2x3 TC1], [IFC4 Add2 TC1], IFC4x1, IFC4x3, and IFC4x3. Extensive geometric support
is implemented for the IFC releases [IFC2x3 TC1] and [IFC4 Add2 TC1]. Extending with support for arbitrary IFC schemas
is possible at compile-time when using C++ and at run-time when using Python.

In addition to a C++ and Python API, IfcOpenShell comes with an ecosystem of tools, notably including IfcConvert (an
application to convert IFC models to
other formats), the BlenderBIM Add-on (an add-on to Blender providing a graphical IFC authoring platform), and many
other libraries, CLI apps, and more. Support is also provided for auxiliary standards such as BCF and IDS.

For more information, see:

* [IfcOpenShell Website](http://ifcopenshell.org)
* [IfcOpenShell Documentation](http://blenderbim.org/docs-python)
* [IfcOpenShell C++ Installation](https://blenderbim.org/docs-python/ifcopenshell/installation.html)
* [IfcOpenShell Python Installation](https://blenderbim.org/docs-python/ifcopenshell-python/installation.html)
* [IfcOpenShell Python Hello World Tutorial](https://blenderbim.org/docs-python/ifcopenshell-python/hello_world.html)
* [BlenderBIM Add-on Website](https://blenderbim.org)
* [BlenderBIM Add-on Documentation](http://blenderbim.org/docs)
* [Add-on Installation](https://blenderbim.org/docs/users/installation.html)
* [Exploring an IFC model](https://blenderbim.org/docs/users/exploring_an_ifc_model.html)

<table>
  <thead>
    <tr>
      <th>Service</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Anaconda Daily Build</td>
      <td><a href="https://anaconda.org/ifcopenshell/ifcopenshell"><img src="https://img.shields.io/conda/vn/ifcopenshell/ifcopenshell" alt="Anaconda-Server Badge"></a></td>
    </tr>
    <tr>
      <td>Anaconda v0.7.0 Stable</td>
      <td><a href="https://anaconda.org/conda-forge/ifcopenshell"><img src="https://img.shields.io/conda/vn/conda-forge/ifcopenshell" alt="Anaconda-Server Badge"></a></td>
    </tr>
    <tr>
      <td>PyPi Daily Build</td>
      <td><a href="https://pypi.org/project/ifcopenshell/"><img src="https://img.shields.io/pypi/v/ifcopenshell" alt="PyPi Badge"></a></td>
    </tr>
    <tr>
      <td>ArchLinux AUR Package Stable</td>
      <td><a href="https://aur.archlinux.org/packages/ifcopenshell"><img src="https://img.shields.io/aur/version/ifcopenshell" alt="AUR Badge"></a></td>
    </tr>
    <tr>
      <td>ArchLinux AUR Package git</td>
      <td><a href="https://aur.archlinux.org/packages/ifcopenshell-git"><img src="https://img.shields.io/aur/version/ifcopenshell-git" alt="AUR Badge"></a></td>
    </tr>
    <tr>
      <td>BlenderBIM Add-on Chocolatey (under moderation)</td>
      <td><a href="https://community.chocolatey.org/packages/blenderbim-nightly/"><img src="https://img.shields.io/chocolatey/v/blenderbim-nightly" alt="Chocolatey Badge"></a></td>
    </tr>
    <tr>
      <td>Sponsor development on OpenCollective</td>
      <td><a href="https://opencollective.com/opensourcebim/"><img src="https://opencollective.com/opensourcebim/tiers/badge.svg" alt="Financial Contributors"></a></td>
    </tr>
    <tr>
      <td>Docker hub</td>
      <td><a href="https://hub.docker.com/r/aecgeeks/ifcopenshell"><img src="https://img.shields.io/docker/pulls/aecgeeks/ifcopenshell" alt="Docker Pulls"></a></td>
    </tr>

  </tbody>
</table>
Contents
--------

Those marked with an asterisk are part of IfcOpenShell.
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>License</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>bcf</td>
      <td>Library to read and write BCF-XML and query OpenCDE BCF-API modules</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>blenderbim</td>
      <td>Add-on to Blender providing a graphical native IFC authoring platform</td>
      <td>GPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>bsdd</td>
      <td>Library to query the bSDD API</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifc2ca</td>
      <td>Utility to convert IFC structural analysis models to Code_Aster</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifc4d</td>
      <td>Convert to and from IFC and project management software</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifc5d</td>
      <td>Report and optimise cost information from IFC</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifcbimtester</td>
      <td>Wrapper for Gherkin based unit testing for IFC models</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifcblender</td>
      <td>Historic Blender IFC import add-on</td>
      <td>LGPL-3.0-or-later*</td>
    </tr>
    <tr>
      <td>ifccityjson</td>
      <td>Convert CityJSON to IFC</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifcclash</td>
      <td>Clash detection library and CLI app</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifccobie</td>
      <td>Extract IFC data for COBie handover requirements</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
    <tr>
      <td>ifcconvert</td>
      <td>CLI app to convert IFC to many other formats</td>
      <td>LGPL-3.0-or-later*</td>
    </tr>
    <tr>
      <td>ifccsv</td>
      <td>Library and CLI app to export and import schedules from IFC</td>
      <td>LGPL-3.0-or-later</td>
    </tr>
<tr>
  <td>ifcdiff</td>
  <td>Compare changes between IFC models</td>
  <td>LGPL-3.0-or-later</td>
</tr>
<tr>
  <td>ifcfm</td>
  <td>Extract IFC data for FM handover requirements</td>
  <td>LGPL-3.0-or-later</td>
</tr>
<tr>
  <td>ifcgeom</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcgeom_schema_agnostic</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcgeomserver</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcjni</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcmax</td>
  <td>Historic extension for IFC support in 3DS Max</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcopenshell-python</td>
  <td>Python library for IFC manipulation</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcparse</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>ifcpatch</td>
  <td>Utility to run pre-packaged scripts to manipulate IFCs</td>
  <td>LGPL-3.0-or-later</td>
</tr>
<tr>
  <td>ifcsverchok</td>
  <td>Blender Add-on for visual node programming with IFC</td>
  <td>GPL-3.0-or-later</td>
</tr>
<tr>
  <td>ifctester</td>
  <td>Library, CLI and webapp for IDS model auditing</td>
  <td>LGPL-3.0-or-later</td>
</tr>
<tr>
  <td>ifcwrap</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>qtviewer</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
<tr>
  <td>serializers</td>
  <td>Internal library for IfcOpenShell</td>
  <td>LGPL-3.0-or-later*</td>
</tr>
</tbody>
</table>

[LGPL]: https://github.com/IfcOpenShell/IfcOpenShell/tree/master/COPYING.LESSER "LGPL-3.0-or-later"
[IFC]: https://technical.buildingsmart.org/standards/ifc/ "IFC"
[IFC2x3 TC1]: https://standards.buildingsmart.org/IFC/RELEASE/IFC2x3/TC1/HTML/ "IFC2x3 TC1"
[IFC4 Add2 TC1]: https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/ "IFC4 Add2 TC1"
[Visual Studio]: https://www.visualstudio.com/ "Visual Studio"
[Visual C++ Build Tools]: http://landinghub.visualstudio.com/visual-cpp-build-tools "Visual C++ Build Tools"
[MSYS2]: https://msys2.github.io/ "MSYS2"
[win/readme.md]: https://github.com/IfcOpenShell/IfcOpenShell/tree/master/win/readme.md "win/readme.md"
[nix/build-all.py]: https://github.com/IfcOpenShell/IfcOpenShell/tree/master/nix/build-all.py "nix/build-all.py"


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ifcopenshell-green.svg)](https://anaconda.org/freecad/ifcopenshell) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/ifcopenshell.svg)](https://anaconda.org/freecad/ifcopenshell) | [![Conda Version](https://img.shields.io/conda/vn/freecad/ifcopenshell.svg)](https://anaconda.org/freecad/ifcopenshell) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/ifcopenshell.svg)](https://anaconda.org/freecad/ifcopenshell) |

Installing ifcopenshell
=======================

Installing `ifcopenshell` from the `freecad/label/dev` channel can be achieved by adding `freecad/label/dev` to your channels with:

```
conda config --add channels freecad/label/dev
conda config --set channel_priority strict
```

Once the `freecad/label/dev` channel has been enabled, `ifcopenshell` can be installed with `conda`:

```
conda install ifcopenshell
```

or with `mamba`:

```
mamba install ifcopenshell
```

It is possible to list all of the versions of `ifcopenshell` available on your platform with `conda`:

```
conda search ifcopenshell --channel freecad/label/dev
```

or with `mamba`:

```
mamba search ifcopenshell --channel freecad/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search ifcopenshell --channel freecad/label/dev

# List packages depending on `ifcopenshell`:
mamba repoquery whoneeds ifcopenshell --channel freecad/label/dev

# List dependencies of `ifcopenshell`:
mamba repoquery depends ifcopenshell --channel freecad/label/dev
```




Updating ifcopenshell-feedstock
===============================

If you would like to improve the ifcopenshell recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/ifcopenshell-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Krande](https://github.com/Krande/)
* [@looooo](https://github.com/looooo/)

