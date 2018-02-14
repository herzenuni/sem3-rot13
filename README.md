# sem3-rot13
Необходимо разработать программу, реализовывающую алгоритм шифрования [ROT13](https://ru.wikipedia.org/wiki/ROT13).

#### Требования к программе
* оформление должно соответствовать стандарту [PEP8](https://www.python.org/dev/peps/pep-0008/);
* ввод и вывод данных следует реализовать в отдельной функции;
* должна считывать текстовую строку из файла/из консоли;
* должна генерировать исключение в случае, если файл не найден на диске;
* должна кодировать/раскодировать строку и отображать её на экране;
* должна записывать закодированную/раскодированную строку в файл;
* тесты должны содержатся в блоке кода после `if __name__ == '__main__':`;
* должна содержать описание, выполненное с помощью docstring.

##### В программе должен использоваться механизм обработки исключений
```python
try:
  pass
except SomeException:
  pass
finally:
  pass
else:
  pass
```

#### Оформление тестов
Тесты должны быть оформлены следующим образом: 
* один тест — одна функция;
* название функции начинается со слова тест, слова отделяются символом «_»;
* в качестве оператора проверки используется оператор `assert`.
