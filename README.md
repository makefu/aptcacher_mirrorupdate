# aptcacher mirrorupdater

These scripts provide a way to update the <distro>\_mirrors file of
apt-cacher-ng. This prevents 403 errors when updating via the apt-cacher-ng



# running

    ./get_archlx_mirrors > /etc/apt-cacher-ng/archlx_mirrors
    # or
    ./get_ubuntu_mirrors > /etc/apt-cacher-ng/ubuntu_mirrors

# COPYING

Copyright Felix Richter <github-aptcacher@syntax-fehler.de>
This code is licensed under the WTFPLv2 (see COPYING).

