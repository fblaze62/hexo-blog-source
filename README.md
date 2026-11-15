>[!CAUTION]
> ***This repository is no longer updated. New blog at [fblaze62/blog](https://github.com/fblaze62/blog) repository.***

## [[OLD] *FeatherBlaze's Hexo Blog*](https://github.com/fblaze62/hexo-blog) Source Code

[Preview](https://hexo.fblaze62.top/)

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


5. Configuration

   Refer to [Hexo documentation](https://hexo.io/docs/) and [Volantis theme documentation](https://volantis.js.org/v6/getting-started/).

6. Deploy

   Modify the repo and branch fields in the deploy section of \_config.yml.

   ```bash
   npx hexo deploy
   ```

   Deploy using *GitHub Pages* or *Cloudflare Workers / Pages*.
