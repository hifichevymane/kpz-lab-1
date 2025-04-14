# Лабораторне заняття №1

## Ознайомлення з TypeScript

**Мета:** Ознайомитися з основами мови TypeScript шляхом виконання практичних завдань, що демонструють базові можливості мови: типізацію, інтерфейси, класи, композитні типи та дженерики.

## Завдання:

**1. Типізація змінних**

- *Оголосіть змінні наступних типів: string, number, boolean, array, object.*
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%201/1.png?raw=true)
![Неправильні дані](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%201/2.png?raw=true)

- *Створіть функцію, яка приймає як аргумент об'єкт із полями name (тип string) та age (тип number) і повертає рядок виду: "Name: John, Age: 30".*
![Функція](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%201/3.png?raw=true)
![Тестування функції](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%201/4.png?raw=true)
![Неправильні дані](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%201/5.png?raw=true)

**2. Інтерфейси**

- *Оголосіть інтерфейс Person, який містить поля:*
  - name: string
  - age: number
  - address?: string (опціональне поле)
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%202/1.png?raw=true)

- *Реалізуйте функцію printPerson, яка приймає об'єкт типу Person та виводить його дані у консоль.*
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%202/2.png?raw=true)
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%202/3.png?raw=true)

**3. Композитні типи**

- *Оголосіть об'єднаний тип (union type), наприклад: type Status = 'success' | 'error' | 'loading';*
- *Реалізуйте конструкцію (наприклад, функцію або умову), яка виводить повідомлення відповідно до значення Status.*
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%203/1.png?raw=true)
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%203/2.png?raw=true)

**4. Дженерики**

- *Реалізуйте функцію identity<T>(value: T): T, яка повертає передане їй значення.*
- *Використайте її для типів number, string та boolean.*
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%204/1.png?raw=true)

**5. Класи**

- *Реалізуйте клас Car, який містить поля: model: string; year: number*
- *Додайте метод getCarInfo(), який повертає рядок виду: "Model: Toyota, Year: 2020".*
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%205/1.png?raw=true)
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%205/2.png?raw=true)
![Оголошення змін](https://github.com/hifichevymane/kpz-lab-1/blob/main/Task%205/3.png?raw=true)

