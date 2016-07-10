# prompt-text
A collection for prompt text.

# Spec

- This collection is consist of a list of categories. Each of them represents an app in a specific domain. For example:
  - An app to help people make donations to organisations.
- The basic unit is `Prompt(id, title, [description])` default language is English. 
  - alias p=Prompt.
  - Prompt supports other languages as a property. e.g.: `p(1).en = 'This is a english title'`
  - When access the Prompt, use p(id).

# Example

```
- (1, "Login successful", null, )
  - p(1).en = 
```
