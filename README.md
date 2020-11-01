# goSingletonDesignPattern

The Singleton design pattern in Go - The singleton is used for components where it only makes sense for there to be one of them in the system.

An example would be:

- The database repository
- Object factory (stateless)

**Why do we care?** Well, where we have an object or factory that is expensive to create (space/memory etc). The pattern means we want to give everyone the same instance of the object that is a singleton. Therefore, we want to prevent anyone from creating a 2nd instance of the object in the system or from copying it. As we look at the pattern we can see that we want to care of lazy instantiation, we dont want to use this until we need it given it has an expense in resources involved.
