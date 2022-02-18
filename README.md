This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

# Add MaterialUI Theme

1.  create theme
2.  use Theme provider
3.  add h1 , h2 ... styles
4.  set theme colors

# Create Application Context

1.  define context and reducer
2.  set darkMode flag
3.  create store provider
4.  use it on layout

# Connect To MongoDB

1.  install mongodb
2.  install mongoose
3.  define connect and disconnect (Utils Folder)
4.  use it in the api

# Create Products API

1. create product model
2. seed sample data
3. create /api/products/index.js
4. create product api

# Fetch Products From API

1. use getServerSideProps()
2. get product from db
3. return data as props
4. use it in product screen too

# Implement Add to cart

1. define cart in context
2. dispatch add to cart action
3. set click event handler for button

# Create Cart Screen

1. create cart.js
2. redirect to cart screen
3. use dynamic from nextjs
4. use context to get cart items
5. list items in cart items

# Use Dynamic Import In Cart Screen

1. Use next/dynamic
2. Wrap cart in dynamic with out ssr

# Update Remove Items In Cart

1.  Implement onChange for Select
2.  Show notification by notistack
3.  implement delete button handler

# Create Login Screen

1. create form
2. add email and password field
3. add login button
4. style form

# Create Sample Users

1.  create user model
2.  add sample user in seed api

# Build Login API

3.  use jsonwebtoken to sign token
4.  implement login api

# Complete Login Page

1. handle form submission
2. add userInfo to context
3. save userInfo in cookies
4. show user name in nav bar using menu

# Create Register Page

1. create form
2. implement backend api
3. redirect user to redirect page
