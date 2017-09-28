# lcr

# Manually runs recipe
chef-client --local-mode recipe.rb

# Manually runs cookbook
chef-client --local-mode --runlist 'recipe[learn_chef_apache2]'

You also saw the run-list. The run-list lets you specify which recipes to run, and the order in which to run them. This is handy once you have lots of cookbooks, and the order in which they run is important.

