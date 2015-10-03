# Utility

Composer: composer require asmpkg/utility<br>

Português<br>
Manipulação de XML para PHP<br>

A biblioteca XML faz a conversão de XML para Array, de Array para XML.<br>

A documentacao completa sobre como utilizar a biblioteca XML: http://book.cakephp.org/3.0/en/core-libraries/xml.html<br>

Importing Data to XML Class<br>


$text = '<?xml version="1.0" encoding="utf-8"?>
<post>
    <id>1</id>
    <title>Best post</title>
    <body> ... </body>
</post>';
$xml = Xml::build($text);

Local file<br>
$xml = Xml::build('/home/awesome/unicorns.xml');

$data = [
    'post' => [
        'id' => 1,
        'title' => 'Best post',
        'body' => ' ... '
    ]
];
$xml = Xml::build($data);
<br>
<br>
Importante: Esta class foi copiada da biblioteca Utility do framework Cakephp<br>
<br>
<br>
English<br>
XML handling for PHP<br>
<br>
The XML library converts XML to Array, Array to XML.<br>
<br>
Full documentation on how to use the XML library: http://book.cakephp.org/3.0/en/core-libraries/xml.html
<br>
Importing Data to Xml Class<br>
<br>
$text = '<?xml version="1.0" encoding="utf-8"?>
<post>
    <id>1</id>
    <title>Best post</title>
    <body> ... </body>
</post>';
<br>
$xml = Xml::build($text);<br>

Local file<br>
$xml = Xml::build('/home/awesome/unicorns.xml');

$data = [
    'post' => [
        'id' => 1,
        'title' => 'Best post',
        'body' => ' ... '
    ]
];
<br>
$xml = Xml::build($data);<br>
<br>
Important: This class was copied from the Utility Library Cakephp framework<br>