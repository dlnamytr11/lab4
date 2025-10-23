# Лабораторная работа №4: CSS-библиотеки.

## Лендинг на Bootstrap
<img width="1920" height="1080" alt="image" src="https://github.com/dlnamytr11/lab4/blob/main/bootstrap-landing/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA.PNG" />
<img width="1920" height="1080" alt="image" src="https://github.com/dlnamytr11/lab4/blob/main/bootstrap-landing/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA1.PNG" />
<img width="1920" height="1080" alt="image" src="https://github.com/dlnamytr11/lab4/blob/main/bootstrap-landing/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA2.PNG" />


## Лендинг на Tailwind
<img width="1920" height="1080" alt="image" src="https://github.com/dlnamytr11/lab4/blob/main/tailwind-landing/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA3.PNG" />
<img width="1920" height="1080" alt="image" src="https://github.com/dlnamytr11/lab4/blob/main/tailwind-landing/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA4.PNG" />
<img width="1920" height="1080" alt="image" src="https://github.com/dlnamytr11/lab4/blob/main/tailwind-landing/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA5.PNG" />

#Ответы на вопросы:
## Какой подход (компонентный Bootstrap или utility-first Tailwind) показался вам удобнее для этой задачи и почему?
### Bootstrap показался мне удобнее, так как он предоставляет уже готовые стили, но он неудобен когда нам необходима более гибкая стилизация нашей страницы. Tailwind в свою очередь удобен когда необходима гибкость в стилизации страницы. Однако код с его использованием получается громоздким и плохо-читаемым. Tailwind не очень подходит для небольших проектов.
## Приведите пример кода для одного и того же элемента (например, кнопки) на Bootstrap и на Tailwind из вашей работы. В чем ключевое различие в разметке?
### Bootstrap:
```html
<a href="#about" class="btn btn-light btn-lg mt-3">Узнать больше</a>
```
### -Tailwind:
```html
<a href="#about" class="bg-white text-indigo-700 font-semibold px-6 py-3 rounded-lg hover:bg-gray-100 transition">
  Узнать больше
</a>
```
## С какими сложностями вы столкнулись при работе с каждой из библиотек?
### В Tailwind и Bootstrap множество классов-стилей имеют сложные и непонятные названия, из-за чего не всегда понятно, какой за что отвечает.
## Какой блок вы добавили дополнительно?
### В Bootstrap лендинге блок отзывов.
### В Tailwind лендинге блок для контактов.
## Какие запросы вы использовали для помощи ИИ? Насколько полезными были ответы?
```
Сгенерируй адаптивный лендинг для вымышленного продукта с использованием Bootstrap 5. Пусть будет хедер, секция с описанием, блок преимуществ (3 карточки), футер. Добавь теги meta для адаптивности.
```
```
страница должна содержать минимальный набор компонентов: ○ Навигационную панель (<nav class="navbar">...). ○ Главный экран («hero section») с заголовком и кнопкой (<div class="container">..., <button class="btn btn-primary">). ○ Секцию с описанием продукта (<section class="about">…) ○ Секцию с тремя карточками преимуществ продукта (<div class="card">...) ○ Подвал с навигацией (<footer>...).
```
```
сделай такую же версию только на tailwind, чтобы были они похожи.
```
```
«Сгенерируй блок отзывов для страницы, использующей библиотеку Bootstrap»
```
```
«Создай контактную форму для лендинга с Tailwind»
```
### Ответы оказались полезными, однако при генерации страницы с использованием Tailwind ИИ неправильно отображалась навигационная панель.
