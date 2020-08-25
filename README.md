## Imminent Domain Examples

Here are a set of examples built on Next.js that should happily deploy to Vercel.
The intention is to demonstrate the sorts of things you can do with Imminent Domain.

## Getting Started

### Run Locally

First, clone and cd into the example's directory you'd like to run.

For example:

```bash
git clone https://github.com/paulkarayan/vercel-functions-immdom.git
cd vercel-functions-immdom
```

Then run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Deploy to Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

At some point, we'll put links to make this trivially easy in all the example directories.

## What is Imminent Domain?

<p align="center">
  <img src="_assets/thinker.png" />
</p>

Imminent Domain (ImmDom) is an Open Source, community-run software platform.
Our purpose is to accelerate software product development with the sole KPI (key performance indicator)
of Time From Idea to MVP (well - you can argue "time to iteration step" more broadly. work with me, people!)

To accomplish this goal, we curate best of breed tech and build our own where it's needed.

The Foundation Project (forthcoming) has focused around rapid infrastructure build out,
centered around enabling technologies like AWS/GCP and Terraform. We also provide
tutorials and educational materials such as these examples.

## Other Things

### Wish List

We welcome your thoughts on how to achieve our state goal, as well as your contributions.

Please use Github Issues to request additional examples, features, or to file bugs.
We'd also love to showcase community examples. We won't bite - promise!

### Generating the Site

We use Showdown.

```
npm install showdown -g
showdown makehtml -i README.md -o index.html
```

then copy the code into "dummy"

and then add CSS from
https://markdowncss.github.io/

### Catalogue of Examples - working APIs

**Javascript**

[Basic Example](functions.immdom.com/js/basic)

[Params Example](functions.immdom.com/js/param) <-- try more params with /js/param?basicThing=<insertMe>

[Use Files at Runtime Example](functions.immdom.com/js/files)

**Python**
[Basic Example](functions.immdom.com/python/basic)

[Params Example](functions.immdom.com/python/param) <-- this is different. it just prints a dict of params.

[Flask Example](https://functions.immdom.com/api?domain=google.com) <-- dns lookup on a domain.

### Catalogue of Examples - code

**Javascript**

[Basic Example](https://github.com/paulkarayan/vercel-functions-immdom/blob/master/api/js/basic.js)

[Params Example](https://github.com/paulkarayan/vercel-functions-immdom/blob/master/api/js/param.js)

[Use Files at Runtime Example](https://github.com/paulkarayan/vercel-functions-immdom/blob/master/api/js/files.js)

**Python**
[Basic Example](https://github.com/paulkarayan/vercel-functions-immdom/blob/master/api/python/basic.py)

[Params Example](https://github.com/paulkarayan/vercel-functions-immdom/blob/master/api/python/param.py)

[Flask Example](https://github.com/paulkarayan/vercel-functions-immdom/blob/master/api/index.py)

### Sponsors

(not really sponsored by but the logo is cool - and we are looking for people to help us spread the news!)

<p align="center">
  <img src="_assets/irregular_engineering.png" />
</p>
