#User authentication with Auth0 Part One

## Technologies

- Nextjs
- Tailwindcss
- Typescript
- next-Auth
- Auth0
  In this tutorial, we are going to setup authentication with nextjs using Auth0, run the following command in your terminal
  To begin

```bash
npx create-next-app --ts auth_one
cd auth_one
```

Inside the `auth_one` folder got to the `pages` folder select the `index.tsx` file. Replace the contents of the file with the code below

```tsx
import type { NextPage } from 'next'

const Home: NextPage = () => {
  return (
<div>
  <h1>Welcome to Auth One</h1>
</div>
}

export default Home

```

Now in your terminal, run the following code:

```bash
npm run dev
```

if you navigate to 'http://localhost:3000` you should as below:

![browser]['./imgs.jpeg']
