# SCSS Mixin Aspect Ratio

Пакет для интеграции миксина для создания пропорциональных блоков.

Документация: [EN](README.md) | [RU](README.RU.md)

___

## Установка

Вы можете установить пакет автоматически с помощью NPM:

```
npm i @bu0nq/scss-mixin-aspect-ratio
```

## Использование

Чтобы использовать этот пакет, импортируйте его в свой проект:

```scss
@use "@bu0nq/scss-mixin-aspect-ratio" as *;

.demo {
    @include aspect-ratio(100%, 100%) {
        // Styles
    };
}
```

## Изменение пространства имен

Вы можете изменить пространство имен во время импорта миксина и использовать миксин с другим пространством имен:

```scss
@use "@bu0nq/scss-mixin-aspect-ratio" as mixin;

.demo {
    @include mixin.aspect-ratio(100%, 100%) {
        // Styles
    };
}
```
