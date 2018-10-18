# simple-email-template

### responsive

### very basic
less then 50 rows of code

### variable keys
can be replaced dinamiclly
* [hello]
* [message]
* [sign]

### screenshots
![alt text](https://github.com/vastril4o/simple-email-template/blob/master/img/Screenshot1.png)
![alt text](https://github.com/vastril4o/simple-email-template/blob/master/img/Screenshot2.png)

### usage
* asp.net
```
// geting html as string from email.html file
StreamReader str = new StreamReader(Server.MapPath("~/Views/Template/email.html"));
string email_html = str.ReadToEnd();
str.Close();

// replace key whit your values
email_html = email_html.Replace("[hello]", "Hello John Doe");
email_html = email_html.Replace("[message]", "This is your message");
email_html = email_html.Replace("[sign]", "Good luck!");
```
