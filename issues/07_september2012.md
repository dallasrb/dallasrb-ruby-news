# Last Month in Ruby (September 2012)
* Covers what happened in the world of Ruby last month.
* Covers news relevant to you as Ruby Developer that you might have missed.
* Current month available at http://news.dallasrb.org
* Past issues available at http://github.com/hkarthik/dallasrb-ruby-news

# Recursive SQL using Postgres WITH RECURSIVE and Active Record
* Blog post from Hashrocket describing how to use SQL WITH with Postgres and
  Active Record.
* Reduces round trips and reduces AR object creation for performance gains.
* http://bit.ly/QVdF4T

# Rails in Real Time
* Blog post from the Layervault team.
* Talks about how they get real time interactivity using Rails, Socket IO, and Russian
Doll caching.
* Neat stuff to push Rails further without having to introduce Node.js.
* http://bit.ly/QVe1se

# Refactoring in Practice: Speeding up your Rails tests
* Blog post from Nate Klaiber of MixPanel.
* Describes the common ways to decouple tests from Rails and downsides of doing that.
* Offers strategies for speeding up tests without creating too much test noise/setup.
* http://bit.ly/PsB4JR

# Protected Methods and respond_to? in Ruby 2.0
* Blog post from Aaron Patterson.
* Describes why respond_to? will return false for protected methods in Ruby 2.0
* Can override default with respond_to(true)?
* Important to keep this in mind when Ruby 2.0 comes out.
* http://bit.ly/P8L7cf

# Pragmatic Concurrency with Ruby
* Blog post from Dotan Nahum.
* Describes in great detail some of the concurrency concerns across MRI and JRuby.
* Lengthy read, but well worth it.
* http://bit.ly/PsCfsA

# Strong parameters by default in Rails 4.0
* DHH commit to add strong parameters to Rails 4.0 by default.
* Goodbye attr_accessible.
* More guidance will come, but this is where Rails 4.0 is headed.
* http://bit.ly/PsDgB5

# Raise Hell through better error messages
* Blog post from Richard Schneeman at Heroku
* Describes strategies to raise better exceptions and bubble them up appropriately
in your Rails apps.
* Based on his experience teaching students new to Rails. Very useful for beginners.
* http://bit.ly/PsFWys

# Rescuing Resque Call to Action
* Blog post from Steve Klabnik
* Call to action to get more contributors on Resque which is suffering from neglect.
* Significant progress already made, but if you are using Resque and have benefitted from it, 
now is the time to give back.
* http://bit.ly/PsFJLR

# Maximizing Performance on Ruby 1.9.3
* Blog post from Luke Ludwig.
* Described process used at Ngin to optimize Ruby 1.9.3 via Nginx Workers, Rails Processes, and GC variables.
* http://bit.ly/PsFpfQ

# Rails 4.0 Release Notes DRAFT
* Edge Rails guide with Rails 4.0 release notes
* Still very much a Work In Progress.
* http://edgeguides.rubyonrails.org/4_0_release_notes.html

# Rails Rumble Open for registration
* 48 hour contest to build the best Rails app.
* http://blog.railsrumble.com/

# Releases
* RubyMotion 1.24 (iOS 6 support)
* Sequel 3.40
* Bundler 1.2
* ActiveAdmin 0.5.0

# Notable Gems and Code
* zeus: Boot any rails app within a second. http://bit.ly/P8LLq9
* pg_power: Add Postgres extensions to ActiveRecord. http://bit.ly/PsCWlB

# Thanks!
* Sign up for RubyWeekly.com.
* Email me at kar.hariharan@gmail.com.
* Current month available at http://news.dallasrb.org
* Past issues available at http://github.com/hkarthik/dallasrb-ruby-news
