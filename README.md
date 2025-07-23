# Diode Blog

This is the official blog for Diode, where we share insights about rebuilding the hardware toolchain.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the blog during development.

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is):

```
mintlify dev
```

## Publishing

Changes will be deployed to production automatically after pushing to the default branch.

You can also preview changes using PRs, which generates a preview link of the blog.

## Adding New Posts

To add a new blog post:

1. Create a new `.mdx` file in the root directory
2. Add frontmatter with title, description, author, and date
3. Add the post to the navigation in `docs.json`
4. Update the homepage (`index.mdx`) to include a card for the new post
