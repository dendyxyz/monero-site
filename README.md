## Swiss Flag-Inspired Redesign

For https://bounties.monero.social/posts/153/1-202m-create-redesign-for-getmonero-org-and-monero-logo-in-swiss-flag-inspired-color-branding

## Criteria

![Logo](swiss.png)

I am hosting a demo at https://swiss.dendy.xyz

Homepage: https://swiss.dendy.xyz/
Support Monero: https://swiss.dendy.xyz/get-started/contributing/
Merchants and Exchanges: https://swiss.dendy.xyz/community/merchants/

## Monero Address

89AaKpZyAh2XT5JJZcMmy2axcfzVrXVQY7ogJ962oHFGbmgmKZsdLjrJbKRGR9fWNTCDJkWPwQ4EghEJLWU82hks5RCwdiv

# Instructions for running locally

## What you'll need

* Jekyll: [getmonero.org](https://getmonero.org/) is made using a simple, static website generator called [Jekyll](https://jekyllrb.com/). You will need it installed on your system to test any changes that you made. Follow the instructions on the website to get up and going:
  * Install Ruby dependencies as suggested [in the Jekyll documentation](https://jekyllrb.com/docs/installation/)
  * Install Bundler: `gem install bundler`
  * Install Jekyll with all dependencies (run from the project directory): `bundle`

1. Navigate to your local `monero-site` repository.
2. Serve the website: `bundle exec jekyll serve`. If you want, you can speedup this process by loading only the last blog post instead of all of them. Simply add `--limit_posts 1` to the command above. The resulting command will be `bundle exec jekyll serve --limit_posts 1`.
3. Open a browser and go to [http://127.0.0.1:4000](http://127.0.0.1:4000).
4. If all went well, you should see the Monero website and you're ready to make changes.
