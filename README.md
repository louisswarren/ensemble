# ensemble
Finite sets in Agda.

An ensemble is like a list, but with a constructor for set removal. It also has
a constructor for unions, as concatenating ensembles where elements have been
removed is non-trivial.

This project doesn't make use of the standard library, as I find it slow to
use. I instead provide my own implementations, with only what is needed.
Ideally, these could be replaced with the standard library implementations
(perhaps with a little work).
