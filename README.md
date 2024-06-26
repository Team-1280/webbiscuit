# Webbiscuit

Team 1280's state-of-the-art website. Hosts Team 1280's resources, information, and more.

## Development Instructions

Check [TODOS.md](/TODOS.md) for a list of tasks that need to be completed.

The website is built with SvelteKit and TailwindCSS. To run a local development build:

Clone the repository:

```bash
# with https
git clone https://github.com/Team-1280/webbiscuit.git

# or with ssh
git clone git@github.com:Team-1280/webbiscuit.git

# or with GitHub CLI
gh repo clone Team-1280/webbiscuit

# and enter the directory
cd webbiscuit
```

Then, make sure you have [pnpm](https://pnpm.io/) installed, and then run the following to install dependencies:

```bash
pnpm install
```

Start a development server by running:

```bash
# start the development server
pnpm dev
```

The development server will run at `localhost:5173`, and it will reload automatically on file changes or module updates. However, it won't be optimized for performance.

To test a local **production** build, run this instead:

```bash
# compile and bundle the site for production
pnpm build
# serve the production build in a local test server
pnpm preview
```

The preview server runs separately from the dev server at `localhost:4173`.

## Licensing and Copyright

Our name "Team 1280" and its variants, as well as our logos and other branding assets are our copyright and trademarks (where applicable). See [our identity repo and its license for more information](https://github.com/team-1280/identity).

The source code of this website itself, however, is licensed under the GNU Affero General Public License, and is free and open source software. Additionally, all hosted versions of this site, even if modified, **must** provide its source code to end users.
