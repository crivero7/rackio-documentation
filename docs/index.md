
# Rackio: The Python Framework

<div class="admonition attention">
    <p class="first admonition-title">Attention</p>
    <p class="last">
        This Framework is still under development process, some features are still in test, use them with caution.
    </p>
</div>

## Rackio Framework
Rackio is a modern Python Framework for microboard automation and control applications development, it uses a declarative syntax to set your own applications in a bit.

It was developed to bring automation and control engineers the capability of developing high end industrial solutions. Inspired by [Django](https://www.djangoproject.com), [Flask](https://palletsprojects.com/p/flask/) and [Scrapy](https://scrapy.org/), Rackio comes with built-in batteries to make common operations and tasks in the automation field.
You can fork the source right on [Github](https://github.com/rack-io/rackio-framework).
---

## Why Rackio?
Plain simple and honest, we'll there wasn't such a thing before, there is enough information out there in the Internet about how to do a data acquisition and actuation with Python, but too short about how to architect these systems, we built Rackio to solve common real problems found in the Industrial Field, so you can focus, as automation developer, more in the solution rather than the code to achieve your solution.

As we started designing automation systems ourselves, we found out that we needed a way to code applications in such a way that this code would be modular, reusable, maintainable and extensible. We where tired of those codes of infinite while loops, we wanted to create code to produce code in a organized way so that our job would be simplified.

And this way Rackio was born, as a Python Framework, a set of declarative constructs so you can code and configure your automation and control applications, we want to build a culture of code the same way Django does for web applications and Scrapy for web scraping, Rackio is inspired on these Frameworks among others and it's improving each day.

## What can you do with Rackio?

With Rackio you can build complex and advanced automation and control architectures deployable in any pc-based controller that can run Python. Rackio enables the capability of defining systems and subsystems that can perform tasks and operation in concurrency, appropriate features can handle integration within these systems, so you can deliver high end solutions to your automation and control problems.

## So, where is the HMI?

Rackio doesn't come with a default HMI, since it is a server application framework, it comes with an API so you can connect your custom HMI developed in any technology you choose. On the other hand, Rackio comes with an Admin Web Interface (inspired by Django), so you can monitor and set features suchas Tags value, Trends, Alarms, Events and much more.

---

## Built-In Batteries

Rackio comes with some out of the box features that let you start creating rapid and fast coding prototypes and Rackio applications, here is a list of these features:

* Tag based engine
* Custom Models Definitions
* Controls and Math Operations
* State Machine Definitions
* Custom Observers
* Custom Continuous Tasks
* Trend based Logging
* Automatic Data Logging 
* Event History
* Alarm Management System
* RESTful API
* Web Based Admin

Each of these features are presented as declarative decorators, application methods and classes so you can define how your application will behave and interact with-in its own internals.

---

## RESTful API

<div class="admonition note">
    <p class="first admonition-title">Note</p>
    <p class="last">
        This feature is under development process
    </p>
</div>

Rackio is focuses on new trend technologies and promotes web development for automation applications, all of the Rackio Features can be accessed by using the RESTful API, being Rackio a service or backend application, you can define your custom views or HMI with other front-end technologies.

---

## Support

You can follow us on [github](https://github.com/rack-io) or Twitter.

If you have some feedback about our framework, let us know through our [email](mailto:rackio.framework@outlook.com).

## Donations

We make these tools for free, but it takes hours of work to improve the framework every day. You can send us some bucks to promote our development process.

[paypal](https://paypal.me/carrasquel)