**Reproduced typescript issue after build in AdonisJS V6**
Follow these steps, you will see this issue

    npm install
    npm run build

Go to `build/app/models`, open `user.js`, and you will see the `import { DateTime } from 'luxon'` disappear.
