# Software Crafter Journey
This journey is an attempt to centralize useful resources (code kata, workshops, talks) that can help aspiring Software Craftsperson in their Journey.

![Software Crafter Journey](img/crafter-journey.webp)

## Table of Contents
- [Self-assessment](#self-assessment)
- [Clean Code](#clean-code)
  - [Functional Programming](#functional-programming)
- [Clean Testing](#clean-testing)
  - [Prerequisites](#prerequisites)
  - [Fundamentals](#fundamentals-1)
  - [Test Data Builders](#test-data-builders)
  - [Property-Based Testing](#property-based-testing)
  - [Other topics](#other-topics)
- [Solution Design](#solution-design)
  - [Test-Driven Development](#test-driven-development)
  - [Software Architecture](#software-architecture)
- [Refactoring / Technical Debt Management](#refactoring--technical-debt-management)
  - [What is Technical Debt](#what-is-technical-debt)
  - [Legacy Code Refactoring](#legacy-code-refactoring)
  - [Mikado](#mikado)
- [CI / CD](#ci--cd)
- [Collective Ownership](#collective-ownership)
- [Other Resources](#other-resources)
  - [Xtrem T.D.D - All in one kata](#xtrem-tdd---all-in-one-kata)
  - [Refactoring du Bouchonnois](#refactoring-du-bouchonnois---all-in-one-kata)
  - [Advent Of Craft](#advent-of-craft-2023)
  - [Talks and Workshops](#talks-and-workshops)
  - [My Book Infographics](#my-book-infographics)

## Self-assessment
You can drive continuous improvement within your team by using a `self-assessment` tool like the one described here.

There is one category for each big craft topic I have selected.

[![Craft Self Assessment](img/craft-self-assessment.jpg)](files/craft-self-assessment.pdf)

When I start to work with a new team, I use this tool to align team members on the current situation of the team. 
For each card, each individual can express their point of views on the topic by:
- `Choosing` which color represents the most the team situation
- `Expressing` their findings on it
- `Exploring` improvement areas
- `Defining` experiment actions

We can design new cards with the team based on categories they want to improve in.

We then use those cards to measure the improvement of the team in time, and the impact of my `agile technical coaching`.
I use those cards to categorize the below resources. I use them to teach and coach teams on those different axis.

You can download those cards [here](files/craft-self-assessment.pdf).

### Fundamentals
- [What is software craftsmanship?](https://miro.com/app/board/uXjVPjg5-ks=/?share_link_id=130260708635)
  - [Egoless Crafting](https://egolesscrafting.org/)

## Clean Code
![Clean Code](img/clean-code.png)
- [Codefather: A Coding Kata on Naming](https://github.com/gsaslis/coding-kata-naming)
- [Crappy-Driven Development](https://github.com/ythirion/crappy-driven-development/)
- [S.O.L.I.D principles](https://github.com/ythirion/solid-kata)
- [Programmer's Brain - What every programmer needs to know about cognition](https://miro.com/app/board/o9J_l0DSaRQ=/?share_link_id=531195470496)

### Functional Programming
- [Design Patterns in FP](https://github.com/ythirion/scala-fp-guidelines)
- [Functional Programming made easy in Java & C#](https://speakerdeck.com/thirion/functional-programming-made-easy-in-java-and-c-number)
  - [java with vavr](https://github.com/ythirion/vavr-kata)
  - [C# with Language-Ext](https://github.com/ythirion/language-ext-kata)
- [FP 101 on the JVM](https://github.com/ythirion/fp101)
- [Kotlin for java refugees](https://ythirion.github.io/kotlin-for-java-refugees/)
- [F# for OO Programmers](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/f-for-oo-programmers)

#### Baby steps to FP
- [Pure Functions](https://github.com/katalogs/learning-hours/blob/main/functional-programming/1-pure-functions/Facilitation.md)
- [Functors](https://github.com/katalogs/learning-hours/blob/main/functional-programming/2-functors/Facilitation.md)
- [Monads (Option)](https://github.com/katalogs/learning-hours/blob/main/functional-programming/3-monads-part1/Facilitation.md)
- [Monads (Try, Either)](https://github.com/katalogs/learning-hours/blob/main/functional-programming/4-monads-part2/Facilitation.md)
- [FP in Real Life](https://github.com/katalogs/learning-hours/blob/main/functional-programming/5-real-life-example/Facilitation.md)
- [Discriminated Unions](https://github.com/katalogs/learning-hours/blob/main/functional-programming/6-discriminated-unions/Facilitation.md)

## Clean Testing
![Clean Testing](img/clean-testing.png)

### Prerequisites
- [How to write Unit Tests](https://github.com/ythirion/unit-tests-intro)
- [Generate Code From Usage](https://github.com/katalogs/learning-hours/blob/main/generate-code-from-usage/Facilitation.md)

### Fundamentals
- [Anatomy of Unit Tests](https://github.com/katalogs/learning-hours/blob/main/clean-testing/1-test-anatomy/Facilitation.md)
- [Test Doubles](https://github.com/katalogs/learning-hours/blob/main/clean-testing/4-test-doubles/Facilitation.md)
- [Parameterized Tests](https://github.com/katalogs/learning-hours/blob/main/clean-testing/5-parameterized-tests/Facilitation.md)
- [Styles of Unit Tests](https://sammancoaching.org/learning_hours/test_design/styles_of_unit_tests.html)
- [The hunt for anti-patterns](https://github.com/katalogs/learning-hours/blob/main/clean-testing/7-anti-patterns/Facilitation.md)
- [The hunt for 100% code coverage](https://github.com/katalogs/learning-hours/blob/main/clean-testing/8-hunt-to-100percent-coverage/Facilitation.md)
- [Define your Test Strategy](https://philippe.bourgau.net/a-complete-workshop-for-your-team-to-see-what-s-a-good-test-strategy/)

### Test Data Builders
- [Refactoring test inputs with Test Data Builders](https://github.com/katalogs/learning-hours/blob/main/test-data-builders/refactoring-test-inputs-with-test-data-builders/Facilitation.md)
- [Business oriented Test Data Builders](https://github.com/katalogs/learning-hours/blob/main/test-data-builders/business-oriented-test-data-builders/Facilitation.md)

### Property-Based Testing
- [A Journey to Property-Based Testing](https://github.com/ythirion/journey-to-property-based-testing)
- [Bulletproof your code with "Mutation-Based Property-Driven Development"](https://github.com/ythirion/nir-kata)
- [Type-Driven Development with PBT](https://github.com/ythirion/snafu-kata)

### Other topics
- [AssertJ in practice](https://github.com/ythirion/assertj-kata)
- [Approval Testing in C#](https://github.com/ythirion/approval-csharp-kata)
- [Improve your test quality with Mutation testing](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/testing/mutation-testing)

## Solution Design
![Solution Design](img/solution-design.png)

### Test-Driven Development
T.D.D categories are inspired by [Philippe Bourgau's Mind Map](https://philippe.bourgau.net/a-coding-dojo-exercises-plan-towards-refactoring-legacy-code/).

#### Basic
- [FizzBuzz](https://github.com/ythirion/fizzbuzz-kata)
- [Stack](https://github.com/ythirion/stack-kata)
- [Bowling](https://github.com/ythirion/scala-kata-logs/blob/main/BowlingKata/README.md)
- [Roman Numerals](https://github.com/ythirion/clean-crafter/blob/main/tdd-kata/README.md)

#### Designing with TDD
- [Money Problem](https://github.com/ythirion/TDD-money-problem)
- [Yatzee](https://github.com/ythirion/scala-kata-logs/tree/main/YahtzeeKata)
- [Mars Rover](https://github.com/ythirion/scala-kata-logs/blob/main/MarsRoverKata/README.md)

#### TDD on algorithms
- [Diamond](https://github.com/ythirion/scala-kata-logs/blob/main/DiamondKata/README.md)
- [Lags](https://github.com/ythirion/scala-kata-logs/blob/main/LagsKata/README.md)

#### Outside-In TDD
- [Bank Kata](https://github.com/ythirion/bank-kata)

#### Test && Commit || Revert (aka TCR)
- [Submarine kata](https://github.com/les-tontons-crafters/submarine-tcr)

### Software Architecture
- [Domain Driven Design re-Distilled](https://yoan-thirion.gitbook.io/knowledge-base/software-architecture/ddd-re-distilled)
- [DDD / Clean Architecture / Tell don't ask Kata](https://github.com/les-tontons-crafters/tell-dont-ask-kata)
- [Test your Architecture with ArchUnit](https://github.com/ythirion/archunit-examples)
- [Improve the design and testing of your micro-services through Consumer-Driven Contract Testing](https://github.com/ythirion/pact-jvm-demo)
- [Co-designs - From high level Architecture to Solution Design by working collaboratively](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/practices/co-designs)
- [Design sessions - Collaborative Design](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/practices/design-sessions)
- [How to Interview Domain Experts](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/practices/interview-domain-experts)
- [Fundamentals of Software Architecture](https://yoan-thirion.gitbook.io/knowledge-base/software-architecture/fundamentals-of-software-architecture)
- [Aligning Product & Software Design](https://yoan-thirion.gitbook.io/knowledge-base/software-architecture/aligning-product-and-software-design)

#### Specification Pattern
- [Discover the Specification Pattern](https://github.com/katalogs/learning-hours/blob/main/specification-pattern/discover-specification-pattern/Facilitation.md)
- [Specification Pattern 2.0](https://github.com/katalogs/learning-hours/blob/main/specification-pattern/specification-2.0/Facilitation.md)

## Refactoring / Technical Debt Management
![Refactoring and Technical Debt Management](img/refactoring+tech-debt-management.png)

### What is Technical Debt
- [Technical Debt Workshop](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/technical-debt-workshop)

### Legacy Code Refactoring
- [Refactoring journey](https://github.com/ythirion/refactoring-journey)
- [Gilded Rose - with Approval Testing](https://github.com/ythirion/scala-kata-logs/blob/main/GildedRoseKata/README.md)
- [Refactoring by Example](https://github.com/les-tontons-crafters/tell-dont-ask-kata)
- [Yatzy](https://github.com/ythirion/scala-kata-logs/tree/main/YatzyRefactoringKata)
- [Untangled Conditionals Kata](https://github.com/ythirion/untangled-conditionals-kata)
- [Elections](https://github.com/ythirion/scala-kata-logs/blob/main/ElectionsKata/README.md)
- [Ugly trivia game](https://github.com/ythirion/pair-programming-kata)
- [Trip service - refactoring with Seams](https://github.com/ythirion/clean-crafter/blob/main/tripservice-kata/README.md)
- [Theatrical Players Kata](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/code-katas/theatrical-players-refactoring-kata)

### Mikado
- [Mikado kata](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/code-katas/mikado-method)
- [Mikado Method and Test Data Builders](https://github.com/ythirion/mikado-testbuilders-kata)

## CI / CD
![CI/CD](img/ci-cd.png)
- [CI / CD Principles](https://github.com/ythirion/ci-cd)
- [Software Design X-Rays](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/software-design-x-rays/workshop)

## Collective Ownership
![Collective Ownership](img/collective-ownership.png)
- [Pair Programming](https://github.com/ythirion/pair-programming-kata)
- [Code Review Best Practices](https://github.com/ythirion/code-review)
- [Mob Programming](https://github.com/ythirion/mob-programming-kata)
- [How to start a Community Of Practices](https://yoan-thirion.gitbook.io/knowledge-base/agile-coaching/how-to-run-a-community-of-practices-cop)
- [Cultivate Team Learning with Xtrem Reading](https://yoan-thirion.gitbook.io/knowledge-base/xtrem-reading/cultivate-team-learning-with-xtrem-reading)

## Other Resources
### Xtrem T.D.D - All in one kata
[Xtrem T.D.D](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/) is a kata that demonstrates a lot of craft practices:
- [Mutation Testing](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/01.mutation-testing.md)
- [T.D.D from scratch](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/02.portfolio.md)
- [Fight Primitive Obsession / T.D.D on existing code](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/03.no-primitive-types.md)
- [Avoid for Loops](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/04.no-for-loops.md)
- [Immutability](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/05.only-immutable-types.md)
- [Avoid Exceptions](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/06.no-exception-authorized.md)
- [Use existing monads](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/07.use-existing-monad.md)
- [Property-Based Testing to challenge a Domain Model](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/08.bank-properties.md)
- [Example Mapping](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/09.bank-example-mapping.md)
- [Redesign the Bank](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/10.redesign-bank.md)
- [Acceptance Testing](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/11.acceptance-tests.md)
- [Functional Core, Imperative Shell](https://github.com/les-tontons-crafters/xtrem-tdd-money-kata/blob/main/docs/facilitation/12.functional-core-imperative-shell.md)

### Refactoring du Bouchonnois - All in one kata
Toutes les instructions [ici](https://github.com/ythirion/refactoring-du-bouchonnois).

![Refactoring du Bouchonnois](https://raw.githubusercontent.com/ythirion/refactoring-du-bouchonnois/main/img/refactoring-du-bouchonnois.webp)

À travers les différentes étapes présentes dans ce kata voici les sujets couverts :
- Example Mapping
- Static Code Analysis / Linter
- Treat Warnings as Errors
- Mutation Testing
- Test Data Builders
- Approval Testing
- Automated Refactoring
- Property-Based Testing
- Tests d'Architecture
- Test-Driven Development
- Clean Architecture
- Domain Driven Design
- Tell Don't Ask
- Functional Programming
- Avoid Primitives
- Avoid Exceptions
- Architecture Decision Records
- Event Sourcing

### Advent Of Craft 2023
25 challenges to learn and practice craft techniques.

More infos [here](https://github.com/advent-of-craft/advent-of-craft).

![Advent Of Craft](img/advent-of-craft.png)

### Talks and Workshops
- [Agile Tech Coaching - The missing piece of your Agile Transformation](https://bit.ly/3wZMPsv)
- [50 shades of Dev Practices](https://speakerdeck.com/thirion/50-shades-of-dev-practices)
- [Clean Code du point de vue de la Cognition](https://speakerdeck.com/thirion/clean-code-du-point-de-vue-de-la-cognition)
- [Libérez vos entretiens d’embauche avec la gamification](https://yoan-thirion.gitbook.io/knowledge-base/serious-games/craftsminator)
- [Developer Ethics](https://yoan-thirion.gitbook.io/knowledge-base/software-craftsmanship/practices/dev-ethics)
- [Xanpan - a team centric agile method story](https://yoan-thirion.gitbook.io/knowledge-base/agile-coaching/xanpan-a-team-centric-agile-method-story)
- [Drive and Intrinsic motivation](https://speakerdeck.com/thirion/drive-and-intrinsic-motivation-a-toolkit-for-todays-managers)

### My Book Infographics
All my book infographics are available from [here](https://yoan-thirion.gitbook.io/knowledge-base/xtrem-reading/my-book-infographics)
- `The Software Craftsman` by Sandro Mancuso
- `Leadership is language` by David Marquet
- `Culture is Everything` by Tristan White
- `Samman Technical Coaching` by Emily Bache
- `Leadership Strategy and Tactics: Field Manual` by Jocko Willink
- `Software-Design X-Rays` by Adam Tornhill
- `Succeeding with OKRs in Agile` by Allan Kelly
- `Team Topologies` by Matthew Skelton, Manuel Pais
- `Refactoring at Scale: Regaining Control of Your Codebase` by Maude Lemaire
- `La Liberté du Commandement` par Loïc Finaz
- `The programmer's brain` by Felienne Hermans
- `Unit Testing Principles, Practices, and Patterns` by Vladimir Khorikov
- `How to avoid a climate disaster` by Bill Gates
- `Tu fais quoi dans la vie` by Joséphine Bouchez et Mathieu Dardaillon
- `Une vie sur notre planète` by David Attenborough
- `Code that Fits in Your Head` by Mark Seemann
- `Software craft, TDD, Clean Code et autres pratiques essentielles` par Cyrille Martraire, Arnaud Thiéfaine, Dorra Bartaguiz, Fabien Hiegel, Houssam Fakih
- `The Good Life - Ce que nous apprend la plus longue étude scientifique sur le bonheur et la santé` par Robert Waldinger, Marc M.D. Schulz
- `Dynamic Reteaming - The Art and Wisdom of Changing Teams` by Heidi Helfand
- `Réaliser ses rêves, ça s'apprend` par Thomas Gibot 

### Useful Resources
- [Philippe Bourgau's Blog](https://philippe.bourgau.net/)
- [TDD Outcomes - The Good and The Bad](files/tdd-outcomes.pdf)
- [Understand Legacy Code Blog by Nicolas Carlo](https://understandlegacycode.com/)
- [Dantotsu method: from bug to best practice](https://www.promyze.com/dantotsu-best-practices/)
- [Une alternative au concept de dette logicielle](https://medium.com/@tpierrain/une-alternative-au-concept-de-dette-logicielle-68bb1e16842c)

#### Developer's Productivity
- [The SPACE of Developer Productivity](https://queue.acm.org/detail.cfm?id=3454124)
- [DevEx: What Actually Drives Productivity](https://queue.acm.org/detail.cfm?id=3595878)
