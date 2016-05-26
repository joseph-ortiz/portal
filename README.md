# Portal
![Elxiir logo](http://elixir-lang.org/images/logo/logo.png)  
A portal game to introduce me to Elixir
[original](https://howistart.org/posts/elixir/1)

## Learnings
- define a module with a group of functions
- docs are first class citizents and can be access with `h` 

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add portal to your list of dependencies in `mix.exs`:

        def deps do
          [{:portal, "~> 0.0.1"}]
        end

  2. Ensure portal is started before your application:

        def application do
          [applications: [:portal]]
        end
