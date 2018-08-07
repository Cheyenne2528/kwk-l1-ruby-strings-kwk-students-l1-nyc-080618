# Ruby Strings Party

<img src="https://s3.amazonaws.com/after-school-assets/hogwarts.jpg" width="400px" align="right" hspace="10">

Your friend Harry Potter was very impressed with the invitations that you created for Ron Weasley's graduation party. Harry suggests that the two of you start an invitation printing business together. He wants you to create a program that prompts customers for the following party details...

guest_name = gets.chomp
party_name = Best Halloween Party Ever
date = October 31
time = 6pm
host_name = Harry Potter

...and then prints out custom invitations that look something like this:

```
puts "Hi you've been invited to a party, What's your name"
guest_name = gets.chomp
puts "My name is #{guest_name}"

You are cordially invited to the party_name on date at time. Please RSVP no later than date.

Sincerely,
host_name
```
