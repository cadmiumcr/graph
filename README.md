# Graph

EdgeWeightedDigraph represents a digraph, you can add an edge, get the number vertexes, edges, get all edges and use toString to print the Digraph.


## Installation

1. Add the dependency to your `shard.yml`:

   ```yaml
   dependencies:
     cadmium_graph:
       github: cadmiumcr/graph
   ```

2. Run `shards install`

## Usage

```crystal
require "cadmium_graph"
```

```crystal
digraph = Cadmium.edge_weighted_digraph.new

digraph.add(5, 4, 0.35)
digraph.add(5, 1, 0.32)
digraph.add(1, 3, 0.29)
digraph.add(6, 2, 0.40)
digraph.add(3, 6, 0.52)
digraph.add(6, 4, 0.93)

puts digraph.v # => 7
puts digraph.e # => 6
```

## Contributing

1. Fork it (<https://github.com/cadmiumcr/graph/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [Chris Watson](https://github.com/watzon) - creator and maintainer
