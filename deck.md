# TypeScript!

---

# TypeScript!

## *JavaScript that scales.*

TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.

---

# TypeSecript

``` js
// JavaScript, types are implicit
const add = (a, b) => a + b
```

---

# TypeSecript

``` js
// JavaScript, types are implicit
const add = (a, b) => a + b
```

``` ts
// TypeScript, types are explicit
const add = (a: number, b: number): number => a + b
```

---

[.build-lists: true]

# Why Types?

- Catch bugs
- Catch bugs (earlier)
- Documentation & productivity
- GraphQL has a type system
- Refactoring

---

# Why Types?

- Catch bugs
- Catch bugs (earlier)
- Documentation / improve productivity
- GraphQL has a type system
- **Refactoring**

---

![fit](./images/gatekeeper.jpg)

---

Java?

```java
public class Main {
    public static void main(String[] args) {
        int number1 = 10;
        String message = new String("Hello World! ");
        System.out.println(message + number1);
    }
}
```

---

![fit](./images/pair-programming.jpg)

---

![fit](./images/typescript-error-messages.png)

---

# Types are all the rage

---

![fit](./images/python-type-hints.png)

^^^
Python

---

![fit](./images/sorbet.gif)

---

> _Matz_: Yeah
the third major goal of the Ruby 3 is adding some kind of static typing while keeping the duck typing
so some kind of structure for soft-typing or something like that.

-- [Ruby 3x3: Matz Koichi and Tenderlove on the future of Ruby Performance][]

[ruby 3x3: matz koichi and tenderlove on the future of ruby performance]: https://blog.heroku.com/ruby-3-by-3

^^^
Ruby

---

![fit](./images/typed-js.png)

---

# Why TypeScript?

![inline](./images/typed-js.png)

^^^
- gradual
pragmatic
good adoption story
- Community adoption
- VS Code & Language server
- Apollo
Formik are authored in it

---

[.build-lists: true]

## Gradual Adoption Story

- All JS is valid TS!
- Rename `*.js` -> `*.ts{x}`
- Introduce types for libraries
- Dial up the strictness (towards `--strict` mode)

    ```
    --noImplicitAny
    --strictNullChecks
    --strictFunctionTypes
    ```

---

## Community Adoption

![inline](./images/typescript-adoption.png)

---

## Tooling!

![inline](./images/vscode.png)

---

## Language Server

![inline](./images/language-server.png)

---

## Library Support

- Apollo & formik are authored in TypeScript
- React very well supported

---

## How to get started

- All JS is valid TS!
- Rename `*.js` -> `*.ts{x}`
- Introduce types for libraries
- Dial up the strictness (towards `--strict` mode)

    ```
    --noImplicitAny
    --strictNullChecks
    --strictFunctionTypes
    ```
