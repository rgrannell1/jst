
# jst

## Selectors

- `*`:                             matches any part of the program.
- `T`:                             matches a subpart of the program of the matching type of expression.
- `*.KEY`:                         matches a property of a subpart of the program.
- `*."KEY"`                        matches a complex JSON key.
- `A.nth-child(n)`                 matches the nth-child element of an array element.
- `A.nth-last-child(n)`            matches the nth-child element of an array element, counting from the end.
- `A.first-child`                  equivalent to `ARRAY.nth-child(1)`
- `A.last-child`                   equivalent to `ARRAY.nth-last-child(1)`
- `A.only-child`                   matches the only child element of an array element.
- `A.empty-child`                  matches arrays with no children.
- `T U`                            matches parts of the program of expression type U with expression type T as an ancestor.
- `T > U`                          matches parts of the program of expression type U with expression type T as an parent.
- `T ~ U`                          matches parts of the program of expression type U with expression type T as an sibling.
- `S1, S2`                         matches parts of the program that match either selector.
