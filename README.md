SequenceProducer
================

連続した整数を順に返すイテレータ。コンストラクタ第二引数を省略すると無限に動作します。


&lt;?php

require_once(&#039;SequenceProducer.php&#039;);

$it = new SequenceProducer(1, 5);
foreach ($it ..

## License
BSD License