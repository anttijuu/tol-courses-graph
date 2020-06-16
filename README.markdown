# TOL BSc Course Dependencies

The GraphViz dot file `LuK-courses.dot`in this repository maps the dependencies of the Bachelor level courses (LuK in Finnish) at the study program of [Information Processing Science](https://www.oulu.fi/tol/) at the [University of Oulu](https://www.oulu.fi), Finland.

## Dependencies

Requires that [GraphViz](https://www.graphviz.org) is installed. For installation to various OS's, see the GraphViz [download page](https://www.graphviz.org/download/).


## How to use it

Use the provided script to generate a png image of the dependencies.

Or alternatively, use the `dot` tool according to your preferences from the terminal app, e.g.

```
dot -Tpng LuK-courses.dot -o LuK-courses.png
```
For generating SVG graphics file instead, do:

```
dot -Tsvg LuK-courses.dot -o LuK-courses.svg
```

See the [image](LuK-courses.png) or the [svg file](LuK-courses.svg) in the repo depicting a current sample of a generated image.

Note that the courses are not aligned in the image according to the course scheduling. Only prerequisite dependencies are shown, scheduling is not visible in the image layout. See the study year / study period part of the course box for scheduling information.

## Issues

See [repository issues](https://github.com/anttijuu/tol-courses-graph/issues) for reporting any problems with the data, or for things to fix yourself.

If you find some problems:

1. Report the problem as an issue in the repository.
1. If you can fix it yourself, fork the repo and pull it to your local machine.
1. In your fork, create a branch, one for each issue.
1. Fix the issue in that branch of yours.
1. Test that the image is generated properly with your fix.
1. Commit the changes to your local repo and then push to your fork in GitHub.
1. Provide a pull request to this repo, fixing the issue.
1. I will then merge your fix in the repo, if it is OK.


## Who did this

Antti Juustila, lecturer at the [INTERACT Research Unit](https://interact.oulu.fi) at UniOulu.

## License

MIT License. Copyright (c) 2020 Antti Juustila. See LICENSE for details.
