# tl
A bunch of small C++ utilities

[![Linux Build Status](https://travis-ci.org/TartanLlama/tl.png?branch=master)](https://travis-ci.org/TartanLlama/tl)

- [`overload`](https://github.com/TartanLlama/tl/blob/master/include/tl/overload.hpp): a rudimentary implementation of [std::overload](http://open-std.org/JTC1/SC22/WG21/docs/papers/2016/p0051r2.pdf)
- [`integer_sequence`](https://github.com/TartanLlama/tl/blob/master/include/tl/integer_sequence.hpp): C++11 version of `std::integer_sequence` and friends, plus `tl::make_index_range`
- [`type_traits`](https://github.com/TartanLlama/tl/blob/master/include/tl/type_traits.hpp): implementations of some type traits from C++17 and Lib Fundamentals v2 TS
-- `std::bool_constant`
-- `std::conjunction`
-- `std::disjunction`
-- `std::negation`
-- `std::void_t`
-- `std::is_detected`
