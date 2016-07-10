# prompt-text
A collection for prompt text.

## Spec

- This collection is consist of a list of categories. Each of them represents an app in a specific domain. For example:
  - An app to help people make donations to organisations.
- The basic unit is `Prompt(id, title, [description])` default language is English. 
  - Alias p=Prompt. So we can do `p(id, title, [description])`, it's the same as Prompt function.
  - When call the function without title, it will return the whole object.
  - Prompt supports other languages as a property. e.g.: `p(1).en = 'This is a english title'`
  - When access the Prompt, use p(id).
- We encourage you to make your own variation of these translations while keeping it easy to understand by fork this repository and edit it on your end.

## Example

- p(1, 'Login successful', 'When user hit the login button and login successful')
  - p(1).zh = '登录成功'
  - p(1).ja = 'ログインに成功'
- p(2, 'Your password is not strong enough, please consider: Minimum length 6 characters; Has at least one uppercase and a lowercase, and at least a special character such as !@#$%^&*,.', 'In the sign up page, when user input a password which is not meet our requirements')
- p(id, 'title', 'description')

## LICENSE

MIT
