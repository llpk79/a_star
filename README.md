# a_star

Variations on A Star algorithm for fewest turns and shortest route.

- MinTurns

      start_pos and end_pos are tuples of coordinates.
      start, end = (0, 2), (0, 4)

      grid is a list of length n of strings of length n where 'x' indicates a barrier.
      
      grid = ['...x...',
              '.xxxx..',
              '.x.....',
              '.x.xxx.',
              '.x...x.',
              '..xx.x.',
              '.......']

      Instantiate an object
      find_way = MinTurns(start, end, grid)

      Retrieve search results
      min_turns_route, turn_count, route_length = find_way.search()

- ShortestRoute

      start, end, and grid are as above.
      
      search() currently returns an int, the length of the route.
