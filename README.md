# HackTheBox-Crocodile-CTF-Walkthrough

## Introduction
  Crocodile is a vulnerable linux machine hosted by HackTheBox.com. This machine showcases the dangers of misconfigured authentication and sensitive data exposure. A vulnerable FTP server instance is misconfigured to allow anonymous authentication and upon enumerating the server, sensitive files can be found containing cleartext credentials. Enumerating and fuzzing the website will reveal a hidden login endpoint where the previously acquired credentials can be used to gain access to the admin panel.

## Machine link
Here is a link for the machine so you can try it yourself.
[Crocodile - HTB](https://app.hackthebox.com/machines/Crocodile?tab=machine_info&sort_by=created_at&sort_type=desc)
