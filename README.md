#OpenCart Auto complete support for IDE

This tinny scripts is generating whole PHPDoc which is needed to use auto complete features of many code editors.

#Tested

This script is tested on __OC v. 2.2__ and on __PHPStorm__ editor

#Installation

1. Copy `create_php_doc.php` to `upload/` folder => `upload/create_php_doc.php`
2. Go to: `http://[HOST]/create_php_doc.php`
3. Copy result from __textarea__
4. Open file `system/engine/controller.php`
5. Paste whole copied content on top after `<?php` tag

#Authors
1. Lubos Beran (l.beran@factcool.sk / eyeskiller)
