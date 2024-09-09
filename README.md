Комментарии от ментора по твоему решению ТЗ:
Введите выражение: 1 - 2
panic: некорректное число

какое число некорректно?


Честно говоря не знаю в чем проблема, у меня все получается:
@Imanius ➜ /workspaces/codespaces-blank $  cd /workspaces/codespaces-blank ; /usr/bin/env GOPATH=/go /go/bin/dlv dap --client-addr=:34149 
Введите выражение: 1 - 2
Результат: -1
@Imanius ➜ /workspaces/codespaces-blank $ ^C


Если же добавить символ полсе 2, то выдается искомая ошибка. Возможно во время проверки при вводе был задействован лишний символ?

Пример некорректного ввода:
@Imanius ➜ /workspaces/codespaces-blank $  cd /workspaces/codespaces-blank ; /usr/bin/env GOPATH=/go /go/bin/dlv dap --client-addr=:38945 
Введите выражение: 1 - 2.
panic: некорректное число
