# cpp-flashcards

A comprehensive C++ flashcard deck for Anki. With 585 cards it covers:

- **Basics**: statements, functions, variables, syntax, data types
- **Type Conversion**: implicit/explicit conversions, casts
- **Operators**: precedence, associativity
- **Control Flow**: conditionals, loops
- **Memory**: pointers, references, smart pointers
- **OOP**: classes, inheritance, polymorphism, virtual functions
- **Templates**: type deduction, SFINAE, concepts
- **Smart Pointers**: unique_ptr, shared_ptr, weak_ptr
- **STL/Containers**: vectors, iterators, algorithms
- **Modern C++**: auto, decltype, attributes, concepts, requires
- **Metaprogramming**: type traits, compile-time programming, constexpr

## Tags

Every card is tagged with a **difficulty level** and one or more **topic tags**.

### Difficulty Levels

| Level | Count | Description |
|-------|-------|-------------|
| Beginner | 200 | Fundamentals, basic syntax, simple concepts |
| Intermediate | 316 | Core C++ features, common patterns |
| Advanced | 65 | Complex features, edge cases, deeper understanding |
| Expert | 4 | Metaprogramming, SFINAE, advanced template techniques |

### Topic Tags

Cards are categorized by topic. Major categories include:

| Category | Tags |
|----------|------|
| **Core Language** | Basics, Types, Variables, Declarations, Operators, Control-Flow, Scope |
| **Functions** | Functions, Overloading, Lambdas, Recursion |
| **Memory** | Memory, Pointers, References, Smart-Pointers, RAII |
| **OOP** | OOP, Classes, Constructors, Destructors, Inheritance, Polymorphism, Virtual, Access-Specifiers |
| **Semantics** | Copy-Semantics, Move-Semantics, Value-Categories |
| **Templates** | Templates, Type-Deduction, Decltype, Auto, Metaprogramming, SFINAE, Concepts, Type-Traits, Type-Erasure |
| **Modern C++** | Constexpr, Compile-Time, Attributes, C++11, C++20, C++23 |
| **STL** | STL, Containers, Algorithms, Strings |
| **Other** | Initialization, Const, Literals, Enums, Namespaces, Linkage, Exceptions, Concurrency, Preprocessor |
| **Best Practices** | Best-Practices, Optimization, Undefined-Behavior, Errors, Debugging, Testing |

## Project Structure

- `deck.json` — The flashcard deck in JSON format.
- `media/` — Media files (images, audio, etc.) referenced by the deck.

## Usage

1. Edit `deck.json` to add or update flashcards.
2. Place any required media files in the `media/` directory.
3. Use the deck with your preferred flashcard application.

### Import/Export

This deck is designed to be used with the [CrowdAnki](https://ankiweb.net/shared/info/1788670778) Anki add-on for easy import and export.

## Development

- All JSON files are validated automatically via GitHub Actions on push and pull request.
- To manually check JSON validity:
  ```sh
  jq empty deck.json
  ```

## License

MIT
