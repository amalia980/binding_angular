# MyGameApp

Exercise. Bind It!

1. create three new components: GameControl, Odd and Even.
2. The GameControl component should have buttons to start and stop the game
3. when starting the game, an event (holding a incrementing number) should get
emitted each second (ref = setInterval())
4. the event should be listenable from outside the component
5. when stopping the game, no more events should get emmited (clearIntercal(ref))
6. a new Odd component should get created for every Odd number emitted, the same should happen for the Even component (on even numbers)
7. simply output Odd - NUMBER or Even - NUMBER in the two components