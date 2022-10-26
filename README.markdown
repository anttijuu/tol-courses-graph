# TOL BSc Course Dependencies

The GraphViz dot file `LuK-courses.dot` in this repository maps the dependencies of the Bachelor of Science level courses (LuK in Finnish) at the study program of [Information Processing Science](https://www.oulu.fi/tol/) at the [University of Oulu](https://www.oulu.fi), Finland.

Another dot file, `LuK-courses-yearly.dot` models the courses organized by year, using the same color coding for course topic areas, as in the first diagram.


## Dependencies

Requires that [GraphViz](https://www.graphviz.org) is installed. For installation to various OS's, see the GraphViz [download page](https://www.graphviz.org/download/).


## How to use it

Use the `dot` tool according to your preferences from the terminal app, e.g.

```
dot -Tpng LuK-courses.dot -o LuK-courses.png
```
For generating SVG graphics file instead, do:

```
dot -Tsvg LuK-courses.dot -o LuK-courses.svg
```

Or use the provided script to generate a png image of the dependencies.

For generating the course map grouped by year, do

```
dot -Tpng LuK-courses-yearly.dot -o LuK-courses-yearly.png
```

See the [image](LuK-courses.png) or the [svg file](LuK-courses.svg) in the repo depicting a current sample of a generated image. Note that the courses are not aligned in the image according to the course scheduling. Only prerequisite dependencies are shown, scheduling is not visible in the image layout. See the study year / study period part of the course box for scheduling information.

The image grouping the [courses by study year](LuK-courses-yearly.png) is also viewable, if you prefer to view courses grouped by year.

## Issues

See [repository issues](https://github.com/anttijuu/tol-courses-graph/issues) for reporting any problems with the data, or for things to fix yourself.

If you find some problems:

1. Report the problem as an issue in the repository.
1. If you can fix it yourself, fork the repo and pull it to your local machine.
1. In your fork, create a branch, one for each issue.
1. Fix the issue in that branch of yours, by editing `LuK-courses.dot` file.
1. Test that the image is generated properly with your fix.
1. Commit the changes to your local repo and then push to your fork in GitHub.
1. Provide a pull request to this repo, fixing the issue.
1. I will then merge your fix in the repo, if it is OK.


## Who did this

Antti Juustila, lecturer at the [INTERACT Research Unit](https://interact.oulu.fi) at UniOulu.

## License

MIT License. Copyright (c) 2020-2022 Antti Juustila. See LICENSE for details.
