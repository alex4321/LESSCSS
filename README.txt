README.txt
==========

A module with LESS to CSS convertion functions.
May be used by your theme :

function THEMENAME_preprocess_html(&$variables) {
  $variables['styles']->callback = 'less_get_styles';
}

AUTHOR/MAINTAINER
======================
-pozharskii alexander <pozharckey at gmail DOT com>
http://alexcoder.info/
