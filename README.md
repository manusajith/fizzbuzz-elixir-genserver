# FizzBuzz

FizzBuzz implemented with a GenServer

Instructions to run locally:


    iex -S mix
    FizzBuzz.start_link
    1..100 |> Enum.map(&FizzBuzz.print/1)
