```ruby
class AboutMe
  attr_accessor :name, :overview, :my_blog, :twitter, :favourite_programming_languages, :open_sources

  def initialize
    @name = "Tenma Hashizume"
    @overview = "I am an engineer in my third year of experience. Recently, I have been studying AWS."
    @my_blog = "https://kyoto-kanko.jp"
    @twitter = "https://twitter.com/kyoto_kanko_jp"
    @favourite_programming_languages = ["Ruby", "Java"]
    @open_sources = [
      "https://github.com/kyoto-kanko/color-greeting",
      "https://github.com/kyoto-kanko/task-piggy"
    ]
  end
end

about_me = AboutMe.new
puts about_me.inspect
```

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kyoto-kanko&theme=buefy)
![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kyoto-kanko&theme=buefy)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kyoto-kanko&theme=buefy)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=kyoto-kanko&theme=buefy)
![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=kyoto-kanko&theme=buefy&utcOffset=9)
