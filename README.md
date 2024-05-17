```php
<?php

namespace Mustaf;

class About extends Me
{
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            VueJs::class,
            Javascript::class,
            Typescript::class
        ];
    }
    
    public function getCurrentlyLearning(): array
    {
         return [
            Ruby::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

<br/>
<div align="center">
<a href="https://twitter.com/themshllaku" target="_blank">
<img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
</a> 
</div>
