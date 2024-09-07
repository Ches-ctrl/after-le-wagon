# From Demo to MVP 🚀

## What to build in 🏗️

Build your MVP in Rails.

You already have a demo that you can port over. You know Rails. Your collaborators know Rails.

You're going to get a proper CTO to rebuild you a full JavaScript stack later anyway.

## Testing 🧪

* You didn't learn about testing during the Bootcamp. This is key. Have a watch of this [Le Wagon lecture](https://kitt.lewagon.com/knowledge/tutorials/rails_testing).

## Rails Templates 👷 (open source)

* [rails-templates](https://github.com/lewagon/rails-templates) - Le Wagon's own ('24)
* [templatus-hotwire](https://github.com/templatus/templatus-hotwire) - with hotwire ('23)
* [templatus-vue](https://github.com/templatus/templatus-vue) - with vue ('23)
* [templatus-inertia](https://github.com/templatus/templatus-inertia) - with inertia ('23)
* [modern-rails-templates](https://github.com/damienlethiec/modern-rails-template) - a little old but some great gems/ideas ('18)
* [rails-composer](https://github.com/RailsApps/rails-composer) - same as above ('18)
* [suspenders](https://github.com/thoughtbot/suspenders) - thoughtbot's standard template ('24) <<
* [daisy-on-rails](https://github.com/adrienpoly/daisy-on-rails) - daisy on rails ('24)
* [bullet_train](https://github.com/bullet-train-co/bullet_train) - bullet_train ('24) <<
* [nextgen](https://github.com/mattbrictson/nextgen) - with vite support ('24)
* [rails-template](https://github.com/ackama/rails-template) - ackama's template ('24)
* [API boilerplate](https://github.com/rootstrap/rails_api_base) - rootstrap's API only template ('24)
* [ruby-rails-boilerplate](https://github.com/maearon/ruby-rails-boilerplate) - Docker-based template ('24)
* [rails-tabler](https://github.com/tarunvelli/rails-tabler-starter) - Rails template using the UI framework Tabler ('24)

## Rails Boilerplates 🍽️ (paid)
* [Jumpstart Pro](https://jumpstartrails.com/) - GoRail's super popular template (£249) <<
* [Business Class Template](https://businessclasskit.com/) - built-in Kamal ($169)
* [multi-tenancy boilerplate](https://saas.corsego.com/) - Corsego's template for apps with multiple user organisations
* [saas-boilerplates.dev](https://saasboilerplates.dev/tags/ruby-on-rails/) - various RoR boilerplates (free & paid)

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
* [caxlsx](https://github.com/caxlsx/caxlsx) - xlsx generator
* [ahoy_email](https://github.com/ankane/ahoy_email) - first-party email analytics

## Key Providers

Some great lists:
* [awesome-startup-tools-list](https://github.com/Ibexoft/awesome-startup-tools-list)
* [awesome-startup-credits](https://github.com/dakshshah96/awesome-startup-credits)

And some favourites:
* [Vercel](https://vercel.com/) - PaaS
* [Stripe](https://stripe.com/gb) - payments
* [Linear](https://linear.app/) - issue tracking
* [Google Analytics](https://marketingplatform.google.com/intl/en_uk/about/analytics/) - web traffic
* [Mixpanel](https://mixpanel.com/) - site analytics
* [Hotjar](https://www.hotjar.com/) - user behaviour

## Further resources 📝

* [ByteByteGo newsletter](https://bytebytego.com/)
* [Ruby Weekly newsletter](https://rubyweekly.com/)
* [JavaScript Weekly newsletter](https://javascriptweekly.com/)
* [awesome-web-design](https://github.com/nicolesaidy/awesome-web-design)

## FAQs

_**What features/design elements do most web apps have that we didn’t have during demo days? i.e. what takes it to looking and working like a real site?**_
- As long as you have a core journey that fulfils your users’ jobs to be done, don't worry too much about this
- Easy solution if you're worried about this is to buy a template for a few bucks
- Remember you can improve this with usability testing later

_**Are there various benchmarks for web apps for things like number of pages, speed of load etc.?**_
- Yes there are but as long as it’s not slowwww don't worry
- Take a look at [website-response-times](https://www.nngroup.com/articles/website-response-times/) if you're interested
- The stats you should really care about are "are people visiting my site" and eventually "which parts". You can start with stuff like google analytics, or Mixpanel. This being said, if you have < 100 customers, _talking_ to them is faster/easier

_**We didn’t touch questions like code scalability, production DB management, sourcing live data - are there tutorials/benchmarks for this?**_
- Scale is really about "burn that bridge when it will be needed". It's not now, or probably the next two years. It's a nice problem to have that can be solved by throwing money at it (i.e. hire a senior dev)
- Here's a resource on [code scalability](https://www.devgraph.com/resource/developers-guide-scale-rails-apps/)
- Live data comes from APIs, scraping or building manually - make a call what you need

_**What about cybersecurity, customer data management (GDPR) etc.**_
- Don't worry too much about cybersecurity for now but here are some general principles:
	- Keep dependencies updated
	- Ensure you use HTTPS
	- Don’t hardcode sensitive info
	- Encrypt user passwords
	- Avoid using raw SQL queries to prevent SQL injections
- On GDPR, understand the principles and read [this resource for startups](https://www.cookieyes.com/blog/gdpr-compliance-for-startups/)

_**Are there a common list of gems that ruby apps will typically install?**_
- Yes and [here are some](https://taglineinfotech.com/ruby-on-rails-gems/#What_is_Ruby_Gem_Used_For)
- General principle is to only use Gems when you need them
- Remember they are also a dependency for your app
