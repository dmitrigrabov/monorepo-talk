Fast and furious: super charge development with monorepos and component libraries

Using monorepos to supercharge development with component libraries

Dmitri has spent the last 6 months researching monorepos so you don't have to. In this talk you will learn all you need to know about what a monorepo is, benefits it provides, pitfalls to watch out for and how to make it work for you. We will examine how monorepos enable us to accelerate component library development. Along the way we look at some of the tooling involved such as Yarn Worspaces, Lerna, Rollup, npm and Storybook. You will lean about the concepts involved, trade-offs to consider and how monorepos can enable your dev team to deliver at scale.

# Core concepts

Using a mono repo allows us to

Bootstrap

Improve communication

Make development quicker and easier

Deliver functionality at scale

Make it easier to develop components as we are going along

Break down silos

Ease of code reuse

Share dependencies

Google, FB, Twitter use monorepos (worst reason)

monorepo is not a ball of mud

Separate business logic from presentation logic

# Misunderstandings

encouraging tight coupling

Single package

# Downsides of polyrepos

# Why should I care?

Talk description and abstracts

The purpose of the talk is to provide a crash course on monorepos, their pros and cons, as well as enable the audience to get started with monorepo development.

The talk will cover the following

- Quick overview of common pain points in software development
- The theory of how monorepos work and address above
- Single vs independent versioning in monorepos
- Yarn Workspaces
  - Linking
  - Depenency hoisting
  - Cost and benefits of above
- Lerna
  - Bootstrap, version and publish
  - Addressing overlap with Yarn Workspaces
  - Implementing workflow
- How libraries are different from apps
- Rollup
  - Using rollup to build components
  - Useful tools to consider
- npm
  - Namespaces, private registries and deployment
- End to end workflow with CI integration
