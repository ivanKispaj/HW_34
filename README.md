# HW_34

## Ваша задача — потренироваться в написании концептов.
    Напишите концепт под названием ComplexConcept<T> , который будет накладывать следующие ограничения на тип:
    
<ul>
  <li>Наличие у типа T метода hash(), который возвращает тип, конвертируемый в long; </li>
    <li>Наличие у типа T метода toString(), который возвращает std::string; </li>
    <li>Отсутствие у типа T виртуального деструктора. </li>
</ul>

## реализованно:
    метод -> void testFunction(ComplexConcept auto &val)
    принимает на вход любой объект, ктороый соответствует 
    правилам в ComlexConcept!
    У него должны быть 2 метода ->  hash() и toString(),
    и должен отсутствовать виртуальный деструктор!

    При передаче объектов несоответствующих данным требованиям приведет к ошибке на этапе компиляции!

### компиляция:
      make -f makefile
      создаст каталог bin в каталоге с проектом и исполняемый файл в каталоге bin.
