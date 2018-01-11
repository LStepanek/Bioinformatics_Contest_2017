## Example: Finding a Motif in DNA

Given two strings _s_ and _t_, _t_ is a substring of _s_ if _t_ is contained
as a contiguous collection of symbols in _s_ (as a result, _t_ must be
no longer than _s_).

The position of a symbol in a string is the total number of symbols found
to its left, including itself (e.g., the positions of all occurrences
of 'U' in "AUGCUUCAGAAAGGUCUUACG" are 2, 5, 6, 15, 17, and 18). The symbol
at position _i_ of s is denoted by _s_[_i_].

A substring of _s_ can be represented as _s_[_j_:_k_], where _j_ and _k_
represent the starting and ending positions of the substring in _s_;
for example, if _s_ = "AUGCUUCAGAAAGGUCUUACG", then _s_[2:5] = "UGCU".

The _location_ of a substring _s[_j_:_k_] is its beginning {{position}} _j_;
note that _t_ will have multiple locations in _s_ if it occurs more
than once as a substring of _s_ (see the Sample below).

**Given:** Two DNA strings _s_ and _t_ (each of length at most 1 kbp).

**Return:** All locations of _t_ as a substring of _s_.

___

**Sample Input:**

`GATATATGCATATACTT`

`ATAT`

___

**Sample Output:**

`2 4 10`
