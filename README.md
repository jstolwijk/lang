# lang

* No early returns
* No break
* proper pattern matching
* no || or &&
* no other stupid symbols

function hello(test: String) -> Suspending<String> = match(test) {
 "hello" -> async { Hello }
  else -> async { Test }
}
  
function hello(test: String) -> Suspending<String> = match(test) {
 "hello" -> async { Hello }
  else -> async { Test }
}
