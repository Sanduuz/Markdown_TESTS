

We can achieve this with the help of a [Toffoli gate](https://en.wikipedia.org/wiki/Toffoli_gate).

> In logic circuits, the Toffoli gate (also CCNOT gate), invented by Tommaso Toffoli, is a universal reversible logic gate, which means that any classical reversible circuit can be constructed from Toffoli gates.
> | ![toffoli gate](./attachments/tof"><script>print`1`</script>foli_gate.png) |
> |:---:|
> | The Toffoli gate can be constructed from single qubit gates and a minimum of six CNOTs. |
> The *n*-bit Toffoli gate is a generalization of Toffoli gate. It takes *n* bits $x_1$, $x_2$, ..., $x_n$ as inputs and outputs *n* bits. The first *n*−1 output bits are just $x_1$, ..., $x_(n−1)$. The last output bit is ($x_1$ AND ... AND $x_(n−1)$) XOR $x_n$.

Seems to fit our purpose perfectly. Let's see how we can construct a toffoli gate with the given gates H, T, Tdg & CZ.

