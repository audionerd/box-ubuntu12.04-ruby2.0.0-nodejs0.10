# ubuntu12.04-ruby2.0.0-nodejs0.10 box

ubuntu12.04-ruby2.0.0-nodejs0.10

# What is this?

I made a fork of `wercker/box-ubuntu12.04-ruby2.0.0` and set it to inherit from the `wercker/ubuntu12.04-nodejs0.10` instead of `wercker/ubuntu12.04-webessentials`

I'm working on a project which uses `bower`, and I wanted both the latest Ruby **and** Node.js available in my Wercker builds.
