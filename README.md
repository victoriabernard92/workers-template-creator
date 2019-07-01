# Template Creator

This is the template creator. To make a template:

1. run `git clone https://github.com/victoriabernard92/workers-template-creator myTempName`

2. `cd myTempName`

3. Add project logic to the directory. Run `npm install`.

4. Specify the entry point of the Worker script in package.json in `main` property.

5. Fill out the `README.md`. Make sure to include:

   - Description of what the Worker accomplishes.
   - Demo. Ideally a demo using cloudflareworkers.com, but for Worker demos requiring special headers,
     POST bodies,.. a live demo of where the Worker is running also works.

6. Commit source files omitting build files of course.

7. Host a public repo, and then test your project by running `wrangler generate https://github.com/<your-repo>`.

8. (Boilerplate) Submit a PR to add the template to the [template gallery](https://github.com/cloudflare/cloudflare-docs/edit/master/content/templates/_index.md) after having it approved.
   (Snipper) Submit your code to Victoria. Ideally as a PR to a repo you own
