## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

 <h2>Mobile Version</h2>

![](https://i.postimg.cc/qvBc41cL/mobile.png)
![](https://i.postimg.cc/0jdmqSbF/mobile-1.png)
![](https://i.postimg.cc/XYD534Yj/mobile-2.png)
![](https://i.postimg.cc/s2QhgqMp/mobile-3.png)
![](https://i.postimg.cc/fyK3PhPh/mobile-4.png)


<h2>Desktop Version</h2>

![](https://i.postimg.cc/85gjP5QS/mobile-7.png)
![](https://i.postimg.cc/05fbPPVT/mobile-8.png)
![](https://i.postimg.cc/FRvHXB3F/mobile-9.png)
![](https://i.postimg.cc/X7PNYJdz/mobile-10.png)
![](https://i.postimg.cc/0Q9PBJ1b/mobile-11.png)

### Links

- Live Site URL: [live site URL](https://candingpage.web.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I've learned about the clip on the hero section, it will include a background.

Example:

```html
--hero__main--
<section class="hero"></section>
```

```css
  .hero::before {
    background-image: linear-gradient(180deg, #0000008c 0%, #0000008c 100%), url("/firstLandinPage/assets/img/computer.jpg");
    clip-path: polygon(0 0, 100% 0, 100% 80%, 50% 95%, 0 80%);
    z-index: -1;

}
}
```

## Autor
- Frontend Mentor - [@ricardozu](https://www.frontendmentor.io/profile/ricardozu)
- Twitter - [@ricardozu4](https://www.twitter.com/ricardozu4)