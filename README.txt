Written by Phithon <root@leavesongs.com> in 2014 and placed in
the public domain.

phithon <root@leavesongs.com> ��д��20140621
From: XDSEC <www.xdsec.org> & ���� <www.leavesongs.com>

Usage: 
<?php
require('xsshtml.class.php');
$html = '<html code>';
$xss = new XssHtml($html);
$html = $xss->getHtml();
?>

����
PHP Version > 5.0
������汾��IE7+ ��������������޷�����IE6�����°汾������е�XSS
����ʹ��ѡ��� http://phith0n.github.io/XssHtml