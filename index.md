## Welcome to RPM Sphere repository

Collection of extra packages for Fedora Linux.
So far supporting x86_64 and aarch64 architectures.
Feel free to promote them in any form.

### Release

Only the last builds are kept in the repository. Packages will be
rolling-updated occasionally, and not necessarily against the current version
of application or system.

### Install

Recommended is to import repositories from [RPM Fusion](https://rpmfusion.org/Configuration) first, then install
[rpmsphere-release](https://github.com/rpmsphere/noarch/raw/master/r/rpmsphere-release-36-1.noarch.rpm)
package to add this repository.

### Configuration

The installed /etc/yum.repos.d/[rpmsphere.repo](rpmsphere.repo) could be modified manually.
Sub-repositories "basearch" and "noarch" are enabled by default, while "source" and "caution" are disabled.
