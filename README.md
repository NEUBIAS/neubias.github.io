# neubias.github.io
Reserved for the NeuBIAS Blog


# Note

For all those who want to help:

- This blog will be built on Jekyll with automated integration via Travis-CI (unless better options appear)
With that strategy, developers and contributors will have independed access and should be straight forward for ANYONE to contribute with minimal effort. A tutorial will be presented.

- For the developers, I will implement Dev routines with automatic build/deploy for making dev as painless as possible. I use Gulp in my personal projects and works great! **You do NOT have to build the website locally. A push is sufficient to trigger the build.**

- Templates for blog posts will be available.

- Please wait before pushing contributions to this repository. Contact [Victor Caldas](mailto:caldas.victor@gmail.com)

- Suggestions and feedback are welcome.

- Requests and bug report should be made via [Github Issues](https://github.com/NeuBIAS/neubias.github.io/issues)


----


# How to blog

- TUTORIAL UNDER DEVELOPMENT. 

	For now, you can send me the text and I will publish.



----

# How to Develop

This instructions are based on Linux/OSX. 

1. Clone the repository:

```
$ git clone https://github.com/NeuBIAS/neubias.github.io.git
```

You now should have a the folder 'neubias.github.io' available containing all the documents.


Navigate inside the folder and get the gulp packages that will be used:


```
$ npm install
```


#### Gulp

The following Gulp pipelines are available:


``` sh
$ gulp
```

Compile and launch the website

``` sh
$ gulp clean
```
Remove clean all generated files, including the website. It runs before also when building to deploy.


``` sh
$ gulp
```






Thanks!
Victor
