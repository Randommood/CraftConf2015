# Testing and Integration (The Remix)

Accompanying repository for the "Testing and Integration (The Remix)" talk given at [CraftConf 2015](craft-conf.com/2015). Feel free to open any issues for questions and/or to say hi :)

## Abstract
Let's face it, testing distributed systems is hard.  Large number of inputs, partial failures, and asynchrony make these systems seemingly impossible to verify.  Formal testing methods are onerous and system correctness continues to elude us.
Despite the difficulty, we need to have a way to change our systems with confidence.  Integration and unit tests are vital to our sanity and we know it's good for us to use continuous integration to ensure functional consistency across our products.

Come to this talk for a fresh and practical look into the various aspects of distributed systems testing and integration. We will cover CI pipelines: their strengths, weaknesses, and ways to  improvement them. Get ready to rediscover the untapped power of your integration practices and develop a burning desire to make them more awesome!


## Talk Outline
See the [image credits](credits.md) - link to slides and video coming soon.

The talk is broken down in 3 main sessions:
* Testing Distributed Systems
  * Challenges of testing
  * Distributed System Testing in Academia
* Continuous Integration
  * CI challenges
  * Patterns
* Conclusions

The epic soundtrack to this talk can be found on the [CraftConfTalk](https://open.spotify.com/user/randommood/playlist/6DWpHPDyR2F7yBZW4iKL2U) Spotify playlist.

![XKCD code quality](http://imgs.xkcd.com/comics/code_quality.png)


# References

### Distributed Systems Testing
* [My RICON 2014 talk](https://github.com/Randommood/RICON2014) has a deeper look into academic testing.

### Testing practices
* http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid
* http://technologyconversations.com/2013/12/24/test-driven-development-tdd-best-practices-using-java-examples-2/
* http://java.dzone.com/articles/canary-tests
* http://martinfowler.com/bliki/TestPyramid.html

### Continuous Integration
* http://en.wikipedia.org/wiki/Continuous_integration
* http://martinfowler.com/articles/continuousIntegration.html
* http://www.thoughtworks.com/continuous-integration
* http://www.amazon.com/gp/product/0321336380
* http://www.slant.co/topics/186/compare/~circleci_vs_shippable_vs_codeship
* https://www.quora.com/What-is-the-difference-between-Bamboo-CircleCI-CIsimple-Ship-io-Codeship-Jenkins-Hudson-Semaphoreapp-Shippable-Solano-CI-TravisCI-and-Wercker


### Code Quality
* https://codeclimate.com/

### Continuous Delivery
* [Continuous Deployment @ Flickr](https://vimeo.com/24542044)
* https://www.chef.io/solutions/continuous-delivery/
* [ChefConf 2015: Chef Delivery talk](https://www.youtube.com/watch?v=fMyWM2LkwBk) & [Slides](https://speakerdeck.com/sfalcon/delivery-with-chef)
* https://github.com/opscode-cookbooks/delivery-truck
* https://github.com/chef/delivery-cli
* [Package Management in Chef](https://www.youtube.com/watch?v=-HJ7EZ85THU&index=34&list=PL11cZfNdwNyO9CpTWH2qjYfzysEtpfOCd)

### DevOpsy
* [Adam Jacob's ChefConf 2015 keynote](https://www.youtube.com/watch?v=_DEToXsgrPc) & https://github.com/chef/devops-kungfu
* [ChefConf 2014: Jamie Winsor, "The Berkshelf Vision"](https://www.youtube.com/watch?v=Dq_vGxd-jps)
* [How does Etsy manage development and operations](https://codeascraft.com/2011/02/04/how-does-etsy-manage-development-and-operations/)
* [Flickr](http://code.flickr.net/2009/12/02/flipping-out/)
* [10+ Deploys Per Day: Dev and Ops Cooperation at Flickr](http://www.slideshare.net/jallspaw/10-deploys-per-day-dev-and-ops-cooperation-at-flickr)

### General
* http://en.wikipedia.org/wiki/Linear_system
