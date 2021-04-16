<p align="center" style="margin-bottom:0;">
  <img src="./docs/assets/eratosthenes.webp" alt="An etching of a Eratosthenes's head and neck in profile, looking to the left. The Eratosthenes has a beard and is balding." width="200px">
</p>

<h1 style="margin-top:0;">Eratosthenes</h1>

> A librarian for your digital collections

## Why?

At the time of writing, all my books are sitting in a digital "pile". This is an attempt at an automated way of keeping my books organized.

Some issues I'd like to address:

-   [ ] Store books
-   [ ] Search for books
-   [ ] Use a library classification system to stay organized
-   [ ] Keep track of book requests
-   [ ] Send the book to device
-   [ ] Suggest books
-   [ ] Show book ratings

## Development

### Install pre-requisites

You'll need to install the following pre-requisites in order to build SAFE applications

-   The [.NET Core SDK](https://www.microsoft.com/net/download) 3.1 or higher.
-   [npm](https://nodejs.org/en/download/) package manager.
-   [Node LTS](https://nodejs.org/en/download/).

### Starting the application

Before you run the project **for the first time only** you must install dotnet "local tools" with this command:

```bash
dotnet tool restore
```

To concurrently run the server and the client components in watch mode use the following command:

```bash
dotnet fake build -t run
```

Then open `http://localhost:8080` in your browser.

To run concurrently server and client tests in watch mode (run in a new terminal):

```bash
dotnet fake build -t runtests
```

Client tests are available under `http://localhost:8081` in your browser and server tests are running in watch mode in console.

## Attribution

-   `Eratosthenes` is a tribute to [Eratosthenes](https://en.wikipedia.org/wiki/Eratosthenes) who (among other things) was chief librarian at the [Library of Alexandria](https://en.wikipedia.org/wiki/Library_of_Alexandria).

-   [dwyl/library](https://github.com/dwyl/library) as a source of inspiration
