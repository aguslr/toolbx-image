[toolbx-image][1]
=================


[![almalinux](https://github.com/aguslr/toolbx-image/actions/workflows/almalinux.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/almalinux.yml)<br/>
[![alpine](https://github.com/aguslr/toolbx-image/actions/workflows/alpine.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/alpine.yml)<br/>
[![archlinux](https://github.com/aguslr/toolbx-image/actions/workflows/archlinux.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/archlinux.yml)<br/>
[![debian](https://github.com/aguslr/toolbx-image/actions/workflows/debian.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/debian.yml)<br/>
[![fedora](https://github.com/aguslr/toolbx-image/actions/workflows/fedora.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/fedora.yml)<br/>
[![opensuse](https://github.com/aguslr/toolbx-image/actions/workflows/opensuse.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/opensuse.yml)<br/>
[![rhel](https://github.com/aguslr/toolbx-image/actions/workflows/rhel.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/rhel.yml)<br/>
[![rockylinux](https://github.com/aguslr/toolbx-image/actions/workflows/rockylinux.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/rockylinux.yml)<br/>
[![ubuntu](https://github.com/aguslr/toolbx-image/actions/workflows/ubuntu.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/ubuntu.yml)<br/>


Usage
-----

If you use [Toolbx][5]:

    toolbox -i ghcr.io/aguslr/toolbx-fedora:latest -c toolbox
    toolbox enter toolbox

If you use [Distrobox][6]:

    distrobox create -i ghcr.io/aguslr/toolbx-fedora:latest -n distrobox
    distrobox enter distrobox


### Tags

There are several images available in this repository:

- `toolbx-almalinux`: Uses AlmaLinux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-alpine`: Uses Alpine's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-archlinux`: Uses Arch Linux's latest image from
  <https://quay.io/organization/toolbx>.

- `toolbx-debian`: Uses Debian's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-fedora`: Uses Fedora's latest image from
  <https://quay.io/repository/fedora/fedora-toolbox>.

- `toolbx-opensuse`: Uses openSUSE's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-rhel`: Uses RHEL's latest image from
  <https://registry.access.redhat.com>.

- `toolbx-rockylinux`: Uses Rocky Linux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-ubuntu`: Uses Ubuntu's latest image from
  <https://quay.io/organization/toolbx>.


Verification
------------

These images are signed with Sisgstore's [Cosign][4]. You can verify the
signature by downloading the `cosign.pub` key from this repo and running the
following command:

    cosign verify --key cosign.pub ghcr.io/aguslr/toolbx-fedora:latest


References
----------

- [Declaring your own personal distroboxes][7]
- [GitHub - ublue-os/boxkit: A blingier starting image for Toolbx and
  Distrobox.][2]
- [GitHub - toolbx-images/images: Community maintained container images to use
  with toolbx (and distrobox)][3]
- [Cosign - Sigstore Documentation][4]


[1]: https://github.com/aguslr/toolbx-image
[2]: https://github.com/ublue-os/boxkit
[3]: https://github.com/toolbx-images/images
[4]: https://docs.sigstore.dev/cosign/overview/
[5]: https://github.com/containers/toolbox
[6]: https://github.com/89luca89/distrobox
[7]: https://www.ypsidanger.com/declaring-your-own-personal-distroboxes/
