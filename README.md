# Dagger2

A Dependency Injection Library.
    In a nut shell, Dagger provides objects and provide them at the right time.
    We can teach dagger how to create these objects using the following methods

        1. Constructor Injection
            By annotating the constructor of a class with @Inject, we show dagger how to
            create an object of the class.
            This is not always possible, because some classes comes from 3rd party libraries
            so we cant annotate them.
            In such cases we use the @Module annotation
        2. Field Injection
        3. Method Injection