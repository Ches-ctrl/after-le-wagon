# From Demo to MVP 🚀

## What to build in 🏗️

Build your MVP in Rails.

You already have a demo that you can port over. You know Rails. Your collaborators know Rails. You're going to get a proper CTO to rebuild you a full JavaScript stack later anyway.

## Testing 🧪

* You didn't learn about testing during the Bootcamp. This is key. Have a watch of this [Le Wagon lecture](https://kitt.lewagon.com/knowledge/tutorials/rails_testing).
* And stop any timing issues with [capybara-lockstep](https://github.com/makandra/capybara-lockstep)

## Rails Templates 👷

* [modern-rails-templates](https://github.com/damienlethiec/modern-rails-template) - a little old but some great gems/ideas
* [rails-composer](https://github.com/RailsApps/rails-composer) - same as above

## Cool libraries 🤖

* [Stimulus Components](https://github.com/stimulus-components/stimulus-components) - yup, you didn't need to code all of those stimulus controllers
* [Stimulus-hotkeys](https://github.com/leastbad/stimulus-hotkeys) - stimulus controllers for keyboard input
* [pghero](https://github.com/ankane/pghero) - performance dashboard for Postgres
* [Ruby on Jets](https://github.com/rubyonjets/jets) - for AWS Lambdas

## Cool gems 💎

Some great lists:
* [Awesome Ruby](https://github.com/markets/awesome-ruby) << has everything!
* [Awesome Ruby](https://github.com/sdogruyol/awesome-ruby) << A more curated list
* [Awesome Rails Gem](https://github.com/hothero/awesome-rails-gem) << another gem list
* [List of top gems](https://taglineinfotech.com/ruby-on-rails-gems/#What_is_Ruby_Gem_Used_For)
* [Some more cool gems](https://github.com/damienlethiec/modern-rails-template?tab=readme-ov-file#what-is-included)

And some favourites:
* [spidr](https://github.com/postmodern/spidr) - web crawler
* [avo](https://github.com/avo-hq/avo) - admin interface
* [money-rails](https://github.com/RubyMoney/money-rails) - moneeyyy
* [huginn](https://github.com/huginn/huginn) - automated agents
* [derailed_benchmarks](https://github.com/zombocom/derailed_benchmarks) - performance benchmarks
* [brakeman](https://github.com/presidentbeef/brakeman) - security for rails

## Things that can wait for later

* TODO

## Key Providers
* [Vercel](https://vercel.com/) - PaaS
* [Stripe](https://stripe.com/gb) - Payments
* [Linear](https://linear.app/) - Issue tracking
* [Google Analytics](https://marketingplatform.google.com/intl/en_uk/about/analytics/) - Web traffic
* [Hotjar](https://www.hotjar.com/) - User behaviour
* [Mixpanel]() - site analytics
* []() -
* []() -
* []() -

## Further resources 📝

* [ByteByteGo newsletter](https://bytebytego.com/)
* [awesome-web-design](https://github.com/nicolesaidy/awesome-web-design)

## FAQs

_What features/design elements do most web apps have that we didn’t have during demo days? i.e. what takes it to looking and working like a real site?_
- As long as you have a core journey that fulfils your users’ jobs to be done, don't worry too much about this.
- Easy solution if you're worried about this is to buy a template for a few bucks
- Remember you can improve this with usability testing later

_Are there various benchmarks for web apps for things like number of pages, speed of load etc.?_
- Yes there are but as long as it’s not slowwww don't worry. 
- Take a look at [https://www.nngroup.com/articles/website-response-times/](https://www.nngroup.com/articles/website-response-times/) if you're interested
- The stats you should really care about are "are people visiting my site" and eventually "which parts". You can start with stuff like google analytics, or Mixpanel. This being said, if you have < 100 customers, _talking_ to them is faster/easier

_We didn’t touch questions like code scalability, production DB management, sourcing live data - are there tutorials/benchmarks for this?_
- Good questions but ones to worry about later
- Scale is really about "burn that bridge when it will be needed". It's not now, or probably the next two years. It's a nice problem to have that can be solved by throwing money at it (i.e. hire a senior dev)
- Resource on [code scalability](https://www.devgraph.com/resource/developers-guide-scale-rails-apps/)

_What about cybersecurity, customer data management (GDPR) etc._
- Don't worry too much about cybersecurity for now but here are some general principles:
	- Keep dependencies updated
	- Ensure you use HTTPS
	- Don’t hardcode sensitive info
	- Encrypt user passwords
	- Avoid using raw SQL queries to prevent SQL injections
- On GDPR, understand the principles and read [this resource for startups](https://www.cookieyes.com/blog/gdpr-compliance-for-startups/)

_Are there a common list of gems that ruby apps will typically install?_
- Yes and [here are some](https://taglineinfotech.com/ruby-on-rails-gems/#What_is_Ruby_Gem_Used_For)
- General principle is to only use Gems when you need them
- Remember they are also a dependency for your app
