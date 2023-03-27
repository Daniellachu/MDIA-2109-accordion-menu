This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# Environmental Variable

1. create a file at the root of the projects

```

.env
```

2. inside the .env file add the text:

- you must use `NEXT_PUBLIC` or else this will not work

```

NEXT_PUBLIC_TITLE = "Digital Design and Development"
```

3. On the page, in between the export and return write the variable:

```

var title = process.env.NEXT_PUBLIC_TITLE;
```

4. Then in between the main write:

```
{title}
```

5. Make sure the `.gitignore` file has the `.env` inside

- you want to prevent this secrete title to be shown

## Command lines

npm run dev
npx create-next-app

## BCIT data from Digital Design and Development

[Digital Design and Development Diploma Course](https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/#courses)
