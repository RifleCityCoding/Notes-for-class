# Atomic Design

## What is it?

    Atomic Design is not a linear process but rather a mental model to help us design our code. 
    It is a methodology for creating design systems.

## Components

#### Atoms
    Atoms are the basic building blocks of mattter, applied to web interfaces, atoms are our HTML tags usch as a form label, an input, or a button.
    They can also include abstract elements like color palettes, fonts and even more invisible aspects of an interface like animations.

### Molecules
    This is where we combine atoms together to make fundamental units of a compound. Ex: Form label, input, and button are put together to make our "Molecule". These components are useful together but combining them let them do something together. (EX: search bar made of multiple atoms for one function)

### Organisms
    Molecules give us some building blocks to work with, and combine these to form organisms.

### Templates
    At the template stage, we break our chemistry analogy to get into the language that makes more sense to our clients and our final output. Templates contain a collection of organisms stitched together to form pages.

### Pages
    Pages are specific instances of templates. Here, placeholder content is replaced with real representative content to give an accurate depiction of what a user will ultimately see.

## Why do we use atomic design?

    Atomic design provides a clear methodology for crafting design systems. Clients and team members are able to better appreciate the concept of design systems by actually seeing the steps laid out in front of them.Atomic design allows us to traverse from abstract to concrete.