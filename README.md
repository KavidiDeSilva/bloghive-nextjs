# BlogHive Next.js Project
This is a Next.js project that displays blog posts fetched from a GraphQL API. It consists of two pages, the homepage and the blog post page, and a reusable BlogCard component.

## Getting Started
To get started with this project, you can follow these steps:

Clone the repository to your local machine using `git clone https://github.com/KavidiDeSilva/bloghive-nextjs.git.`

Navigate to the project directory using `cd BlogHive`.

Install the dependencies using `npm install`.

Start the development server using `npm run dev`.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Click on a blog post to see the blog post page.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.


## Technologies Used
This project was built using the following technologies:

- Next.js
- GraphQL
- GraphQL Request
- Inter font from Google Fonts
- CSS modules

## Pages
This project has two pages:

### Homepage
The homepage displays a list of blog posts fetched from the GraphQL API. Each blog post is displayed using the reusable BlogCard component.

### Blog Post Page
The blog post page displays a single blog post fetched from the GraphQL API. It displays the title, author, cover photo, date published, and content of the blog post.

## Components
This project has one reusable component:

### BlogCard
The BlogCard component is used to display a single blog post on the homepage. It displays the title, author, cover photo, and date published of the blog post.

### GraphQL API
This project fetches blog posts from a GraphQL API. The GraphQL API is provided by GraphCMS.

## Deployment
This project is deployed using hosting services Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
