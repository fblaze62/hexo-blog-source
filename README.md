>[!CAUTION]
> ***This repository is no longer updated. New blog at [fblaze62/blog](https://github.com/fblaze62/blog) repository.***

# [OLD] Source Code for [*FeatherBlaze's Hexo Blog*](https://github.com/fblaze62/hexo-blog)

[Preview](https://hexo.fblaze62.top/)

## Requirements

- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)

## Installation

1. Clone the repository

   ```bash
   git clone https://github.com/fblaze62/hexo-blog-source.git
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Build for production

   ```bash
   npx hexo clean
   npx hexo generate
   ```

4. Start the development server

   ```bash
   npx hexo server
   ```


## Configuration

   Refer to [Hexo documentation](https://hexo.io/docs/) and [Volantis theme documentation](https://volantis.js.org/v6/getting-started/).

## Deploy

   Modify the repo and branch fields in the deploy section in \_config.yml.

   ```bash
   npx hexo deploy
   ```

   Deploy using *GitHub Pages* or *Cloudflare Workers / Pages*.
