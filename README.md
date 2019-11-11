### macOS High Sierra

В цій версії ОС наявні [глюки](https://apple.stackexchange.com/questions/300606/keyboard-layout-keeps-reverting-since-upgrade-to-high-sierra) при встановленні розкладки для всіх користувачів. Тому для даної версії ОС, рекомендуєтся, встановлювати для поточного користувача.

### Інсталяція

## Вручну
1. Завантажте актуальний інсталятор з розділу [Releases](../../releases/)
2. Запустіть `Install Ukrainian Unicode Layout.app`

## Brew-cask
1. Відкрийте `Terminal.app`
2. Запустіть команду:

        brew cask install ukrainian-unicode-layout

## Git
1. Відкрийте `Terminal.app`
2. Запустіть команду для встановлення:

    a) Лише для поточного користувача:

        git clone --depth 1 https://github.com/korzhyk/macOS-Ukrainian-Unicode-Layout.git ~/Library/Keyboard\ Layouts/Ukrainian-Unicode-Layout.bundle

    b) Для усіх користувачів:

        git clone --depth 1 https://github.com/korzhyk/macOS-Ukrainian-Unicode-Layout.git /System/Library/Keyboard\ Layouts/Ukrainian-Unicode-Layout.bundle

