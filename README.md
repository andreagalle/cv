# Andrea Gallegati

Hi there! I'm an aerospace engineer. I love programming — that’s why I decided to write my CV in LaTeX.

I set up this project in a `devcontainer`: my CV is automatically built at every push/merge into the master branch and deployed to this GitHub Page.

You can download any version of it, here:

- [Detailed CV](https://andreagalle.github.io/cv/long.pdf) (Extended Version)
- [One-Pager](https://andreagalle.github.io/cv/short.pdf) (Short Version)

## Cloning This Project
To clone this repository, ensuring the `.devcontainer` submodule is fetched automatically, run the following commands and follow the instructions you can find there:

    git clone --recurse-submodules https://github.com/andreagalle/cv.git

then, to fetch the latest commit from the submodule repository:

    git submodule update

to list all submodules and their status:

    git submodule

If you have already cloned this repository, you can still initialize and update the `LaTeX` submodule with:

    git submodule update --init --recursive

I hope you enjoy reading about me. Happy coding!
