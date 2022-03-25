### Introduction

The purpose of this assignment is for engineers to exhibit their way of thinking, problem solving and writting skills, when facing an unknown problem.

You should spend between 2 and 4 hours on this, depending on your familiarity with web servers configuration and SSL certificates.

### How to succeed

* Fellow engineers will be reading and reviewing your solution - make it easy to understand and follow, but at the same time with right level of detail to provide a technical solution.
* Perfect is the enemy of done! We're looking to assess your problem solving skills, not that you are able to write a cli tool in Go. As a business we're always balancing time and quality. When making trade-offs to optimize for time - be explicit!

### Assignment

At Homerun, we offer our customers the option to add a custom domain to serve their career site and vacancies under a personalised domain, like jobs.mycompany.com. Customers will be able to configure the custom domain via application settings, as shown in this image:

![Custom domain settings](https://raw.githubusercontent.com/homerunco/platform-assignment/main/img/settings.png)

The pages under this custom domain **must** be served over HTTPS, and it's Homerun's responsibility to provide this security feature for our customers. Once they configure the domain in the application, the funtionality must be available in less than 5 minutes.

![Public website](https://raw.githubusercontent.com/homerunco/platform-assignment/main/img/website.png)

Given that the UI is already implemented, it sends the request to the API with the provided custom domain, and the static pages are ready to be served, how would you design a system that allows such functionality?
