# Repository to verify the issue where the build fails when NODE_ENV is set to 'development'

next version: 13.5.1 or 13.5.2


## Please run the following
``` sh
NODE_ENV=development npm run dev
```

## log
```sh
---
Error occurred prerendering page "/404". Read more: https://nextjs.org/docs/messages/prerender-error
Error: <Html> should not be imported outside of pages/_document.
Read more: https://nextjs.org/docs/messages/no-document-import-in-page
---
Error occurred prerendering page "/". Read more: https://nextjs.org/docs/messages/prerender-error
TypeError: Cannot read properties of null (reading 'useContext')
---
```
