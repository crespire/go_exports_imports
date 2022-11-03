# Go Export/Import

Identifiers with lowercase first chars are not exported for general use.

There are cases were you can use unexported identifiers elsewhere, but it typically relies on having set up an exported *interface* to access those identifiers.

https://www.ardanlabs.com/blog/2014/03/exportedunexported-identifiers-in-go.html