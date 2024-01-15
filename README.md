[![Build status](https://ci.appveyor.com/api/projects/status/ixjbpcob04jvqavv/branch/master?svg=true)](https://ci.appveyor.com/project/Sergius92739/ra-12-1-redux-observable-front/branch/master)

# Поиск

### Deployment: <a href="https://sergius92739.github.io/ra-12.1-redux-observable-front/">Github Pages</a>

Взяв за основу проект, рассмотренный на лекции, доработайте его следующим образом (либо напишите с нуля):

1. При пустой форме ввода список не отображается (**в state он должен быть пустым!**)
2. Выводится сообщение: "Type something to search..."

#### Задача

Реализовать поиск на сайте. Именно поиск, а не
фильтрацию. Это значит, что мы должны отправлять HTTPзапрос на сервер, дожидаться ответа и отображать
результаты
