# CV

## Анна Борковская

## Контакты:

- annaborkovskaja@gmail.com
- +375 (29) 282 23 81

## Summary:

    Имею хорошие коммуникативные способности. Добросовестная, организованная. Готовность к обучению и развитию. Предприимчивая, инициативная.
Вежливая, честная, тактичная.

## Skills: 

- HTML
- CSS
- JS
- основы Git
- знание SOLID принципов 
- знание методологии scrum

## Код из задания "Любовный треугольник"

```JS
module.exports = function getLoveTrianglesCount(preferences = []) {
  let count = 0;
  for (let i = 0; i < preferences.length; i++) {
    if (
      preferences[i] -1 != i &&
      preferences[i] - 1 < preferences.length &&
      preferences[preferences[i] - 1] - 1 < preferences.length &&
      preferences[preferences[preferences[i] - 1] - 1] - 1 == i
    ) {
      count++;
    }
  }
  return count / 3;
};
```

## Опыт: 

- Написание лабораторных работ по C++
- Вёрстка страниц с использованием HTML и CSS
- Выполнение заданий на JS
- Прохождение курсов на HTML Academy и Codecademy

## Образование:

- БГУИР, факультет компьютерного проектирования (ФКП)
- Прохождение курсов на HTML Academy и Codecademy
- Прохождение курсов по английскому языку (офлайн)

## Уровень английского:

### A2 - 1год курсов 
