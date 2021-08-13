# OpenFoodFacts Infrastructure
Sysadmin repository for the various parts of the Open Food Facts infrastructure.

## Requests

### Virtual Machines

<!-- VM table -->
|                                                                     Title                                                                      |State |        OS         | CPU #  |               RAM                |         SSD (Local)          |HDD (Remote)|                            Services                            |
|------------------------------------------------------------------------------------------------------------------------------------------------|------|-------------------|--------|----------------------------------|------------------------------|------------|----------------------------------------------------------------|
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/40>VM for the dev instance of Robotoff [#40]</a>                   |open  |Debian last Stable.|       4|8 Gb                              |32 Gb                         |100 Gb      |robotoff, elastic search, tensorflow, postgresql                |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/37>Container for Wild School Eco-Score project [#37]</a>           |open  |Debian             |       4|16 Gb                             |30 Gb                         |0           |MongoDB                                                         |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/36>Container for slack.openfoodfacts.org [#36]</a>                 |open  |Debian last stable |       1|1 Gb                              |10 Gb                         |None        |Node.js                                                         |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/29>Container for Adminer [#29]</a>                                 |open  |Debian last Stable.|       2|512 Mb.                           |4 Gb or even less.            |0           |Nginx, PHP, Adminer.                                            |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/28>Two containers to build a replica set for OFF database [#28]</a>|open  |Debian 10 stable.  |       4|32 GB                             |50 GB (the database is 20 GB).|0           |Mongodb.                                                        |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/27>Container for feedme app [#27]</a>                              |open  |Debian last Stable.|       3|3 Gb.                             |15 Gb.                        |0           |PostgreSQL, Node.js, Nginx.                                     |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/24>Matomo VM and deployment [#24]</a>                              |open  |Debian last Stable |No idea.|No idea.                          |No idea.                      |No idea.    |LAMP                                                            |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/21>Container for OFF wiki [#21]</a>                                |open  |Last Debian Stable.|       2|3 Gb                              |14 Gb.                        |14 Gb       |Apache, PHP, MySQL, Mediawiki.                                  |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/19>VM for OFF API testing instance (openfoodfacts.net) [#19]</a>   |open  |Debian last Stable.|       2|4 Gb                              |64 Gb                         |            |nginx, apache2, mongodb, product opener                         |
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/41>VM for off-net OVH deployment [#41]</a>                         |closed|Debian             |       4|8GB (ProductOpener requires > 6GB)|64GB                          |64GB        |ProductOpener frontend + backend, MongoDB, PostgreSQL, Memcached|
|<a href=https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/20>VM for robotoff (robotoff.openfoodfacts.org) [#20]</a>          |closed|Debian last Stable.|       4|8 Gb                              |32 Gb                         |100 Gb      |robotoff, elastic search, tensorflow, postgresql                |
<!-- VM table -->

<a href="https://github.com/openfoodfacts/openfoodfacts-infrastructure/issues/new?assignees=cquest&labels=container&template=vm-template.md&title="><img src="./scripts/add.png" style="background: transparent; vertical-align: middle" width="30"/>&nbsp;&nbsp;Request a VM</img></a>
