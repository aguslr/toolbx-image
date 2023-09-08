[toolbx-image][1]
=================

[![build-image](https://github.com/aguslr/toolbx-image/actions/workflows/build.yml/badge.svg)](https://github.com/aguslr/toolbx-image/actions/workflows/build.yml)

Usage
-----

If you use [Toolbx][5]:

    toolbox -i ghcr.io/aguslr/toolbx-image:latest -c toolbox
    toolbox enter toolbox

If you use [Distrobox][6]:

    distrobox create -i ghcr.io/aguslr/toolbx-image:latest -n distrobox
    distrobox enter distrobox


### Tags

There are several flavors for this container:

- `fedora`, `latest`: Uses Fedora's latest image from
  <https://registry.fedoraproject.org/>.

- `almalinux`: Uses Alma Linux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `alpine`: Uses Alpine's latest image from
  <https://quay.io/organization/toolbx-images>.

- `archlinux`: Uses Arch Linux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `debian`: Uses Debian's latest image from
  <https://quay.io/organization/toolbx-images>.

- `opensuse`: Uses openSUSE's latest image from
  <https://quay.io/organization/toolbx-images>.

- `rhel`: Uses RHEL's latest image from
  <https://quay.io/organization/toolbx-images>.

- `ubuntu`: Uses Ubuntu's latest image from
  <https://quay.io/organization/toolbx-images>.


Verification
------------

These images are signed with Sisgstore's [Cosign][4]. You can verify the
signature by downloading the `cosign.pub` key from this repo and running the
following command:

    cosign verify --key cosign.pub ghcr.io/aguslr/toolbx-image:latest


References
----------

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
