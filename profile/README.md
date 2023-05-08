# Fōrmulæ

Fōrmulæ is a software framework for visualization and edition of complex expressions (either mathematical expressions or expressions from many other fields). Fōrmulæ also includes the manipulation of such these expressions, so Fōrmulæ is also a (Turing complete) programming —and symbolic— language. If you want to know more about Fōrmulæ, please refehttps://formulae.org).

Here you can find the source code for the Fōrmulæ framework.

With Fōrmulæ, you can create code to visualize, edit or manipulate expressions from many fields. The code is grouped in units called packages. The code for every package is hosted in the following repositories:

| Package | Repository | Brief description |
| ------- | ---------- | ----------------- |
| Arithmetics | [package-arithmetic-js](https://github.com/formulae-org/package-arithmetic-js) | Integer, decimal, rational and complex numbers. Basic arithmetic, trascendental, trigonometric, hyperbolic operations with arbitrary precision integers and decimals. Rounding modes. |
| Relation | [package-relation-js](https://github.com/formulae-org/package-relation-js) | Basic comparison operations, three-way comparison, minimum, maximum, membership. |
| Logic | [package-logic-js](https://github.com/formulae-org/package-logic-js) | Logic literals, basic logic operations (negation, conjunction, disjunction, conditional, equivalence, exclsuive disjunction). |
| Expression | [package-expression-js](https://github.com/formulae-org/package-expression-js) | Common operations to expressions and reflection, such as cardinality, subexpression, insertion and deletion of subexpressions, serialization/deserialization, programatic creation of expressions. |
| List | [package-list-js](https://github.com/formulae-org/package-list-js) | List manipulation, list and table creation, operation with list and matrices. |
| Symbolic | [package-symbolic-js](https://github.com/formulae-org/package-symbolic-js) | Definition and referecing of local and global symbols and functions, lambda expressions. |
| Strings | [package-string-js](https://github.com/formulae-org/package-string-js) | Creation and operations with strings, text, and regular expressions, Unicode support. |
| Color | [package-color-js](https://github.com/formulae-org/package-color-js) | Creation and operations on colors, visual representation of colors. |
| Programming | [package-programming-js](https://github.com/formulae-org/package-programming-js) | Structured programming structures, such as sequences (blocks), selections and iterations. Visualizacion as either flowchart or code indentation. |
| Raster graphics | [package-graphic-raster-js](https://github.com/formulae-org/package-graphic-raster-js) | Creation of graphics, pixel operations, outline and filling of geometric primitives (lines, rectangles, ellipses, arcs), inclusion of other graphics, text, turtle graphics, primitives on coordinates (translations, rotating, scaling). |
| Charts | [package-chart-js](https://github.com/formulae-org/package-chart-js) | Creation of charts from data. Bar, line, area, dot, step, and pie types. |
| Diagramming | [package-diagramming-js](https://github.com/formulae-org/package-diagramming-js) | Diagrams, tree structures (for now). |
| Typesetting | [package-typesetting-js](https://github.com/formulae-org/package-typesetting-js) | Typesetting (see below). |
| Visualization | [package-visualization-js](https://github.com/formulae-org/package-visualization-js) | Changing the look of expressions, font color, size and attributes (bold, italic), crossing out, arrangement of expressions. |
| Bitwise | [package-bitwise-js](https://github.com/formulae-org/package-bitwise-js) | Bitswise (and, or, not, xor), bit length, bit count, shifts, bit (set, get, clear, flip) operation on arbitrary length integers. |

| Package | Repository | Brief description |
| ------- | ---------- | ----------------- |
| Time | [package-time-js](https://github.com/formulae-org/package-time-js) | Time datatype and operations, Gregorian calendar  part management |
| Localization | [package-localization-js](https://github.com/formulae-org/package-localization-js) | Languages, countries, scripts, numerals, calendars, locales, time zones. |
| Plot | [package-plot-js](https://github.com/formulae-org/package-plot-js) | Mathematical plots. 2D function plot, 2D parametric plot, 2D polar curve, 3D parametric curve, 3D function surface, 3D parametric surface, surface map, surface contour. |

Moreover, with Fōrmulæ you can create formatted content (text with styles, use of images, paragraphs, bulleted list, alignment, etc.) (typesetting). All the content of its website —tutorials, reference, examples, etc.— is written in Fōrmulæ itself. This content is also hosted in the [web-content](https://github.com/formulae-org/web-content) repository.
