# Maksim Panineyeu  
---  
### Contact information:  
#### Phone: +375 29 750 85 73
#### E-mail: <pan71@tut.by>
#### Telegram: @madmax1412
---  
### About myself:
I'm 49 y.o. I have technical aducation.
I'm going to become a front-end developer
### Skills:
- HTML5, CSS3
- JavaScript Basics
- VS Code  
### Code example:
  ```
  const calc = (size, material, options, promocode, res) => {
    const sizeBlock = document.querySelector(size),
          materialBlock = document.querySelector(material),
          optionsBlock = document.querySelector(options),
          promocodeBlock = document.querySelector(promocode),
          resBlock = document.querySelector(res);
    let sum = 0;
    const calcPrice = () => {
        sum = Math.round((+sizeBlock.value) * (+materialBlock.value) + (+optionsBlock.value));
        if(sizeBlock.value == '' || materialBlock.value == '') {
            resBlock.textContent = 'Пожалуста введите размер и материал картины';
        } else if(promocodeBlock.value === 'IWANTPOPART') {
            resBlock.textContent = Math.round(sum * 0.7);
        } else {
            resBlock.textContent = sum;
        }
    };
    sizeBlock.addEventListener('change', calcPrice);
    materialBlock.addEventListener('change', calcPrice);
    optionsBlock.addEventListener('change', calcPrice);
    promocodeBlock.addEventListener('input', calcPrice);
};
export default calc;   
```
### Education and courses:  
- Udemy: WEB-разработчик 2021
- Udemy: Полный курс по JavaScript + React - с нуля до результата  
### Language:  
I graduated from the special faculty of the Minsk University of Foreign Languages 
my English level is between A2 and B1.
my English level is between A2 and B1.Long time i workd only with aviation english.