## rsschool-cv

---

# Filipp Kadushkin

## Contacts:

- **Phone**: +7(960)314-55-30
- **E-mail**: kadushkin.feniks@gmail.com
- **GitHub**: https://github.com/soulflamecompany
- **GitLab**: https://gitlab.com/soulflamecompany
- **Telegram**: https://t.me/FenxxOG

## About Me

I’m 31 years old and the last thing I did before I went into the IT world was a chef at a restaurant.
While teaching frontend for 8 months I learned to work with REACT framework and have already participated in the development of several projects:

1. service to find specialists https://github.com/soulflamecompany/GENEJOB-project
2. site of photo studio https://gitlab.com/soulflamecompany/photojet-project

My goal is full immersion in _JavaScript_ to allow free study of the framework with libraries and also for easy problem solving on _CodeWars_

## Skills

- HTML
- CSS/SCSS
- JavaScript(ES6)
- React/Next.JS
- Git
- Figma

## Code Examples

```javascript
const API_URL = "https://api.openweathermap.org/data/2.5/";
const API_KEY = "ee66ee66ee66ee66ee66ee66ee66ee66e";

export const fetchWeather = async (city) => {
  try {
    const response = await fetch(
      `${API_URL}weather?&q=${city}&appid=${API_KEY}&lang=ru`
    );
    if (!response.ok) {
      throw new Error("Ошибка запроса");
    }

    const data = await response.json();
    return { success: true, data };
  } catch (error) {
    return { success: false, error };
  }
};
```

## Education

- HTML and CSS in Result School ( _Vladilen Minin_ )
- JavaScript in Hexlet ( _code-basics.com_ ) / A manual in _learn.javascipt.ru_ / Youtube course ( _Bogdan Stashchuk_ )/etc...
- React in youtube channel ( _Archakov blog_ )
  - And a bunch of different free marathons and intensives

## Languages

- Russian - Native
- English - B1

---
