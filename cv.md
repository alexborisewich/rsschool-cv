# Aliaksei Barysewich

### _Junior Frontend Developer_

---

#### Contact information:

![Location](./img/icons/map.png) **Minsk, Belarus**
[![Phone](./img/icons/phone-call.png)](tel:+375336742330) [**+375336742330**](tel:+375336742330)
[![e-mail](./img/icons/gmail.png)](mailto:alexboris61529@gmail.com) [**alexboris61529@gmail.com**](mailto:alexboris61529@gmail.com)

[![WhatsApp](./img/icons/whatsapp.png)](https://wa.me/+375336742330) [![Viber](./img/icons/viber.png)](https://msng.link/o/?375336742330=vi) [![Telegram](./img/icons/telegram.png)](https://t.me/albo61529) [![LinkedIn](./img/icons/linkedin.png)](https://linkedin.com/in/alexborisewich) [![GitHub](./img/icons/github-logo.png)](https://github.com/alexborisewich) [![Facebook](./img/icons/facebook.png)](https://www.facebook.com/profile.php?id=100078016082384) [![Instagram](./img/icons/instagram-logo.png)](https://www.instagram.com/alexborisewich/) [![VK](./img/icons/vkontakte.png)](https://vk.com/alexborisewich) [![Twitter](./img/icons/twitter.png)](https://twitter.com/alexborisewich) [![Discord](./img/icons/discord.png)](https://discord.gg/QvEYg7EaQ4) [![Skype](./img/icons/skype.png)](https://join.skype.com/invite/MR0s1GEIyNbe)

---

#### About myself:

Let me introduce myself. My name is Aliaksei Borisewich. I was born on the 16th of March 1992. I am an individual entrepreneur. After graduation from university, I served for five years in the internal affairs agencies. Then I worked in the RUE "Belmedpreparaty" as the head of the economic security department. In 2021, I decided to try something new, and I started to be interested in software development. It immediately became interesting for me. I want to get the position of Junior Front-End Developer.

---

#### Skills:

- HTML5(Semantic)
- CSS3(Flexbox, Grid)
- SASS(SCSS)
- BEM
- MaterialUI
- Bootstrap
- Git, GitHub
- VS Code
- SASS (SCSS)
- BEM methodology
- JavaScript
- TypeScript
- React,
- Redux,
- Jest,
- REST API,
- Webpack,
- ESLint,
- Prettier,
- Git,
- Figma, Adobe Photoshop.

---

#### Code example:

```
import React from 'react';
import { Navigate, Outlet } from 'react-router-dom';

import { types } from '.';

import { PATHS, PRIVACY_REASONS } from 'data';

const PrivateRoute = ({ isAvailable, privacyReason }: types.PrivateRouteProps) => {
  if (privacyReason === PRIVACY_REASONS.notForUser && !isAvailable) {
    return <Navigate to={PATHS.main} replace />;
  }
  if (privacyReason === PRIVACY_REASONS.userOnly && !isAvailable) {
    return <Navigate to={PATHS.welcome} replace />;
  }
  return <Outlet />;
};

export default PrivateRoute;
```

---

#### Education:

[The Academy of the Ministry of Internal Affairs of the Republic of Belarus](https://www.amia.by/), Faculty of militia, Economic lawyer (2009-2014).

---

#### Courses:

- "Website development basics" [BelHard Academy](https://www.belhard.com/ru/) ([certificate](https://drive.google.com/file/d/1URsgiz_bMpTIBKIo_m9GsTMh5xeXo3GN/view?usp=drivesdk))
- "Modern Front-End with JavaScript and HTML5" [BelHard Academy](https://www.belhard.com/ru/) ([certificate](https://drive.google.com/file/d/1Ed0x4ViL_sOZ8ejT5FnnOM0QFrdQs2ho/view?usp=drivesdk))
- JavaScript/Front-End 2022Q1 (Javascript) [The Rolling Scopes School](https://rs.school/) ([certificate](https://app.rs.school/certificate/127nj3k0))
- React 2022Q3 [The Rolling Scopes School](https://rs.school/) ([certificate](https://app.rs.school/certificate/3yjm0udy))

---

#### Experience:

There’s no commercial experience yet.

---

#### Languages:

- English - (B1) Intermediate (according to the online test at [![EFset](./img/efset-logo_black.svg)](https://www.efset.org/)
[<img src="./img/englevel.jpg" width="300"/>]()
- Belorussian - Native
- Russian - Native
- Ukrainian - Elementary
- Polish - Elementary
