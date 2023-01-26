# PYMailer

A simple and comprehensive Python class based SMTP mailer module

In Progress ... [^1]

[^1]: [Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)


### Usage:

```python
smtp = SmtpClient()
smtp.useTLS = True
smtp.useSSL = False
smtp.server.address='smtp.server.tld'
smtp.server.username='user@mail.tld'
smtp.server.password='secret_password'
smtp.mail.addTo(['to1@email.tld','to2@email.tld'])
smtp.mail.addBcc(['bcc1@email.tld','bcc2@email.tld'])
smtp.mail.addCc(['cc1@email.tld','cc2@email.tld'])
smtp.mail.addSubject('mail subject')
smtp.mail.addBody('text, html, or file here')
smtp.execute()
```
