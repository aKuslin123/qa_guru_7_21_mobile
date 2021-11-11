# Wikipedia Android tests

### Запуск тестов Appium (default):

```
gradle clean test -Ddevice.name=appium
```

где appium это настройки для real или emulator

### Запуск тестов Selenoid:

```
gradle clean test -Ddevice.host=selenoid
```

### Запуск тестов BrowserStack:

```
gradle clean test -Ddevice.host=browser_stack
```