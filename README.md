# Build your own effect system

This is a course designed to help you build an effect system in Scala that is similar to [Cats Effect](https://typelevel.org/cats-effect/). The intention is that by building it yourself you should gain a deeper understanding of how an `IO` action is evaluated and the impact of things like blocking, timers, async execution on the performance of your application. The assumption is that you are familiar with using a library like Cats Effect so usage of an effect system is not explained.

## How to use

The course is divided into chapters which should iteratively build on top of each other. Each chapter has its own git branch. The goal of that chapter will be described in the corresponding `README.md`. If you get stuck then you can consult `hints.md` for some guidance. If you're really stuck then you can look at the source code, which is a possible solution for that chapter.

## Running the provided solutions

The solutions are built with [scala-cli](https://scala-cli.virtuslab.org). To
get you started quickly, here are some of the most common operations:

### Run tests

`scala-cli test .`

### Import into IDE

`scala-cli setup-ide .`
