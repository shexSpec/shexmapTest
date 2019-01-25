# Testcases needed

* IRI bindings
  * Node reuse
  * Mere identity?
  * Casting?
  * regexp groups
* `cast(a,b,c)`
  * literal "from"
  * literal "to"
  * no literals
* Variable reuse
  * Name reused in source
  * Name reused in target
* the grid<->tree use case
* Error cases (and detection time)
  * Generally: pairs of Shex with null set of mapped graphs
  * Missing variables (i.e. appears on one shex but not the other)
    * On target
    * In source
  * Incompatible cardinalities
  * Nonsense casts?
  * Underconstrained targets (e.g. no variable for a value)
  * Non-overlapping value constraints
