# A trivial proof search with Celf

Celf is a linear logic proof assistant.

This is a work in progress, more to come.

Quiescence is reached when there are no rules that can be applied.

Proof search can be done with two opposite methods: forward chaining and backward chaining.

When the proposition/type 'end' enters the context no rules can be applied so quiescence is reached. If we were to add a rule with 'end' as part of the antecedent, the program, as is, would never reach quiescence.

## Installation

TODO: Describe the installation process

## Usage

TODO: Write usage instructions

## Credits

Much of my knowledge on this subject was taken from Chris Martens thesis: http://www.cs.cmu.edu/~cmartens/thesis/ 