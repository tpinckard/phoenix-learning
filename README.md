### install elixir

`brew install elixir`

### install hex, package manager for elixir

`mix local.hex`

### install hex, package manager for elixir

`mix local.hex`

### Make sure that elixir got installed along with erlang

`elixir -v`

### Make sure that elixir got installed along with erlang

`mix archive.install https://github.com/phoenixframework/archives/raw/master/phx_new.ez`

### You'll need nodejs and postgres as well

### start a new phoenix project named 'hello':

`mix phx.new hello`

### it will ask to install dependancies... say yes

### (after install) Go into your application by running:

`cd hello`

### Then configure your database in config/dev.exs and run:

`mix ecto.create`

### Start your Phoenix app with:

`mix phx.server`

### run app inside IEx (Interactive Elixir):

`iex -S mix phx.server`
