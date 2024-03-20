# remmina_rhel8


sudo yum -y install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm


## List of packages
[root@xps yum.repos.d]# dnf install 'remmina*'
Updating Subscription Management repositories.
Extra Packages for Enterprise Linux 8 - x86_64                                                                                          19 MB/s |  16 MB     00:00    
Last metadata expiration check: 0:00:03 ago on Tue 19 Mar 2024 09:32:16 PM EDT.
Dependencies resolved.
=======================================================================================================================================================================
 Package                                      Architecture      Version                                 Repository                                                Size
=======================================================================================================================================================================
Installing:
 remmina                                      x86_64            1.4.33-1.el8                            epel                                                     1.0 M
 remmina-debuginfo                            x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina            464 k
 remmina-debugsource                          x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina            267 k
 remmina-devel                                x86_64            1.4.33-1.el8                            epel                                                      53 k
 remmina-gnome-session                        x86_64            1.4.33-1.el8                            epel                                                      23 k
 remmina-plugins-exec                         x86_64            1.4.33-1.el8                            epel                                                      27 k
 remmina-plugins-exec-debuginfo               x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             30 k
 remmina-plugins-kwallet                      x86_64            1.4.33-1.el8                            epel                                                      27 k
 remmina-plugins-kwallet-debuginfo            x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             97 k
 remmina-plugins-nx-debuginfo                 x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             59 k
 remmina-plugins-python                       x86_64            1.4.33-1.el8                            epel                                                      44 k
 remmina-plugins-rdp                          x86_64            1.4.33-1.el8                            epel                                                      74 k
 remmina-plugins-rdp-debuginfo                x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina            145 k
 remmina-plugins-secret                       x86_64            1.4.33-1.el8                            epel                                                      26 k
 remmina-plugins-secret-debuginfo             x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             27 k
 remmina-plugins-spice                        x86_64            1.4.33-1.el8                            epel                                                      36 k
 remmina-plugins-spice-debuginfo              x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             38 k
 remmina-plugins-st-debuginfo                 x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             28 k
 remmina-plugins-vnc                          x86_64            1.4.33-1.el8                            epel                                                      44 k
 remmina-plugins-vnc-debuginfo                x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             60 k
 remmina-plugins-www                          x86_64            1.4.33-1.el8                            epel                                                      33 k
 remmina-plugins-www-debuginfo                x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             41 k
 remmina-plugins-x2go                         x86_64            1.4.33-1.el8                            epel                                                      50 k
 remmina-plugins-xdmcp-debuginfo              x86_64            1.4.4-1.el8                             copr:copr.fedorainfracloud.org:castor:remmina             31 k
Installing dependencies:
 avahi-ui-gtk3                                x86_64            0.7-21.el8_9.1                          rhel-8-for-x86_64-appstream-rpms                          27 k
 breeze-icon-theme                            noarch            5.96.0-1.el8                            epel                                                     5.3 M
 dbusmenu-qt5                                 x86_64            0.9.3-0.20.20160218.el8.1               epel                                                     103 k
 kde-filesystem                               x86_64            4-67.el8                                epel                                                      51 k
 kde-settings                                 noarch            36.1-1.el8.1                            epel                                                      53 k
 kf5-filesystem                               x86_64            5.96.0-1.el8                            epel                                                      23 k
 kf5-kauth                                    x86_64            5.96.0-1.el8                            epel                                                     158 k
 kf5-kcodecs                                  x86_64            5.96.0-1.el8                            epel                                                     191 k
 kf5-kconfig-core                             x86_64            5.96.0-1.el8                            epel                                                     367 k
 kf5-kconfig-gui                              x86_64            5.96.0-1.el8                            epel                                                      65 k
 kf5-kconfigwidgets                           x86_64            5.96.0-1.el8                            epel                                                     441 k
 kf5-kcoreaddons                              x86_64            5.96.0-1.el8                            epel                                                     547 k
 kf5-kdbusaddons                              x86_64            5.96.0-1.el8                            epel                                                     103 k
 kf5-kguiaddons                               x86_64            5.96.0-1.el8                            epel                                                     120 k
 kf5-ki18n                                    x86_64            5.96.0-1.el8                            epel                                                     3.1 M
 kf5-knotifications                           x86_64            5.96.0-1.el8                            epel                                                     195 k
 kf5-kservice                                 x86_64            5.96.0-1.el8                            epel                                                     401 k
 kf5-kwallet                                  x86_64            5.96.0-1.el8                            epel                                                     339 k
 kf5-kwallet-libs                             x86_64            5.96.0-1.el8                            epel                                                     104 k
 kf5-kwidgetsaddons                           x86_64            5.96.0-1.el8                            epel                                                     1.6 M
 kf5-kwindowsystem                            x86_64            5.96.0-1.el8                            epel                                                     201 k
 libXcomp                                     x86_64            3.5.99.26-1.el8                         epel                                                     542 k
 libappindicator-gtk3                         x86_64            12.10.0-19.el8                          rhel-8-for-x86_64-appstream-rpms                          43 k
 libdbusmenu                                  x86_64            16.04.0-12.el8                          rhel-8-for-x86_64-appstream-rpms                         140 k
 libdbusmenu-gtk3                             x86_64            16.04.0-12.el8                          rhel-8-for-x86_64-appstream-rpms                          41 k
 libindicator-gtk3                            x86_64            12.10.1-14.el8                          rhel-8-for-x86_64-appstream-rpms                          70 k
 libsodium                                    x86_64            1.0.18-2.el8                            epel                                                     162 k
 nx-libs                                      x86_64            3.5.99.26-1.el8                         epel                                                     173 k
 nxproxy                                      x86_64            3.5.99.26-1.el8                         epel                                                      23 k
 polkit-qt5-1                                 x86_64            0.114.0-3.el8                           epel                                                      85 k
 pyhoca-cli                                   noarch            0.6.1.2-1.el8                           epel                                                      50 k
 python3-bcrypt                               x86_64            3.1.6-2.el8.1                           epel                                                      44 k
 python3-cffi                                 x86_64            1.11.5-6.el8                            rhel-8-for-x86_64-baseos-rpms                            238 k
 python3-cryptography                         x86_64            3.2.1-7.el8_9                           rhel-8-for-x86_64-baseos-rpms                            559 k
 python3-gevent                               x86_64            1.2.2-4.el8                             rhel-8-for-x86_64-appstream-rpms                         497 k
 python3-greenlet                             x86_64            0.4.13-4.el8                            rhel-8-for-x86_64-appstream-rpms                          31 k
 python3-paramiko                             noarch            2.12.0-2.el8                            epel                                                     340 k
 python3-pycparser                            noarch            2.14-14.el8                             rhel-8-for-x86_64-baseos-rpms                            109 k
 python3-pynacl                               x86_64            1.3.0-5.el8                             epel                                                     100 k
 python3-setproctitle                         x86_64            1.1.10-17.el8                           epel                                                      24 k
 python3-simplejson                           x86_64            3.17.0-2.el8                            epel                                                     286 k
 python3-x2go                                 noarch            0.6.1.3-1.el8                           epel                                                     357 k
 python3-xlib                                 noarch            0.33-2.el8                              epel                                                     281 k
Installing weak dependencies:
 python3-pyasn1                               noarch            0.3.7-6.el8                             rhel-8-for-x86_64-appstream-rpms                         126 k

Transaction Summary
=======================================================================================================================================================================
Install  68 Packages
