# Собственно говоря сам CV
[Ради примера добавил ссылку на Google](https://google.com)
>Уважать всякого человека, как самого себя, и поступать с ним, как мы желаем, чтобы с нами поступали, — выше этого нет ничего. 

#### Небольшой код JavaScript
```javascript
let low = 0;
let high = list.length - 1;

while (low <= high) {
    let mid = Math.floor((low + high) / 2);
    let guess = list[mid];

    if (guess === item) return mid;

    if (guess > item) high = mid - 1;
    else low = mid + 1;
  }
    return undefined;
```