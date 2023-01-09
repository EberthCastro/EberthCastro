Hi there 👋

<?php

namespace EberthCastro;

class About extends Me
{
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Reactjs::class,
            TypeScript::class,
            Javascript::class,
            Sass::class,
            Html::class,            
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to help';
    }
}
