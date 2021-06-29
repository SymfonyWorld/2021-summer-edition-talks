# [SymfonyWorld Online 2021 Summer Edition](https://web.archive.org/web/20210618075532/https://live.symfony.com/2021-world/schedule) talks

- All talks are in **english**.
- You can send feedback and love to speakers on their twitter account

## Keynote

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/598)

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Symfony Forms: Advanced Use Cases

<dl>
  <dt>Description</dt>
  <dd>The Symfony Form component offers many features out of the box. It covers 80% of
use cases, but how do you deal with the 20% left? If you have read the
documentation, you probably know how to use it. But do you know how it works?

To implement your business on top of Symfony Form, you must know how it works
under the hood, and how you can extend it. I will illustrate those underlying
concepts through a series of standard use cases:

- Make a list of items sortable;
- Hide or disable fields based on user permissions;
- (more, to be discovered during the conference).

This presentation will give you insights into how things work inside the Form
component, and how you can hook in it.</dd>
</dl>

[Slides](https://speakerdeck.com/alexandresalome/symfony-forms-advanced-use-cases)  
[Video](https://live.symfony.com/account/replay/video/589)

By [Alexandre Salomé](https://connect.symfony.com/profile/alexandresalome)  
![github](icon/github.png) [@alexandresalome](https://github.com/alexandresalome)  
![twitter](icon/twitter.png) [@alexandresalome](https://twitter.com/alexandresalome)

---

## Cartographing Symfony

<dl>
  <dt>Description</dt>
  <dd>Symfony has grown a lot since its inception. Between 2.0 and the current release over 25 components were added to Symfony. In our talk we want to take a look at these components, group them into layers and then discuss common principles for components in these layers. At the heart of this discussion are package design principles.

This knowledge will not only help you better understand how Symfony is built and how to use these components standalone (or possibly not), it will also help you design better applications and libraries yourself.</dd>
</dl>

[Slides](https://speakerdeck.com/dbrumann/cataloging-symfony)  
[Video](https://live.symfony.com/account/replay/video/581)

By [Christian Flothmann](https://connect.symfony.com/profile/xabbuh)  
![github](icon/github.png) [@xabbuh](https://github.com/xabbuh)  
![twitter](icon/twitter.png) [@xabbuh](https://twitter.com/xabbuh)

And [Denis Brumann](https://connect.symfony.com/profile/dbrumann)  
![github](icon/github.png) [@dbrumann](https://github.com/dbrumann)  
![twitter](icon/twitter.png) [@dbrumann](https://twitter.com/dbrumann)

---

## My Symfony application in Serverless cloud

<dl>
  <dt>Description</dt>
  <dd>Dive deep into the deployment of PHP & Symfony applications to the serverless cloud: study available options, discover and test Bref.</dd>
</dl>

[Slides](https://www.slideshare.net/secret/cXIitf7Cgd0Gkx)  
[Video](https://live.symfony.com/account/replay/video/584)  
[Code](https://github.com/MarieMinasyan/php-serverless)


By [Marie Minasyan](https://connect.symfony.com/profile/marie.minassyan)  
![github](icon/github.png) [@MarieMinasyan](https://github.com/MarieMinasyan)  
![twitter](icon/twitter.png) [@MarieMinasyan](https://twitter.com/MarieMinasyan)

---

## What's new in Doctrine 2021?

<dl>
  <dt>Description</dt>
  <dd>This talk will cover the changes, new features and improvements across the Doctrine ecosystem over the last 12 month and an outlook over what is (probably) coming in 2021. Topics include DBAL 3, Deprecations, Annotations vs Attributes, New Features in recent ORM versions and our roadmap.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/587)

By [Benjamin Eberlei](https://connect.symfony.com/profile/beberlei)  
![github](icon/github.png) [@beberlei](https://github.com/beberlei)  
![twitter](icon/twitter.png) [@beberlei](https://twitter.com/beberlei)

---

## Feedback on our use of Varnish

<dl>
  <dt>Description</dt>
  <dd>On a large French e-commerce site, we use Varnish as HTTP cache.

We use it for the API as well as for the HTML front ends.

We use ESI, with user-context-hashes allowing us to do
authenticated caching. We mix invalidation by tags but also by ttl.

This is a feedback to explain the choices we had to make, how we use it, what it brings us.

We'll also answer a lot of questions that people have about HTTP caching in practice.</dd>
</dl>

[Slides](https://speakerdeck.com/bastnic/symfonyworld-2021-summer-edition-feedback-on-our-use-of-varnish)  
[Video](https://live.symfony.com/account/replay/video/592)  
[Blog post](https://jolicode.com/blog/scaling-the-symfony-demo-app-to-the-extreme-with-varnish)

By [Bastien Jaillot](https://connect.symfony.com/profile/bastnic)  
![github](icon/github.png) [@bastnic](https://github.com/bastnic)  
![twitter](icon/twitter.png) [@bastnic](https://twitter.com/bastnic)

---

## You need an AutoMapper, but you don't know it yet!

<dl>
  <dt>Description</dt>
  <dd>It is quite common for a developer to have to map data. In the long run, this kind of code is boring to write. Why not generate it automatically? This is the promise that AutoMapper tries to solve: generating the code needed to map one data to another (array, class, etc.)

Through this talk, we will first see the Symfony Serializer and how it works.

Then, we will discover how AutoMapper takes advantage of the Serializer ecosystem while revolutionizing the Normalizer concept by adding code generation, thus drastically boosting performance!</dd>
</dl>

[Slides](https://speakerdeck.com/korbeil/you-need-an-automapper-but-you-dont-know-it-yet)  
[Video](https://live.symfony.com/account/replay/video/467)

By [Baptiste Leduc](https://connect.symfony.com/profile/korbeil)  
![github](icon/github.png) [@Korbeil](https://github.com/Korbeil)  
![twitter](icon/twitter.png) [@Korbeil_](https://twitter.com/Korbeil_)

---

## Pedal to the metal: introducing Symfony Turbo

<dl>
  <dt>Description</dt>
  <dd>Hotwire Turbo is a tiny library recently introduced by DHH (the creator of Ruby On Rails) allowing to have the speed of Single-Page Apps without having to write any JavaScript!

As part of the Symfony UX initiative, I created an official integration between Turbo and Symfony. With Symfony Turbo, you can get rid of JavaScript and enjoy using Twig again!

During this talk, we'll discover how the library works, how to leverage it to enhance your Twig templates, how to add real-time features to your websites using the Mercure integration of Symfony Turbo and how to test your Turbo apps with Symfony Panther!</dd>
</dl>

[Slides](https://speakerdeck.com/dunglas/pedal-to-the-metal-introducing-symfony-turbo)  
[Video](https://live.symfony.com/account/replay/video/588)

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Symfony Notifier Demystified

<dl>
  <dt>Description</dt>
  <dd>The Notifier Component is marked stable with the Symfony 5.3 release. A good time to have a closer look at how the Symfony Notifier works and what you can do with it.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/582)

By [Jan Schädlich](https://connect.symfony.com/profile/jschaedl)  
![github](icon/github.png) [@jschaedl](https://github.com/jschaedl)  
![twitter](icon/twitter.png) [@jschaedl](https://twitter.com/jschaedl)

---

## You're not in IT

<dl>
  <dt>Description</dt>
  <dd>You may think you're in the IT business but think again. You are actually in the learning business. If you don't learn, you fall behind. Let's go on a journey through 20+ years of PHP experience and look at some key learnings and why it is important to learn.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/585)

By [Stefan Koopmanschap](https://connect.symfony.com/profile/skoop)  
![github](icon/github.png) [@skoop](https://github.com/skoop)  
![twitter](icon/twitter.png) [@skoop](https://twitter.com/skoop)

---

## Towards Digital Sustainability

<dl>
  <dt>Description</dt>
  <dd>The digital activity accounts for 4% of the total carbon emissions worldwide - roughly as much as planes. Who is responsible for that ? For the most part, developers like you and me. It means it's our job to track, analyze and reduce the carbon emissions of the software we develop. Except it's a hard problem and they aren't many tools available for that.

In this talk, I'll go over the why, the when and the how we should work on building more sustainable software. It's not one of these talks about climate change that put you in a horrible mood for the next month - rather the type of talk with tips that you can start using right away to improve your practice, and make the world a better place.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/586)

By [François Zaninotto](https://connect.symfony.com/profile/fzaninotto)  
![github](icon/github.png) [@fzaninotto](https://github.com/fzaninotto)  
![twitter](icon/twitter.png) [@francoisz](https://twitter.com/francoisz)

---

## Can your code live without the Symfony Framework?

<dl>
  <dt>Description</dt>
  <dd>Everyday, we build our applications on the shoulder of the Symfony Framework. I wonder how long our applications can live. What if Symfony is transformed into totally different, brand-new form?

We already experienced painful migration from symfony1 to Symfony2+, from doctrine1 to Doctrine2+, and Doctrine3 is coming.

In this talk, I will describe how we can extend the lifetime of our applications, through loose coupling between our code and Symfony (or any third-party dependency really.)</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/595)

By [Hiromi Hishida](https://connect.symfony.com/profile/77web)  
![github](icon/github.png) [@77web](https://github.com/77web)  
![twitter](icon/twitter.png) [@77web](https://twitter.com/77web)

---

## Building a SaaS product with Symfony : tips and tricks

<dl>
  <dt>Description</dt>
  <dd>After several years of experience building Software As A Service products, I would like to share with you the crucial and less crucial tips on how to build a technically effective platform while focusing on your business. We will talk about how to build great subscription mechanisms, how to leverage EasyAdmin, why and how you should rely on other platforms (Stripe, Sentry, SymfonyCloud) and finally how you can plan your software architecture for growth.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/597)

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)

---

## A short tale about state machine

<dl>
  <dt>Description</dt>
  <dd>Entities lifecycle is usually something more than create and delete. Models with which we are working on day to day basis change their state under some business circumstances. State machine patterns can be a powerful allay when solving this kind of problem. How does it look like? What are the pros and cons of state machine usage? What are the things that we should be beware of? I will answer these questions during my talk, together with practical differences between the most popular implementation (including Symfony Workflow of course ;)).</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/580)

By [Łukasz Chruściel](https://connect.symfony.com/profile/lchrusciel)  
![github](icon/github.png) [@lchrusciel](https://github.com/lchrusciel)  
![twitter](icon/twitter.png) [@lukaszchrusciel](https://twitter.com/lukaszchrusciel)

---

## Cypress, the E2E must learn from the past

<dl>
  <dt>Description</dt>
  <dd>In this talk, we'll learn what is Cypress, an E2E framework which is growing (companies like Paypal, Disney, Github, Slack and so on uses it everyday).
The first objective will be to compare it against competitors like Behat (especially when used with Mink/Selenium), a well known tool.

Regarding his rapid growth, Cypress can face issues and bad habits, we'll see how to manage these traps and learn from old tools, we'll also see the main drawbacks and advantages and how to use it in a daily basis.

In the end, we'll see how to integrate it into a Symfony application and ease his usage, maintenance and write future-proof tests.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/591)

By [Guillaume Loulier](https://connect.symfony.com/profile/guikingone)  
![github](icon/github.png) [@Guikingone](https://github.com/Guikingone)  
![twitter](icon/twitter.png) [@Guikingone](https://twitter.com/Guikingone)

---

## Runtime component: The game changer

<dl>
  <dt>Description</dt>
  <dd>Symfony 5.3 will be released with a new Runtime component. It allows your application to run decoupled from the global state. That means your application will be portable to many different systems without making any changes.

This is a massive step forward not only for Symfony but for all PHP applications. It is especially beneficial for users that want to run ReactPHP, Bref, Swoole, etc.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/583)

By [Tobias Nyholm](https://connect.symfony.com/profile/tobias)  
![github](icon/github.png) [@Nyholm](https://github.com/Nyholm)  
![twitter](icon/twitter.png) [@TobiasNyholm](https://twitter.com/TobiasNyholm)

---

## PasswordHasher Component: A simple yet powerful password hashing library

<dl>
  <dt>Description</dt>
  <dd>In Symfony 5.3, the password hashing logic has been extracted out from the security-core package to a first-class package named password-hasher.
This component provides a clean API to manage passwords securely, and it can be used in any PHP project.
Let's see how this component works and how it can ease managing passwords in your applications.</dd>
</dl>

[Slides](https://slides.com/chalasr/symfony-password-hasher)  
[Video](https://live.symfony.com/account/replay/video/590)

By [Robin Chalas](https://connect.symfony.com/profile/chalas_r)  
![github](icon/github.png) [@chalasr](https://github.com/chalasr)  
![twitter](icon/twitter.png) [@chalas_r](https://twitter.com/chalas_r)

---

## What is the Symfony UID component?

<dl>
  <dt>Description</dt>
  <dd>The Symfony UID component has been released one year ago as a simple OOP layer on top of the "uuid" extension and polyfill. Since then, it has matured from experimental to stable and has increased the range of use cases it can fulfill, while keeping a clean and simple design.

But what are "UIDs" in the first place? Unique IDentifiers serve many purposes! During this talk, we will explore the component itself. We will also discuss the various types of UIDs and when each of them should be preferably used.

Last but not least, we will make this an opportunity to discuss why the Symfony project decided to create a new component on the topic, while alternatives exist.</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/596)

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## A Dynamic Frontend with Twig & Zero JavaScript? Say Hello to...

<dl>
  <dt>Description</dt>
  <dd>Traditional web apps are back! The Symfony UX initiative - with tools like
Stimulus & Turbo - makes it possible to built your HTML using Twig templates
but *with* a "single-page experience" and professionally-written JavaScript.

Could we go further? Could we organize Twig templates into reusable
units? And could we expose those units so we can load them via AJAX calls or
HTTP-cache them?

And, if we did that... would it be possible to write Twig templates that
automatically update on the frontend when the user interacts with them? All
with zero JavaScript?

Let's go on a journey!</dd>
</dl>

~~Slides~~  
[Video](https://live.symfony.com/account/replay/video/594)

By [Ryan Weaver](https://connect.symfony.com/profile/weaverryan)  
![github](icon/github.png) [@weaverryan](https://github.com/weaverryan)  
![twitter](icon/twitter.png) [@weaverryan](https://twitter.com/weaverryan)
