## Hi, my name is Yuri.

### Contacts
    * email: y.a.shishkin@gmaol.com
    * telegram: yuri_Ibirby
    * discord: Yuri_SH
    * github: Ibirby

### I am a student of the RS-Shcool course and dream of becoming a wonderful frontend developer. I already have some skills in site layout and programming. I have the skills to work with the following technologies:
    1. HTML, semantic, HTML5;
    2. CSS, SASS, SCSS;
    3. JavaScript;
    4. Gulp;

### If you wish, you can see my works and projects on [GitHub](https://github.com/Ibirby)

### Code example:
```
// Timer
const deadLine = '2022-11-10';
    function getTimeRemaining(endtime) {
        const t = Date.parse(endtime) - Date.parse(new Date()),
              days = Math.floor(t / (1000 * 60 *60 * 24)),
              hours = Math.floor((t / (1000 * 60 * 60) % 24)),
              minutes = Math.floor((t / 1000 / 60) % 60),
              seconds = Math.floor((t /1000) % 60);

        return {
            'total': t,
            'days': days,
            'hours': hours,
            'minutes': minutes,
            'seconds': seconds
        };
    }
    
    function getZero(num) {
        if (num >= 0 && num < 10) {
            return `0${num}`;
        } else {
            return num;
        }
    }

    function setClock(selector, endtime) {
        const timer = document.querySelector(selector),
              days = timer.querySelector('#days'),
              hours = timer.querySelector('#hours'),
              minutes = timer.querySelector('#minutes'),
              seconds = timer.querySelector('#seconds'),
              timeInterval = setInterval(updateClock, 1000);
        
              updateClock();
     
        function updateClock() {
            const t = getTimeRemaining(endtime);

            days.innerHTML = t.days;
            hours.innerHTML = getZero(t.hours);
            minutes.innerHTML = getZero(t.minutes);
            seconds.innerHTML = getZero(t.seconds);
            
            if (t.total <= 0) {
                clearInterval(timeInterval);
            }
        }
    }
```

### Education and courses:
    * SoloLearn. HTML, CSS, JS;
    * Udemy. Web разработка 2021;
    * Udemy. Полный курс JS + React;
    * Hexlet, Stepik, etc.... for learning GIT

### English level - A2 Preintermediate