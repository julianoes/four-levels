
At the moment, you can program your ARM microcontroller using Rust at four
different levels:

   - Bare register programming using *unsafe*

   - Using the API autogenerated by svd2rust

   - Using an *embedded-hal* implementation

   - Using a board support crate

All of this is based on the work of [Jorge Aparicio](http://blog.japaric.io/). This repository
contains full implementations of an elementary *light-up-the-LED* program written using all
four levels. The code runs on an STM32F3Discovery board.


