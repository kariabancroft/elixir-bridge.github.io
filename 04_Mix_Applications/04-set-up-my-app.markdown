---
layout: page
title: Our first application
date: 2016-10-1 13:38:30 -0700
---

## Set up Myapp

Remember the keyword `use`. We'll use it to add functionality to the `Myapp` module.

Let's open up `myapp.ex`. It is in the `lib` directory.

```elixir
# myapp.ex
defmodule Myapp do
  use Application
  def start(_type, _args) do
  end
end
```

We will tell my app to `use` the `Application` module.






