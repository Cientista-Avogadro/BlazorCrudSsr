# What's new in ASP.NET Core 8.0 - Blazor

Blazor

Full-stack web UI

With the release of .NET 8, Blazor is a full-stack web UI framework for developing apps that render content at either the component or page level with:

Static Server rendering (also called static server-side rendering, static SSR) to generate static HTML on the server.

Interactive Server rendering (also called interactive server-side rendering, interactive SSR) to generate interactive components with prerendering on the server.

Interactive WebAssembly rendering (also called client-side rendering, CSR, which is always assumed to be interactive) to generate interactive components on the client with prerendering on the server.

Interactive Auto (automatic) rendering to initially use the server-side ASP.NET Core runtime for content rendering and interactivity. The .NET WebAssembly runtime on the client is used for subsequent rendering and interactivity after the Blazor bundle is downloaded and the WebAssembly runtime activates. Interactive Auto rendering usually provides the fastest app startup experience.

Interactive render modes also prerender content by default.

For more information, see the following articles:

ASP.NET Core Blazor fundamentals: New sections on rendering and static/interactive concepts appear at the top of the article.

ASP.NET Core Blazor render modes

Migration coverage: Migrate from ASP.NET Core 7.0 to 8.0

Examples throughout the Blazor documentation have been updated for use in Blazor Web Apps. Blazor Server examples remain in content versioned for .NET 7 or earlier.

New article on class libraries with static server-side rendering (static SSR)

We've added a new article that discusses component library authorship in Razor class libraries (RCLs) with static server-side rendering (static SSR).

For more information, see ASP.NET Core Razor class libraries (RCLs) with static server-side rendering (static SSR).

New article on HTTP caching issues

We've added a new article that discusses some of the common HTTP caching issues that can occur when upgrading Blazor apps across major versions and how to address HTTP caching issues.

For more information, see Avoid HTTP caching issues when upgrading ASP.NET Core Blazor apps.

New Blazor Web App template

We've introduced a new Blazor project template: the Blazor Web App template. The new template provides a single starting point for using Blazor components to build any style of web UI. The template combines the strengths of the existing Blazor Server and Blazor WebAssembly hosting models with the new Blazor capabilities added in .NET 8: static server-side rendering (static SSR), streaming rendering, enhanced navigation and form handling, and the ability to add interactivity using either Blazor Server or Blazor WebAssembly on a per-component basis.

As part of unifying the various Blazor hosting models into a single model in .NET 8, we're also consolidating the number of Blazor project templates. We removed the Blazor Server template, and the ASP.NET Core Hosted option has been removed from the Blazor WebAssembly template. Both of these scenarios are represented by options when using the Blazor Web App template.

New JS initializers for Blazor Web Apps

For Blazor Server, Blazor WebAssembly, and Blazor Hybrid apps:

beforeWebStart is used for tasks such as customizing the loading process, logging level, and other options.

afterWebStarted is used for tasks such as registering Blazor event listeners and custom event types.

The preceding legacy JS initializers aren't invoked by default in a Blazor Web App. For Blazor Web Apps, a new set of JS initializers are used: beforeWebStart, afterWebStarted, beforeServerStart, afterServerStarted, beforeWebAssemblyStart, and afterWebAssemblyStarted.

For more information, see ASP.NET Core Blazor startup.

Here you can see my Test App:

This App Execute All Crud Operations:

Create New Video Game

Edit Video Game

Delete Video Game

Get All Video Game Saved in Db

I did use also EntityFramework to persist data from DB(Sql Server).

More about the project:

<a href="https://www.linkedin.com/pulse/whats-new-aspnet-core-80-blazor-sebasti%C3%A3o-de-sousa-moniz-70kxf">https://www.linkedin.com/pulse/whats-new-aspnet-core-80-blazor-sebasti%C3%A3o-de-sousa-moniz-70kxf</a>
