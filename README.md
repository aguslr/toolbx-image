[toolbx-image][1]
=================


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

- `toolbx-almalinux`: Uses Alma Linux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-alpine`: Uses Alpine's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-archlinux`: Uses Arch Linux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-debian`: Uses Debian's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-fedora`: Uses Fedora's latest image from
  <https://registry.fedoraproject.org/>.

- `toolbx-opensuse`: Uses openSUSE's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-rhel`: Uses RHEL's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-rockylinux`: Uses Rocky Linux's latest image from
  <https://quay.io/organization/toolbx-images>.

- `toolbx-ubuntu`: Uses Ubuntu's latest image from
  <https://quay.io/organization/toolbx-images>.


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
