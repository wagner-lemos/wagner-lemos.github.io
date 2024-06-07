```php
<?php
namespace WagnerLemos;

class About extends Me
{
    public function getPersonalInfo(): array
    {
        return [
            'name'     => 'Wagner Lemos',
            'position' => 'FullStack developer',
            'location' => 'Florianópolis, Brazil 🇧🇷',
            'email'    => 'wagnerlemosce@gmail.com',
            'website'  => 'https://wagner-lemos.github.io'
        ];
    }
    public function getSkills(): array
    {
        return [
            'languages'  => ['PHP', 'JavaScript', 'TypeScript', 'Python', 'HTML', 'CSS'],
            'frameworks' => [
                              'Angular', 'React', 'Vue', 'Nest', 'Next', 'Nuxt', 'Laravel', 'CodeIgnite', 'Yii',
                              'CakePHP', 'Phalcon', 'WordPress'
                            ],
            'databases'  => ['MySQL', 'PostgreSQL', 'MongoDB'],
            'Design'     => ['PhotoShop', 'Figma']
        ];
    }
}
```
---
You can reach me via [Linkedin](https://www.linkedin.com/in/wagnerlemos).

