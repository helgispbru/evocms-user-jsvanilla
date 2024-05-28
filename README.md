# evocms-user-jsvanilla

В пакете https://github.com/webber12/evocms-user используется JS на базе jQuery, это не подходит тем, у кого нет jQuery. В репозитории переписаный на ванилу js.

Установка:

1. Положить файл в `/assets/plugins/evocms-user/script-vanilla.js`
2. Дописать в конфиг `/core/custom/evocms-user/configs/evouser.php` параметр
```
return [
    'FrontJS' => 'assets/plugins/evocms-user/script-vanilla.js',
];
```
3. Доработать по вкусу

