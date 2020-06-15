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

See [repository issues](https://github.com/anttijuu/tol-courses-graph/issues) for reporting any problems with the data, or for things to fix yourself.

If you find some problems, do this:

1. Report the problem as an issue
1. If you can fix it yourself, fork the repo
1. In your fork, create a branch, one for one issue
1. Fix the issue in that branch of yours
1. Provide a pull request to this repo, fixing the issue
1. I will then include your fix in the repo, if it is OK.


## Who did this

Antti Juustila, lecturer at the [INTERACT Research Unit](https://interact.oulu.fi) at UniOulu.

