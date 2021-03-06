# Accounts Office reference

<p style="margin-bottom:50px;margin-top:-30px">
<strong class="phase-tag">EXPERIMENTAL</strong><br>
This is currently experimental because more research is needed.</p>

This component lets the user enter an Accounts Office reference. Do not call it ‘Accounts Office reference number’, ‘accounts office reference’ or ‘PAYE Accounts Office reference’.

## When to use

Use this component when the user must enter an Accounts Office reference to use a service.

If there is a good reason for asking for an Accounts Office reference but the user does not have to enter one, make it optional.

## When not to use

If there is no good reason for asking for an Accounts Office reference and the user does not have to enter one to use the service, do not ask for one.

## How it works

You can ask for the Accounts Office reference as the main heading or `<h1>` of the screen. It can be a question or statement.

{{ example("accounts-office-reference-heading.html", scaled=false, cy=false, html=true) }}

Or you can ask for the Accounts Office reference as a form label, separate from the `<h1>`.

{{ example("accounts-office-reference-label.html", scaled=false, cy=false, html=true) }}

Use a single text input and get the user to enter the reference formatted as:

- 3 numbers
- ‘P’
- a letter
- 8 numbers or 7 numbers and an ‘X’

### Provide help

Always provide help in the form label, normal content or hint text that is as clear as possible. This may include:

- a short explanation of what an Accounts Office reference is
- where the user can find it
- what it looks like
- an example – if you show an example, always use ‘123PX00123456’ or ‘123PX0012345X’.

You can use an image that shows where it is on documents and letters.

Do not use the [details component](https://design-system.service.gov.uk/components/details/) to hide any help. Research shows users may:

- not know what an Accounts Office reference is
- need help to know what an Accounts Office reference looks like

### Error messages

Error messages should be styled like this:

{{ example("accounts-office-reference-label-error.html", scaled=false, cy=false, html=true) }}

Make sure errors follow the [guidance about error messages](https://design-system.service.gov.uk/components/error-message/) in the GOV.UK Design System and have specific error messages for specific error states.

#### If the Accounts Office reference is empty

Say ‘Enter [whatever it is]’.<br/>
For example, ‘Enter your Accounts office reference’.

#### If the Accounts Office reference is in the wrong format

Say ‘Enter [whatever it is] in the correct format’.<br/>
For example, ‘Enter your Accounts Office reference in the correct format’

## Research

Research has shown that users often expect this kind of information to be pre-populated, especially when they have signed in.

We need more research. If you have used Accounts Office reference, get in touch to share your research findings.

[Discuss Accounts Office reference on GitHub](https://github.com/hmrc/design-patterns/issues/153)
