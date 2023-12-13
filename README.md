# Typescript Styleguide

This guide is based on my private TypeScript preferences.

## Table of Contents

- [Naming Conventions](#naming-conventions)

## Naming Conventions

### General

- Identifiers must use only ASCII letters.
- Names should be informative and easily understood by someone new to the material. Avoid using abbreviations that might be unclear or not widely recognized outside your project. Also, refrain from shortening words by omitting letters.
- In TypeScript, since types convey information, there's no need to embellish names with details already indicated by the type. This practice keeps code clean and straightforward.
- Avoid single letter names.
- Do not use trailing or leading underscores.

### Interfaces

- Avoid using prefixes like "I" or suffixes such as "Interface" in the names, as in "IUser" or "UserInterface.
- Interface names in TypeScript should be nouns or noun phrases that describe the object represented by the interface.
- Follow the PascalCase naming convention, where each word in the name starts with a capital letter.

### Types

- Type names in TypeScript should be nouns or noun phrases that describe the object represented by the type.
- Follow the PascalCase naming convention, where each word in the name starts with a capital letter.
- When it comes to union types, it's preferable to use descriptive noun phrases, often connected with the conjunction “Or”. However, it's better to avoid relying on “Or” when possible and choose names that are more descriptive and indicative of the type's purpose or nature.

### Enums

- When defining a set of named constants in TypeScript using enums, choose a singular noun or noun phrase that describes the group of constants.
- For the enum name itself, adhere to the PascalCase convention.
- For the properties within the enum, either PascalCase or CONSTANT_CASE should be used.

### Generics

- When defining a generic with just one type parameter, use a single uppercase letter to represent it.
- If the generic type is used multiple times, or if you're working with multiple generic types, opt for more descriptive names that clearly indicate their purpose or nature.
