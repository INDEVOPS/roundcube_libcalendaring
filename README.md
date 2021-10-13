Orginal plugin [repository][2]

Library providing common functions for calendar-based plugins
-------------------------------------------------------------

Provides utility functions for calendar-related modules such as

* alarms display and dismissal
* attachment handling
* iCal parsing and exporting
* iTip invitations handling

iCal parsing and exporting is done with the help of the Sabre VObject
library [1]. It needs to be insalled with Roundcube using composer:

  $ composer require "sabre/vobject" "~3.3.3"

[1]: http://sabre.io/vobject/
[2]: <https://git.kolab.org/diffusion/RPK/browse/master/plugins/libcalendaring>
