# Telephone-number-validator 🚀

## Project Description 📝

> Phone number validator project created in HTML, CSS and javaScript it can check the number is valid or not.

### HTML:
```html

  <div class="container">
    <div id="hed"></div>
    <div>
      <h3>Enter a Phone Number:</h3>
      <input type="tel" id="user-input">
    </div>
    <div id="results-div"></div>
    <div class="button">
      <button class="check" id="check-btn">Check</button>
      <button class="clear" id="clear-btn">Clear</button>
    </div>
  </div>
```
### CSS:
```css

#hed {
  width: 13px;
  height: 13px;
  background-color: black;
  margin-top: -47px;
  border-radius: 50%;
}

header {
  margin: 15px;
  padding: 15px 20px;
  font-size: 15px;
  text-shadow: 11px 11px 5px white;
  font-family: fantasy;
}

```
### JS:
```javascript


check.addEventListener('click', () => {
  const regex = /^(1\s?)?(\(\d{3}\)|\d{3})([\s-]?)\d{3}([\s-]?)\d{4}$/;

  if (!input.value) {
    alert('Please provide a phone number');
    results.innerText = '';
  } else if (regex.test(input.value)) {
    results.innerText = `Valid US number: ${input.value}`;
  } else {
    results.innerText = `InValid US number: ${input.value}`;
  }
});

clear.addEventListener('click', () => { results.innerText = ''; });

```

## Demo 📸



## Technologies Used 🛠️

- HTML
- CSS
- JavaScript

## Features ⭐

- Building Telephone number converter.

## Author 👩‍💻


- LinkedIn: (linkedin.com/in/hasina-rahmani-4a21a9311)
- Email: (hasinarahmani548@gmail.com)
- GitHub: (https://github.com/Hasinarahman/telephone-number-validator)

