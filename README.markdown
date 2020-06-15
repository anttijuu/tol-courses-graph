# TOL BSc Course Dependencies

The GraphViz dot file `LuK-courses.dot`in this repository maps the dependencies of the Bachelor level courses (LuK in Finnish) at the study program of Information Processing Science at the University of Oulu, Finland.

## Dependencies

Requires that [GraphViz](https://www.graphviz.org) is installed. For installation to various OS's, see the GraphViz [download page](https://www.graphviz.org/download/).


## How to use it

Use the provided script to generate a png image of the dependencies.

Or alternatively, use the `dot` tool according to your preferences, e.g.

```
dot -Tpng LuK-courses.dot -o LuK-courses.png
```

See the [image](LuK-courses.png) in the repo depicting a current sample of a generated image.

Note that the courses are not aligned in the image according to the course scheduling. Only prerequisite dependencies are shown, scheduling is not visible in the image layout.

## Issues

* 811379A  Käyttöliittymien perusteet mentions a prerequisite 811177P which is a deprecated course.
* 811366A Projektitoiminta lists many old deprecated courses as prerequisites.


## Who did this

Antti Juustila, lecturer at the [INTERACT Research Unit](https://interact.oulu.fi) at UniOulu.

