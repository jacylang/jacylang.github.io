<div class="books">
    <a class="book-link" href="/dev-book">
        <span class="title">📓 Dev Book</span>
        <p class="description">
            Dev Book is a collection of notes and helpful information about <span class="jacy-logo-text">Jacy</span> internals.
        </p>
    </a>
    <a class="book-link" href="https://github.com/jacylang/dev-book">
        <span class="title">📝 Dev Book Source</span>
        <p class="description">
            The source code of Dev Book.
        </p>
    </a>
    <a class="book-link" href="https://github.com/jacylang/jacy">
        <span class="title"><img class="jacy-logo"> Source Repository</span>
        <p class="description">
            Contribute 😇
        </p>
    </a>
    <a class="book-link" href="https://marketplace.visualstudio.com/items?itemName=jacy-lang.jacy-lang">
        <span class="title"><img src="assets/img/vscode.svg"><span>VSCode extension</span></span>
        <p class="description">
            Supports basic highlighting for <span class="jacy-logo-text">Jacy</span> and <span class="jacy-logo-text">Jon</span>.
        </p>
    </a>
    <a class="book-link" href="https://atom.io/packages/language-jacy">
        <span class="title"><img src="assets/img/atom.svg"><span>Atom extension</span></span>
        <p class="description">
            The first developed text editor extension.<br>
            Includes tree-sitter grammar.<br>
            <b>[outdated]</b>
        </p>
    </a>
    <a class="book-link" href="/color-scheme">
        <span class="title">🎨 <span class="jacy-logo-text">Jacy</span> color scheme</span>
        <p class="description">
            Color scheme used by <span class="jacy-logo-text">Jacy</span> VSCode color theme and web sources such as this site. Currently, scheme needs much improvements. If you are a designer, it would be nice to have some advices on it.
        </p>
    </a>
</div>

# <span class="jacy-logo-text">Jacy</span> programming language

<span class="jacy-logo-text">Jacy</span> is a WIP experimental project aimed at easily writing low-level and high-level code using modern features.

It is mostly inspired by <span class="rust-logo">Rust</span>, other influencers are: Swift, C++, OCaml (from view of Rust), Cyclone.

Features <span class="jacy-logo-text">Jacy</span> will/does have power of:

- Functional programming:
  - Pattern matching
  - Closures (lambdas)
  - Immutable data (forced by default)
  - Algebraic Data Types
  - Parametric polymorphism
  - Affine types
- Type system:
  - Static
  - Nominal sub-typing
  - Traits (aka type classes)
- Safety:
  - Borrow checker
  - References are always valid
  - No `null`
  - No Undefined Behavior
