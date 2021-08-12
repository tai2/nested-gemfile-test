```
$ bundle exec foreman start
11:27:18 rspec.1 | started with pid 56770
11:27:18 rspec.1 | bundler: failed to load command: rspec (/Users/tai2/.rbenv/versions/3.0.0/bin/rspec)
11:27:18 rspec.1 | /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/rubygems_integration.rb:362:in `block in replace_bin_path': can't find executable rspec for gem rspec-core. rspec-core is not currently included in the bundle, perhaps you meant to add it to your Gemfile? (Gem::Exception)
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/rubygems_integration.rb:390:in `block in replace_bin_path'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/bin/rspec:23:in `<top (required)>'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/cli/exec.rb:63:in `load'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/cli/exec.rb:63:in `kernel_load'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/cli/exec.rb:28:in `run'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/cli.rb:474:in `exec'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/vendor/thor/lib/thor/command.rb:27:in `run'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/vendor/thor/lib/thor/invocation.rb:127:in `invoke_command'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/vendor/thor/lib/thor.rb:392:in `dispatch'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/cli.rb:30:in `dispatch'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/vendor/thor/lib/thor/base.rb:485:in `start'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/cli.rb:24:in `start'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/exe/bundle:49:in `block in <top (required)>'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/lib/bundler/friendly_errors.rb:130:in `with_friendly_errors'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/lib/ruby/gems/3.0.0/gems/bundler-2.2.19/exe/bundle:37:in `<top (required)>'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/bin/bundle:23:in `load'
11:27:18 rspec.1 | 	from /Users/tai2/.rbenv/versions/3.0.0/bin/bundle:23:in `<main>'
11:27:19 rspec.1 | exited with code 1
11:27:19 system  | sending SIGTERM to all processes
```
