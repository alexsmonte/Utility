# Utility

Composer: composer require asmpkg/utility

Português<br>
Manipulação de XML para PHP<br>

A biblioteca XML faz a conversão de XML para Array, de Array para XML.<br>

A documentacao completa sobre como utilizar a biblioteca XML: http://book.cakephp.org/3.0/en/core-libraries/xml.html

Importing Data to XML Class


$text = '<?xml version="1.0" encoding="utf-8"?>
<post>
    <id>1</id>
    <title>Best post</title>
    <body> ... </body>
</post>';
$xml = Xml::build($text);

Local file
$xml = Xml::build('/home/awesome/unicorns.xml');

$data = [
    'post' => [
        'id' => 1,
        'title' => 'Best post',
        'body' => ' ... '
    ]
];
$xml = Xml::build($data);


Importante: Esta class foi copiada da biblioteca Utility do framework Cakephp


English
XML handling for PHP

The XML library converts XML to Array, Array to XML.

Full documentation on how to use the XML library: http://book.cakephp.org/3.0/en/core-libraries/xml.html

Importing Data to Xml Class

$text = '<?xml version="1.0" encoding="utf-8"?>
<post>
    <id>1</id>
    <title>Best post</title>
    <body> ... </body>
</post>';
$xml = Xml::build($text);

Local file
$xml = Xml::build('/home/awesome/unicorns.xml');

$data = [
    'post' => [
        'id' => 1,
        'title' => 'Best post',
        'body' => ' ... '
    ]
];
$xml = Xml::build($data);

Important: This class was copied from the Utility Library Cakephp framework