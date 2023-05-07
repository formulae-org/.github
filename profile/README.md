# Fōrmulæ

Fōrmulæ is a software framework for visualization and edition of complex expressions (either mathematical expressions or expressions from many other fields). Fōrmulæ also includes the manipulation of such these expressions, so Fōrmulæ is also a (Turing complete) programming —and symbolic— language. If you want to know more about Fōrmulæ, please refer to its website [formulae.org](https://formulae.org). 

Here you can find the source code for the Fōrmulæ framework.

With Fōrmulæ, you can create code to visualize, edit or manipulate expressions from many fields. The code is grouped in units called packages. The code for every package is hosted in the following repositories:

| Package     | Repositoty                                                                     | Status | Description |
| ----------- | ------------------------------------------------------------------------------ | ------ | ----------- |
| Arithmetics | [package-arithmetic-js](https://github.com/formulae-org/package-arithmetic-js) | Stable | Integer, decimal, rational and complex numbers. Basic arithmetic, trascendental, trigonometric, hyperbolic operations with arbitrary precision integers and decimals. Rounding modes. |
| Relation    | [package-relation-js](https://github.com/formulae-org/package-relation-js)     | Stable | Basic comparison operations, Three way comparison, minimum, maximum, membership |
| Logic       | [package-logic-js](https://github.com/formulae-org/package-logic-js)           | Stable | Logic literals, basic logic operations (negation, conjunction, disjunction, conditional, equivalence, exclsuive disjunction). |
| Expression  | [package-expression-js](https://github.com/formulae-org/package-expression-js) | Stable | Common operations to expressions and reflection, such as cardinality, subexpression, insertion and deletion of subexpressions, serialization/deserialization, programatical creation of expressions. |

Moreover, with Fōrmulæ you can create formatted content (text with styles, use of images, paragraphs, bulleted list, alignment, etc.) (typesetting). All the content of its website —tutorials, reference, examples, etc.— is written in Fōrmulæ itself. This content is also hosted here. 
