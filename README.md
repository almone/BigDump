# BigDump
Staggered import of large and very large MySQL Dumps (like <a href="http://www.phpmyadmin.net/">phpMyAdmin</a> dumps) even through the web servers with hard runtime limit and those in safe mode. The script imports only a small part of the huge dump and restarts itself. The next session starts where the last was stopped.

Please don’t hesitate to report any bugs in this release but read the <a href="http://www.ozerov.de/bigdump/usage/">usage notes</a> and <a href="http://www.ozerov.de/bigdump/faqs/">the FAQs</a> first! 

THIS SCRIPT IS PROVIDED AS IS, WITHOUT ANY WARRANTY OR GUARANTEE OF ANY KIND.
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version. If you change this script or add any features please tell me. I will consider adding these features for everybody.

Author: Alexey Ozerov (alexey at ozerov dot de)
AJAX & CSV functionalities: Krzysiek Herod (kr81uni at wp dot pl)