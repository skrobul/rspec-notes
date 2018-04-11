# Effective Testing with RSpec 3

#### A good test should provide:
  * Design Guidance
  * Safety Net
  * Documentation

#### What to test first?
   * Ask yourself: "whats the core of the project?"
   
#### Good Habits
  * Describe precisely what you want the program to do in order to avoid being to strict or lax.
  * Write specs to report failure at the right level of detail.
  * Give the right detail to find the cause of the problem without drowning in excessive output.
  * Clearly separate noisy setup code from essential test code.
  * Reorder, profile, and filter specs to unearth dependencies.
  * Arrange/Act/Assert.
  * Red/Green/Refactor.
  * Focus only on what needs to be done to make the next spec pass.
  * Outline several related examples at once.
  * Create reusable helper code.
  * Avoid brittle specs.
  * Do not overtest.
  * As little branching logic as possible.
  * Start on the outside - acceptance specs.
  * Write the code you wish you had, then fill in the implementation.
  * Design from the callers perspective.
  * Use obviously fake data in tests.
  * Refactor while green.
  * Move only setup code to a hook.
  * 'Slim the test' - temporary hard-coded return values.
